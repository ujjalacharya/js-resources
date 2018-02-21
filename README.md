## Table of contents

- [7 Hacks for ES6 Developers]()

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
