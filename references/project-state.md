# Persistent project state and Obsidian output

Use persistent files when the author provides a project folder, asks to create one, or wants work to continue across sessions. Otherwise work in chat and offer project creation at a natural stage boundary.

Do not hardcode one vault path into the skill. Respect the author-provided location. Preserve unrelated notes and existing frontmatter.

## Recommended Markdown project

Create only files needed by the current project:

```text
novel-project/
├── 00-项目状态.md
├── 01-核心故事.md
├── 02-三幕结构.md
├── 03-人物档案.md
├── 04-叙事线矩阵.md
├── 05-真实时间线.md
├── 06-信息揭示顺序.md
├── 07-章节与场景大纲.md
├── 08-伏笔回收表.md
├── 09-世界规则.md
├── 10-逻辑问题台账.md
└── 99-创作决策记录.md
```

Use stable IDs for characters, lines, beats, scenes, clues, rules, decisions, and logic issues so cross-file links survive renaming. Obsidian wikilinks are welcome when the project already uses them.

## Canon states

Mark material as:

- `confirmed` — author-approved canon;
- `candidate` — proposed but not approved;
- `rejected` — ruled out; retain enough context to avoid repetition;
- `undecided` — intentionally open;
- `conflict` — incompatible with confirmed material;
- `accepted-risk` — known logic or plausibility concern retained deliberately.

Never promote a candidate merely because it appeared in generated prose or a prior suggestion.

## Project state file

`00-项目状态.md` should provide a fast resume snapshot:

```markdown
---
project: 小说名或代号
stage: 当前阶段
updated: YYYY-MM-DD
---

## 故事承诺

## 已确认核心设定

## 当前工作模式

## 正在解决的问题

## 待决定事项

## 已接受风险

## 最近决定

## 下一步建议
```

Read this file first when resuming, then open only the artifacts needed for the current decision.

## Decision record

For material choices, record:

- stable decision ID and date;
- question;
- selected answer;
- reason or intended effect;
- rejected alternatives when useful;
- affected artifacts;
- superseding decision if later changed.

## Change propagation

Before applying a material change:

1. identify the canon fact being replaced;
2. search the project for its stable ID, name, consequences, setups, and payoffs;
3. list affected artifacts and distinguish required from optional changes;
4. present a concise change preview;
5. update only after the author approves the creative change or has already explicitly requested the update;
6. record the decision and leave unrelated prose intact;
7. rerun the relevant logic checks.

If a change produces unresolved downstream choices, mark them `undecided` rather than inventing silent fixes.

## Stage-boundary update

At a stage boundary, update the project state with:

- newly confirmed canon;
- candidate ideas still under consideration;
- open and resolved logic issues;
- affected narrative lines and scenes;
- the next highest-leverage question.

Avoid rewriting every file on every turn. Update only artifacts changed by the decision.
