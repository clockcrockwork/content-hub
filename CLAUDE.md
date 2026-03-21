# Content Hub — エージェント規約（公開版）

## プロジェクト概要
全GHAワークフローの実行エンジン。コンテンツ実体（blog/note無料部分/x/tiktok）を管理。
Astro + Cloudflare Pagesでブログをホスティング。

## ディレクトリ構成
- src/content/blog/ : Astro Content Collectionsで管理するブログ記事
- content/note/ : note用コンテンツ（★ 無料部分のみ。有料部分はcontent-hub-private）
- content/x-twitter/ : X/Twitter投稿の下書き
- content/tiktok/ : TikTok動画の台本・キャプション
- .github/workflows/ : 全GHAワークフロー（AIパイプライン含む）
- scripts/ : パブリック側のユーティリティスクリプト

## 重要
- このリポジトリはパブリック。GHAログも公開される
- 秘匿情報（プロンプト・口調ポリシー・APIキー）をログに出力しないこと
- 有料コンテンツはここに置かない（content-hub-privateに保管）
- Issueはここに起票しない（content-hub-privateに集約）
