# Grant Figure Studio

A Codex skill for clear, coherent scientific schematics and technical-route figures in grant applications, with particular attention to Chinese proposals reviewed by researchers outside the immediate specialty.

**基金申请科研绘图 skill**：核心概念一眼可认，科学逻辑清晰，画面紧凑，文字简洁，字体、框线和语义配色统一。

## Design principles

- Make the central research object or method immediately recognizable.
- Use terms and noun phrases instead of explanatory sentences inside the figure.
- Limit the figure to three font sizes; use bold labels, Chinese Heiti and Latin Arial.
- Use a white canvas, clear frames and selective fills for emphasis.
- Assign consistent colors to concepts across inputs, tools, details and outputs.
- Distinguish containment, tool calls, information flow, parallel branches, feedback and expanded views.
- Keep internal platform modules identifiable before expanding their details outside the main frame.
- Fit the canvas and label boxes to the content; do not add filler to match a reference figure’s density.
- Preserve scientific meaning and clearly distinguish schematic illustrations from measured results.
- Inspect the final editable source and its exported preview, including previously corrected issues, before delivery.

These are grant-figure design defaults, not universal publication rules. The user's instructions, scientific content and grant template take precedence.

## Install

Clone this repository into the local skill directory:

```sh
git clone https://github.com/Pyramtee/grant-figure-studio.git ~/.codex/skills/grant-figure-studio
```

If you use a custom skill directory, place the repository there instead. The installed folder contains `SKILL.md` at its root.

## Example request

> Use $grant-figure-studio to design a grant proposal figure from my approved research plan and reference figure. Discuss the layout first, then create an editable source and a PNG preview after I approve it.

> 使用 $grant-figure-studio，根据已确认的研究方案和参考图设计基金申请示意图。先讨论构图，确认后再绘制，并在交稿前检查逻辑、重点、密度、字体、线条和语义配色。

## Contents

| File | Purpose |
| --- | --- |
| [SKILL.md](SKILL.md) | Skill entry point and workflow |
| [Design system](references/design-system.md) | Typography, sizing, frames, palette and layout |
| [Visual logic](references/visual-logic.md) | Core concepts, platform containment, functional flows, expanded details, comparisons and feedback |
| [Acceptance checklist](references/acceptance.md) | Final-source and export review |
| [Textual examples](references/approved-example.md) | Agent and platform structures, parameters and transfer boundaries |
| [UI metadata](agents/openai.yaml) | Skill display name and description |

The skill instructions and detailed references are written in Chinese; the name and discovery description are in English. The skill provides design guidance, rather than a standalone rendering engine. Use the document or graphics tools available in your environment to produce the figure.

## Reference materials

This public repository contains **rules and textual examples only**. Original reference artwork, PPTX files and project figure previews are kept outside the public package. Provide reference materials that you are authorized to use for each new task.
