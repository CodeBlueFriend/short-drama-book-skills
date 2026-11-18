# 反例与边界候选（中文EPUB）

依据 counter-example-extractor，在案例提取之后执行。19章已逐章扫描小节及失败信号，以下收录作者有机制说明的局部警告。warning_signs 为从机制转写的诊断信号，不冒充原文。电影史、市场、心理与医学概括均是原书论述，不自动升级为当代事实。

## ce01 把生活实录或奇观当故事

```yaml
id: "ce01"
title: "把生活实录或奇观当故事"
type: "counter-example"
source_chapter: "第1章"
source_section: "故事与生活"
source_file: "index_split_007.txt"
paragraphs: "P0050–P0062"
chunk_id: "zh-007-P0050–P0062"
source_quote: "故事是生活的比喻"
failure_mode: "把逼真细节、特技堆积当成意义。"
mechanism: "材料未被组织成对人物处境有意义的变化，事实真实不等于故事真实。"
warning_signs: ["只以确实发生过辩护", "删除特技后没有人物追求。"]
bound_to: ["事件设计"]
tags: ["counter-example", "boundary"]
```

## ce02 把形式当必胜公式

```yaml
id: "ce02"
title: "把形式当必胜公式"
type: "counter-example"
source_chapter: "第1章"
source_section: "故事要领"
source_file: "index_split_007.txt"
paragraphs: "P0041"
chunk_id: "zh-007-P0041"
source_quote: "形式并不等于“公式”"
failure_mode: "以固定步骤保证作品成功。"
mechanism: "形式原则需要情境判断，万能公式抹除素材差异。"
warning_signs: ["按时间点硬塞转折", "先填槽再找人物动机。"]
bound_to: ["所有六项旧卡"]
tags: ["counter-example", "boundary"]
```

## ce03 把多景点误算成多场

```yaml
id: "ce03"
title: "把多景点误算成多场"
type: "counter-example"
source_chapter: "第2章"
source_section: "故事设计术语"
source_file: "index_split_010.txt"
paragraphs: "P0032–P0040；index_split_010-blocks.txt B0001"
chunk_id: "zh-010-P0032–P0040"
source_quote: "这一系列动作和地点创造了一个场景"
failure_mode: "按地点变化而不是价值动作划场。"
mechanism: "同一连续关系动作跨景点，切地点不等于产生新事件。"
warning_signs: ["分镜换景就重置目标", "重复标开场价值。"]
bound_to: ["五步场景分析", "场景划分"]
tags: ["counter-example", "boundary"]
```

## ce04 场景始末无价值变化

```yaml
id: "ce04"
title: "场景始末无价值变化"
type: "counter-example"
source_chapter: "第2章"
source_section: "故事设计术语"
source_file: "index_split_010.txt"
paragraphs: "P0027–P0031"
chunk_id: "zh-010-P0027–P0031"
source_quote: "我的剧本中为什么要采用这个场景"
failure_mode: "用解说性活动占满场景。"
mechanism: "内容没有改变有意义处境，观众得不到事件。"
warning_signs: ["开尾价值及负荷一致", "唯一用途是交代背景。"]
bound_to: ["五步场景分析"]
tags: ["counter-example", "boundary"]
```

## ce05 无知世界催生陈词滥调

```yaml
id: "ce05"
title: "无知世界催生陈词滥调"
type: "counter-example"
source_chapter: "第3章"
source_section: "向陈词滥调宣战"
source_file: "index_split_012.txt"
paragraphs: "P0003–P0004"
chunk_id: "zh-012-P0003–P0004"
source_quote: "作者不了解他故事中的世界"
failure_mode: "不了解背景便开始写，以既有影视片段补空缺。"
mechanism: "缺乏事实与想象知识，只能调用看过的套路。"
warning_signs: ["场景放到任何职业城市均成立", "对白像拼接。"]
bound_to: ["调查研究", "背景设计"]
tags: ["counter-example", "boundary"]
```

## ce06 研究永远不转化为事件

