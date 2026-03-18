# comfyui-jp-prompt-translator
日本語自然言語→SDXLやPonyへのプロンプト変換

> 🚧 Work In Progress / 開発中

## 概要 / Overview

日本語の自然言語でプロンプトを入力すると、
SDXL・Pony向けの英語プロンプトに自動変換し、
ポジティブ・ネガティブに分けてテキストエンコーダに渡す
ComfyUIカスタムノードです。

A ComfyUI custom node that converts Japanese natural language input
into optimized English prompts for SDXL/Pony models,
automatically split into positive and negative encoders.

## 特徴 / Features

- 日本語で直感的にプロンプトを記述できる
- SDXL・Pony両モデルに対応した最適化
- ポジティブ・ネガティブの自動分離
- ローカルLLM（Ollama）対応でAPIキー不要

## 開発状況 / Status

- [ ] 基本ノード構造
- [ ] LLM連携（Ollama）
- [ ] SDXL用プロンプト最適化
- [ ] Pony用プロンプト最適化
- [ ] サンプル画像

## 作者 / Author

ご意見・ご要望はIssueまでお気軽にどうぞ。
