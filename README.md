## Table of contents

- [7 Hacks for ES6 Developers]()

# 7 Hacks for ES6 Developers

### Hack #1 — Swap variables
Using `Array Destructuring` to swap values
```
let a = 'world', b = 'hello'
[a, b] = [b, a]
console.log(a) // -> hello
console.log(b) // -> world
// Yes, it's magic
```