```yaml
id: "ce06"
title: "研究永远不转化为事件"
type: "counter-example"
source_chapter: "第3章"
source_section: "调查研究"
source_file: "index_split_012.txt"
paragraphs: "P0048–P0049"
chunk_id: "zh-012-P0048–P0049"
source_quote: "但它绝不能取代创作"
failure_mode: "堆资料或以研究推迟创作。"
mechanism: "信息本身不产生事件因果、冲突与高潮。"
warning_signs: ["笔记增长而没有可测试场景。"]
bound_to: ["调查研究"]
tags: ["counter-example", "boundary"]
```

## ce07 类型承诺错配

```yaml
id: "ce07"
title: "类型承诺错配"
type: "counter-example"
source_chapter: "第4章"
source_section: "精通类型"
source_file: "index_split_014.txt"
paragraphs: "P0055–P0058"
chunk_id: "zh-014-P0055–P0058"
source_quote: "营销策略将观众定位于神秘谋杀类型"
failure_mode: "《麦克谋杀案》把成熟故事包装成谋杀谜题。"
mechanism: "观众按错误问题等待，原有优点无法兑现其预期。"
warning_signs: ["片名海报承诺的类型问题迟迟不存在。"]
bound_to: ["类型常规", "开篇承诺"]
tags: ["counter-example", "boundary"]
```

## ce08 善良标签代替压力选择

```yaml
id: "ce08"
title: "善良标签代替压力选择"
type: "counter-example"
source_chapter: "第5章"
source_section: "人物VS人物塑造"
source_file: "index_split_016.txt"
paragraphs: "P0005–P0008"
chunk_id: "zh-016-P0005–P0008"
source_quote: "在没有任何风险的情况下做出的选择意义甚微"
failure_mode: "凭身份、口头品质或无代价善举证明人物。"
mechanism: "缺乏可失去的东西，选择不暴露价值排序。"
warning_signs: ["没有不做善事的诱因", "人物自称善良即算完成。"]
bound_to: ["危机", "人物真相"]
tags: ["counter-example", "boundary"]
```

## ce09 为证明思想故意削弱反方

```yaml
id: "ce09"
title: "为证明思想故意削弱反方"
type: "counter-example"
source_chapter: "第6章"
source_section: "说教倾向"
source_file: "index_split_018.txt"
paragraphs: "P0046–P0052"
chunk_id: "zh-018-P0046–P0052"
source_quote: "不要偏向“论战”的任何一方"
failure_mode: "把反派写蠢、把正方写成无缺点答案。"
mechanism: "冲突结果被作者保护，胜利不再构成可信论证。"
warning_signs: ["对手自毁", "所有角色轮流复述主题。"]
bound_to: ["主控思想", "对抗力量"]
tags: ["counter-example", "boundary"]
```

## ce10 可爱主人公未必能移情

```yaml
id: "ce10"
title: "可爱主人公未必能移情"
type: "counter-example"
source_chapter: "第7章"
source_section: "观众纽带"
source_file: "index_split_021.txt"
paragraphs: "P0031–P0041"
chunk_id: "zh-021-P0031–P0041"
source_quote: "可爱并不是观众认同的保证"
failure_mode: "只给主角讨喜特征，不建立可理解的深层欲望。"
mechanism: "观众无法把自己置于人物处境，人物与观众纽带中断。"
warning_signs: ["主角显得在抱怨却回避显而易见的出路", "只靠明星魅力。"]
bound_to: ["主人公", "移情"]
tags: ["counter-example", "boundary"]
```

## ce11 没有损失的欲望

```yaml
id: "ce11"
title: "没有损失的欲望"
type: "counter-example"
source_chapter: "第7章"
source_section: "关于风险"
source_file: "index_split_021.txt"
paragraphs: "P0070–P0072"
chunk_id: "zh-021-P0070–P0072"
source_quote: "如果主人公失败，生活将会回到正常状态"
failure_mode: "主角失败没有有意义后果。"
mechanism: "欲望被赋予的价值没有风险支持，观众缺少投入理由。"
warning_signs: ["最坏情况只是恢复原状", "得失无差别。"]
bound_to: ["鸿沟", "危机"]
tags: ["counter-example", "boundary"]
```

## ce12 预期总被原样满足

