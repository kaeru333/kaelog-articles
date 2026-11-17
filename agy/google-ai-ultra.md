# Claude Max 5x から Google AI Ultra に移行した話

## ターゲット

- google AI urtra を検討している人.

## TR;DR

- claude code → antigravity cli
- youtube music で，spotify の課金を停止した．
- claude は，proプランで継続(hermesエージェント用)．

## Google AI Ultra について

Google AI Ultra は，Google One が提供する最上位の AI サブスクリプションプランだよ．


- [Google One AI プラン公式ページ](https://one.google.com/about/google-ai-plans/)
- [Google Antigravity 料金・モデル一覧](https://antigravity.google/pricing)

同じ 100 ドル帯 (日本円では 14,500 円前後) の主要プランとして，**Claude Max (5x)** および **ChatGPT Pro 100** と付帯内容を比較すると次のようになります．

| 項目 | Google AI Ultra (5x) | Claude Max (5x) | ChatGPT Pro 100 |
| :--- | :--- | :--- | :--- |
| **月額料金 (税込目安)** | 14,500 円 | $110 ($100 + 日本消費税 10%) | 約 16,800 円 ($100 帯) |
| **コーディング CLI** | Antigravity CLI (`agy`) | Claude Code CLI | Codex CLI |
| **IDE・アプリ連携** | Antigravity App / IDE 拡張 (VS Code 等) / SDK | Claude Code IDE 拡張・デスクトップ / Web | Codex IDE 拡張 / ChatGPT アプリ・Web |
| **軽量モデル (高速)** | Gemini 4 Hydrogen | Claude Haiku 5.5 | GPT-6 Luna |
| **主力モデル (日常)** | Gemini 4 Argon | Claude Sonnet 5.5 / Opus 5.5 | GPT-6.1 Sol / GPT-6.1 Terra |
| **最上位モデル (重作業)** | Gemini 4 Carbon / Orchestrator (Carbon) | Claude Fable 5.2 | GPT-6 Astra |
| **利用枠** | 5h / 1w | 5h / 1w | 1w のみ |
| **画像生成** | Nano Banana Pro (Gemini 3 Pro Image) | なし | GPT Image |
| **動画生成** | Veo 3.1 | なし | なし |
| **その他付帯特典** | Google One 20 TB，YouTube Premium (YouTube Music 含む)，Google Colab (毎月の計算単位・優先 GPU・バックグラウンド実行)，毎月の Google Cloud クレジット，Google Health Premium (旧 Fitbit Premium)，Gemini Notebook (旧 NotebookLM) 上位枠 | 高負荷時の優先アクセス等 | ChatGPT クレジットによる超過延長等 |

## 感想

- antigravity cli が良さげ．
- colab, Google Cloud で個人開発がはかどる．
