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
| `session5.html` | 番外編: 秘密情報とAIの使い方（秘密情報を渡す前に読んでもらう） |

第4回終了時点で、要件定義書（別リポジトリ）を渡す想定です。

## 編集するときの注意

- 全回で共通のCSS（スライド枠・フッター・メニュー・`.note`・`.step-card`など）は `assets/css/common.css` にまとめています。デザインを変える場合はここを直せば全回に反映されます
- 回ごとに違うCSS（`.cmd`・用語カード・`details.more`など）は、各HTMLファイルの `<style>` に残しています。JSは今も各ファイルに埋め込まれているため、変える場合は複数ファイルへの重複反映が必要です
- 画像は `assets/images/<回>/` に置きます
- 実際の開発環境（`docker-compose.yml`のポート番号、npmスクリプト名など）に変更があった場合は、`session2.html`の手順もあわせて更新してください
- このリポジトリはPublicです。スライドに実際のIDやパスワード、スプレッドシート名、個人名を書かないでください（例はダミーの値にする）
