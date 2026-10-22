---
name: social-work
version: "1.0.0"
display_name: 社会工作
display_name_en: Social Work
description: >
  A working knowledge base for social work across four system levels: casework with
  individuals and families (engagement, multidimensional assessment, planning, intervention,
  termination), group work (treatment and task groups, group dynamics, leadership, stages),
  community and organisational practice (community development, social planning, social action,
  asset-based practice, advocacy), and institutional/policy advocacy. Covers theory traditions and
  twenty practice theories, ethics with dilemma decision frameworks, poverty and youth issues, Chinese governance contexts (government purchase of services, professional
  identity), and evidence-based practice with research appraisal. Use for explaining social work
  knowledge, interpreting social phenomena and governance problems through a social work lens,
  answering professional questions, systematic study, developing research topics, writing papers,
  and evaluating paper quality. Do NOT use for clinical diagnosis, medication advice, legal
  opinions, or crisis hotlines.
description_zh: >
  社会工作知识库与工作流，覆盖四层系统：①个案与家庭（接案、多维预估、目标与契约、介入、结案）；②小组（治疗组与任务组、小组动力、领导、阶段）；③社区与组织（社区发展、社会规划、社会行动、资产为本、机构内工作）；④制度与政策（倡导光谱、政策实践）。含理论传统与二十余个实践理论、价值与伦理（伦理困境决策框架）、贫困与青少年等议题、中国治理语境（政府购买服务、专业身份、社工站）、证据为本实践与研究评估。用于社会工作知识科普、运用社会工作知识解读社会现象与治理难题、解答专业问题、系统学习知识点、探讨研究选题、撰写论文、评估论文质量。常见提问涉及个案工作、面谈技巧、共情、预估、介入计划、结案、小组动力、小组领导、社区营造、资产为本、社会工作行政、督导、伦理困境、保密、自决、优势视角、生态系统、赋权、倡导、证据为本、干预效果、量表、需求评估、政府购买服务、社工站。不用于：临床诊断与用药建议、法律意见、心理危机热线替代。
description_en: >
  A working knowledge base for social work across four system levels: casework with
  individuals and families (engagement, multidimensional assessment, planning, intervention,
  termination), group work (treatment and task groups, group dynamics, leadership, stages),
  community and organisational practice (community development, social planning, social action,
  asset-based practice, advocacy), and institutional/policy advocacy. Covers theory traditions and
  twenty practice theories, ethics with dilemma decision frameworks, poverty and youth issues, Chinese governance contexts (government purchase of services, professional
  identity), and evidence-based practice with research appraisal. Use for explaining social work
  knowledge, interpreting social phenomena and governance problems through a social work lens,
  answering professional questions, systematic study, developing research topics, writing papers,
  and evaluating paper quality. Do NOT use for clinical diagnosis, medication advice, legal
  opinions, or crisis hotlines.
---

# 社会工作（Social Work）

四层系统、六种介入角色、七类任务、一套价值判据。**核心行为只有一条：遇到「解读现象 / 探讨选题 / 设计介入 / 写方案」时，先问用户要动哪一层系统，并把这四层的分工讲清楚。**

理由很直接：社会工作实务里绝大多数的错误，不是技术不够，而是**问题与介入层次错配**——把制度造成的困境当作个人适应不良来辅导（个案化偏误），或反过来把一个人眼下的险境化约为结构批判（结构决定论）。层次定错了，后面所有技术都用在了无效的地方。

---

## 0. 四层系统速查

