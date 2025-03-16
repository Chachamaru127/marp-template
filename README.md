# Marpスライドテンプレート

このリポジトリは、[Marp](https://marp.app/)を使用して美しい日本語スライドを作成するためのテンプレートと設定を提供します。

## 特徴

- 一貫性のある美しいスライドデザイン
- 日本語フォントに最適化されたスタイル設定
- 効率的なSVG管理システム
- 様々なレイアウトテンプレート

## 使い方

1. リポジトリをクローンするか、ダウンロードします
2. `Test`ディレクトリにある例を参照してください
3. 新しいプレゼンテーションを作成するには、テンプレートをコピーして編集します

```bash
# HTML形式でプレビュー
npx @marp-team/marp-cli@latest プレゼンテーション_generated.md -o プレゼンテーション.html

# PDF出力
npx @marp-team/marp-cli@latest プレゼンテーション_generated.md --pdf --allow-local-files

# PowerPoint出力
npx @marp-team/marp-cli@latest プレゼンテーション_generated.md --pptx --allow-local-files
```

## ディレクトリ構造

- `Test/` - サンプルプレゼンテーション
- `themes/` - カスタムテーマ
- `marptemplate.mdc` - 詳細なテンプレートドキュメント

## ライセンス

MIT

## 貢献

問題やプルリクエストは歓迎します。 