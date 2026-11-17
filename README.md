# 短剧编剧书籍技能

四个 Codex skill 试稿，依据公开试读、作者资料或出版社目录制作。覆盖范围见下表。能力卡里的执行步骤和案例用于短剧创作，来源段记录核对到的章节或公开资料。

| Skill | 可调用能力 | 公开资料范围 |
| --- | --- | --- |
| [从零开始学短剧创作](skills/short-drama-basics/SKILL.md) | 主线与付费点检查 | 北大出版社目录第 7、9 章。操作步骤为原创改编 |
| [编剧路线图](skills/tv-showrunner-roadmap/SKILL.md) | 人物秘密与分集揭露 | Routledge 英文初版第 12 章开头。中文版对应正文待核 |
| [救猫咪](skills/save-the-cat-short-drama/SKILL.md) | 一句话梗概、全篇节拍表 | 孟影译本第 1 章试读，第 4 章节拍方法核对官方资料 |
| [对白](skills/mckee-dialogue-short-drama/SKILL.md) | 对白作为行动 | 中文版第 1 章目录定位，方法核对作者官网 |

每个 skill 可独立使用。把所需的整个目录复制到 Codex 能发现的技能目录，再按目录名调用。例如「用 `$mckee-dialogue-short-drama` 检查这一场戏的潜台词，保留已确定的剧情事实」。

后续合并时，用各书 `books/<目录>/.cangjie/capabilities/` 中的能力卡和稳定 ID 对照现有写作流程。修改能力卡源文件后用仓颉的 `cangjie.py compile --output single` 重新生成对应 skill。整书正文核对及完整覆盖待完成。

[试写记录](examples.md)