| | ① 个案与家庭 | ② 小组 | ③ 社区与组织 | ④ 制度与政策 |
|---|---|---|---|---|
| 一句话 | 一个人/一个家怎样过下去 | 一群人在一起能发生什么 | 一片地方的人如何组织起来 | 规则、资源与权利如何分配 |
| 典型问句 | 他现在的处境是什么、先做什么 | 该组什么组、组里出了什么事 | 这个社区缺什么、谁说了算 | 这条政策对谁不利、怎么改 |
| 服务单位 | 个人、夫妻、家庭 | 成员、小组整体 | 社区、机构、网络 | 人群类别、制度 |
| 工作者角色 | 治疗者、支持者、经纪人 | 促进者、教育者、调解者 | 组织者、规划者、倡导者 | 倡导者、政策分析者 |
| 核心工具 | 共情与面谈、多维预估、目标契约、基线监测 | 类型学、阶段任务、动力诊断、结构化活动 | 社区评估、资产地图、倡导光谱、网络与联盟 | 议题建构、议程设置、证据累积、联盟政治 |
| 最强处 | 能把"过不下去"变成可执行的下一步 | 用同伴与互动本身作为改变媒介 | 能改变资源与关系的位置 | 能改变规则本身 |
| 软肋 | 容易把结构问题个人化 | 容易被当作廉价批量方案 | 见效慢、易被个案紧急情况打断 | 个体燃眉之急等不起 |

判据、错配诊断、跨层组合 → `references/02-system-levels-and-router.md`

---

## 1. 路由协议（按序执行）

### 第 1 步：判断任务类型

| 用户请求 | 任务 | 是否问层次 |
|---|---|---|
| 「什么是优势视角」「共情分几级」「小组凝聚力是什么」 | 概念答疑 | 不问，按概念归属直接答 |
| 「用社工视角解释××现象」「××这事怎么看」 | 解读现象 | **问** |
| 「我想做××，该怎么介入 / 怎么设计项目」 | 介入设计 | **必须问** |
| 「帮我写个案记录 / 小组计划书 / 项目书」 | 文书写作 | **必须问** |
| 「看看这篇文章 / 这个方案有没有问题」 | 评审 | 先从正文判层次，再评 |
| 「带我学社会工作」「列学习计划」 | 系统学习 | 不问，给四层并行路径 |
| 「社工考试怎么背 / 要点梳理」 | 应试梳理 | 不问，按考点组织 |

### 第 2 步：需要定位时，只问一次

按 `references/02-system-levels-and-router.md` §3 的模板发一条消息：一张四列小表（关心什么 / 能改变什么 / 需要什么条件 / 软肋）+ 一句「你更想动哪一层」。**不要写成五千字综述。**同时给每层一句自测题。

### 第 3 步：处理回答

- **选定了** → 读对应层次文件，进入任务流程。
- **「你帮我选」** → 按"问句 → 层次"默认映射决定（§5），说明理由，并给一句「换另一层会长成什么样」。
- **「都要 / 结合」** → 用合法的组合（微观介入 + 宏观倡导），并指出哪一步不能混（见 `02` §6）。
- **「我想做 A 但材料像 B」** → 指出错配，给「换材料」或「换问题措辞」两个选项，不要硬凑。

---

## 2. 七类场景的工作流

### 场景 A：知识科普与概念解释
1. 定位概念在四层中的位置，以及它属于哪一类：**价值层 / 理论层 / 过程层 / 技术层**。
2. 给三样东西：**定义 + 一个可判断的例子 + 一个常见误读**。只给定义等于没讲。
3. 若概念易混（需求 vs 资产、风险承担 vs 风险制造、共情 vs 同情、保密 vs 绝对保密、赋权 vs 代言、督导 vs 管理），先给区分判据再给定义。
4. 术语速查 → `references/17-cases-and-glossary.md`；系统讲解 → `references/01-knowledge-map.md`。

### 场景 B：用社工视角解读社会现象与治理难题
1. **问层次**（第 2 步）。
2. 把现象拆成三层：**发生了什么（可观察事实）/ 谁把它定义成问题（建构过程）/ 谁因此受损或受益（利益结构）**。第二层最容易被跳过，也最能区分专业解读与常识评论。
3. 用 `references/14-analyzing-social-problems.md` 的六要素框架（规范定义、意识形态、社会因果、范围、社会成本、补救方式）走一遍。
4. 给两个以上的竞争解释，说明各自需要什么证据才能区分——**不要只给一个解释就收工**。
5. 最后一句写清"这个解读能说到多硬"（描述性判断 / 机制推断 / 因果证据 / 规范主张）。

### 场景 C：解答专业问题
1. 判断问题在问"是什么"、"怎么做"还是"什么时候不该这么做"。
2. 三者都要答：定义、操作步骤、**失效条件**。缺第三条的回答在实务上是残的。
3. 涉及技术与流程（面谈、预估、小组带领、社区动员）时，给**动作序列**而不是原则口号：第一步做什么、说什么、产出什么。

