# プロジェクト概要

このプロジェクトは、enno合同会社の公式ウェブサイトです。Jekyllを使用して構築され、GitHub Pagesでホスティングされています。

## ビルドと実行

### 依存関係のインストール

```bash
bundle install
```

### 開発サーバーの起動

```bash
bundle exec jekyll serve -P 8080
```

これにより、ローカルでサイトをプレビューできます（通常は `http://localhost:4000`）。

## デプロイ

このサイトはGitHub Pagesでホストされているため、`main` ブランチにプッシュすると自動的にデプロイされます。

## 主要ファイル

*   `_config.yml`: Jekyllサイトの全体的な設定ファイル。サイトのタイトルやURLなどが定義されています。
*   `index.markdown`: トップページのコンテンツです。
*   `404.html`: 404エラーページ。
*   `CNAME`: GitHub Pagesでカスタムドメインを設定する場合に使用。
*   `Gemfile`: Rubyの依存関係（Jekyll、プラグインなど）を管理します。
*   `_layouts/`: サイトのレイアウトを定義するファイル群を含むディレクトリ。
*   `assets/`: CSSや画像などの静的アセットを含むディレクトリ。
