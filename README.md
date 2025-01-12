# micro-docgen (Forked)

[![npm version](https://badge.fury.io/js/%40hitomihiumi%2Fmicro-docgen.svg)](https://badge.fury.io/js/%40hitomihiumi%2Fmicro-docgen)

[![downloads](https://img.shields.io/npm/dm/%40hitomihiumi%2Fmicro-docgen.svg)](https://www.npmjs.com/package/%40hitomihiumi%2Fmicro-docgen)

TypeScript documentation generator on steroids 💉. MicroDocgen is built on top of typedoc to leverage its power and add more features.

## TODO

-   Update to 0.3.0 original version

## Installation

```sh
$ npm install @hitomihiumi/micro-docgen
```

## Usage

```js
import { createDocumentation } from '@hitomihiumi/micro-docgen';

await createDocumentation({
    // source files
    input: ['src'],
    // output directory
    output: 'docs',
    // tsconfig path
    tsconfigPath: './tsconfig.json',
    // to generate markdown files
    markdown: true,
    // to generate json file
    jsonName: 'docs.json',
    // include custom files such as readme
    custom: [...]
});
```
