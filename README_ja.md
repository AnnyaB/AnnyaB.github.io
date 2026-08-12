# Academic Homepage

\[[ホームページ](https://annyab.github.io/)\]  \[[English](./README.md)\]

このリポジトリには、**Riya Basak の学術ホームページ**のソースコードが含まれています。

サイトは、オープンソースの Jekyll テーマ
[Minimal Light](https://github.com/yaoyao-liu/minimal-light)
を使用し、GitHub Pages で公開しています。

## 主な機能

- シンプルな学術ホームページ構成
- Jekyll / GitHub Pages による公開
- デスクトップ・モバイル対応
- ライトモード・ダークモード対応
- Markdown ベースのコンテンツ管理
- `_config.yml` による SEO メタデータ設定
- リポジトリ内 CV ファイルへの直接リンク
- `_includes` を用いた研究内容の分離管理

## リポジトリ構成

```text
.
├── _includes/
│   └── research.md
├── assets/
│   └── files/
│       └── riya-basak-cv.pdf
├── .gitignore
├── Gemfile
├── README.md
├── README_ja.md
├── _config.yml
└── index.md
```

## 公開先

```text
https://annyab.github.io/
```

`main` ブランチのリポジトリルートから GitHub Pages として公開しています。

## テーマ設定

```yaml
remote_theme: yaoyao-liu/minimal-light
```

ホームページ本文は `index.md`、研究内容は `_includes/research.md`、
個人情報・リンク・テーマ設定は `_config.yml` で管理しています。

## ローカルでの確認

Ruby と Bundler をインストールした環境で以下を実行します。

```bash
bundle install
bundle exec jekyll serve
```

その後、ブラウザで次を開きます。

```text
http://localhost:4000
```

## 謝辞

このホームページは
[Yaoyao Liu の Minimal Light](https://github.com/yaoyao-liu/minimal-light)
Jekyll テーマを使用しています。

また、同じ Minimal Light テーマを利用している
[Dongkeun Yoon の公開ホームページ・リポジトリ](https://github.com/MattYoon/mattyoon.github.io)
の簡潔な学術ホームページ構成を参考にしています。
同リポジトリの個人情報、研究内容、業績、経歴は本サイトでは使用していません。

Minimal Light は以下のオープンソース・プロジェクトも参照しています。

- [pages-themes/minimal](https://github.com/pages-themes/minimal)
- [orderedlist/minimal](https://github.com/orderedlist/minimal)
- [al-folio](https://github.com/alshedivat/al-folio)

## ライセンスと帰属

テーマ部分には、上流の
[Minimal Light repository](https://github.com/yaoyao-liu/minimal-light)
のライセンス条件が適用されます。
このサイト固有のコンテンツとアセットの権利は、それぞれの所有者に帰属します。