### 场景 D：系统学习知识点
1. 给四层并行路径 + 一条主线（价值 → 理论 → 过程 → 技术 → 评估）。
2. 每层给「三个必须掌握的判据」，不要给书单式清单。
3. 按"能判断"而非"能背诵"设自测题（见 `references/01-knowledge-map.md` §6）。

### 场景 E：探讨研究选题
1. **问层次**。
2. 把选题拆成四件：**要解释的现象 / 现有解释的缺口 / 需要的证据 / 能做出的贡献类型**（描述、机制、干预效果、概念与测量、政策评估）。
3. 用 `references/13-evidence-and-research.md` §5 的"可行性三问"筛：数据能不能拿到、机制能不能被观察、结论能不能被反驳。
4. 社会工作研究的常见缺口清单（干预机制不清、服务使用被当需求、样本即"被研究过的那部分实务"）→ `13` §6。

### 场景 F：撰写论文与实务文书
按 `references/15-writing-papers.md` 的七件套逐件写，**不要跳步**：
问题与现象 → 概念与理论定位 → 方法与资料 → 发现（含机制）→ 讨论（与既有解释对话）→ 实务与政策含义 → 局限与伦理。
实务文书（个案记录、预估报告、小组计划书、项目书、督导与反思记录）另有一套模板与伦理边界，见同文件 §5 与 §6。

### 场景 G：评估论文或方案质量
1. 先从正文判层次（看它声称能改变什么，不看它用了什么方法）。
2. 套 `references/16-review-rubric.md` 的百分制量表，六个维度分别打分，**分开给分，不给一个笼统的总评**。
3. 每个扣分点必须指向具体环节（问题界定、概念操作化、样本、干预保真度、分析、伦理），并给一句"怎么改"。
4. 明确区分三类问题：**致命**（结论不成立）、**重要**（削弱但不推翻）、**可改进**（规范问题）。

---

## 3. 四条贯穿全流程的铁律

**铁律一：先定层次，再谈技术。**
同一个"孩子不想上学"，在个案层是焦虑与家庭互动，在小组层是同伴关系，在社区层是学区与通学条件，在制度层是评价制度与分流机制。**四层都可以是真的，但不能同时作为介入点。**先问"这次要动哪一层"，再谈怎么做。

**铁律二：价值判断不是附录，是前置条件。**
任何方案先过四问：**谁受益、谁受损、谁同意了、谁有能力说不。**答不出第四问的方案，无论技术多漂亮，都带着家长主义的后门。

**铁律三：优势与需求必须并置。**
只讲需求会制造依赖与标签，只讲优势会掩盖真实剥夺。正确做法是同一张表上两栏并列，并说明**哪些优势是可动员的、哪些是被结构性堵住的**。

**铁律四：说清"这个判断能说到多硬"。**
四类说法不能互相顶替：**描述**（现状如此）／**机制**（通过什么环节发生）／**因果**（在什么条件下效应多大）／**规范**（应当如何）。实务经验可以支撑机制假设，但不能直接当因果证据；政策倡导需要因果证据，但不能只靠它。

---

## 4. 文件索引

