
# 📘 README (日本語)

## プロンプトインタプリタ v1.5

**概要**
プロンプトインタプリタは、ユーザーの相談や資料を整理し、他のAIが正しく動作するための指示プロンプトに変換するシステムです。入力内容を診断し、不足情報や曖昧さを検出して補足仮説を提示し、必要に応じて追加資料を求めます。最終的に、\[📝骨子]（最小構成）と\[📚詳細]（完成版）の二層構造で出力します。

**特徴**

* 🤖 独り言で進行状況を提示
* 💡 備考として仮置きメモを提示（任意で読む補足）
* 外部資料がある場合は自動で統合サマリーを作成
* 内部的にドメインを推定し、関連する観点を自然に追加
* gaps（不足情報）が多い場合は、不足項目を具体的に指摘して再添付を依頼

**利用シーン**

* ビジネス文書の下準備
* 教育・教材設計
* 技術調査やレポート整理
* 会議記録や要件定義のプロンプト化

---

### 注記

このプロンプトインタプリタは **日本語での利用を前提に設計**されています。英語環境でも利用可能ですが、最適な動作は日本語入力で保証されます。

---

# 📘 README (English)

## Prompt Interpreter v1.5

**Overview**
The Prompt Interpreter organizes user queries and documents into actionable instructions for other AIs. It diagnoses inputs, detects missing or ambiguous elements, proposes assumptions, and—if necessary—requests additional files. Outputs are always presented in two layers: \[📝Core] for minimal sets and \[📚Detail] for complete prompts.

**Key Features**

* 🤖 One-line “robot asides” to indicate progress
* 💡 Optional notes for assumptions and hints
* Automatic **consolidated summaries** when external materials are provided
* **Domain inference** (business, education, tech, etc.) to enrich context naturally
* When gaps are significant, missing items are explicitly listed and re-attachment is requested

**Use Cases**

* Preparing business proposals
* Curriculum or training material design
* Technical research and reporting
* Converting meeting notes or requirement docs into structured prompts

---

### Note

This Prompt Interpreter is **designed primarily for Japanese-language use**. While it can be used in English, its optimal functionality is guaranteed with Japanese inputs.
次は **「利用例（サンプル入出力）」** を追加して、READMEをより実務的にしましょうか？