```yaml
id: "ce12"
title: "预期总被原样满足"
type: "counter-example"
source_chapter: "第7章"
source_section: "鸿沟内的创造"
source_file: "index_split_021.txt"
paragraphs: "P0204–P0212"
chunk_id: "zh-021-P0204–P0212"
source_quote: "迫使期望等同于结果"
failure_mode: "人物敲门后正常进门等活动占据节拍。"
mechanism: "没有新反应、新认识或策略变化，时间消耗不产生推进。"
warning_signs: ["每个计划都成功", "只在台词口头称困难。"]
bound_to: ["鸿沟", "节拍"]
tags: ["counter-example", "boundary"]
```

## ce13 以搬家或心情替代激励事件

```yaml
id: "ce13"
title: "以搬家或心情替代激励事件"
type: "counter-example"
source_chapter: "第8章"
source_section: "激励事件"
source_file: "index_split_023.txt"
paragraphs: "P0044–P0048"
chunk_id: "zh-023-P0044–P0048"
source_quote: "地址的改变丝毫没有改变她生活中的价值"
failure_mode: "主角厌倦便换地方，生活价值及控制感未变。"
mechanism: "没有失衡就缺少恢复平衡的欲望与追求。"
warning_signs: ["开头只有自述想重新开始。"]
bound_to: ["激励事件"]
tags: ["counter-example", "boundary"]
```

## ce14 伏笔分晓隔得过远

```yaml
id: "ce14"
title: "伏笔分晓隔得过远"
type: "counter-example"
source_chapter: "第8章"
source_section: "激励事件"
source_file: "index_split_023.txt"
paragraphs: "P0050–P0055"
chunk_id: "zh-023-P0050–P0055"
source_quote: "主人公必须对激励事件做出反应"
failure_mode: "先宣布威胁，主角长期不知情，如原书批评《怒河春醒》。"
mechanism: "主线启动被生活片断截断，观众等待而人物无法响应。"
warning_signs: ["观众知道核心危险，主角却连续忙无关事情。"]
bound_to: ["激励事件", "开篇节奏"]
tags: ["counter-example", "boundary"]
```

## ce15 激励事件与必备对峙在画外

```yaml
id: "ce15"
title: "激励事件与必备对峙在画外"
type: "counter-example"
source_chapter: "第8章"
source_section: "激励事件的设计"
source_file: "index_split_023.txt"
paragraphs: "P0077–P0085"
chunk_id: "zh-023-P0077–P0085"
source_quote: "主情节的激励事件必须发生在银幕之上"
failure_mode: "靠事后告知启动主线，或省去已承诺的核心对峙。"
mechanism: "观众未经历钩子或承诺落空，戏剧大问题没有被行动兑现。"
warning_signs: ["重大冲突只由幸存者口述。"]
bound_to: ["激励事件", "危机", "高潮"]
tags: ["counter-example", "boundary"]
```

## ce16 进展退回轻量行动

```yaml
id: "ce16"
title: "进展退回轻量行动"
type: "counter-example"
source_chapter: "第9章"
source_section: "进展纠葛／不归点"
source_file: "index_split_025.txt"
paragraphs: "P0005–P0014"
chunk_id: "zh-025-P0005–P0014"
source_quote: "作者在令故事循环，而观众则是在踩水"
failure_mode: "第二幕继续尝试第一幕已无效的同力度同性质动作。"
mechanism: "前次失败没有排除旧策略，后续失去因果压力与不可退回后果。"
warning_signs: ["换一人求情但代价不变", "羞辱回合重置。"]
bound_to: ["进展纠葛", "鸿沟"]
tags: ["counter-example", "boundary"]
```

## ce17 把冲突简化为暴力或回避一切冲突

```yaml
id: "ce17"
title: "把冲突简化为暴力或回避一切冲突"
type: "counter-example"
source_chapter: "第9章"
source_section: "冲突法则"
source_file: "index_split_025.txt"
paragraphs: "P0021–P0029"
chunk_id: "zh-025-P0021–P0029"
source_quote: "缺乏意味深长而又得到忠实呈现的冲突"
failure_mode: "机械制造打斗或只写美好生活肖像。"
mechanism: "前者脱离欲望与生活斗争，后者没有对抗导致的推进。"
warning_signs: ["声量很大却无法说清争什么", "或所有困难一沟通便消失。"]
bound_to: ["进展纠葛", "多层冲突"]
tags: ["counter-example", "boundary"]
```

