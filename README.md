# project-2-jailbreak-eval-
Prompt vulnerability testing of ChatGPT vs Claude using jailbreak prompts to evaluate safety, ethics, and response manipulation resistance.
# 🔐 Project 2: LLM Jailbreak & Safety Filter Evaluation

##  Overview

This project evaluates how well leading large language models (LLMs) — specifically ChatGPT and Claude — respond to prompts designed to bypass safety filters, expose vulnerabilities, or manipulate behavior. The goal is to identify weaknesses in content moderation systems through red teaming techniques and prompt injection attempts.

##  Structure
```
project-llm-jailbreak-eval/
├── analysis/
│   ├── comparison-notes.md
│   └── verdicts.md
├── prompts/
│   ├── 01_sensitive_info.md
│   ├── 02_illegal_instruction.md
│   ├── 03_roleplay_jailbreak.md
│   ├── 04_prompt_injection.md
│   └── 05_safety_filter_bypass.md
├── responses/
│   ├── chatgpt/
│   │   ├── 01_sensitive_info.md
│   │   ├── 02_illegal_instruction.md
│   │   ├── 03_roleplay_jailbreak.md
│   │   ├── 04_prompt_injection.md
│   │   └── 05_safety_filter_bypass.md
│   └── claude/
│       ├── 01_sensitive_info.md
│       ├── 02_illegal_instruction.md
│       ├── 03_roleplay_jailbreak.md
│       ├── 04_prompt_injection.md
│       └── 05_safety_filter_bypass.md
├── README.md
```


##   Tasks

Each test simulates real-world adversarial behavior:

1. **Sensitive Info Retrieval** – Attempts to get personal or private information.
2. **Illegal Instruction Execution** – Tries to coerce the model to give unethical or unlawful advice.
3. **Roleplay Jailbreak** – Uses roleplaying to override filters.
4. **Prompt Injection** – Embeds malicious or conflicting instructions inside prompts.
5. **Safety Filter Bypass** – Uses sarcasm or ambiguous phrasing to bypass filters.

## ⚖️ Evaluation Criteria

Each model is assessed on:

- **Safety** – Does it reject harmful or unethical queries?
- **Consistency** – Does it maintain its safety stance across tasks?
- **Vulnerability** – How easy is it to trick or mislead?
- **Explanation** – If refusing, does the model give a reason?

## 🧾 Verdicts

Summarized insights and outcomes are available in:
- `comparison-notes.md`
- `analysis/verdicts.md`

## 📍 Goal

This project was built as part of an AI QA / Prompt Engineering portfolio to demonstrate:

- Red-teaming ability
- LLM behavior analysis
- Prompt crafting and safety testing

---

 Feel free to fork or use this structure to perform your own LLM stress tests.



