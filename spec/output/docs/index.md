# 要件定義書 インデックス

- Batch converted at: `2026-07-14T04:21:25.387065+00:00`
- 変換ファイル数: 1 (1 完了 / 0 処理待ち)

## ドキュメント一覧

| ドキュメント | 説明 | 主な利用者 |
| --- | --- | --- |
| [業務要件](business-requirements.md) | 対象業務・ステークホルダー・ユーザーストーリー・業務フロー | PO / BA / 開発者 |
| [機能要件](functional-requirements.md) | 機能一覧(MoSCoW)・データモデル・非機能要件 | 開発者 / アーキテクト |
| [設計要件](design-requirements.md) | 全体構成・コンポーネント・リスク・実装タスク分解 | アーキテクト / 開発者 |
| [テスト要件](test-requirements.md) | テストシナリオ・受け入れ条件・非機能テスト | QA / 開発者 |

## 処理状況

- Batch converted at: `2026-07-14T04:21:25.387065+00:00`
- Files: 1

| Source | Staging markdown | Status | Note |
| --- | --- | --- | --- |
| `20260714_ TMI_調達ナレッジ資産化.pdf` | `20260714_ TMI_調達ナレッジ資産化.pdf.MD` | `completed` | Microsoft Japan 提案資料（調達ナレッジ資産化・AI活用構想） |

## 開発利用フロー

1. `spec/output/staging/` の変換完了を確認する（`conversion-checklist.json` で `is_completed=true`）
2. staging の内容を元に各 docs の `要確認` を実際の要件に更新する
3. 機能要件の MoSCoW 優先度を PO と合意する
4. 設計要件の実装タスク分解を確定させ、開発に着手する
5. テスト要件の受け入れ条件を機能要件と紐付ける
6. 変更が発生した場合は各 docs の **要件変更履歴** に記録する

## 備考

- 情報不足は推測せず `要確認` として残すこと
- `要確認` が残っているセクションは必ず PO / BA と確認すること
- 2026-07-14 現在の情報が反映されています
