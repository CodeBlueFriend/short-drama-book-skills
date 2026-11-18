# 《故事》短剧写作交接包

六项能力覆盖行动预期与结果、激励事件、递进纠葛、场景分析、危机选择、高潮回收。本包包含一个独立 Codex skill 和六份知识库导入稿，面向短剧剧本写作。

本次依据英文原书第三部分的方法段落，覆盖范围和页码见每张卡及来源审核。整书其余章节、中文版本与译本页码待核。操作步骤为短剧改编，演练案例由本项目编写。

## 独立调用

把 skills/mckee-story-short-drama 整个目录放入个人 Codex 技能目录。下一条消息用 `$mckee-story-short-drama` 指定本次要查的场次或大纲。

## 交给负责更新的智能体

将本包解压后交给负责更新的智能体，可使用以下指令。

> 按我现有 mm-write-short-drama 的知识库流程，导入 knowledge-inbox 里的六份资料。保留原书章节、英文印刷页码、PDF 页码和短剧改编说明。先建 draft，语义核对与已有卡的重复、冲突和适用范围，再启用适用卡，运行知识库校验及分阶段检索。

也可从本包解压目录使用现有导入器。

```bash
skill="/Users/liming/.codex/skills/mm-write-short-drama"
kb="/实际知识库绝对路径"
python3 "$skill/scripts/ingest_knowledge.py" --kb "$kb" --status draft ./knowledge-inbox
python3 "$skill/scripts/validate_knowledge.py" --kb "$kb"
```

[试写与检查](examples.md)
