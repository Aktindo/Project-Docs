# Overview
## :cat: Some Random Cat

### About
Some Random Cat is a powerful node.js tool for generating random stuff like cats, dogs, jokes and much more!
It uses the idea of static functions and is very fast compared to other packages and very easy to setup in your projects.

### Why?
+ Object Oriented
+ Fully Static
+ Powerful Functions
+ Easy to use
+ Regular Updates

### Example
```javascript
const SomeRandomCat = require('../index').Random; // Replace ../index with some-random-cat
SomeRandomCat.getCat() // Function for generating cat
.then(res => {
    console.log(res)
    return
})
.catch(e => {
    console.error(e)
    return
});
```

[Get Started](/some-random-cat/documentation/general/getting-started/){: .md-button .md-button--primary } [:material-discord: Discord](https://discord.gg/6g297Usrsn){: .md-button }