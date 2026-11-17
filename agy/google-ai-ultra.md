# Claude Max 5x から Google AI Ultra に移行した話

## ターゲット

- google AI urtra を検討している人.

## TR;DR

- claude code -> antigravity cli
- youtube music で，spotify の課金を停止した．
- claude は，proプランで継続(hermesエージェント用)．

## Google AI Ultra について

Google AI Ultra は，Google One が提供する最上位の AI サブスクリプションプランです．フラッグシップの Gemini モデルや開発者向けエージェント環境「Google Antigravity」(CLI の `agy` を含む) の高い利用枠に加え，動画・画像生成ツール (Google Flow / Whisk) や大容量クラウドストレージ，YouTube Premium などがひとつにまとめられています．

- [Google One AI プラン公式ページ](https://one.google.com/about/google-ai-plans/)
- [Google Antigravity 料金・モデル一覧](https://antigravity.google/pricing)

同じ 100 ドル帯 (日本円では 14,500 円前後) の主要プランとして，**Claude Max (5x)** および **ChatGPT Pro 100** と付帯内容を比較すると次のようになります．

| 項目 | Google AI Ultra (5x) | Claude Max (5x) | ChatGPT Pro 100 |
| :--- | :--- | :--- | :--- |
| **月額料金 (目安)** | 14,500 円 (税込) | $100 | $100 |
| **コーディング CLI / 環境** | Antigravity CLI (`agy`) / IDE / SDK | Claude Code (Web・デスクトップと枠を共有) | Codex (ChatGPT ワークフローと枠を共有) |
| **主な利用可能モデル** | Gemini 4 Carbon / Argon / Hydrogen，Claude Sonnet / Opus 5.5 等 | Claude Opus / Sonnet 系 | GPT 系 / Pro 向け推論モデル |
| **利用枠・更新サイクル** | 5 時間ごとの高容量クォータ + 週間上限 (Pro の 5 倍相当) | Pro の 5 倍 (5 時間ローリング + 週間上限) | Plus の約 5 倍の Codex / ワークフロー枠 |
| **画像・動画生成** | Google Flow (Veo) / Whisk + 月次 AI クレジット | なし | 内蔵の画像生成 (テキストより枠を速く消費) |
| **その他付帯特典** | Google One 20 TB，YouTube Premium (YouTube Music 含む)，NotebookLM 上位枠 | 高負荷時の優先アクセス等 | ChatGPT クレジットによる超過延長等 |## 感想

- antigravity cli が良さげ．
