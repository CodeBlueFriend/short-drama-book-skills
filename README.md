# 短剧写作书籍技能与知识库交接

五个独立 Codex skill，面向短剧剧本创作。每个入口包含可按任务检索的能力卡，统一导入目录共24份知识稿。用户可将本仓库地址交给现有写作项目更新知识库。

| 书籍 | Skill | 当前来源和覆盖 |
| --- | --- | --- |
| 从零开始学短剧创作 | [主线与卡点](skills/short-drama-basics/SKILL.md) | 1张卡，依据出版社第7、9章目录，操作步骤为短剧适配，正文待核 |
| 编剧路线图 | [人物秘密](skills/tv-showrunner-roadmap/SKILL.md) | 1张卡，依据英文初版第12章公开开头，中文正文待核 |
| 救猫咪 | [梗概与节拍](skills/save-the-cat-short-drama/SKILL.md) | 2张卡，依据孟影译本第1章试读及官方节拍资料 |
| 对白 | [言语行动](skills/mckee-dialogue-short-drama/SKILL.md) | 1张卡，依据麦基官网原则，中文目录定位第1章，正文待核 |
| 故事 | [中文版19项写作任务](skills/mckee-story-short-drama/SKILL.md) | 周铁东译，天津人民出版社2014年9月第1版，ISBN 9787201088334，中文EPUB正文已取得，19章扫描与方法段回读 |

《故事》的第三方EPUB版本通过CIP和版权页核对，含推广字样和少量可疑错字。19张卡使用中文章节、小节、文件和电子段号定位，纸本页码及逐字校勘待核。图像仅做相关关键图核验。前四本继续保留各自公开材料范围，后续可据整书正文补充。

## 给写作项目的更新指令

> 从本仓库 knowledge-inbox 导入24份知识稿，按现有 mm-write-short-drama 知识库流程先创建 draft。保留中文章节、小节、文件段号、书目与仓颉能力ID，先核对与原库的重复、冲突和适用范围，再激活确认可用的规则。若已有旧版《故事》六张卡，按相同仓颉能力ID建立修订映射，归档或停用旧卡后替换。 即使规则正文哈希相同，也须更新该卡的来源版本和电子定位。新增规则的正文哈希会变化，需同时核对能力ID。导入后运行知识库校验并逐阶段验证检索。

更新的输入位于 [knowledge-inbox](knowledge-inbox)。独立调用时，将 [skills](skills) 下所需的完整目录放入个人技能目录，下一条消息按目录名调用。

## 交接与审计

- [五本统一导入稿](knowledge-inbox)
- [前四本交接说明](handoff/README.md)
- [《故事》中文版交接说明](story-handoff/README.md)
- [《故事》版本及源哈希](books/mckee-story-short-drama/source-manifest.json)
- [《故事》覆盖审核](books/mckee-story-short-drama/coverage-audit.md)
- [《故事》独立执行测试](books/mckee-story-short-drama/test-results.md)
- [前四本共用试写](examples.md)
- [发布说明](RELEASE_NOTES.md)

源能力卡和编译数据位于 books/<书籍目录>/.cangjie/capabilities。使用仓颉的 cangjie.py compile --output single 重新编译。能力语义保持时沿用稳定ID并递增修订，行为拆分或合并时另做映射。
