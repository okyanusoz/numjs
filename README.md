# NumJS without image functions

This is a fork of NumJS without image functions. This version is lighter and does not include sharp.

This version is mostly for use in my own projects to speed up installation.

## Installation
Installation is as simple as:
`npm install https://github.com/okyanusoz/numjs-noimage # (or yarn add https://github.com/okyanusoz/numjs-noimage with Yarn)`

## Docs
Docs are the same as https://github.com/nicolaspanel/numjs, but without the `nj.images` module. 

*NOTE*: **You will also need to change `require("numjs")` code to `require("numjs-noimage")`.**

## TypeScript

For TypeScript, you need to add the `skipLibCheck: true` to your tsconfig.json file or you need to run the compiler with `--skipLibCheck`.

I may add types in the future.

See https://stackoverflow.com/questions/52311779/usage-of-the-typescript-compiler-argument-skiplibcheck
