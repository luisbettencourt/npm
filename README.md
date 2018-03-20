# Example

```shell
$ npm install sensitive-words  --save
```

```javascript
const {sensitiveWords} = require("sensitive-words)

const filtered = sensitiveWords.default("The new apple macbook pro will have a touchbar", ["pro", "touchbar"])

console.log(filtered);
// The new apple macbook *** will have a ***
```
