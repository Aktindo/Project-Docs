???+ danger
    Please do not instantiate this class as it is static.  
    You can access it using `require('some-random-cat').Generation`.

The class which is used to generate stuff like IDs, Time formats etc.

=== "Methods"

> | Name |
| :---------|
| `formatTime`      |
| `shorten`       | 
| `generateId`    |
| `getAcronym`    |

## Methods

### `.formatTime(time)`
> Formats a time to `00:00` 24 hour format.

> | Parameter     | Type | Optional | Default | Description |
| :---------: | :-----: | :-----: | :-----: | :-----: |
| `time`       | Number/Date  | :fontawesome-solid-times: | *none* | The time that is to be formatted. |

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)>

### `.shorten(text, length)`
> Shortens a text by adding a `...` after the specified length.

> | Parameter     | Type | Optional | Default | Description |
| :---------: | :-----: | :-----: | :-----: | :-----: |
| `text`       | String  | :fontawesome-solid-times: | *none* | The text that is to be formatted. |
| `length`       | Number  | :fontawesome-solid-times: | *none* | The length of the text to be removed. |

> **Returns:** [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)  
**Examples:**  
```javascript
// Import the package.
const SomeRandomCat = require('some-random-cat').Generation
// Defining a variable.
let myText = "hello there this is cool!"
// Actual Function
SomeRandomCat.shorten(myText, 3)
// Returns "hello there this is co..."
```

### `.generateId({ops})`
> Generates a UUID. Useful when you need to generate secure and unique ID for every person.

> | Parameter     | Type | Optional | Default | Description |
| :---------: | :-----: | :-----: | :-----: | :-----: |
| `ops `      | Object  | :fontawesome-solid-check: | ops | Options for generating the ID. |
| `ops.putDash`       | Boolean  | :fontawesome-solid-check: | true | Whether to keep a `-` in the ID. |

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>

### `.getAcronym(text)`
> Gets an acronym for a text. **For example:** `I like cats` = `Ilc` 

> | Parameter     | Type | Optional | Default | Description |
| :---------: | :-----: | :-----: | :-----: | :-----: |
| `text`       | String  | :fontawesome-solid-times: | *none* | The text that is to be formatted. |

> **Returns:** [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>