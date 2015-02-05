# questor

Promise based HTTP client inspired by clj-http

## Usage

```javascript
var questor = require('questor');

questor('https://github.com').then(function (res) {
});
```

## TODO

- Small resulting browserify bundle
- Streaming request and response bodies
- Types for requests, responses and errors
