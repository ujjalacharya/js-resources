# Table of contents

- [Javascript](#javascript)

## Javascript

- async loop

```js

const array = [0,1,2,3,4,5,6,7,8,9];

console.log("Async Loop example")

const delayLog = (item) => {
    return new Promise(resolve => setTimeout(resolve, 300))
}

const asyncLoop = async () => {
    Object.keys(array).forEach(async (item) => {
        console.log("Log before", item)
        await delayLog(item)
        console.log("Log after", item)
    })
}

asyncLoop()

console.log("Done")
```

[Source](/examples/async-loop/async-loop.js)