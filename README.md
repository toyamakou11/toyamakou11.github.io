# 開発とアートの記録

Jekyll で作成した個人ブログです。開発とアート制作の記事を掲載します。

## ローカルで表示する

1. Ruby をインストールします。
2. `bundle install` を実行します。
3. `bundle exec jekyll serve` を実行します。
4. `http://127.0.0.1:4000` を開きます。

記事は `_posts` に追加します。ファイル名は `年-月-日-題名.md` にします。

```yaml
---
layout: post
title: 記事の題名
date: 2026-10-10 09:00:00 +0900
categories: [development]
---
```

開発記事には `development`、アート記事には `art` を指定します。

## GitHub Pages

`main` に変更を push すると、GitHub Actions がサイトをビルドして公開します。
リポジトリの Pages 設定で公開元に GitHub Actions を選びます。