## ce18 用加人加景替代复杂性

```yaml
id: "ce18"
title: "用加人加景替代复杂性"
type: "counter-example"
source_chapter: "第9章"
source_section: "纠葛型VS复杂型"
source_file: "index_split_025.txt"
paragraphs: "P0030–P0047"
chunk_id: "zh-025-P0030–P0047"
source_quote: "不要增生人物，不要繁殖景点"
failure_mode: "只有同一层面的麻烦不断增加。"
mechanism: "人物与景点扩张，内心、关系、外部冲突却未相互作用。"
warning_signs: ["每集新反派新空间而旧关系不变。"]
bound_to: ["进展纠葛", "有限世界"]
tags: ["counter-example", "boundary"]
```

## ce19 一句话算一个节拍

```yaml
id: "ce19"
title: "一句话算一个节拍"
type: "counter-example"
source_chapter: "第11章"
source_section: "场景分析技巧"
source_file: "index_split_029.txt"
paragraphs: "P0037–P0041"
chunk_id: "zh-029-P0037–P0041"
source_quote: "直到行为发生明显变化，才会出现一个新的节拍"
failure_mode: "按对白句数切节拍。"
mechanism: "动作反应策略未变的多次交流仍是一个行为单位。"
warning_signs: ["节拍名称只是台词复述", "每行都机械编号。"]
bound_to: ["五步场景分析"]
tags: ["counter-example", "boundary"]
```

## ce20 五步分析只看价值标签不定位鸿沟

```yaml
id: "ce20"
title: "五步分析只看价值标签不定位鸿沟"
type: "counter-example"
source_chapter: "第11章"
source_section: "场景分析技巧"
source_file: "index_split_029.txt"
paragraphs: "P0042–P0045"
chunk_id: "zh-029-P0042–P0045"
source_quote: "找到期望和结果裂开鸿沟的那一瞬间"
failure_mode: "写正负标签便算场景有效，却不追踪动作因果。"
mechanism: "价值转变若无可指认的行为及新反应，只是作者宣布。"
warning_signs: ["不知道哪一个节拍使末尾不同", "冲突双方欲望相切而不相反。"]
bound_to: ["五步场景分析", "鸿沟"]
tags: ["counter-example", "boundary"]
```

## ce21 连续同强度快慢耗尽观众

```yaml
id: "ce21"
title: "连续同强度快慢耗尽观众"
type: "counter-example"
source_chapter: "第12章"
source_section: "进度／节奏和速度"
source_file: "index_split_031.txt"
paragraphs: "P0007–P0025"
chunk_id: "zh-031-P0007–P0025"
source_quote: "挣得停顿的资格"
failure_mode: "不分重要性地持续紧张或漫长迟缓。"
mechanism: "缺少张弛对比，重大场景与普通场景争夺相同注意力。"
warning_signs: ["高潮前无节奏变化", "所有场都吵或都解释。"]
bound_to: ["节奏", "高潮"]
tags: ["counter-example", "boundary"]
```

## ce22 终极决定只是明显选好不要坏

```yaml
id: "ce22"
title: "终极决定只是明显选好不要坏"
type: "counter-example"
source_chapter: "第13章"
source_section: "危机"
source_file: "index_split_033.txt"
paragraphs: "P0002–P0009"
chunk_id: "zh-033-P0002–P0009"
source_quote: "不可调和的两善之间或两恶之轻的选择"
failure_mode: "把毫无代价的正确答案当两难。"
mechanism: "没有互斥价值，主角不必暴露最终排序。"
warning_signs: ["另一个选项无人会选", "可同时兼得。"]
bound_to: ["危机"]
tags: ["counter-example", "boundary"]
```

## ce23 危机与高潮被支线插断

