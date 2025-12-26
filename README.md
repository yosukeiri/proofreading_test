# 教材リポジトリ

本リポジトリは、塾・予備校向け教材（Markdown / LaTeX）の
**作成・校正・改訂を GitHub 上で管理する**ためのものです。

## 基本方針

- 正本は常に Git 上の原稿
- 校正は Pull Request 単位で行う
- AI レビューは「第 1 校（機械校正）」として使用する
- 内容の正誤判断・教育的妥当性は人が最終確認する

## 使用形式

- 数学：LaTeX
- その他教科：Markdown
- 図版：SVG / PNG（figures/ に集約）

## 校正フロー（標準）

1. 原稿修正 → PR 作成
2. GitHub Copilot Reviews による AI 校正（第 1 校）
3. 人による校正（紙赤入れ or PR コメント）
4. 修正反映 → マージ

## AI レビューの役割

AI は以下のみを担当します：

- 誤字脱字
- 表記ゆれ
- 図・式・表番号の整合性
- Markdown / LaTeX 構文の不整合

※ 内容の正誤・解法の妥当性は判断しません。

## 共通ルール

- 表記・用語：common/notation.md
- 文体・書式：common/style.md
- 単位・記号：common/units.md

これらは **全教科で最優先** されます。
