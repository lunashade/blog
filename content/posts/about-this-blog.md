---
title: "About This Blog"
date: 2020-10-06T20:03:06+09:00
tags: ["tech", "blog"]
draft: false
---
機運が出てきたのでブログ環境を作ることにした。

設定について。

## Github Actionsによるビルド

全面的にこちらのQiita記事[GitHub Actions による GitHub Pages への自動デプロイ](https://qiita.com/peaceiris/items/d401f2e5724fdcb0759d)を参考にした。

https://github.com/lunashade/blog で管理することにした。

## 記事の作成

基本`hugo new **.md`だけ知ってれば十分

ただまあ色々面倒なので、`cargo-make`を導入してやることにした。
`makers post <title>`でpostを作成してエディタが開く。

コマンドは色々と実装していこう…
