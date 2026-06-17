# Humanize Chinese Writing

Humanize Chinese Writing is a Codex skill for reviewing and polishing Chinese prose so it reads more naturally, plainly, and less formulaically. It is designed for Chinese academic papers, literature essays, reports, summaries, and formal prose that needs a more human writing rhythm.

## What It Does

This skill helps an agent revise Chinese writing with attention to the following areas.

1. Structure and argument flow
2. Sentence rhythm and variation
3. Overly formulaic phrasing
4. Punctuation discipline
5. Evidence chains in academic writing
6. Literature review integration
7. Removal of prompt traces and process language

## Core Style Rules

The skill is built around a specific set of Chinese writing preferences.

1. Write plainly and naturally. Avoid decorative language, stiff templates, and obvious generated prose.
2. Avoid fixed contrast templates such as “不是……而是……”“并非……而是……”“并不只是……它……”。
3. Do not overcorrect into short, broken sentences. Important arguments should use coherent medium length sentences when needed.
4. Never use Chinese dash punctuation. Use sentence structure and connective language instead.
5. Avoid using colons for routine explanation, setup, summary, and transition. Keep them only for necessary cases such as titles, bibliography formats, and quoted speech.
6. Avoid excessive parentheses in formal Chinese writing.
7. Use Chinese punctuation in Chinese prose. Do not mix in English punctuation or English quotation marks.
8. Use semicolons sparingly. Prefer connective wording and natural sentence order.
9. Avoid unnecessary Chinese English mixing in formal prose.
10. For academic writing, every attributed claim must be traceable to source evidence.

## When To Use

Use this skill when the user asks for any of the following.

1. 去ＡＩ味
2. 中文文风润色
3. 论文润色
4. 文献综述改写
5. 标点审查
6. 句式调整
7. 降低机器生成痕迹
8. 把中文写得更自然

## Skill Files

The main skill file is `SKILL.md`。It contains the full operating rules for Codex.

The optional UI metadata is stored in `agents/openai.yaml`。

## Installation

Copy this folder into your Codex skills directory.

```powershell
Copy-Item -Recurse . "$env:USERPROFILE\.codex\skills\humanize-chinese-writing"
```

After installation, start a new Codex session so the skill list refreshes.

## Repository Name

The project uses an English repository name, `humanize-chinese-writing`, rather than a pinyin transliteration.
