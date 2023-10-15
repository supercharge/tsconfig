<div align="center">
  <a href="https://superchargejs.com">
    <img width="471" style="max-width:100%;" src="https://superchargejs.com/images/supercharge-text.svg" />
  </a>
  <br/>
  <br/>
  <p>
    <h3>Supercharge shareable TypeScript Config</h3>
  </p>
  <p>
    Shared TypeScript config for Supercharge projects
  </p>
  <br/>
  <p>
    <a href="#installation"><strong>Installation</strong></a> ·
    <a href="#usage"><strong>Usage</strong></a>
  </p>
  <br/>
  <br/>
  <p>
    <a href="https://www.npmjs.com/package/@supercharge/tsconfig"><img src="https://img.shields.io/npm/v/@supercharge/tsconfig.svg" alt="Latest Version"></a>
    <a href="https://www.npmjs.com/package/@supercharge/tsconfig"><img src="https://img.shields.io/npm/dm/@supercharge/tsconfig.svg" alt="Monthly downloads">
  </p>
  <p>
    <em>Follow <a href="http://twitter.com/marcuspoehls">@marcuspoehls</a> and <a href="http://twitter.com/superchargejs">@superchargejs</a> for updates!</em>
  </p>
</div>

---

## Installation

```
npm i -D @supercharge/tsconfig
```


## Targets

| Major Release | Node.js version | Module System |
| ------------- | --------------- | ------------  |
| `6.x`         | `20.x`          | CommonJS      |
| `5.x`         | `18.x`          | CommonJS      |
| `4.x`         | `16.x`          | CommonJS      |
| `3.x`         | `14.x`          | CommonJS      |
| `2.x`         | `12.x`          | CommonJS      |
| `1.x`         | `8.x`           | CommonJS      |


## Usage
Create a `tsconfig.json` file in your project and extends the `@supercharge/tsconfig` [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html):

### Basic Usage
When installed, configure your `tsconfig.json` like this:

```json
{
  "extends": "@supercharge/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```


### Refined Configuration
You can refine your `tsconfig.json` to your needs. Let’s say you want to target Node.js v14 instead of v12 (which is the default). Change your `compilerOptions` to this:

```json
{
  "extends": "@supercharge/tsconfig",
  "display": "Node 16",

  "compilerOptions": {
    "outDir": "dist",
    "lib": ["es2021"],
    "target": "es2021",
  }
}
```

Customizing your `compilerOptions` when extending the `@supercharge/tsconfig` package only overrides the listed properties. Every other option defined in the base configuration will be inherited.


## Contributing

1.  Create a fork
2.  Create your feature branch: `git checkout -b my-feature`
3.  Commit your changes: `git commit -am 'Add some feature'`
4.  Push to the branch: `git push origin my-new-feature`
5.  Submit a pull request 🚀


## License
MIT © [Supercharge](https://superchargejs.com)

---

> [superchargejs.com](https://superchargejs.com) &nbsp;&middot;&nbsp;
> GitHub [@supercharge](https://github.com/supercharge) &nbsp;&middot;&nbsp;
> Twitter [@superchargejs](https://twitter.com/superchargejs)
