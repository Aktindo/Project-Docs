[![NPM](https://nodei.co/npm/some-random-cat.png)](https://nodei.co/npm/some-random-cat/)

![Total Downloads](https://img.shields.io/npm/dt/some-random-cat?style=flat&label=Downloads) ![Discord](https://img.shields.io/discord/772129415005470740?color=%237289DA&label=chat&logo=Discord&style=flat) ![npm](https://img.shields.io/npm/v/some-random-cat?style=flat) ![NPM](https://img.shields.io/npm/l/some-random-cat?style=flat) ![GitHub Repo stars](https://img.shields.io/github/stars/aktindo/some-random-cat?style=flat)

This is the official documentation for some-random-cat.

## Installation
Node.js v12x or higher is required. Ignore any unmet peer warnings, as they are optional.
```
npm install some-random-cat 
```

## Example Usage
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

## Links
- [Website](https://aktindo.thedev.id/Some Random Cat) ([Source](https://github.com/Aktindo/Project-Docs)
)
- [Documentation](https://aktindo.thedev.id/Some Random Cat/Documentation/General/Welcome) ([Source](https://github.com/Aktindo/Project-Docs))
- [NPM](https://npmjs.com/package/some-random-cat)
- [Some Random Cat Discord Server](https://discord.gg/6g297Usrsn)

## Contributing
Before creating an issue, please ensure that it hasn't already been reported/suggested, and double-check the documentation.

## Help
If you are stuck or do not understand something, you can freely ask it in the Some Random Cat [Discord server](https://discord.gg/6g297Usrsn)!
