???+ danger
    Please do not instantiate this class as it is static.  
    You can access it using `require('some-random-cat').Random`.

The class which is used to generate random things like cats, dogs etc.

=== "Methods"

> | Name |
| :---------|
| `getAdvice`    |
| `getCat`      |
| `getDog`       | 
| `getFact`    |
| `getJoke`    |
| `getMeme`    |
| `getString`    |
| `getTopic`    |

## Methods

### `.getAdvice()`
> Gets an Advice.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>

### `.getCat()`
> Gets a random cat image.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>

### `.getDog()`
> Gets a random dog.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>

### `.getFact()`
> Gets a random fact.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>

### `.getJoke()`
> Gets a random joke and returns an object with the title, description, uri.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)>

### `.getMeme()`
> Gets a random meme and returns an object with all the data like image and title.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)>

### `.getString(number)`
> Gets a random string of a specified length.

> | Parameter     | Type | Optional | Default | Description |
| :---------: | :-----: | :-----: | :-----: | :-----: |
| `number`       | Number  | :fontawesome-solid-times: | *none* | The length of the string. |

> **Returns:** [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

### `.getTopic()`
> Gets a random topic.

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)>