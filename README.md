# neutralinojs-types

This package contains type definitions for Neutralinojs (https://neutralino.js.org/).

At the time of writing this, `neu create <name>` does not include type definitions. You could build Neutralinojs from its [repository](https://github.com/neutralinojs/neutralinojs) and get the official types but it doesn't completely implement the [documentation](https://neutralino.js.org/docs/api/overview).

## Installation

Install the package in the npm registry.

```bash
npm install --save-dev neutralinojs-types
```

If the types do not appear in autocomplete, you can create a script in your codebase and add this line.
```ts
import 'neutralinojs-types'
```