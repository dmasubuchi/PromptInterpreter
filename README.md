
# README.md

## Why Prompt Interpreter?

プロンプトインタプリタは、相談や資料を整理し、他のAIが正しく動くための指示プロンプトを自動生成するツールです。
日本語こちら 👉 Japanese version available: [README-JP.md](./README-JP.md)


Working with generative AI often begins with enthusiasm and ends with frustration.
Why? Because the first barrier is not the AI itself—it’s the *prompt*.

* Write too vaguely, and the AI misunderstands your intent.
* Paste long documents without context, and you get half-baked answers.
* Ask ten people to write a “good prompt,” and you’ll get ten completely different styles—some usable, some not at all.

The result? Endless rework, wasted hours, and the sinking feeling of “AI was supposed to save me time, not cost me more of it.”

---

## Enter the Prompt Interpreter

The **Prompt Interpreter** was designed to solve this exact pain.
Think of it as a **translator between your messy thoughts and the AI’s strict instructions**.

Here’s what it does:

1. **Diagnose** your input

   * Splits apart vague wording, missing details, and contradictions.
   * Shows progress via small 🤖 “robot asides,” so you always know what it’s doing.

2. **Supplement & confirm**

   * Drops in 💡 “assumptions” to fill obvious gaps.
   * If something important is missing, it politely asks you to add or re-attach.

3. **Summarize documents**

   * If you provide multiple files or long notes, it creates a **consolidated summary**—tidy but never omitting key information.

4. **Infer domain silently**

   * Business, education, technology… the Interpreter guesses your domain and subtly adds relevant angles without breaking generality.

5. **Output in two layers**

   * \[📝 Core] → the lean, minimal set you can hand to another AI immediately.
   * \[📚 Detail] → the full-fledged prompt, with constraints, success criteria, and context baked in.

---

## Why is this valuable?

* **Less rework** – No more starting over because the AI “didn’t get it.”
* **Speed** – First align on the core skeleton, then dive into detail.
* **Reproducibility** – Removes the personal “prompting style” bias; everyone can generate consistent, usable prompts.
* **Safety** – Instead of guessing, it lists *exact missing items* and asks for clarification.
* **Flexibility** – Domain-agnostic, but smart enough to enrich context when needed.

For business users, this means proposal drafts, meeting notes, or research briefs are prepared for AI execution without hours of back-and-forth. For educators, it means lesson design that doesn’t get lost in translation. For tech teams, it means requirements and investigations get structured cleanly, even from messy source material.

---

## Quickstart

You can use Prompt Interpreter in **two ways**:

1. **As a MyGPT (recommended)**

   * Create a custom GPT in ChatGPT → Paste in the instructions from [`MyGPT-instruct-EN.md`](./MyGPT-instruct-EN.md).
   * Follow the setup steps in [`MyGPT-setup-EN.md`](./MyGPT-setup-EN.md).
   * You’ll get the full experience: startup UI, state management, mini-UI prompts when needed.

2. **Copy-paste into regular ChatGPT**

   * Don’t know what MyGPT is? No problem.
   * Simply copy the instruction prompt and paste it directly into a standard ChatGPT chat.
   * It behaves slightly differently (no auto-start UI, state less visible), but the **diagnose → supplement → confirm → build** flow still works.

---

## File structure

* [`README.md`](./README.md) … English documentation (this file)
* [`README-JP.md`](./README-JP.md) … Japanese documentation
* [`MyGPT-setup-EN.md`](./MyGPT-setup-EN.md) … Setup guide for MyGPT (English)
* [`MyGPT-setup-JP.md`](./MyGPT-setup-JP.md) … Setup guide for MyGPT (Japanese)
* [`MyGPT-instruct-EN.md`](./MyGPT-instruct-EN.md) … Instruction prompt (English)
* [`MyGPT-instruct-JP.md`](./MyGPT-instruct-JP.md) … Instruction prompt (Japanese)

---

## Important notes

* **Costs** → Usage depends on each user’s ChatGPT plan (Free, Plus, Team, Enterprise). The creator does **not** pay for other people’s usage.
* **Languages** → This repository provides both English and Japanese versions. Choose what fits your workflow.
* **Information handling** → Only paste information you’re comfortable sharing. The Interpreter organizes and clarifies, but does not magically sanitize confidential material.

---

## Final word

Prompt Interpreter is not another static “prompt library.”
It’s a **dynamic companion** that listens, diagnoses, and helps you produce **AI-ready instructions**.

Think of it as the friendly colleague who takes your rough notes and turns them into a clean brief—except this colleague never gets tired, never judges, and always leaves a little 🤖 aside to let you know what’s happening.

👉 For Japanese version, see [README-JP.md](./README-JP.md).

---

