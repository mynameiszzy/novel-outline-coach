# 小说大纲教练 · Novel Outline Coach

一个面向 Codex 的小说大纲辅助 Skill，帮助作者把模糊灵感逐步发展成逻辑清晰、可以实际开写的章节或场景大纲。

它以雪花写作法作为渐进扩展流程，以灵活的三幕多线结构整理宏观叙事，并内置选项式提问、逻辑质疑和修改影响追踪。核心原则是作者负责创作决定，Skill 负责提出问题、提供选择、检查结构并维护一致性。

## 主要功能

- 从零构思、继续已有材料或诊断现有大纲；
- 没有概念时提供 3–5 个差异明显的选项和推荐理由；
- 区分已确认、候选、否决、待决定、冲突和已接受风险；
- 从一句话故事逐步扩展到人物弧光、详细梗概和场景表；
- 使用三幕结构和可变数量的叙事线检查长篇结构；
- 分离真实时间线与读者获知顺序，支持插叙、倒叙和悬疑；
- 质疑因果、人物动机、信息来源、时间空间、世界规则和反派反应；
- 针对逻辑问题提供多种修复方案、影响和取舍；
- 修改核心设定前追踪受影响的人物、支线、章节和伏笔；
- 用 Markdown 或 Obsidian 文件维护项目状态、决策记录和逻辑问题台账。

## 安装

将仓库克隆到个人 Skills 目录：

```powershell
git clone https://github.com/mynameiszzy/novel-outline-coach.git "$HOME\.agents\skills\novel-outline-coach"
```

如果你的 Codex 使用 `.codex/skills`：

```powershell
git clone https://github.com/mynameiszzy/novel-outline-coach.git "$HOME\.codex\skills\novel-outline-coach"
```

Codex 通常会自动发现新 Skill；若没有显示，重启一次 Codex。

## 使用示例

### 从模糊想法开始

```text
$novel-outline-coach

我想写一个玄幻悬疑故事，但现在只有“死者会托梦”这个想法。
请每次只问一个关键问题，在我没有概念时提供几个选项。
```

### 扩展已有大纲

```text
$novel-outline-coach

读取我现有的故事梗概，判断目前处于雪花法的哪个阶段，
保留已确定内容，从下一层开始扩展。
```

### 检查剧情逻辑

```text
$novel-outline-coach

对这个大纲做标准逻辑审查，重点检查人物动机、反派反应和时间线。
每次只处理最重要的三个问题，并给我修复选项。
```

### 极限压力测试

```text
$novel-outline-coach

开启极限压力测试：寻找更简单的角色方案、世界规则漏洞、
不公平反转和依赖巧合的情节，并说明修改会影响哪些章节。
```

## 工作结构

```text
novel-outline-coach/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── guided-questioning.md
    ├── logic-audit.md
    ├── project-state.md
    ├── snowflake-workflow.md
    └── three-act-multiline.md
```

主 `SKILL.md` 只负责选择工作模式和路由。详细方法按当前任务加载，减少无关上下文。

## 设计边界

- 不强制所有小说使用恰好九条叙事线；
- 不把候选建议自动写成正式设定；
- 不把审美偏好误判为逻辑错误；
- 不默默重写受修改影响的其他内容；
- 不模仿特定在世作者的具体语言风格，只使用通用的高层结构技巧；
- 默认专注于完善大纲，而不是批量生成正文。
