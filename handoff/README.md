# 短剧编剧书籍技能交接

本包含四个可独立使用的 Codex skill、五份适配 `mm-write-short-drama` 的知识库导入稿，以及共用的六集试写记录。书籍方法来自公开试读、作者资料和出版社目录，逐章正文待核。每份导入稿都标明来源范围、适用阶段、例外、正反例和原仓颉能力 ID。

| 书籍 | 独立 skill | 知识库导入稿 |
| --- | --- | --- |
| 从零开始学短剧创作 | [主线与卡点](skills/short-drama-basics/SKILL.md) | [相邻卡点](knowledge-inbox/01-short-drama-payoff-turn.md) |
| 编剧路线图 | [人物秘密](skills/tv-showrunner-roadmap/SKILL.md) | [秘密揭露](knowledge-inbox/02-showrunner-character-mystery.md) |
| 救猫咪 | [梗概与节拍](skills/save-the-cat-short-drama/SKILL.md) | [一句话梗概](knowledge-inbox/03-save-the-cat-logline.md) · [整季节拍](knowledge-inbox/04-save-the-cat-beat-sheet.md) |
| 对白 | [言语行动](skills/mckee-dialogue-short-drama/SKILL.md) | [对白诊断](knowledge-inbox/05-mckee-verbal-action.md) |

## 自行更新写作知识库

把整个交接包发给负责更新的智能体，并给它以下指令。

> 用我现有的 mm-write-short-drama 知识库流程，导入 knowledge-inbox 里的五份资料。保留原书章节定位、公开资料的覆盖范围、短剧改编说明和原能力 ID。先导入为 draft，核对与现有规则的重复和冲突，再把适用规则激活。跑知识库校验，并分别用策划、结构、分集、对白查询验证能找到对应规则。

也可在解压目录执行下列命令。知识库路径填实际使用的库。导入器会保存来源副本并生成知识卡及索引。

```bash
skill="/Users/liming/.codex/skills/mm-write-short-drama"
kb="/实际使用的知识库绝对路径"
python3 "$skill/scripts/ingest_knowledge.py" --kb "$kb" --status draft ./knowledge-inbox
python3 "$skill/scripts/validate_knowledge.py" --kb "$kb"
```

`draft` 是待复核状态。按目标库已有流程将确认可用的卡转为 `active` 后，写作 skill 才会默认检索到它们。重新导入会触发去重，已有卡的状态按目标库流程更新。

## 独立使用

将 `skills/` 下面任选一个完整技能目录放入 Codex 的技能目录。下一条消息可以用目录名调用，例如「用 `$mckee-dialogue-short-drama` 检查这场对质戏的潜台词」。

[六集短剧试写记录](examples.md)
