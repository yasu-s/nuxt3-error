# nuxt3-error

## 概要

- [Nuxt3](https://v3.nuxtjs.org/)のエラーページのサンプルです。

## 動作環境

- Node.js - 16.x
- Yarn - 1.22.x

## ライブラリ

- nuxt - 3.0.0-rc.3

## 動作確認

```bash
# パッケージインストール
yarn

# サーバー起動
yarn dev
```

## 実行結果

<img width="710" alt="スクリーンショット 2022-05-13 16 03 04" src="https://user-images.githubusercontent.com/2668146/168229880-bf961737-1422-4b05-a796-a9087c9719de.png">

## サンプルコード

**error.vue**

```vue
<script setup lang="ts">
const error = useError()
</script>

<template>
  <div>
    <ul>
      <li>{{ error.statusCode }}</li>
      <li>{{ error.message }}</li>
    </ul>
  </div>
</template>
```

## 参考URL

- https://v3.nuxtjs.org/guide/features/error-handling/

