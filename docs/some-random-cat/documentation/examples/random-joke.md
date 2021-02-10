```javascript
// This snippet uses some-random-cat version 2x

const somethingRandom = require('some-random-cat').Random
somethingRandom.getJoke()
.then(res => {
    console.log(res)
    return
}) // Get the result
.catch(e => {
    console.error(e)
    return
}) // Catch the error
```

!!! info
    Please note that this returns an object. To use the properties, you can access it by `<Result>#<Property>`