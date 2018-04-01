# Examples

- class export

```js
// class-export.js
class Self {
    constructor() {
        console.log('Self invoke class');
    }
}

module.exports = (
    () => {
        return new Self()
    }
)

// index.js
const Self = require('./class-export')()
```

Source: [async-loop.js](/examples/node/class-export/class-export.js#L1)