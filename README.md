# Shuffle Array (JavaScript)

[**⚖️** MIT](./LICENSE.md)

**🗂️**
[![GitHub: hugoalh-studio/shuffle-array-js](https://img.shields.io/badge/hugoalh--studio/shuffle--array--js-181717?logo=github&logoColor=ffffff&style=flat "GitHub: hugoalh-studio/shuffle-array-js")](https://github.com/hugoalh-studio/shuffle-array-js)
[![NPM: @hugoalh/shuffle-array](https://img.shields.io/badge/@hugoalh/shuffle--array-CB3837?logo=npm&logoColor=ffffff&style=flat "NPM: @hugoalh/shuffle-array")](https://www.npmjs.com/package/@hugoalh/shuffle-array)

**🆙** ![Latest Release Version](https://img.shields.io/github/release/hugoalh-studio/shuffle-array-js?sort=semver&color=2187C0&label=&style=flat "Latest Release Version") (![Latest Release Date](https://img.shields.io/github/release-date/hugoalh-studio/shuffle-array-js?color=2187C0&label=&style=flat "Latest Release Date"))

A JavaScript module to shuffle the array's indexes.

## 🎯 Target

- Bun ^ v1.0.0
- Cloudflare Workers
- Deno >= v1.34.0
  > **🛡️ Require Permission**
  >
  > *N/A*
- NodeJS >= v16.13.0

### 🔗 Other Edition

- [TypeScript](https://github.com/hugoalh-studio/shuffle-array-ts)

## 🔰 Usage

### Via Installation

> **🎯 Supported Target**
>
> - Cloudflare Workers
> - NodeJS

1. Install via console/shell/terminal:
    - Via NPM
      ```sh
      npm install @hugoalh/shuffle-array[@<Tag>]
      ```
    - Via PNPM
      ```sh
      pnpm add @hugoalh/shuffle-array[@<Tag>]
      ```
    - Via Yarn
      ```sh
      yarn add @hugoalh/shuffle-array[@<Tag>]
      ```
2. Import at the script (`<ScriptName>.js`):
    ```js
    import ... from "@hugoalh/shuffle-array";
    ```
    > **ℹ️ Note**
    >
    > Although it is recommended to import the entire module, it is also able to import part of the module with sub path if available, please visit [file `package.json`](./package.json) property `exports` for available sub paths.

### Via NPM Specifier

> **🎯 Supported Target**
>
> - Bun
> - Deno

1. Import at the script (`<ScriptName>.js`):
    ```js
    import ... from "npm:@hugoalh/shuffle-array[@<Tag>]";
    ```
    > **ℹ️ Note**
    >
    > Although it is recommended to import the entire module, it is also able to import part of the module with sub path if available, please visit [file `package.json`](./package.json) property `exports` for available sub paths.

## 🧩 API

- ```ts
  function shuffleArray<T>(item: T[]): T[];
  ```

## ✍️ Example

- ```js
  const chain = [3, 7, 25, 26, 42, 62, 71, 76, 92, 93];

  shuffleArray(chain);
  //=> [62, 93, 26, 42, 25, 7, 76, 71, 3, 92]

  shuffleArray(chain);
  //=> [42, 3, 26, 62, 93, 7, 76, 25, 92, 71]
  ```
