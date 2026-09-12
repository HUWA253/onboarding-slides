# onboarding-slides

サークルアプリ（[myapp_v2_gas](https://github.com/HUWA253/circle-app-v2)）開発への後輩オンボーディング用スライド集。GitHub Pagesで公開しています。

## 公開URL

https://huwa253.github.io/onboarding-slides/

## 構成

矢印キー/ボタンでページ送りできる、全画面表示対応のHTMLスライドです。ビルド不要、静的ファイルをそのままGitHub Pagesで配信しています。

| ファイル | 内容 |
|---|---|
| `index.html` | 各回へのリンク一覧 |
| `session0.html` | 第0回: キックオフ・利用体験会 |
| `session1.html` | 第1回: Git/GitHub基礎会 |
| `session2.html` | 第2回: 開発環境構築会（Codespaces / Docker） |
| `session3.html` | 第3回: コードリーディング＆最初のタスク会 |
| `session4.html` | 第4回: PR・レビュー実践会 |

第4回終了時点で、要件定義書（別リポジトリ）を渡す想定です。

## 編集するときの注意

- 各スライドは1つのHTMLファイルに完結しています。共通のCSS/JSも各ファイルに埋め込まれているため、デザインを変える場合は複数ファイルへの重複反映が必要です
- 実際の開発環境（`docker-compose.yml`のポート番号、npmスクリプト名など）に変更があった場合は、`session2.html`の手順もあわせて更新してください