```yaml
id: "ce23"
title: "危机与高潮被支线插断"
type: "counter-example"
source_chapter: "第13章"
source_section: "危机的设计"
source_file: "index_split_033.txt"
paragraphs: "P0028–P0034"
chunk_id: "zh-033-P0028–P0034"
source_quote: "把观众被抑制的能量耗尽"
failure_mode: "做完终极决定后转去别处支线，再回来兑现行动。"
mechanism: "决定中积聚的焦虑被耗散，形成反高潮。"
warning_signs: ["最紧张时刻被无关材料截断", "决定干脆发生画外。"]
bound_to: ["危机", "高潮"]
tags: ["counter-example", "boundary"]
```

## ce24 危机过早使余下只剩重复执行

```yaml
id: "ce24"
title: "危机过早使余下只剩重复执行"
type: "counter-example"
source_chapter: "第13章"
source_section: "高潮的定位"
source_file: "index_split_033.txt"
paragraphs: "P0023–P0027"
chunk_id: "zh-033-P0023–P0027"
source_quote: "巨大风险就是重复"
failure_mode: "激励事件后马上作最终决定，却没有足够多样性和进展支撑后续。"
mechanism: "长段执行循环追打/饮酒等同质动作。"
warning_signs: ["余下各集仅重复任务，无新策略或代价。"]
bound_to: ["危机定位", "进展纠葛"]
tags: ["counter-example", "boundary"]
```

## ce25 把高潮当噪音特技或解释

```yaml
id: "ce25"
title: "把高潮当噪音特技或解释"
type: "counter-example"
source_chapter: "第13章"
source_section: "高潮"
source_file: "index_split_033.txt"
paragraphs: "P0037–P0042"
chunk_id: "zh-033-P0037–P0042"
source_quote: "它必须充满意义"
failure_mode: "用大战规模、结尾宣言代替不可逆的价值变化。"
mechanism: "动作无法自明兑现中心价值，情绪缺少意义支点。"
warning_signs: ["删去结尾演说便不知道改变什么。"]
bound_to: ["高潮"]
tags: ["counter-example", "boundary"]
```

## ce26 把坏蛋等同全部对抗力量

```yaml
id: "ce26"
title: "把坏蛋等同全部对抗力量"
type: "counter-example"
source_chapter: "第14章"
source_section: "反面人物塑造原理"
source_file: "index_split_036.txt"
paragraphs: "P0002–P0006"
chunk_id: "zh-036-P0002–P0006"
source_quote: "各种力量的总和"
failure_mode: "只升级反派的恶，忽视主角内心、亲密关系、机构、环境。"
mechanism: "总阻力不足以迫使主角挖掘能力并发展。"
warning_signs: ["反派出场外主角一路顺利", "有能力却无代价。"]
bound_to: ["对抗力量", "进展纠葛"]
tags: ["counter-example", "boundary"]
```

## ce27 把展示误读成背景照片蒙太奇

```yaml
id: "ce27"
title: "把展示误读成背景照片蒙太奇"
type: "counter-example"
source_chapter: "第15章"
source_section: "展示，不要告诉"
source_file: "index_split_038.txt"
paragraphs: "P0004–P0010"
chunk_id: "zh-038-P0004–P0010"
source_quote: "这也是告诉，而不是展示"
failure_mode: "用摄影机扫照片代替口头背景，便认定完成戏剧化。"
mechanism: "形式视觉化但信息仍未进入当前冲突。"
warning_signs: ["角色互讲双方已知事实", "开篇堆资料。"]
bound_to: ["解说戏剧化"]
tags: ["counter-example", "boundary"]
```

## ce28 无压力吐露最痛秘密

```yaml
id: "ce28"
title: "无压力吐露最痛秘密"
type: "counter-example"
source_chapter: "第15章"
source_section: "展示，不要告诉"
source_file: "index_split_038.txt"
paragraphs: "P0011–P0016"
chunk_id: "zh-038-P0011–P0016"
source_quote: "人们总是会另有所指"
failure_mode: "初识角色坐下便尽数倾吐核心创伤。"
mechanism: "没有更强欲望迫使暴露，秘密失去分晓与终局力量。"
warning_signs: ["为观众方便而坦白", "没有保护秘密的动机。"]
bound_to: ["解说", "潜文本", "进展"]
tags: ["counter-example", "boundary"]
```

