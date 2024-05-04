# Changelog


## [8.0.1](https://github.com/supercharge/tsconfig/compare/v8.0.0...v8.0.1) - 2024-05-04

### Updated
- bump `engine` property in `package.json` to `Node.js >= 22`


## [8.0.0](https://github.com/supercharge/tsconfig/compare/v7.0.0...v8.0.0) - 2024-05-04

### Updated
- bump `target` to `ES2023` because Node.js 22 supports it (https://node.green/#ES2023)
- bump `engine` property in `package.json` to `Node.js >= 22`

### Breaking Changes
- target Node.js v22

**Notice:** version `8.0.0` requires TypeScript version 5.5 or later with support for ES2023. At the time of writing this release note, TypeScript 5.5 is in beta stage. Please don’t upgrade if you’re not fine with running a TypeScript beta version.


## [7.0.0](https://github.com/supercharge/tsconfig/compare/v6.0.0...v7.0.0) - 2023-10-15

### Added
- add [`skipLibCheck: true`](https://www.typescriptlang.org/tsconfig#skipLibCheck) rule
- add [`moduleDetection: 'force'`](https://www.typescriptlang.org/tsconfig#skipLibCheck) rule
## [6.0.0](https://github.com/supercharge/tsconfig/compare/v5.0.0...v6.0.0) - 2023-10-15

### Updated
- bump `target` and `lib` to Node.js 20
- bump `engine` property in `package.json` to `Node.js >= 20`
- change `module` from `CommonJS` to `ESNext`
- change `moduleResolution` from `Node` to `NodeNext`
- change `compilerOptions.lib` from `2022` to `2023`

### Breaking Changes
- target Node.js v20 with ESM


## [6.0.0](https://github.com/supercharge/tsconfig/compare/v5.0.0...v6.0.0) - 2023-10-15

### Updated
- bump `target` and `lib` to Node.js 20
- bump `engine` property in `package.json` to `Node.js >= 20`

### Breaking Changes
- target Node.js v20


## [5.0.0](https://github.com/supercharge/tsconfig/compare/v4.0.0...v5.0.0) - 2023-07-22

### Added
- add [`noImplicitReturns: true`](https://www.typescriptlang.org/tsconfig#noImplicitReturns) rule
- add [`noUncheckedIndexedAccess: true`](https://www.typescriptlang.org/tsconfig#noUncheckedIndexedAccess) rule
- add [`noFallthroughCasesInSwitch: true`](https://www.typescriptlang.org/tsconfig#noFallthroughCasesInSwitch) rule

### Updated
- bump `target` and `lib` to Node.js 18
- bump `engine` property in `package.json` to `Node.js >= 18`

### Breaking Changes
- target Node.js v18


## [4.0.0](https://github.com/supercharge/tsconfig/compare/v3.0.0...v4.0.0) - 2022-06-16

### Added
- add `allowUnreachableCode: false` rule
- add `forceConsistentCasingInFileNames: true` rule

### Updated
- bump `target` and `lib` to Node.js 16
- bump `engine` property in `package.json` to `Node.js >= 16`

### Breaking Changes
- target Node.js v16


## [3.1.0](https://github.com/supercharge/tsconfig/compare/v3.0.0...v3.1.0) - 2021-08-30

### Added
- add `DOM` and `DOM.Iterable` to libs
- add `noImplicitOverride: true` option
- add `engine` property to `package.json` requiring `Node.js >= 12`


## [3.0.0](https://github.com/supercharge/tsconfig/compare/v2.0.0...v3.0.0) - 2021-06-10

### Added
- target and libs require `es2020`, resolving to Node.js v14

### Breaking Changes
- target to Node.js v14


## [2.1.0](https://github.com/supercharge/tsconfig/compare/v2.0.0...v2.1.0) - 2021-08-30

### Added
- add `DOM` and `DOM.Iterable` to libs


## [2.0.0](https://github.com/supercharge/tsconfig/compare/v1.0.0...v2.0.0) - 2021-06-10

### Added
- required libs to to properly resolve Node.js v12

### Breaking Changes
- target to Node.js v12 instead of Node.js v8


## 1.0.0 - 2020-05-06

### Added
- `1.0.0` release 🚀 🎉
