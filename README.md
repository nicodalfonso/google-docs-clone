<h1 align="center">Welcome to google-docs-clone 👋</h1>
<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://mit-license.org/" target="_blank">
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/nicodalfonso" target="_blank">
    <img alt="Twitter: nicodalfonso" src="https://img.shields.io/twitter/follow/nicodalfonso.svg?style=social" />
  </a>
</p>
<p align="center">
  <img alt="Preview of google-docs-clone" src="./preview.gif" />
</p>

> A Google Docs Clone, made with React, Quill, MongoDB, and Sockect.IO, featuring persistent storage, autosaves, and unique document IDs.

## Prerequisites

- You have MongoDB installed and running locally.

## Install

```sh
cd client
yarn install

cd ../server
yarn install
```

## Usage

From the `server` directory, run

```sh
yarn run devStart
```

and from the `client` directory, run

```sh
yarn start
```

Document changes will persist upon page refresh.

To see these changes synced across browsers, copy and paste the full URL into a new browser, beginning with `localhost:3000`, and ending with the document's UUID.

To create a new document, visit `localhost:3000`, omitting a UUID.

## Author

👤 **Nico D Alfonso**

* Website: https://nicodalfonso.com
* Twitter: [@nicodalfonso](https://twitter.com/nicodalfonso)
* Github: [@nicodalfonso](https://github.com/nicodalfonso)
* LinkedIn: [@nicodalfonso](https://linkedin.com/in/nicodalfonso)

## 📝 License

Copyright © 2021 [Nico D Alfonso](https://github.com/nicodalfonso).<br />
This project is [MIT](https://mit-license.org/) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
