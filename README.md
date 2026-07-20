AI 组织健康度诊断 Skill
基于 Q12 员工组织氛围调研数据的 AI 组织诊断工具，模拟资深 OD 顾问和经理人专家的诊断流程。

功能
基于 Q12 问卷数据自动计算组织健康度指数
多维度问题诊断（基础支持、价值贡献、管理关系、成长发展）
组织差异分析（按事业部/部门逐层分析）
经理效能矩阵（VP 视角）：4 象限散点图识别问题团队/沉默团队/不稳定优秀团队/稳定优秀团队
绩效-敬业度人才九宫格（经理人视角）：基于绩效×敬业度的员工分类，识别核心贡献者/成长型人才/高产出风险人才/潜在流失者等
CEO 根因链战略诊断（CEO 视角）：基于 Gallup Q12 层次模型 + Burke-Litwin 变革模型的跨维度根因合成，区分系统性文化问题 vs 局部管理问题，输出 30/60/90 天分层行动建议
员工画像差异分析（司龄、绩效、管理身份等）
自动生成分级报告（CEO/VP/部门经理三个版本）
内置行业基准数据库（Gallup/Culture Amp/美世等），自动对标
自动匹配改善动作库，生成 30/60/90 天改善计划
工作流程
01 SKILL.md                        →  AI 工作流程（怎么诊断）
02 metric-model.md                 →  指标怎么算
03 diagnosis-rules.md              →  问题怎么判断
04 action-library.md               →  问题怎么解决
05 report-template.md              →  结果怎么呈现
06 industry-benchmarks.md          →  行业基准怎么对标（内置数据，无需联网）
07 industry-benchmarks-methodology.md → 基准数据方法论（推导过程、局限性、使用边界）
文件结构
ai-org-health-diagnosis/
├── SKILL.md                              # Skill 主文件：角色定义 + 分析流程
├── README.md                             # 本文件
└── references/
    ├── metric-model.md                   # 指标计算模型
    ├── diagnosis-rules.md                # 诊断规则库
    ├── action-library.md                 # 改善动作库
    ├── report-template.md                # 报告生成模板
    ├── industry-benchmarks.md            # 行业基准数据库（Gallup/Culture Amp/美世等）
    └── industry-benchmarks-methodology.md # 基准数据方法论说明（推导、局限、Q&A）
安装方法
方法一：WorkBuddy 对话安装
在 WorkBuddy 对话中直接输入：

请帮我安装 C:\path\to\ai-org-health-diagnosis 文件夹下的 skill
方法二：手动安装
将 ai-org-health-diagnosis 文件夹复制到：

~/.workbuddy/skills/ai-org-health-diagnosis/
然后重启 WorkBuddy 即可。

使用方式
安装后，在 WorkBuddy 对话中上传员工组织氛围调研数据（Excel/CSV 格式），AI 会自动触发该 Skill 进行诊断分析。

触发关键词：组织健康度、组织氛围、员工调研、Q12 问卷、敬业度调研、组织诊断

适用场景
公司年度组织氛围调研分析
部门级组织健康度诊断
新管理者接管团队前的组织摸底
并购后的文化融合评估
组织变革前的基线测量
许可
MIT License
