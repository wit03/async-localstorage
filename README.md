[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com)

[![forthebadge](https://forthebadge.com/images/badges/made-with-crayons.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)

# Async LocalStorage

Async implemented localStorage library for javascript and typescript (coming soon).

## Why?
Since localStorage API is a synchronous and took so long to get or set value which is pretty annoying. Using Async LocalStorage will helps you deal with race condition.

## Installation
```ssh
// using
> npm install @wit03/async-localstorage
> yarn add @wit03/async-localstorage
```

## Getting Started
1. ES6
```js
import { setItem, getItem } from '@wit03/async-localstorage'

//setItem
setItem(key, data).then(()=> {
    //value has been set
})
//getItem
getItem(key).then((value)=> {
    //return value data
})
```
2. Module
```js
const asyncLocalStorage = '@wit03/async-localstorage'

//setItem
asyncLocalStorage.setItem(key, data).then(()=> {
    //value has been set
})
//getItem
asyncLocalStorage.getItem(key).then((value)=> {
    //return value data
})
```
## Contributions
feel free to create PR and also issues~
