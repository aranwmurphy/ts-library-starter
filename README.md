# ts-library-starter
TypeScript library starter template

## Available Scripts

In the project directory, you can run:

### `npm test`

Runs the library test suite, and reports the results of each test.

### `npm build`

Builds the library for production to the `lib` folder.<br />
It correctly bundles the library in production mode and optimizes the build for the best performance.

### `npm lint`

Lints the project files.

## Usage

### JavaScript

```javascript
const Redis = require('ioredis');

const client = new Redis();

async function main() {
    // ... ADD CODE HERE
}
```

### TypeScript

```typescript
import Redis = require("ioredis");

const client = new Redis();

async function main(): Promise<void> {
    // ... ADD CODE HERE
}
```

## License
MIT