## ce29 廉价惊奇冒充见解

```yaml
id: "ce29"
title: "廉价惊奇冒充见解"
type: "counter-example"
source_chapter: "第16章"
source_section: "惊奇问题"
source_file: "index_split_040.txt"
paragraphs: "P0053–P0060"
chunk_id: "zh-040-P0053–P0060"
source_quote: "缺乏悲情之惊"
failure_mode: "靠幻觉尸体或突然一吓打断叙事，却不揭示人物世界真相。"
mechanism: "惊吓消耗脆弱而无后续认识与行为后果。"
warning_signs: ["下一镜宣布没发生", "撤回并不影响故事。"]
bound_to: ["鸿沟", "真实惊奇"]
tags: ["counter-example", "boundary"]
```

## ce30 巧合只来解决问题便消失

```yaml
id: "ce30"
title: "巧合只来解决问题便消失"
type: "counter-example"
source_chapter: "第16章"
source_section: "巧合问题"
source_file: "index_split_040.txt"
paragraphs: "P0063–P0074"
chunk_id: "zh-040-P0063–P0074"
source_quote: "千万不要利用巧合来转折一个结局"
failure_mode: "晚到的偶然救场代替主人公决定。"
mechanism: "主体行动被撤销，故事因果与意义受损。反结构以巧合统领全篇是作者明确例外。"
warning_signs: ["陌生人报地址后消失", "天灾突然惩罚反派。"]
bound_to: ["高潮", "巧合"]
tags: ["counter-example", "boundary"]
```

## ce31 怪癖技能堆叠冒充人物维

```yaml
id: "ce31"
title: "怪癖技能堆叠冒充人物维"
type: "counter-example"
source_chapter: "第17章"
source_section: "人物维"
source_file: "index_split_042.txt"
paragraphs: "P0018–P0022"
chunk_id: "zh-042-P0018–P0022"
source_quote: "这些矛盾必须是连贯一致的"
failure_mode: "多才多艺或突然做反常事便算立体。"
mechanism: "缺少持续的深层矛盾，特点未变成选择压力。"
warning_signs: ["好人无铺垫踢猫", "人设只有技能和喜好清单。"]
bound_to: ["人物维", "人物真相"]
tags: ["counter-example", "boundary"]
```

## ce32 文学化而无法拍出的描写

```yaml
id: "ce32"
title: "文学化而无法拍出的描写"
type: "counter-example"
source_chapter: "第18章"
source_section: "描写"
source_file: "index_split_044.txt"
paragraphs: "P0039–P0043"
chunk_id: "zh-044-P0039–P0043"
source_quote: "我在银幕上看见（或听见）了什么"
failure_mode: "用抽象比喻代替可见可听事件。"
mechanism: "制作无法把心理修辞直接转成镜头声响。"
warning_signs: ["删掉形容后无具体动作", "无法说明观众实际感知什么。"]
bound_to: ["剧本描写"]
tags: ["counter-example", "boundary"]
```

## ce33 爱惜对白导致死抱失败场景

```yaml
id: "ce33"
title: "爱惜对白导致死抱失败场景"
type: "counter-example"
source_chapter: "第19章"
source_section: "从外到里的写作／银幕剧本"
source_file: "index_split_046.txt"
paragraphs: "P0003–P0018；P0041–P0042"
chunk_id: "zh-046-P0003–P0018；P0041–P0042"
source_quote: "你必须回到处理台本"
failure_mode: "先写漂亮台词，后用新连接方式保护旧场景。"
mechanism: "局部润色无法修复伏笔、分晓、选择与结构问题。"
warning_signs: ["故事不通却只改台词", "拒绝删心爱场景。"]
bound_to: ["创作方法", "五步场景分析"]
tags: ["counter-example", "boundary"]
```

## 迁移边界

原书的40–60场、电影两三分钟场景均为电影论述，不是竖屏短剧定额。旧六卡不得把每集卡点强制等同全故事激励事件、危机或高潮；场景价值也不强制每句对白反转。原书关于“加州人”及全球观众的文化/心理断言只是修辞，提取其压力逼出秘密的机制即可。源本版本与讹误见 cases-zh.md 末节。
