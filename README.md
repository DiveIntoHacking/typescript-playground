# TypeScript Playground

## 目的

本リポジトリは、TypeScript の実行環境を提供するものです。
以下の手順で環境をセットアップしてご使用ください。

## セットアップ手順

```
$ git clone git@github.com:DiveIntoHacking/typescript-playground.git
$ cd typescript-playground
$ npm install
```

## nodemon を使用した TypeScript ファイルの実行

src 配下に hello-typescript.ts というファイルがあるので以下の実行例にならって実行してみてください。
下の例の様に'Hello, TypeScript!'と表示されたらオッケーです。
あとは適宜 ts ファイルなり tsx ファイルなりを引数に与えて遊んでください。

```
$ npx nodemon --exec ts-node -- src/hello-typescript.ts
[nodemon] 1.19.1
[nodemon] to restart at any time, enter `rs`
[nodemon] watching: *.*
[nodemon] starting `ts-node src/hello-typescript.ts`
{ message: 'Hello, TypeScript!' }
[nodemon] clean exit - waiting for changes before restart
```
