# peoplex

株式会社PeopleXの採用スカウト運用で使うプロンプト・ドキュメントを管理するリポジトリです。

## プロンプト

- [`prompts/youtrust-scout-generation.md`](prompts/youtrust-scout-generation.md) — YOUTRUST候補者向けスカウトメッセージ生成プロンプト（判定基準・メッセージ設計・除外ルール・ブラウザ操作時の注意事項を含む）
- [`prompts/scout-gpt/`](prompts/scout-gpt/) — **統合版：YOUTRUSTスカウトGPT**（スカウト生成v2＋スカウト相性チェッカー）。カスタムGPTに登録すれば、以後はGoogleスプレッドシートのURLを貼るだけで除外チェック・求人相性判定（A〜D）・1通目生成・xlsx納品まで実行
  - [`00_使い方.md`](prompts/scout-gpt/00_使い方.md) — 初回設定とスプレッドシートの作り方
  - [`01_GPT指示文.txt`](prompts/scout-gpt/01_GPT指示文.txt) — カスタムGPTの「指示」欄に貼る
  - [`02_統合ルール集.md`](prompts/scout-gpt/02_統合ルール集.md) — カスタムGPTの「知識」にアップロードする
  - `テンプレート_候補者.csv` / `テンプレート_求人.csv` — スプレッドシートの雛形
