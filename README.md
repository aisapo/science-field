# LEARBORATORY

GitHub Pages + Jekyll + Pages CMS で動かすサイエンスメディアです。

## CMS

Pages CMS: https://app.pagescms.org/

リポジトリに `.pages.yml` があるので、GitHubでログインして `aisapo/science-field` を開くと、`Articles` から記事を作成・編集できます。

記事本文は `_posts/` のMarkdownとして保存され、画像は `images/` に保存されます。

## 公開

GitHub Pages が `main` ブランチの root をソースにしていれば、コミット後にJekyllで自動ビルドされます。


## 追加機能

- ヘッダーの「管理」から Pages CMS を開けます。Pages CMS 側で GitHub 認証が必要です。
- 記事ページの「お気に入り」ボタンは、同じブラウザの `localStorage` に保存されます。
- トップページの「お気に入り」から保存した記事を一覧できます。
- 現時点では広告・アフィリエイト機能は含めていません。


### 画像について
Pages CMSの画像URLはGitHub Pagesのリポジトリ配下（/science-field/images/）を前提にしています。サムネイルはrelative_urlを二重適用せず、そのまま表示する設定です。
