# Mimeng Writing Codex Skill

`mimeng-writing` is a Codex Skill for writing original high-emotion Chinese WeChat-style opinion articles from a topic, article, video, or brief.

It distills reusable writing mechanisms from a local longform corpus analysis: conflict-first angle selection, second-person reader pressure, short paragraph rhythm, anecdote stacking, reversal, and value-judgment closing.

This is not an imitation or style-cloning package. It does not bundle source text and should not be used to impersonate any writer, copy original passages, or rewrite known articles too closely.

## What It Helps With

- Generate original Chinese公众号长文 from a topic or source material.
- Create sharp title options and opening hooks.
- Turn news, video, social cases, or personal stories into opinion pieces.
- Calibrate emotional intensity without relying on plagiarism, personal attacks, or unverifiable claims.
- Run originality and safety checks before finalizing.

## Structure

```text
mimeng-writing/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── article-architecture.md
    ├── originality-and-safety.md
    ├── title-and-angle.md
    └── voice-and-rhythm.md
```

## Installation

Copy this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R mimeng-writing ~/.codex/skills/mimeng-writing
```

Restart or refresh Codex if needed so the skill is discovered.

## Usage Examples

Ask Codex:

```text
Use mimeng-writing to turn this video into an original公众号文章.
```

```text
用 mimeng-writing 给这个选题写 10 个标题和一篇 2500 字文章。
```

```text
用 mimeng-writing 改写这篇文章的结构，但不要模仿原文表达。
```

## Safety Boundary

The skill explicitly requires:

- no author impersonation
- no copied titles, sentences, metaphors, jokes, or distinctive turns
- no close paraphrase of known articles
- no invented statistics, quotes, or factual claims
- no harassment, dehumanization, body shaming, or protected-class attacks

Strong writing should target behaviors, systems, incentives, and arguments, not private individuals or protected traits.

## License

MIT
