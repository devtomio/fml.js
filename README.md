# fml.js

> API Wrapper for <https://fmylife.com>

<div align="center">
	<p>
  		<a href="https://www.npmjs.com/package/@1chi/fml.js"><img src="https://img.shields.io/npm/v/@1chi/fml.js.svg?maxAge=3600" alt="NPM version" /></a>
  		<a href="https://www.npmjs.com/package/@1chi/fml.js"><img src="https://img.shields.io/npm/dt/@1chi/fml.js?maxAge=3600" alt="NPM downloads" /></a>
  		<a href="https://david-dm.org/1chiSensei/@1chi/fml.js"><img src="https://david-dm.org/1chiSensei/fml.js/status.svg?maxAge=3600" alt="Dependencies" /></a>
 	</p>
 	<p>
  		<a href="https://nodei.co/npm/@1chi/fml.js/"><img src="https://nodei.co/npm/@1chi/fml.js.png?downloads=true&stars=true" alt="NPM info" /></a>
 	</p>
</div>

## Features

- Actually maintained
- Uses async/await
- Has support for ESM and CJS

## Install

```bash
npm i @1chi/fml.js # NPM
yarn add @1chi/fml.js # Yarn
pnpm add @1chi/fml.js # PNPM
```

## Usage

```js
import fml from '@1chi/fml.js'; // import syntax
const fml = require('@1chi/fml.js').default; // require()

// Async/Await
async () => {
	const quote = await fml();

	console.log(quote);
};

// .then()
fml().then((quote) => console.log(quote));
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

**fml.js** © [Yoshida Tomio](https://github.com/1chiSensei), Released under the [Apache-2.0](https://github.com/1chiSensei/fml.js/blob/main/LICENSE) License.<br>
Authored and maintained by 1chiSensei.

> GitHub [@1chiSensei](https://github.com/1chiSensei)
> Discord https://discord.gg/zGvtAnGhdP
