# rust-handson

2018/12/15開催のRust入門者向けハンズオン #5向けリポジトリになります。

必要に応じてご利用ください。

## 使いかた

```bash
# 過去にwasm-bindgen-cliをインストールしている方はSKIPしてください
$ cargo +nightly install wasm-bindgen-cli
$ cargo +nightly build --target wasm32-unknown-unknown
$ wasm-bindgen target/wasm32-unknown-unknown/debug/rust_handson.wasm \
  --out-dir .
$ npm i
$ npm run serve
```

## 実行に必要なもの

* Rustのコンパイラ
  * [こちら](https://www.rust-lang.org/learn/get-started)を参考にしてください
* Node.js
  * [こちら](https://nodejs.org/ja/download/)を参考にしてください