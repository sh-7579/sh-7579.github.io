# sh-7579.github.io

個人サイト用のレポジトリです．

🔗 https://sh-7579.github.io

## 概要

- 東北大学大学院情報科学研究科 修士課程
- 研究分野：自然言語処理（NLP）、大規模言語モデルの解釈可能性
- [al-folio](https://github.com/alshedivat/al-folio) テーマ（Jekyll）をベースに構築

## 使用技術

- [Jekyll](https://jekyllrb.com/) — 静的サイトジェネレーター
- [al-folio](https://github.com/alshedivat/al-folio) — Jekyllテーマ
- [GitHub Pages](https://pages.github.com/) — ホスティング
- Docker — ローカル開発環境

## ディレクトリ構成

```
_pages/       # 各ページのコンテンツ（about, cv など）
_posts/       # ブログ記事
_projects/    # プロジェクト一覧
_bibliography/ # 論文リスト（BibTeX）
assets/       # 画像・CSS・JS
_config.yml   # サイト全体の設定
```

## ローカル開発

```bash
docker compose up
# http://localhost:8080 で確認
```

## ライセンス

サイトのコンテンツは著作権で保護されています。
テーマ部分（al-folio）は [MIT License](LICENSE) に基づきます。