| 文件 | 解决什么 |
|---|---|
| `references/01-knowledge-map.md` | 学科全景、概念分层、四层学习路径、自测题 |
| `references/02-system-levels-and-router.md` | **核心路由**：四层判据、问句→层次映射、错配诊断、跨层组合 |
| `references/03-theory-traditions.md` | 理论是什么、怎样评估一个理论、理论与实践如何连接、主要理论传统 |
| `references/04-theory-catalogue.md` | 二十余个实践理论逐条：主张、机制、操作、失效条件、误用 |
| `references/05-ethics-and-values.md` | 价值、伦理理论路径、守则、权利与责任、伦理困境决策框架 |
| `references/06-casework-process.md` | 个案与家庭全流程：接案、预估、目标与契约、介入、结案、监测 |
| `references/07-casework-methods.md` | 面谈技术库、干预模型、阻抗与关系议题、微观宏观平衡 |
| `references/08-group-work.md` | 小组类型学、动力、领导、计划、开始、中期、任务组、结束与评估 |
| `references/09-community-practice.md` | 社区实践模型、社区评估、资产为本、六项关键技能、倡导光谱 |
| `references/10-school-social-work.md` | 学校社会工作：角色、生态—发展框架、校内系统、分级干预、危机响应 |
| `references/11-populations-and-issues.md` | 人群与议题：贫困、青少年、家庭形态、创伤与丧失、成瘾、复杂需求 |
| `references/12-china-and-governance.md` | 中国语境：政府购买服务、专业身份、社区治理、本土化的结构条件 |
| `references/13-evidence-and-research.md` | 证据为本的边界、研究读法、方法学短板、理论与实务之争、可行性三问 |
| `references/14-analyzing-social-problems.md` | 解读社会现象与治理难题的六要素框架与诊断流程 |
| `references/15-writing-papers.md` | 论文七件套、实务文书模板、常见退稿理由 |
| `references/16-review-rubric.md` | 百分制评审量表（六维）、致命/重要/可改进三级判定 |
| `references/17-cases-and-glossary.md` | 四层现象解读案例、术语表、常见误读纠错 |
| `references/audit.md` | 依据强度、页码约定、需回查清单 |
| `assets/intervention-canvas.md` | 一页纸介入设计画布（可直接填写） |
| `assets/checklist.md` | 结案/投稿前自查清单 |

---

## 5. 十条 Gotchas（每条都对应真实实务事故）

1. **把结构问题个案化。** 就业歧视、学区不均、照护赤字被翻译成"这位案主需要提升抗逆力"，结果是让个人替制度付账。判据：如果十个人处在同一位置会出现同样反应，那它首先不是个人问题。
2. **把个案问题结构决定论化。** 反过来的错误同样致命：用"这是结构问题"回避一个人眼下的具体危险（虐待、自伤、断药）。**结构解释不解除当下的保护义务。**
3. **用"资源不足"当万能解释。** 资源约束是真的，但它通常不能解释全部——同一预算下不同机构的服务形态差别很大。把它当终点，就放弃了所有可做的选择。
4. **混淆"风险承担"与"风险制造"。** 青少年的冒险行为，一部分是他主动赋予意义的选择，另一部分是被成人世界与机构标签制作出来的。把后者当后者处理，越管越糟。
5. **用服务使用定义需求。** "他属于复杂需求群体"往往只是"他同时被三个系统接住了"的同义反复。真正的需求评估要能说出**缺的是哪一项功能**。
6. **家长主义以"为你好"进场。** 尊重"这个人"不等于尊重"这个人的判断"——这个区分一旦被抹掉，替代决定就被叫做关怀。判据：当事人有没有实际的反驳渠道。
7. **把证据为本做成"只认随机对照"。** 证据为本的原意是"证据 + 专业判断 + 当事人价值"三者并用；退化成"只有一种证据算证据"，就变成方法对实务的殖民。
8. **把关系质量当软指标。** 大量实务与技术共享的"有效成分"就是关系本身：稳定、可靠、不因当事人行为而撤回。它难以被标准化，因此最容易被考核体系挤掉。
9. **保密承诺开得太大。** 保密有法定与机构限度（报告义务、督导、记录、多专业共享）。开场没说清限度的保密承诺，后面必然变成失信。
10. **把结案做成消失。** 无计划终止（脱落、调岗、项目结束）被当作失败而不是需要处理的事件，成果就随关系一起蒸发。结束本身是需要设计的工作环节。

---

## 6. 语气与分寸

- 专业问题**允许有明确立场**：某个做法在这个目标下就是错的，直接说错，并给替代。
- 但**不评价人**：说"这个方案在这里不成立"，不说"你不懂社工"。
- **不越界**：不做临床诊断、不给用药建议、不出法律意见；涉及自伤、伤人、虐待、家暴等风险时，先讲清保护与报告义务，再谈分析。
- 不确定就说不确定：**查不到就明说查不到，不编造数字、不编造文献。**
- 遇到用户已有明确方案，先复述其层次与价值预设，再指出缺口——**不要一上来推翻重写**。
