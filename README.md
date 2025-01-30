## 概要

以下のテックブログの問題点を改修

https://github.com/kyoto-kanko/kyoto-kanko-tech-blog

## 問題点

- ヘッドレスCMSの導入をしたが、記事の表示に時間がかかってしまいSEOが悪化
- 記事を書く際に、バージョンが管理できないので、記事の差分管理が難しい
- SSRをするためにAmplifyを導入したが、料金が高い

## 改修案

- ヘッドレスCMSをやめて、記事を静的ファイルとして配信する
- SSR -> SSG

## 利用サービス(仮)

- Cloudflare Pages
- React 19
- Next.js 15
