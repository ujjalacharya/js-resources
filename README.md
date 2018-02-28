## Table of contents

- [7 Hacks for ES6 Developers]()
- [React Native resources](#react-native-resources)

# 7 Hacks for ES6 Developers

### Hack #1 — Swap variables
Using `Array Destructuring` to swap values

```js
let a = 'world', b = 'hello'
[a, b] = [b, a]
console.log(a) // -> hello
console.log(b) // -> world
// Yes, it's magic
```

### Hack #2 — Async/Await with Destructuring
Once again, Array Destructuring is great. Combined with async/await and promises to make a complex flow — simple.

```js
const [user, account] = await Promise.all([
  fetch('/user'),
  fetch('/account')
])
```

### Hack #3—Debugging
For anyone who likes to debug using `console.log`, here’s something
awesome (and yes, I heard of `console.table`):
```js
const a = 5, b = 6, c = 7
console.log({ a, b, c })
// outputs this nice object:
// {
// a: 5,
// b: 6,
// c: 7,
// }
```

- Optional Chaining operator


# React Native Resources

- react native social auth
  - https://github.com/adamjmcgrath/react-native-simple-auth
  - https://www.codementor.io/microsem31/react-native-google-and-facebook-authentication-cohpznykf
