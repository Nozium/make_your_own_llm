# Make Your Own LLM

ChatGPTの会話履歴を使って、自分専用のLLMを簡単に作成できるノートブック集です。

## 特徴

- 初心者向けの日本語ガイド付き
- Google Colabで無料で実行可能
- ChatGPTエクスポートから直接学習データを作成

## ノートブック

| ファイル | 説明 | Colab |
|----------|------|-------|
| `gpt_oss_20b_finetuning_ja.ipynb` | 日本語版（ステップバイステップ） | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nozium/make_your_own_llm/blob/main/notebooks/gpt_oss_20b_finetuning_ja.ipynb) |
| `gpt_oss_20b_finetuning_gradio.ipynb` | Gradio UI版（GUI操作） | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nozium/make_your_own_llm/blob/main/notebooks/gpt_oss_20b_finetuning_gradio.ipynb) |

## 使い方

### 準備

1. ChatGPTから会話データをエクスポート
   - [ChatGPT](https://chat.openai.com) → Settings → Data controls → Export data
   - メールで届くZIPを解凍して `conversations.json` を取得

2. Google Colabでノートブックを開く
   - 上のColabバッジをクリック

3. GPUを有効化
   - ランタイム → ランタイムのタイプを変更 → T4 GPU

### 実行

**日本語版**: 「ランタイム」→「すべてのセルを実行」でサンプルデータで学習を試せます

**Gradio版**: UIが表示されるので、各タブで操作してください

## 必要環境

- Google アカウント
- Google Colab（無料版でOK）

## 謝辞

このプロジェクトは [Unsloth](https://github.com/unslothai/unsloth) のノートブックを元に作成しました。

## ライセンス

LGPL-3.0 License - 詳細は [LICENSE](LICENSE) を参照してください。
