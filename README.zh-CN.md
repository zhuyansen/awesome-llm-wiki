# Awesome LLM Wiki

[English](README.md)

**由 LLM 或 agent 搭建和维护知识库**的开源工具:Markdown 互链的 LLM Wiki、RAG 知识库平台、MCP 与 skill、文档问答、知识图谱、个人知识库。共 230 个仓库,每个都由 [Agent Skills Hub](https://agentskillshub.top?utm_source=github&utm_medium=awesome-list) 读过 README 并做了安全评级。

带类型筛选的在线页面:**[https://agentskillshub.top/best/knowledge-base/](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list)** · 每 8 小时刷新

## 这些知识库长什么样

<table>
<tr>
<td align="center" valign="top" width="33%"><b>📖 LLM Wiki</b><br><sub>70 个仓库</sub><br><br><sub>由 agent 撰写并维护的 Markdown 互链 wiki。</sub><br><a href="#type-llm_wiki"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🏗 RAG 知识库平台</b><br><sub>9 个仓库</sub><br><br><sub>自带界面的 RAG 知识库平台。</sub><br><a href="#type-rag_platform"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🔌 MCP 与 Agent Skill</b><br><sub>58 个仓库</sub><br><br><sub>让 agent 检索知识库的 MCP 服务和 skill。</sub><br><a href="#type-mcp"><b>查看列表 →</b></a></td>
</tr>
<tr>
<td align="center" valign="top" width="33%"><b>📄 文档问答</b><br><sub>23 个仓库</sub><br><br><sub>基于产品文档、代码库、论文或 PDF 回答问题。</sub><br><a href="#type-docs_qa"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🕸 知识图谱</b><br><sub>64 个仓库</sub><br><br><sub>以实体和关系组织知识的图谱。</sub><br><a href="#type-graph"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🧠 个人知识库</b><br><sub>6 个仓库</sub><br><br><sub>由 AI 维护的笔记、收藏和第二大脑。</sub><br><a href="#type-personal"><b>查看列表 →</b></a></td>
</tr>
</table>

## 目录

- [📖 LLM Wiki](#type-llm_wiki) (70)
- [🏗 RAG 知识库平台](#type-rag_platform) (9)
- [🔌 MCP 与 Agent Skill](#type-mcp) (58)
- [📄 文档问答](#type-docs_qa) (23)
- [🕸 知识图谱](#type-graph) (64)
- [🧠 个人知识库](#type-personal) (6)

## 什么样的仓库能上榜

1. 知识库本身就是产品:LLM 维护的 wiki、RAG 知识库,或 agent 据以回答的文档。通用聊天机器人、单纯的向量数据库不算。
2. 它是能安装或运行的软件,不是链接合集或空仓库。
3. 它有 README。没有 README 就没法评级。
4. 50 星及以上只看是否切题;50 星以下还要过 README 质量线(展示效果、一条命令上手、说清产出、文档完整),并且至少 5 星。

这些问题由决策模型逐个读 README 回答,不是人工挑选。卡在线上的仓库可能判到任一边,归错了请提 issue。

<a id="type-llm_wiki"></a>
## 📖 LLM Wiki

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list#type-llm_wiki)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | 39.2k | AI Agent 的自演化上下文数据库，统一 Agent 记忆、知识 RAG 和 skill。 | [SAFE](https://agentskillshub.top/skill/volcengine/OpenViking/?utm_source=github&utm_medium=awesome-list) |
| [AsyncFuncAI/deepwiki-open](https://github.com/AsyncFuncAI/deepwiki-open) | 18.1k | DeepWiki：为 GitHub/GitLab/Bitbucket 仓库生成 AI Wiki 的开源工具 | [SAFE](https://agentskillshub.top/skill/AsyncFuncAI/deepwiki-open/?utm_source=github&utm_medium=awesome-list) |
| [langchain-ai/openwiki](https://github.com/langchain-ai/openwiki) | 16.9k | OpenWiki 是为代码库编写和维护 agent 文档的 CLI。 | [SAFE](https://agentskillshub.top/skill/langchain-ai/openwiki/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) | 15.3k | Obsidian + Claude Code 的 AI 第二大脑：将资料整理成纯 Markdown 知识图谱，支持 AI 笔记与 PKM，基于 Karpath… | [SAFE](https://agentskillshub.top/skill/AgriciDaniel/claude-obsidian/?utm_source=github&utm_medium=awesome-list) |
| [eugeniughelbur/obsidian-second-brain](https://github.com/eugeniughelbur/obsidian-second-brain) | 4.7k | Claude Code等7个CLI agent的持久记忆，以Markdown存储于Obsidian库。含45个命令：语义搜索、笔记改写、免密网络研究和定时维护… | [SAFE](https://agentskillshub.top/skill/eugeniughelbur/obsidian-second-brain/?utm_source=github&utm_medium=awesome-list) |
| [SamurAIGPT/llm-wiki-agent](https://github.com/SamurAIGPT/llm-wiki-agent) | 3.6k | 自维护个人知识库：导入资料，Claude（或 Codex/Gemini）提取知识并维护互联 wiki。支持 Claude Code、Codex、OpenCod… | [SAFE](https://agentskillshub.top/skill/SamurAIGPT/llm-wiki-agent/?utm_source=github&utm_medium=awesome-list) |
| [agentscope-ai/ReMe](https://github.com/agentscope-ai/ReMe) | 3.5k | ReMe：面向 agent 的记忆管理工具包 | [SAFE](https://agentskillshub.top/skill/agentscope-ai/ReMe/?utm_source=github&utm_medium=awesome-list) |
| [Ar9av/obsidian-wiki](https://github.com/Ar9av/obsidian-wiki) | 3.5k | 通过 Obsidian wiki 构建和维护数字大脑的 AI agent 框架，agent 记忆系统 | [SAFE](https://agentskillshub.top/skill/Ar9av/obsidian-wiki/?utm_source=github&utm_medium=awesome-list) |
| [agenticnotetaking/arscontexta](https://github.com/agenticnotetaking/arscontexta) | 3.5k | 基于对话生成个性化知识系统的 Claude Code 插件，输出你拥有的 Markdown 文件第二大脑。 | [SAFE](https://agentskillshub.top/skill/agenticnotetaking/arscontexta/?utm_source=github&utm_medium=awesome-list) |
| [Astro-Han/karpathy-llm-wiki](https://github.com/Astro-Han/karpathy-llm-wiki) | 2.4k | 兼容 Agent Skills 的 LLM wiki，适用于 Claude Code、Cursor 和 Codex。用原始资料、引用和 linting 构建… | [SAFE](https://agentskillshub.top/skill/Astro-Han/karpathy-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [atomicstrata/llm-wiki-compiler](https://github.com/atomicstrata/llm-wiki-compiler) | 2.2k | 知识编译器。输入原始资料，输出相互链接的 Wiki。受 Karpathy 的 LLM Wiki 模式启发。 | [SAFE](https://agentskillshub.top/skill/atomicstrata/llm-wiki-compiler/?utm_source=github&utm_medium=awesome-list) |
| [lucasastorian/llmwiki](https://github.com/lucasastorian/llmwiki) | 1.7k | Karpathy 的 LLM Wiki 开源实现。上传文档，通过 MCP 连接 Claude 账户，让它编写 wiki！ | [SAFE](https://agentskillshub.top/skill/lucasastorian/llmwiki/?utm_source=github&utm_medium=awesome-list) |
| [axoviq-ai/synthadoc](https://github.com/axoviq-ai/synthadoc) | 1.6k | Synthadoc：开源LLM知识编译引擎，将原始文档转为结构化、本地优先的Wiki。透明、易读，可自行管理和改进，无需工具。 | [SAFE](https://agentskillshub.top/skill/axoviq-ai/synthadoc/?utm_source=github&utm_medium=awesome-list) |
| [nduckmink/arkon](https://github.com/nduckmink/arkon) | 1.5k | Arkon：企业 AI 知识库与 MCP Server；自托管管理 RAG 上下文、访问策略和 AI skill，通过 MCP 连接 Claude 等 LLM… | [SAFE](https://agentskillshub.top/skill/nduckmink/arkon/?utm_source=github&utm_medium=awesome-list) |
| [nvk/llm-wiki](https://github.com/nvk/llm-wiki) | 1.4k | 为任意 AI agent 编译知识库。支持并行多 agent 研究、论点驱动调查、来源导入、Wiki 编纂、查询和产物生成。 | [SAFE](https://agentskillshub.top/skill/nvk/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [AlmanacCode/codealmanac](https://github.com/AlmanacCode/codealmanac) | 997 | 供 AI coding agents 使用的代码库 wiki，记录代码未表达的决策、流程、不变量和易错点。 | [SAFE](https://agentskillshub.top/skill/AlmanacCode/codealmanac/?utm_source=github&utm_medium=awesome-list) |
| [undefined-ui/second-brain-os](https://github.com/undefined-ui/second-brain-os) | 886 | 能自我维护的 AI 第二大脑，包含指南、起始知识库、agent skills 和脚本，用于在 Claude Code 和 Obsidian 中构建自组织知识库。 | [SAFE](https://agentskillshub.top/skill/undefined-ui/second-brain-os/?utm_source=github&utm_medium=awesome-list) |
| [swarmclawai/swarmvault](https://github.com/swarmclawai/swarmvault) | 708 | 本地优先的LLM Wiki：开源知识图谱、RAG知识库和agent记忆；可替代Obsidian，支持Claude Code、Codex、OpenClaw。 | [SAFE](https://agentskillshub.top/skill/swarmclawai/swarmvault/?utm_source=github&utm_medium=awesome-list) |
| [lewislulu/llm-wiki-skill](https://github.com/lewislulu/llm-wiki-skill) | 655 | Karpathy 风格的 LLM 知识库 Agent Skill，适用于 OpenClaw/Codex。实验性项目，将持续迭代。 | [SAFE](https://agentskillshub.top/skill/lewislulu/llm-wiki-skill/?utm_source=github&utm_medium=awesome-list) |
| [opendatalab/MinerU-Document-Explorer](https://github.com/opendatalab/MinerU-Document-Explorer) | 637 | Agent 原生知识引擎：用 MCP 工具索引文档、整理 Wiki、快速检索和深度阅读，支持 PDF/DOCX/PPTX/Markdown | [SAFE](https://agentskillshub.top/skill/opendatalab/MinerU-Document-Explorer/?utm_source=github&utm_medium=awesome-list) |
| [zosmaai/pi-llm-wiki](https://github.com/zosmaai/pi-llm-wiki) | 600 | 可自维护、兼容 Obsidian 的 pi 知识库，将原始资料整理为互联的 wiki。原生支持 Open Knowledge Format (OKF) v0.… | [SAFE](https://agentskillshub.top/skill/zosmaai/pi-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [Pratiyush/llm-wiki](https://github.com/Pratiyush/llm-wiki) | 394 | 基于 LLM 的知识库，来自 Claude Code、Codex CLI、Copilot、Cursor 和 Gemini 会话。实现并发布 Karpathy… | [SAFE](https://agentskillshub.top/skill/Pratiyush/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [ussumant/llm-wiki-compiler](https://github.com/ussumant/llm-wiki-compiler) | 325 | 将 Markdown 知识文件编译为主题式 wiki 的 Claude Code 插件，采用 Karpathy 的 LLM Knowledge Base 模式。 | [SAFE](https://agentskillshub.top/skill/ussumant/llm-wiki-compiler/?utm_source=github&utm_medium=awesome-list) |
| [luotwo/llm-wiki](https://github.com/luotwo/llm-wiki) | 223 | LLM Wiki - 用 LLM 构建持续积累的个人知识库，含 Claude Code Skill 和实战经验 | [SAFE](https://agentskillshub.top/skill/luotwo/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [mduongvandinh/llm-wiki](https://github.com/mduongvandinh/llm-wiki) | 213 | 由 LLM 驱动的全自动个人知识库，基于 Andrej Karpathy 的 LLM Wiki 模式。 | [SAFE](https://agentskillshub.top/skill/mduongvandinh/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [kfchou/wiki-skills](https://github.com/kfchou/wiki-skills) | 186 | Claude Code 的 LLM 维护个人 Wiki skills，实现 Karpathy 的 LLM Wiki 模式 | [SAFE](https://agentskillshub.top/skill/kfchou/wiki-skills/?utm_source=github&utm_medium=awesome-list) |
| [IssacW228/student-llm-wiki](https://github.com/IssacW228/student-llm-wiki) | 176 | 学生LLMWiki：把课程幻灯片整理成互联知识库，支持费曼复习、备考、信心衰减和跨课关联，适配Claude Code与Obsidian。 | [SAFE](https://agentskillshub.top/skill/IssacW228/student-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [serradura/okf-gem](https://github.com/serradura/okf-gem) | 172 | 编程 agent 的开放知识格式。okf gem 管理 Markdown 知识包；okf-mcp 服务 MCP host，含 Docker 和 Claude… | [SAFE](https://agentskillshub.top/skill/serradura/okf-gem/?utm_source=github&utm_medium=awesome-list) |
| [alfadur7/llm-wiki-newsroom](https://github.com/alfadur7/llm-wiki-newsroom) | 169 | Harness engineering：agent 编辑部将文档转成交链 Markdown wiki；reground 防页面过时，写作≠审阅，本地优先，结构… | [SAFE](https://agentskillshub.top/skill/alfadur7/llm-wiki-newsroom/?utm_source=github&utm_medium=awesome-list) |
| [bybit-exchange/kaas](https://github.com/bybit-exchange/kaas) | 149 | 将零散笔记、文档和文字稿整理为可查询的 Markdown wiki，支持 MCP 访问，无需 embeddings，可自托管。 | [SAFE](https://agentskillshub.top/skill/bybit-exchange/kaas/?utm_source=github&utm_medium=awesome-list) |
| [MehmetGoekce/llm-wiki](https://github.com/MehmetGoekce/llm-wiki) | 147 | 使用 Claude Code 构建 Karpathy 的 LLM Wiki，采用 L1/L2 缓存架构，支持 Logseq + Obsidian。 | [SAFE](https://agentskillshub.top/skill/MehmetGoekce/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [Mark393295827/third-brain-v5-skills](https://github.com/Mark393295827/third-brain-v5-skills) | 141 | agent 百科 | [SAFE](https://agentskillshub.top/skill/Mark393295827/third-brain-v5-skills/?utm_source=github&utm_medium=awesome-list) |
| [Mark393295827/third-brain-v7-skills](https://github.com/Mark393295827/third-brain-v7-skills) | 141 | agent wiki + 工程 skills | [SAFE](https://agentskillshub.top/skill/Mark393295827/third-brain-v7-skills/?utm_source=github&utm_medium=awesome-list) |
| [psinetron/echoes-vault-codex](https://github.com/psinetron/echoes-vault-codex) | 131 | Codex 持久记忆插件，跨会话保留的 Obsidian 风格知识库 | [SAFE](https://agentskillshub.top/skill/psinetron/echoes-vault-codex/?utm_source=github&utm_medium=awesome-list) |
| [ctxr-dev/llm-wiki-memory](https://github.com/ctxr-dev/llm-wiki-memory) | 130 | 本地、Git 版本化的 AI 编程 agent 记忆。无需 RAG、Docker 或外部服务。借助本地 LLM wiki、设备端 embeddings 和 M… | [SAFE](https://agentskillshub.top/skill/ctxr-dev/llm-wiki-memory/?utm_source=github&utm_medium=awesome-list) |
| [frankchu91/mindbase](https://github.com/frankchu91/mindbase) | 125 | Karpathy 的 LLM Wiki 产品：AI 根据笔记和来源构建并维护 markdown wiki。MCP server + web UI，支持 Oll… | [SAFE](https://agentskillshub.top/skill/frankchu91/mindbase/?utm_source=github&utm_medium=awesome-list) |
| [frankchu91/mindbase-llm-wiki](https://github.com/frankchu91/mindbase-llm-wiki) | 125 | Karpathy 的 LLM Wiki 产品：AI 根据笔记和资料构建并维护 Markdown wiki。MCP server + web UI，支持 Oll… | [SAFE](https://agentskillshub.top/skill/frankchu91/mindbase-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [NimaChu/my-wiki-skill](https://github.com/NimaChu/my-wiki-skill) | 124 | 用于构建有证据支持的 Markdown 知识库的 Agent Skill，支持图像感知采集、自动维护 wiki 和交互式知识图谱，无需 RAG 技术栈或 Ob… | [SAFE](https://agentskillshub.top/skill/NimaChu/my-wiki-skill/?utm_source=github&utm_medium=awesome-list) |
| [praneybehl/llm-wiki-plugin](https://github.com/praneybehl/llm-wiki-plugin) | 116 | Andrej Karpathy 的 LLM Wiki 模式，作为 skill 和 Claude Code 插件：将资料转为可自维护、可扩展的 Markdown… | [SAFE](https://agentskillshub.top/skill/praneybehl/llm-wiki-plugin/?utm_source=github&utm_medium=awesome-list) |
| [SherwinQ/karpathy-wiki](https://github.com/SherwinQ/karpathy-wiki) | 113 | 基于 Andrej Karpathy 提出的 LLM Wiki 模式构建的 Agent skill，通过四阶段流水线将碎片信息转化为结构化、可检索、持续增长的… | [SAFE](https://agentskillshub.top/skill/SherwinQ/karpathy-wiki/?utm_source=github&utm_medium=awesome-list) |
| [toolboxmd/karpathy-wiki](https://github.com/toolboxmd/karpathy-wiki) | 104 | Karpathy Wiki - 用于构建持久积累知识库的 Claude Code skills，基于 Andrej Karpathy 的 LLM Wiki 模… | [SAFE](https://agentskillshub.top/skill/toolboxmd/karpathy-wiki/?utm_source=github&utm_medium=awesome-list) |
| [doum1004/llmwiki-cli](https://github.com/doum1004/llmwiki-cli) | 103 | 用于构建和维护个人知识库的 LLM agent CLI 工具 | [SAFE](https://agentskillshub.top/skill/doum1004/llmwiki-cli/?utm_source=github&utm_medium=awesome-list) |
| [NulightJens/ai-second-brain-skills](https://github.com/NulightJens/ai-second-brain-skills) | 100 | 用于构建 Karpathy 风格 LLM wiki 的两个 Claude Code skill。 | [SAFE](https://agentskillshub.top/skill/NulightJens/ai-second-brain-skills/?utm_source=github&utm_medium=awesome-list) |
| [klemensgc/modular-context-obsidian-plugin](https://github.com/klemensgc/modular-context-obsidian-plugin) | 99 | 模块化上下文：Karpathy LLM 知识库与 Gmail、G-Cal，多账户 Claude Code MCP 服务器，本地优先并加密 | [SAFE](https://agentskillshub.top/skill/klemensgc/modular-context-obsidian-plugin/?utm_source=github&utm_medium=awesome-list) |
| [capitalparser/notebooklm-wiki-pipeline](https://github.com/capitalparser/notebooklm-wiki-pipeline) | 94 | Turn Google Drive PDFs into Obsidian wiki notes via NotebookLM MCP without loading full PDFs into Claude context | [SAFE](https://agentskillshub.top/skill/capitalparser/notebooklm-wiki-pipeline/?utm_source=github&utm_medium=awesome-list) |
| [zby/commonplace](https://github.com/zby/commonplace) | 91 | LLM wiki 协同运行理论：供 agent 操作知识的框架，包含带类型、可链接、经审核的 Markdown，由 agent 执行。 | [SAFE](https://agentskillshub.top/skill/zby/commonplace/?utm_source=github&utm_medium=awesome-list) |
| [johnfkoo951/cmds-llm-wiki](https://github.com/johnfkoo951/cmds-llm-wiki) | 90 | LLM Wiki 模板：Karpathy 三层模式＋Gold In Gold Out 目的门＋Claude Code·Codex 双 harness（11 个… | [SAFE](https://agentskillshub.top/skill/johnfkoo951/cmds-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [Lambenthan/empiricalwiki](https://github.com/Lambenthan/empiricalwiki) | 89 | 经管实证研究 AI 知识库，覆盖文献阅读至 Stata 执行，按10类实体组织：变量、数据集、模型、机制、假设、识别策略、稳健性、异质性、表格、论文。 | [SAFE](https://agentskillshub.top/skill/Lambenthan/empiricalwiki/?utm_source=github&utm_medium=awesome-list) |
| [vouchdev/vouch](https://github.com/vouchdev/vouch) | 82 | 面向 AI agents 的 Git 原生审核知识库：它们提议写入，你审批。每条声明引用来源，每次变更均为仓库中的 diff。MCP + CLI。 | [SAFE](https://agentskillshub.top/skill/vouchdev/vouch/?utm_source=github&utm_medium=awesome-list) |
| [7xuanlu/wenlan](https://github.com/7xuanlu/wenlan) | 79 | Wenlan 是面向 AI 原生时代的知识库，AI agent 记录所学并生成持续更新、标注来源的 wiki 页面。 | [SAFE](https://agentskillshub.top/skill/7xuanlu/wenlan/?utm_source=github&utm_medium=awesome-list) |
| [tuirk/Kompl](https://github.com/tuirk/Kompl) | 78 | 可持续积累的 LLM wiki，适合作为个人第二大脑，随内容增长自动整理和更新，无需维护 | [CAUTION](https://agentskillshub.top/skill/tuirk/Kompl/?utm_source=github&utm_medium=awesome-list) |
| [ndjordjevic/pin-llm-wiki](https://github.com/ndjordjevic/pin-llm-wiki) | 76 | 用于 Claude、Cursor 和 Copilot 的 skill，自动执行 Karpathy LLM Wiki 流程：将网页、GitHub 和 YouTu… | [SAFE](https://agentskillshub.top/skill/ndjordjevic/pin-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [smixs/autograph](https://github.com/smixs/autograph) | 73 | Obsidian 中 AI agent 的 schema-as-code 记忆：类型化卡片、实体去重、链接修复、原位更新、艾宾浩斯衰减。你拥有的纯 Markd… | [SAFE](https://agentskillshub.top/skill/smixs/autograph/?utm_source=github&utm_medium=awesome-list) |
| [zcag/tela](https://github.com/zcag/tela) | 73 | 开源自托管 Markdown 团队 Wiki，内置 MCP server，支持 AI agents 读写和搜索文档、实时协作、语义及全文搜索。 | [SAFE](https://agentskillshub.top/skill/zcag/tela/?utm_source=github&utm_medium=awesome-list) |
| [sametbrr/llm-wiki-manager](https://github.com/sametbrr/llm-wiki-manager) | 71 | 用于持久化 LLM 管理的 wiki 的 skill：LLM 编写并交叉引用，你维护来源。 | [SAFE](https://agentskillshub.top/skill/sametbrr/llm-wiki-manager/?utm_source=github&utm_medium=awesome-list) |
| [Benboerba620/karpathy-claude-wiki](https://github.com/Benboerba620/karpathy-claude-wiki) | 69 | 面向 LLM 的 Karpathy 风格个人 wiki：Markdown + frontmatter，无向量数据库、无 RAG。为 Claude Code 打… | [SAFE](https://agentskillshub.top/skill/Benboerba620/karpathy-claude-wiki/?utm_source=github&utm_medium=awesome-list) |
| [vanillaflava/llm-wiki-skills](https://github.com/vanillaflava/llm-wiki-skills) | 69 | 将 Markdown 知识库整理为 Wiki，含 6 个 agent skill；支持 Obsidian、Logseq、本地文件夹和 LLM 会话记忆，跨平台。 | [SAFE](https://agentskillshub.top/skill/vanillaflava/llm-wiki-skills/?utm_source=github&utm_medium=awesome-list) |
| [oliver-kriska/scribe](https://github.com/oliver-kriska/scribe) | 64 | 由LLM管理的个人知识库，自动从git仓库、Claude Code会话和iMessage书签提取内容，跨项目使用，qmd索引，按cron运行 | [CAUTION](https://agentskillshub.top/skill/oliver-kriska/scribe/?utm_source=github&utm_medium=awesome-list) |
| [remember-md/remember](https://github.com/remember-md/remember) | 62 | AI-powered second brain for Claude Code that builds itself. Extract knowledge from every session—past and present—into auto-organized Markdown. Local… | [SAFE](https://agentskillshub.top/skill/remember-md/remember/?utm_source=github&utm_medium=awesome-list) |
| [JanYork/llm-wiki-cli](https://github.com/JanYork/llm-wiki-cli) | 61 | 由 agent 驱动的主动记忆 CLI：跨会话自主回忆、维护并演化有来源依据的持久知识 | [SAFE](https://agentskillshub.top/skill/JanYork/llm-wiki-cli/?utm_source=github&utm_medium=awesome-list) |
| [iamsashank09/llm-wiki-kit](https://github.com/iamsashank09/llm-wiki-kit) | 61 | 别再向 AI agent 反复解释研究内容。LLM 持续维护并积累的 wiki。导入 PDF、URL、YouTube，agent 永久记住。基于 Karpat… | [SAFE](https://agentskillshub.top/skill/iamsashank09/llm-wiki-kit/?utm_source=github&utm_medium=awesome-list) |
| [MetamusicX/zissa-wiki](https://github.com/MetamusicX/zissa-wiki) | 58 | Zissa Wiki——纯 Markdown 研究知识库，可由任意 AI agent 维护；采用 Karpathy 的 LLM Wiki 模式，核对每条引文来… | [SAFE](https://agentskillshub.top/skill/MetamusicX/zissa-wiki/?utm_source=github&utm_medium=awesome-list) |
| [bashiraziz/llm-wiki-template](https://github.com/bashiraziz/llm-wiki-template) | 52 | A reusable template for building personal LLM-maintained knowledge bases. Implements Karpathy's LLM Wiki pattern. | [SAFE](https://agentskillshub.top/skill/bashiraziz/llm-wiki-template/?utm_source=github&utm_medium=awesome-list) |
| [lpaiu-cs/osk-system](https://github.com/lpaiu-cs/osk-system) | 51 | Source-grounded MCP memory runtime and Obsidian-compatible vault template for LLM agents. | [SAFE](https://agentskillshub.top/skill/lpaiu-cs/osk-system/?utm_source=github&utm_medium=awesome-list) |
| [sodam-ai/SoDam-WikiMate](https://github.com/sodam-ai/SoDam-WikiMate) | 51 | AI에게 '정리해줘'라고 하면 흩어진 자료를 옵시디언(원본)에 노트로 정리하고, 관련 노트끼리 연결·분류·요약하고, 선택적으로 노션에 색인하는 Claude Code 플러그인 + 이식형 MCP 코어. 보관함 자동탐지·정리·자동 링크/MOC·자동 분류·요약(원자 노트)·… | [SAFE](https://agentskillshub.top/skill/sodam-ai/SoDam-WikiMate/?utm_source=github&utm_medium=awesome-list) |
| [Oshayr/LLM-Wiki](https://github.com/Oshayr/LLM-Wiki) | 50 | Autonomous knowledge base plugin for Claude Code - captures reserch, ideas, and decisions into an interlinked wiki with reserch-on-miss, semantic sea… | [SAFE](https://agentskillshub.top/skill/Oshayr/LLM-Wiki/?utm_source=github&utm_medium=awesome-list) |
| [6eanut/llm-wiki](https://github.com/6eanut/llm-wiki) | 47 | Claude Code skill for building persistent, interlinked knowledge bases from source documents. Knowledge is compiled once and kept current — never re-… | [SAFE](https://agentskillshub.top/skill/6eanut/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [cobusgreyling/llm-wiki](https://github.com/cobusgreyling/llm-wiki) | 45 | A compounding knowledge base maintained by LLM agents — inspired by Karpathy's LLM Wiki pattern | [SAFE](https://agentskillshub.top/skill/cobusgreyling/llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [2233admin/obsidian-llm-wiki](https://github.com/2233admin/obsidian-llm-wiki) | 36 | Your markdown vault, compiled into a 6-persona MCP team for Claude Code, Codex, OpenCode, and Gemini CLI. Headless-first. Cites, doesn't guess. | [SAFE](https://agentskillshub.top/skill/2233admin/obsidian-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [atukunare/wiki-knowledge-agent](https://github.com/atukunare/wiki-knowledge-agent) | 19 | Your AI forgets. A wiki doesn't. Turn chat-pasted text/links into a verified, translated, searchable wiki knowledge base — verify links, filter ads,… | [SAFE](https://agentskillshub.top/skill/atukunare/wiki-knowledge-agent/?utm_source=github&utm_medium=awesome-list) |

<a id="type-rag_platform"></a>
## 🏗 RAG 知识库平台

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list#type-rag_platform)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 91.6k | RAGFlow 是开源的检索增强生成（RAG）引擎，结合 RAG 与 Agent 能力，为 LLMs 提供上下文层 | [SAFE](https://agentskillshub.top/skill/infiniflow/ragflow/?utm_source=github&utm_medium=awesome-list) |
| [1Panel-dev/MaxKB](https://github.com/1Panel-dev/MaxKB) | 22.9k | MaxKB 是用于构建企业级智能体的开源平台。 | [SAFE](https://agentskillshub.top/skill/1Panel-dev/MaxKB/?utm_source=github&utm_medium=awesome-list) |
| [airweave-ai/airweave](https://github.com/airweave-ai/airweave) | 6.6k | 面向 AI agent 的开源上下文检索层 | [SAFE](https://agentskillshub.top/skill/airweave-ai/airweave/?utm_source=github&utm_medium=awesome-list) |
| [dmayboroda/minima](https://github.com/dmayboroda/minima) | 1.0k | 可配置容器的本地部署对话式 RAG | [SAFE](https://agentskillshub.top/skill/dmayboroda/minima/?utm_source=github&utm_medium=awesome-list) |
| [Ciao1019/Petrichor](https://github.com/Ciao1019/Petrichor) | 143 | 面向人类和 AI agents 的自托管知识平台，发布 wiki、博客和可移植的 Agent Skills。 | [SAFE](https://agentskillshub.top/skill/Ciao1019/Petrichor/?utm_source=github&utm_medium=awesome-list) |
| [madarco/ragrabbit](https://github.com/madarco/ragrabbit) | 136 | 开源、自托管的网站 AI 搜索和 LLM.txt | [SAFE](https://agentskillshub.top/skill/madarco/ragrabbit/?utm_source=github&utm_medium=awesome-list) |
| [gmickel/gno](https://github.com/gmickel/gno) | 115 | 本地 AI 文档搜索与编辑，支持混合检索、LLM 回答、WebUI、REST API 和 MCP，适用于 AI 客户端。 | [SAFE](https://agentskillshub.top/skill/gmickel/gno/?utm_source=github&utm_medium=awesome-list) |
| [joungminsung/OpenDocuments](https://github.com/joungminsung/OpenDocuments) | 115 | 自托管 RAG 平台，支持搜索 GitHub、Notion、Google Drive、本地文件和网页文档，并提供引用。 | [SAFE](https://agentskillshub.top/skill/joungminsung/OpenDocuments/?utm_source=github&utm_medium=awesome-list) |
| [quanta-quest/quanta-quest](https://github.com/quanta-quest/quanta-quest) | 102 | AI 驱动的个人数据通用搜索，按你的需求定制。目标：以“端侧 LLM + 用户数据本地化”为核心发展方向。 | [SAFE](https://agentskillshub.top/skill/quanta-quest/quanta-quest/?utm_source=github&utm_medium=awesome-list) |

<a id="type-mcp"></a>
## 🔌 MCP 与 Agent Skill

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list#type-mcp)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [zilliztech/memsearch](https://github.com/zilliztech/memsearch) | 2.7k | 基于 Markdown 和 Milvus，为 Claude Code、Codex、DSH 等 AI agent 提供统一记忆层。 | [SAFE](https://agentskillshub.top/skill/zilliztech/memsearch/?utm_source=github&utm_medium=awesome-list) |
| [coleam00/mcp-crawl4ai-rag](https://github.com/coleam00/mcp-crawl4ai-rag) | 2.3k | 为 AI agents 和 AI coding assistants 提供网页抓取与 RAG 能力 | [SAFE](https://agentskillshub.top/skill/coleam00/mcp-crawl4ai-rag/?utm_source=github&utm_medium=awesome-list) |
| [MicrosoftDocs/mcp](https://github.com/MicrosoftDocs/mcp) | 1.9k | Microsoft Learn MCP Server 和 CLI 工具，为 LLM 和 AI agent 提供实时、可信的 Microsoft 文档与代码示例。 | [SAFE](https://agentskillshub.top/skill/MicrosoftDocs/mcp/?utm_source=github&utm_medium=awesome-list) |
| [chunkhound/chunkhound](https://github.com/chunkhound/chunkhound) | 1.4k | 深入理解你的整个工程上下文 | [SAFE](https://agentskillshub.top/skill/chunkhound/chunkhound/?utm_source=github&utm_medium=awesome-list) |
| [study8677/antigravity-workspace-template](https://github.com/study8677/antigravity-workspace-template) | 1.3k | 为 Claude Code、Cursor、Codex CLI 提供代码库问答。多 agent 知识引擎，回答附文件路径和行号，适用于任意 AI IDE。 | [SAFE](https://agentskillshub.top/skill/study8677/antigravity-workspace-template/?utm_source=github&utm_medium=awesome-list) |
| [study8677/repobrain](https://github.com/study8677/repobrain) | 1.3k | RepoBrain（原名 Antigravity）为代码库提供对话功能，支持 Claude Code、Cursor、Codex、Windsurf 等。 | [SAFE](https://agentskillshub.top/skill/study8677/repobrain/?utm_source=github&utm_medium=awesome-list) |
| [0xranx/OpenContext](https://github.com/0xranx/OpenContext) | 1.3k | 面向 AI agents/assistants 的个人上下文库：用 Codex/Claude/OpenCode、Skills/tools 和桌面 GUI，跨… | [SAFE](https://agentskillshub.top/skill/0xranx/OpenContext/?utm_source=github&utm_medium=awesome-list) |
| [jerry-ai-dev/MODULAR-RAG-MCP-SERVER](https://github.com/jerry-ai-dev/MODULAR-RAG-MCP-SERVER) | 1.2k | 采用 MCP Server 架构的模块化 RAG 系统，使用 Skill 让 AI 遵循规范逐步完成代码。 | [SAFE](https://agentskillshub.top/skill/jerry-ai-dev/MODULAR-RAG-MCP-SERVER/?utm_source=github&utm_medium=awesome-list) |
| [chubbyguan/chubbyskills](https://github.com/chubbyguan/chubbyskills) | 1.2k | 14个AI Skill：采集抖音、B站、小红书、公众号、X和播客内容到个人知识库，图文存图、视频转文字稿、字幕优先免GPU，附知识库MCP server | [SAFE](https://agentskillshub.top/skill/chubbyguan/chubbyskills/?utm_source=github&utm_medium=awesome-list) |
| [BagelHole/DevOps-Security-Agent-Skills](https://github.com/BagelHole/DevOps-Security-Agent-Skills) | 1.1k | 面向 agent 的 DevOps 与安全知识库，涵盖 Kubernetes、云、AI 平台、容器、合规和事件响应，含80+ skills及脚本、模板、操作手… | [SAFE](https://agentskillshub.top/skill/BagelHole/DevOps-Security-Agent-Skills/?utm_source=github&utm_medium=awesome-list) |
| [0xK3vin/MegaMemory](https://github.com/0xK3vin/MegaMemory) | 709 | 面向编程 agent 的持久化项目知识图谱，提供语义搜索、进程内嵌入和网页探索器的 MCP server。 | [SAFE](https://agentskillshub.top/skill/0xK3vin/MegaMemory/?utm_source=github&utm_medium=awesome-list) |
| [GeminiLight/MindOS](https://github.com/GeminiLight/MindOS) | 677 | MindOS 是人类与 AI 协作的思维系统：人类思考，agents 执行；为所有 agents 同步思维，透明、可控并协同演进。 | [SAFE](https://agentskillshub.top/skill/GeminiLight/MindOS/?utm_source=github&utm_medium=awesome-list) |
| [docsagent/docsagent](https://github.com/docsagent/docsagent) | 625 | DocsAgent：私有知识库搜索，支持Zotero、Obsidian、Apple Notes；MCP支持Claude、Cursor、Cline。 | [SAFE](https://agentskillshub.top/skill/docsagent/docsagent/?utm_source=github&utm_medium=awesome-list) |
| [Ikalus1988/MisakaNet](https://github.com/Ikalus1988/MisakaNet) | 520 | 基于 git 的零依赖微课程库，供 AI Agents 异步分享和检索已验证的调试经验。https://misakanet.org | [SAFE](https://agentskillshub.top/skill/Ikalus1988/MisakaNet/?utm_source=github&utm_medium=awesome-list) |
| [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) | 415 | 在 Claude 中与笔记对话。使用 Model Context Protocol 对 Apple Notes 进行 RAG。 | [SAFE](https://agentskillshub.top/skill/RafalWilinski/mcp-apple-notes/?utm_source=github&utm_medium=awesome-list) |
| [shinpr/mcp-local-rag](https://github.com/shinpr/mcp-local-rag) | 405 | 面向开发者的本地优先 RAG 服务器，支持代码和技术文档的语义与关键词搜索，可通过 MCP 或 CLI 使用 | [SAFE](https://agentskillshub.top/skill/shinpr/mcp-local-rag/?utm_source=github&utm_medium=awesome-list) |
| [andrea9293/mcp-documentation-server](https://github.com/andrea9293/mcp-documentation-server) | 342 | MCP 文档服务器：文档管理、Gemini 集成、AI 语义搜索、文件上传、智能分块、多语言支持；适用于新框架、API 文档和内部指南 | [SAFE](https://agentskillshub.top/skill/andrea9293/mcp-documentation-server/?utm_source=github&utm_medium=awesome-list) |
| [ergut/mcp-logseq](https://github.com/ergut/mcp-logseq) | 339 | 通过 LogSeq 本地 HTTP API 交互的 MCP server，支持 Claude 等 AI 助手读写和管理图谱 | [SAFE](https://agentskillshub.top/skill/ergut/mcp-logseq/?utm_source=github&utm_medium=awesome-list) |
| [nameforjt-afk/session-knowledge](https://github.com/nameforjt-afk/session-knowledge) | 336 | 将 Claude Code 会话历史变成可搜索的本地知识库——13 个 MCP 工具，仅用标准库，数据不离开本机 | [SAFE](https://agentskillshub.top/skill/nameforjt-afk/session-knowledge/?utm_source=github&utm_medium=awesome-list) |
| [aa0101181514/tw-legal-rag](https://github.com/aa0101181514/tw-legal-rag) | 327 | 台湾法律 MCP 服务器与 CLI：收录 2,250 万笔裁判书、行政函释及宪法法庭裁判，支持 Claude/ChatGPT/Codex，仅提供检索与引用查核。 | [SAFE](https://agentskillshub.top/skill/aa0101181514/tw-legal-rag/?utm_source=github&utm_medium=awesome-list) |
| [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) | 299 | 防止 AI 助手提供过时的 Rust 代码建议。MCP server 获取最新 crate 文档，使用 embeddings/LLMs，通过工具调用提供准确上… | [SAFE](https://agentskillshub.top/skill/Govcraft/rust-docs-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [lyonzin/knowledge-rag](https://github.com/lyonzin/knowledge-rag) | 290 | Claude Code 的本地 RAG MCP 服务器：混合搜索、交叉编码器重排，13 个 MCP 工具，支持 20 种格式解析，无需外部服务器或 API 密… | [SAFE](https://agentskillshub.top/skill/lyonzin/knowledge-rag/?utm_source=github&utm_medium=awesome-list) |
| [asgard-ai-platform/skills](https://github.com/asgard-ai-platform/skills) | 239 | 301 open-source coding agent skills across 22 domains — methodology, judgment & gotchas packaged as Claude Agent Skills for the Asgard AI Platform. | [SAFE](https://agentskillshub.top/skill/asgard-ai-platform/skills/?utm_source=github&utm_medium=awesome-list) |
| [MLT-OSS/FirstData](https://github.com/MLT-OSS/FirstData) | 183 | The World's Most Comprehensive, Authoritative, and Structured Open Source Data Source Knowledge Base | [SAFE](https://agentskillshub.top/skill/MLT-OSS/FirstData/?utm_source=github&utm_medium=awesome-list) |
| [ascend-ai-coding/awesome-ascend-skills](https://github.com/ascend-ai-coding/awesome-ascend-skills) | 174 | 面向华为 Ascend NPU 开发的知识库，以分布式 Agent Skills 组织。 | [SAFE](https://agentskillshub.top/skill/ascend-ai-coding/awesome-ascend-skills/?utm_source=github&utm_medium=awesome-list) |
| [andylow92/file-system-brain-mcp](https://github.com/andylow92/file-system-brain-mcp) | 168 | 可自我改进的 AI 原生 Markdown 知识库，供 Claude/Cursor 通过 MCP server 使用，支持搜索、RAG、引用回答和人工审核，学… | [SAFE](https://agentskillshub.top/skill/andylow92/file-system-brain-mcp/?utm_source=github&utm_medium=awesome-list) |
| [andylow92/file-system-like-github](https://github.com/andylow92/file-system-like-github) | 168 | AI 知识库，供 agent 使用；GitHub 文件树、Notion 编辑，经 MCP 接入 Claude/Cursor；支持搜索、RAG、引用回答；本地… | [SAFE](https://agentskillshub.top/skill/andylow92/file-system-like-github/?utm_source=github&utm_medium=awesome-list) |
| [ali-kamali/Axon.MCP.Server](https://github.com/ali-kamali/Axon.MCP.Server) | 166 | 将代码库转为智能知识库，供 Cursor IDE、Google AntiGravity 和支持 MCP 的助手进行 AI 开发 | [SAFE](https://agentskillshub.top/skill/ali-kamali/Axon.MCP.Server/?utm_source=github&utm_medium=awesome-list) |
| [0xchamin/mcptube](https://github.com/0xchamin/mcptube) | 161 | 将 YouTube 视频转为可积累的知识库，支持文字稿、视觉分析和 agent 搜索。作为 MCP server 支持 Claude、Copilot 等。 | [SAFE](https://agentskillshub.top/skill/0xchamin/mcptube/?utm_source=github&utm_medium=awesome-list) |
| [dnotitia/akb](https://github.com/dnotitia/akb) | 161 | AKB——Agent Knowledgebase。AI agent 的组织记忆：通过 URI 图统一管理 vault 内的文档、表格和文件，并经 MCP 提供… | [SAFE](https://agentskillshub.top/skill/dnotitia/akb/?utm_source=github&utm_medium=awesome-list) |
| [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) | 149 | 用于从 Pinecone 读取和写入的 Model Context Protocol 服务器，基础 RAG | [SAFE](https://agentskillshub.top/skill/sirmews/mcp-pinecone/?utm_source=github&utm_medium=awesome-list) |
| [zilliztech/mfs](https://github.com/zilliztech/mfs) | 148 | AI agent 的上下文工具：将分散的代码、记忆、文档、数据库和 SaaS 汇集到可搜索、可浏览的文件式界面中。 | [SAFE](https://agentskillshub.top/skill/zilliztech/mfs/?utm_source=github&utm_medium=awesome-list) |
| [jztan/pdf-mcp](https://github.com/jztan/pdf-mcp) | 147 | MCP server让 Claude Code和其他AI agent读取搜索大型PDF及文件夹，支持agentic RAG、混合搜索、按页读取、表格、图片、O… | [SAFE](https://agentskillshub.top/skill/jztan/pdf-mcp/?utm_source=github&utm_medium=awesome-list) |
| [radimsem/remindb](https://github.com/radimsem/remindb) | 128 | 面向 agent 的记忆数据库，可减少会话 token 82–99%。可移植的 SQLite 文件，随处保存 agent 记忆。 | [SAFE](https://agentskillshub.top/skill/radimsem/remindb/?utm_source=github&utm_medium=awesome-list) |
| [BingoWon/apple-rag-mcp](https://github.com/BingoWon/apple-rag-mcp) | 120 | 通过 RAG 为 AI agent 提供 Apple 开发者文档即时访问的 MCP server | [SAFE](https://agentskillshub.top/skill/BingoWon/apple-rag-mcp/?utm_source=github&utm_medium=awesome-list) |
| [plasma-ai/wiki](https://github.com/plasma-ai/wiki) | 103 | 为 agent 提供带索引的知识库和命令行工具。 | [SAFE](https://agentskillshub.top/skill/plasma-ai/wiki/?utm_source=github&utm_medium=awesome-list) |
| [IvenKooLab/loci](https://github.com/IvenKooLab/loci) | 100 | 可查询的第二大脑，整合分散的笔记和文档：混合检索（向量+BM25）、章节级引用，支持 AI agents 使用 MCP server。约300行，无需 Lan… | [SAFE](https://agentskillshub.top/skill/IvenKooLab/loci/?utm_source=github&utm_medium=awesome-list) |
| [Tubo2333/obsidian-knowledge-brain](https://github.com/Tubo2333/obsidian-knowledge-brain) | 100 | 记忆技术决策和错误修复并跨会话学习的 AI agent skill。v4.0，MIT | [SAFE](https://agentskillshub.top/skill/Tubo2333/obsidian-knowledge-brain/?utm_source=github&utm_medium=awesome-list) |
| [Albertchamberlain/Awesome-OKF](https://github.com/Albertchamberlain/Awesome-OKF) | 99 | OKF（Open Knowledge Format）——面向 agent 的工具、插件、skill、提案和文档目录，由 YAML 驱动，支持 agent 搜索… | [SAFE](https://agentskillshub.top/skill/Albertchamberlain/Awesome-OKF/?utm_source=github&utm_medium=awesome-list) |
| [byenzyme/enzyme](https://github.com/byenzyme/enzyme) | 86 | 面向知识库的本地优先编译步骤，较前沿模型成本降低350倍、速度提升1000倍 | [SAFE](https://agentskillshub.top/skill/byenzyme/enzyme/?utm_source=github&utm_medium=awesome-list) |
| [Asklear/Klear-Team-Brain](https://github.com/Asklear/Klear-Team-Brain) | 84 | 将团队的 AI 编程会话、GitHub 代码和文档整合为共享可搜索记忆的自托管 Git 事实库，可在编辑器中通过 MCP 查询 | [SAFE](https://agentskillshub.top/skill/Asklear/Klear-Team-Brain/?utm_source=github&utm_medium=awesome-list) |
| [hassancs91/brainoutside](https://github.com/hassancs91/brainoutside) | 76 | 面向 AI agent 的自托管记忆服务器。你的大脑是 git 仓库，通过 MCP 和 REST 提供服务。 | [SAFE](https://agentskillshub.top/skill/hassancs91/brainoutside/?utm_source=github&utm_medium=awesome-list) |
| [krokozyab/Agent-Fusion](https://github.com/krokozyab/Agent-Fusion) | 73 | Agent Fusion：完全本地RAG搜索代码和文档（Markdown、Word、PDF），减少AI agent幻觉，支持agent编排，单个JAR部署 | [SAFE](https://agentskillshub.top/skill/krokozyab/Agent-Fusion/?utm_source=github&utm_medium=awesome-list) |
| [nozomio-labs/nia](https://github.com/nozomio-labs/nia) | 73 | Nia 是面向 agent 的上下文增强层，主要为 coding agent 提供最新知识库。 | [SAFE](https://agentskillshub.top/skill/nozomio-labs/nia/?utm_source=github&utm_medium=awesome-list) |
| [bahdotsh/indxr](https://github.com/bahdotsh/indxr) | 72 | 面向 AI agent 的快速代码库索引器和知识维基。 | [SAFE](https://agentskillshub.top/skill/bahdotsh/indxr/?utm_source=github&utm_medium=awesome-list) |
| [MontyGovernance/montycat-mcp](https://github.com/MontyGovernance/montycat-mcp) | 67 | Shared, persistent memory for AI agents. Self-hosted MCP server with semantic search, vector RAG, and live updates. Works with Claude, Cursor, Codex,… | [SAFE](https://agentskillshub.top/skill/MontyGovernance/montycat-mcp/?utm_source=github&utm_medium=awesome-list) |
| [liangdabiao/deepseek-v4-flash-vision-video-rag](https://github.com/liangdabiao/deepseek-v4-flash-vision-video-rag) | 67 | DeepSeek V4-Flash Vision Video RAG：让AI理解视频并回答问题，附[MM:SS]时间戳、片段、关键帧和HTML预览。 | [SAFE](https://agentskillshub.top/skill/liangdabiao/deepseek-v4-flash-vision-video-rag/?utm_source=github&utm_medium=awesome-list) |
| [tomohiro-owada/devrag](https://github.com/tomohiro-owada/devrag) | 64 | 用于 Claude Code 的 Markdown 向量搜索 MCP 服务器，使用 multilingual-e5-small 嵌入进行自然语言搜索 | [CAUTION](https://agentskillshub.top/skill/tomohiro-owada/devrag/?utm_source=github&utm_medium=awesome-list) |
| [NatsuFox/Tapestry](https://github.com/NatsuFox/Tapestry) | 63 | Tapestry：基于 Agent Skill Bundle 的轻量书签知识库 | [SAFE](https://agentskillshub.top/skill/NatsuFox/Tapestry/?utm_source=github&utm_medium=awesome-list) |
| [hermes-labs-ai/zer0dex](https://github.com/hermes-labs-ai/zer0dex) | 62 | AI agent 的本地双层记忆：可读 Markdown 索引结合本地向量库语义检索，每次消息前查询。支持跨项目回忆，弥补扁平记忆文件或纯向量 RAG 的不足… | [SAFE](https://agentskillshub.top/skill/hermes-labs-ai/zer0dex/?utm_source=github&utm_medium=awesome-list) |
| [tobocop2/lilbee](https://github.com/tobocop2/lilbee) | 62 | 单个可执行文件管理多GPU本地AI模型，基于文件、代码和网页提供带引用的对话搜索；含MCP、TUI、CLI和API，兼容Ollama、LM Studio。 | [SAFE](https://agentskillshub.top/skill/tobocop2/lilbee/?utm_source=github&utm_medium=awesome-list) |
| [ccf/agentcairn](https://github.com/ccf/agentcairn) | 61 | 面向 AI coding agents 的长期跨项目记忆。以你自己的 Obsidian vault 为依据，无需 daemon 或不透明数据库，记忆归你所有。 | [UNSAFE](https://agentskillshub.top/skill/ccf/agentcairn/?utm_source=github&utm_medium=awesome-list) |
| [msdanyg/smart-connections-mcp](https://github.com/msdanyg/smart-connections-mcp) | 58 | Give Claude semantic memory of your Obsidian vault — local semantic search over Smart Connections embeddings via MCP. Multi-vault, block-level, 100%… | [SAFE](https://agentskillshub.top/skill/msdanyg/smart-connections-mcp/?utm_source=github&utm_medium=awesome-list) |
| [cbtw-apac/qdrant-loader](https://github.com/cbtw-apac/qdrant-loader) | 55 | Enterprise-ready vector database toolkit for building searchable knowledge bases from multiple data sources. Supports multi-project management, autom… | [SAFE](https://agentskillshub.top/skill/cbtw-apac/qdrant-loader/?utm_source=github&utm_medium=awesome-list) |
| [jeanibarz/knowledge-base-mcp-server](https://github.com/jeanibarz/knowledge-base-mcp-server) | 53 | This MCP server provides tools for listing and retrieving content from different knowledge bases. | [SAFE](https://agentskillshub.top/skill/jeanibarz/knowledge-base-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [lna-lab/distill-kura](https://github.com/lna-lab/distill-kura) | 53 | 蒸留蔵 — distilled long-term memory for agents: recall by meaning, writing gated by evidence, one kura per agent mode. Ships as a DeepSeek Harness plugi… | [SAFE](https://agentskillshub.top/skill/lna-lab/distill-kura/?utm_source=github&utm_medium=awesome-list) |
| [docouno/notarium](https://github.com/docouno/notarium) | 5 | File-first knowledge base for humans and AI agents — self-hosted Markdown notes with a web editor and a built-in MCP server. | [SAFE](https://agentskillshub.top/skill/docouno/notarium/?utm_source=github&utm_medium=awesome-list) |
| [pillumina/ascend-sleuth](https://github.com/pillumina/ascend-sleuth) | 5 | 知识驱动的昇腾训练/推理诊断 skill 套件 — Ascend training/inference diagnosis skill suite (5 skills + 3-tier knowledge base, Agent Skills standard) | [SAFE](https://agentskillshub.top/skill/pillumina/ascend-sleuth/?utm_source=github&utm_medium=awesome-list) |

<a id="type-docs_qa"></a>
## 📄 文档问答

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list#type-docs_qa)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | 33.4k | 将技术书籍 PDF 转为 Claude Code skill，便于学习、查阅和工作中使用。 | [SAFE](https://agentskillshub.top/skill/virgiliojr94/book-to-skill/?utm_source=github&utm_medium=awesome-list) |
| [mrsibe/KnowNote](https://github.com/mrsibe/KnowNote) | 1.2k | 基于 Electron 构建的本地优先 AI 知识库和 NotebookLM 替代品 | [SAFE](https://agentskillshub.top/skill/mrsibe/KnowNote/?utm_source=github&utm_medium=awesome-list) |
| [viddexa/autollm](https://github.com/viddexa/autollm) | 1.0k | 几秒发布基于 RAG 的 LLM 网页应用。 | [SAFE](https://agentskillshub.top/skill/viddexa/autollm/?utm_source=github&utm_medium=awesome-list) |
| [Bessouat40/RAGLight](https://github.com/Bessouat40/RAGLight) | 672 | RAGLight 是用于 Retrieval-Augmented Generation（RAG）的模块化框架，支持接入不同 LLM、embeddings、ve… | [SAFE](https://agentskillshub.top/skill/Bessouat40/RAGLight/?utm_source=github&utm_medium=awesome-list) |
| [ggozad/haiku.rag](https://github.com/ggozad/haiku.rag) | 618 | 本地及自托管文档搜索的 agentic RAG：混合检索、重排序、多模态 RAG，基于嵌入式 LanceDB，支持 Docling 解析和 MCP server | [SAFE](https://agentskillshub.top/skill/ggozad/haiku.rag/?utm_source=github&utm_medium=awesome-list) |
| [iamzulx/crypto-rag](https://github.com/iamzulx/crypto-rag) | 465 | 印尼语加密货币助手：267个主题RAG知识库+实时市场数据（6家交易所、WebSocket、衍生品、链上、TVL、DeFi）+工具调用agent+LLM合成 | [SAFE](https://agentskillshub.top/skill/iamzulx/crypto-rag/?utm_source=github&utm_medium=awesome-list) |
| [Ayanami0730/arag](https://github.com/Ayanami0730/arag) | 354 | A-RAG：通过分层检索接口实现的智能体检索增强生成框架，提供关键词、语义和分块读取工具，支持多跳问答。 | [SAFE](https://agentskillshub.top/skill/Ayanami0730/arag/?utm_source=github&utm_medium=awesome-list) |
| [Laurent00TT/PharosRAG](https://github.com/Laurent00TT/PharosRAG) | 243 | Pharos：本地优先的 agentic RAG，支持多格式导入、混合检索、企业 ACL 及 HTTP、MCP 接口 | [SAFE](https://agentskillshub.top/skill/Laurent00TT/PharosRAG/?utm_source=github&utm_medium=awesome-list) |
| [Laurent00TT/pharos](https://github.com/Laurent00TT/pharos) | 243 | Pharos——本地优先的团队文档库 agentic RAG：多格式导入、混合检索、企业 ACL，支持 HTTP 与 MCP 接口。 | [SAFE](https://agentskillshub.top/skill/Laurent00TT/pharos/?utm_source=github&utm_medium=awesome-list) |
| [aws-samples/serverless-rag-demo](https://github.com/aws-samples/serverless-rag-demo) | 224 | Amazon Bedrock 基础模型与 Amazon Opensearch Serverless 向量数据库 | [SAFE](https://agentskillshub.top/skill/aws-samples/serverless-rag-demo/?utm_source=github&utm_medium=awesome-list) |
| [Francis1998/scholar-rag-agent](https://github.com/Francis1998/scholar-rag-agent) | 149 | 本地优先的科学文献 RAG，支持引文锚定证据标注、人工筛选、固化溯源和无模型研究工作表。 | [SAFE](https://agentskillshub.top/skill/Francis1998/scholar-rag-agent/?utm_source=github&utm_medium=awesome-list) |
| [JetXu-LLM/DocMason](https://github.com/JetXu-LLM/DocMason) | 147 | DocMason是仓库原生agent，将办公文件转为本地LLM知识库。仓库即应用，Codex是运行时。 | [SAFE](https://agentskillshub.top/skill/JetXu-LLM/DocMason/?utm_source=github&utm_medium=awesome-list) |
| [guhcostan/claude-mega-brain](https://github.com/guhcostan/claude-mega-brain) | 126 | OKF 驱动的 Claude Code 知识上下文，每次会话注入项目知识库 | [SAFE](https://agentskillshub.top/skill/guhcostan/claude-mega-brain/?utm_source=github&utm_medium=awesome-list) |
| [flamehaven01/Flamehaven-Filesearch](https://github.com/flamehaven01/Flamehaven-Filesearch) | 109 | 开源语义文档搜索（RAG）引擎，基于 FastAPI，可即时自行部署 | [SAFE](https://agentskillshub.top/skill/flamehaven01/Flamehaven-Filesearch/?utm_source=github&utm_medium=awesome-list) |
| [aws-samples/aws-agentic-document-assistant](https://github.com/aws-samples/aws-agentic-document-assistant) | 98 | 基于 agent 的 LLM 助手，通过批量实体提取和 SQL 查询扩展 RAG，提升多步骤和分析类问题的性能。 | [SAFE](https://agentskillshub.top/skill/aws-samples/aws-agentic-document-assistant/?utm_source=github&utm_medium=awesome-list) |
| [dukesun99/Corpus2Skill](https://github.com/dukesun99/Corpus2Skill) | 92 | EMNLP 2026 官方结论：Corpus2Skill 将文档语料编译为可导航的 skill 层级，供 LLM agent 查询时探索，用文档查找替代服务时… | [SAFE](https://agentskillshub.top/skill/dukesun99/Corpus2Skill/?utm_source=github&utm_medium=awesome-list) |
| [kevins981/Socratic](https://github.com/kevins981/Socratic) | 81 | Socratic 是构建垂直 AI agent 的框架，专家可通过交互教学将隐性知识转化为持续改进的知识库。 | [CAUTION](https://agentskillshub.top/skill/kevins981/Socratic/?utm_source=github&utm_medium=awesome-list) |
| [PangHu1020/scholar-rag](https://github.com/PangHu1020/scholar-rag) | 80 | 适合初学者且易扩展的 Agentic RAG 项目，展示文档解析、检索、重排、工作流编排、工具调用和答案生成流程，便于学习和二次开发。 | [SAFE](https://agentskillshub.top/skill/PangHu1020/scholar-rag/?utm_source=github&utm_medium=awesome-list) |
| [liangdabiao/deepseek-v4-flash-vision-rag](https://github.com/liangdabiao/deepseek-v4-flash-vision-rag) | 70 | deepseek-v4-flash-vision-exp：PDF RAG 问答，支持扫描版，理解图表、表格、代码块和公式，回答并标页码、展示原图。 | [SAFE](https://agentskillshub.top/skill/liangdabiao/deepseek-v4-flash-vision-rag/?utm_source=github&utm_medium=awesome-list) |
| [aws-samples/bedrock-kb-rag-workshop](https://github.com/aws-samples/bedrock-kb-rag-workshop) | 66 | 用于检索增强生成（RAG）的 Bedrock 知识库和代理 | [SAFE](https://agentskillshub.top/skill/aws-samples/bedrock-kb-rag-workshop/?utm_source=github&utm_medium=awesome-list) |
| [shredEngineer/Archive-Agent](https://github.com/shredEngineer/Archive-Agent) | 64 | 用自然语言查找文件并提问。 | [SAFE](https://agentskillshub.top/skill/shredEngineer/Archive-Agent/?utm_source=github&utm_medium=awesome-list) |
| [RipeMangoBox/BITE](https://github.com/RipeMangoBox/BITE) | 60 | 半自动化研究助手和本地知识库，用于论文分析、构思、编码、实验、写作和发表流程。 | [SAFE](https://agentskillshub.top/skill/RipeMangoBox/BITE/?utm_source=github&utm_medium=awesome-list) |
| [AkiRusProd/llm-agent](https://github.com/AkiRusProd/llm-agent) | 55 | LLM using long-term memory through vector database | [SAFE](https://agentskillshub.top/skill/AkiRusProd/llm-agent/?utm_source=github&utm_medium=awesome-list) |

<a id="type-graph"></a>
## 🕸 知识图谱

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list#type-graph)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph) | 73.1k | 预索引代码知识图谱，代码变更自动同步，适用于 Claude Code 等，减少令牌和工具调用，本地运行 | [SAFE](https://agentskillshub.top/skill/colbymchenry/codegraph/?utm_source=github&utm_medium=awesome-list) |
| [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) | 40.0k | [EMNLP2025] LightRAG：检索增强生成 | [SAFE](https://agentskillshub.top/skill/HKUDS/LightRAG/?utm_source=github&utm_medium=awesome-list) |
| [topoteretes/cognee](https://github.com/topoteretes/cognee) | 31.3k | Cognee 是面向 agent 的开源 AI 记忆平台，用小模型为 AI agent 提供持久长期记忆 | [SAFE](https://agentskillshub.top/skill/topoteretes/cognee/?utm_source=github&utm_medium=awesome-list) |
| [xerrors/Yuxi](https://github.com/xerrors/Yuxi) | 7.3k | Yuxi：可私有部署的多租户知识智能体平台，支持 RAG、知识图谱、多智能体工作流、MCP/Skills、沙盒和权限管理。 | [SAFE](https://agentskillshub.top/skill/xerrors/Yuxi/?utm_source=github&utm_medium=awesome-list) |
| [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) | 5.2k | 面向 monorepo 的 RAG，借助 AI 和知识图谱查询、理解并编辑多语言代码库 | [SAFE](https://agentskillshub.top/skill/vitali87/code-graph-rag/?utm_source=github&utm_medium=awesome-list) |
| [FlowElement-ai/m_flow](https://github.com/FlowElement-ai/m_flow) | 4.5k | 仿生认知记忆引擎，用于 Graph RAG。 | [SAFE](https://agentskillshub.top/skill/FlowElement-ai/m_flow/?utm_source=github&utm_medium=awesome-list) |
| [FlowElement-xinliuyuansu/m_flow](https://github.com/FlowElement-xinliuyuansu/m_flow) | 4.5k | 仿生认知记忆引擎，面向 Graph RAG。 | [SAFE](https://agentskillshub.top/skill/FlowElement-xinliuyuansu/m_flow/?utm_source=github&utm_medium=awesome-list) |
| [pipeshub-ai/pipeshub-ai](https://github.com/pipeshub-ai/pipeshub-ai) | 3.8k | AI agents 的开源上下文层。PipesHub 将企业知识接入可按权限搜索、导航和引用的工作区，支持 MCP、SDKs、内置 agents，可自托管。 | [SAFE](https://agentskillshub.top/skill/pipeshub-ai/pipeshub-ai/?utm_source=github&utm_medium=awesome-list) |
| [Ontos-AI/knowhere](https://github.com/Ontos-AI/knowhere) | 3.6k | Knowhere提取、解析并输出适用于AI Agents和RAG的结构化片段。 | [SAFE](https://agentskillshub.top/skill/Ontos-AI/knowhere/?utm_source=github&utm_medium=awesome-list) |
| [sdyckjq-lab/llm-wiki-skill](https://github.com/sdyckjq-lab/llm-wiki-skill) | 2.5k | 基于 Karpathy llm-wiki 方法论的个人知识库构建 Skill，支持多平台 | [SAFE](https://agentskillshub.top/skill/sdyckjq-lab/llm-wiki-skill/?utm_source=github&utm_medium=awesome-list) |
| [mex-memory/mex](https://github.com/mex-memory/mex) | 1.8k | 工程师及其 AI agent 的团队记忆，存于仓库，通过 Git 共享。 | [SAFE](https://agentskillshub.top/skill/mex-memory/mex/?utm_source=github&utm_medium=awesome-list) |
| [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) | 1.3k | ApeRAG：支持多模态索引、AI agents、MCP 和可扩展 K8s 部署的 GraphRAG | [SAFE](https://agentskillshub.top/skill/apecloud/ApeRAG/?utm_source=github&utm_medium=awesome-list) |
| [yuezhiai/jonex](https://github.com/yuezhiai/jonex) | 1.3k | 多模态解析引擎与基于本体、LLM Wiki 驱动的 AI 知识引擎 | [SAFE](https://agentskillshub.top/skill/yuezhiai/jonex/?utm_source=github&utm_medium=awesome-list) |
| [Deodat-Lawson/LaunchStack](https://github.com/Deodat-Lawson/LaunchStack) | 890 | 基于 AI 的创业加速引擎，使用 Next.js、LangChain、PostgreSQL + pgvector 构建。支持上传、整理并与文档对话，提供缺失文… | [SAFE](https://agentskillshub.top/skill/Deodat-Lawson/LaunchStack/?utm_source=github&utm_medium=awesome-list) |
| [Jakedismo/codegraph-rust](https://github.com/Jakedismo/codegraph-rust) | 885 | 基于 Rust 的 code graphRAG，实现 AST+FastML 解析、surrealDB 后端及通过 MCP 提供代码分析工具，用于 code a… | [SAFE](https://agentskillshub.top/skill/Jakedismo/codegraph-rust/?utm_source=github&utm_medium=awesome-list) |
| [verygoodplugins/automem](https://github.com/verygoodplugins/automem) | 820 | AI 助手的长期记忆，通过图和向量存储跨会话记住决策、关系和上下文。 | [SAFE](https://agentskillshub.top/skill/verygoodplugins/automem/?utm_source=github&utm_medium=awesome-list) |
| [agentic-box/memora](https://github.com/agentic-box/memora) | 729 | 为 AI agents 提供持久共享记忆，支持去重吸收、替代谱系、语义搜索和图形界面，支持 MCP。 | [SAFE](https://agentskillshub.top/skill/agentic-box/memora/?utm_source=github&utm_medium=awesome-list) |
| [green-dalii/obsidian-llm-wiki](https://github.com/green-dalii/obsidian-llm-wiki) | 680 | Karpathy 的 LLM Wiki Obsidian 插件：将笔记和 PDF 转为关联知识库，支持实体页、概念页、图谱问答和本地隐私。 | [SAFE](https://agentskillshub.top/skill/green-dalii/obsidian-llm-wiki/?utm_source=github&utm_medium=awesome-list) |
| [benmaster82/Kwipu](https://github.com/benmaster82/Kwipu) | 607 | 本地 Graph RAG 查询 Markdown，支持 Obsidian；解析 wikilinks/YAML，使用混合检索；多语言，用 Ollama，无云端 | [SAFE](https://agentskillshub.top/skill/benmaster82/Kwipu/?utm_source=github&utm_medium=awesome-list) |
| [Beever-AI/beever-atlas](https://github.com/Beever-AI/beever-atlas) | 450 | LLM-Wiki 对话知识库 | [SAFE](https://agentskillshub.top/skill/Beever-AI/beever-atlas/?utm_source=github&utm_medium=awesome-list) |
| [awslabs/graphrag-toolkit](https://github.com/awslabs/graphrag-toolkit) | 445 | 用于构建图增强型生成式 AI 应用的 Python 工具包 | [SAFE](https://agentskillshub.top/skill/awslabs/graphrag-toolkit/?utm_source=github&utm_medium=awesome-list) |
| [zhuzhaoyun/Molio](https://github.com/zhuzhaoyun/Molio) | 431 | 面向 AI agents 的本地优先个人知识层。用 LLM Wiki、知识图谱和 agent 工作流构建持续演进的知识空间。 | [SAFE](https://agentskillshub.top/skill/zhuzhaoyun/Molio/?utm_source=github&utm_medium=awesome-list) |
| [aayoawoyemi/Ori-Mnemos](https://github.com/aayoawoyemi/Ori-Mnemos) | 328 | 由 Recursive Memory Harness（RMH）驱动的本地优先持久化 agent 记忆 | [SAFE](https://agentskillshub.top/skill/aayoawoyemi/Ori-Mnemos/?utm_source=github&utm_medium=awesome-list) |
| [Qingyon-AI/Revornix](https://github.com/Qingyon-AI/Revornix) | 292 | Revornix 是开源、本地优先的 AI 信息/Markdown 工作区，可收集零散输入，整理为结构化知识，生成图文报告和播客音频，并通过自动通知发送。 | [SAFE](https://agentskillshub.top/skill/Qingyon-AI/Revornix/?utm_source=github&utm_medium=awesome-list) |
| [HarimxChoi/google-surf-mcp](https://github.com/HarimxChoi/google-surf-mcp) | 291 | 将 Google Search、论文和代码库自动转为供 AI agent 使用的本地知识图谱。 | [SAFE](https://agentskillshub.top/skill/HarimxChoi/google-surf-mcp/?utm_source=github&utm_medium=awesome-list) |
| [Lyra-stellAI/BYO-LLM-WIKI](https://github.com/Lyra-stellAI/BYO-LLM-WIKI) | 280 | 构建 LLM 原生 WIKI 知识库：搜索、提取、摘要、RAG 问答、知识图谱、记忆与 skill 生成，经人工审核。 | [SAFE](https://agentskillshub.top/skill/Lyra-stellAI/BYO-LLM-WIKI/?utm_source=github&utm_medium=awesome-list) |
| [Lyra-stellAI/BYO-WIKI](https://github.com/Lyra-stellAI/BYO-WIKI) | 280 | WIKI：搜索提取总结、RAG问答、分层图谱、强化记忆；选定上下文生成skill，经Claude subagents、CodeAct pipeline和人工审… | [SAFE](https://agentskillshub.top/skill/Lyra-stellAI/BYO-WIKI/?utm_source=github&utm_medium=awesome-list) |
| [FreePeak/LeanKG](https://github.com/FreePeak/LeanKG) | 220 | LeanKG：停止浪费 tokens，开始编写 Lean 代码。 | [SAFE](https://agentskillshub.top/skill/FreePeak/LeanKG/?utm_source=github&utm_medium=awesome-list) |
| [EduardTalianu/erag](https://github.com/EduardTalianu/erag) | 213 | 支持 RAG 混合搜索、对话上下文、网页内容处理及基于 LLM/GPT 的结构化数据分析的 AI 交互工具 | [SAFE](https://agentskillshub.top/skill/EduardTalianu/erag/?utm_source=github&utm_medium=awesome-list) |
| [aouicher/graphmind](https://github.com/aouicher/graphmind) | 212 | 面向 AI 助手的本地优先代码智能，将代码库转为可查询、导航和记忆的知识图谱。25 个 MCP 工具。 | [SAFE](https://agentskillshub.top/skill/aouicher/graphmind/?utm_source=github&utm_medium=awesome-list) |
| [judegomila/OnCo](https://github.com/judegomila/OnCo) | 194 | OnCo：带引用的公共肿瘤学知识图谱，提供网站、JSON API、MCP server 和 CLI；每项各有一页。 | [SAFE](https://agentskillshub.top/skill/judegomila/OnCo/?utm_source=github&utm_medium=awesome-list) |
| [stevereiner/flexible-graphrag](https://github.com/stevereiner/flexible-graphrag) | 188 | 支持Python、LlamaIndex、LangChain、GraphRAG、RAG、MCP Server；14个数据源（10个自动同步）、知识图谱自动构建 | [SAFE](https://agentskillshub.top/skill/stevereiner/flexible-graphrag/?utm_source=github&utm_medium=awesome-list) |
| [Nazm-AI/open-hikmah](https://github.com/Nazm-AI/open-hikmah) | 173 | AI驱动的《古兰经》知识图谱：将经文置于画布上，探索主题、语言和神学关联。 | [SAFE](https://agentskillshub.top/skill/Nazm-AI/open-hikmah/?utm_source=github&utm_medium=awesome-list) |
| [serradura/okf](https://github.com/serradura/okf) | 172 | OKF：为 AI agent 提供本地持久化结构化记忆，通过 Skills、MCP、图谱、TUI、CLI、Docker 和 Claude Code plugi… | [SAFE](https://agentskillshub.top/skill/serradura/okf/?utm_source=github&utm_medium=awesome-list) |
| [Haaaiawd/Nexus-skills](https://github.com/Haaaiawd/Nexus-skills) | 165 | 面向 AI 编程助手的代码库分析 skill，生成 .nexus-map/ 知识库，查询文件结构、依赖图和变更影响。 | [SAFE](https://agentskillshub.top/skill/Haaaiawd/Nexus-skills/?utm_source=github&utm_medium=awesome-list) |
| [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) | 164 | 实现 Zettelkasten 知识管理方法的 MCP 服务器，可通过 Claude 等 MCP 客户端创建、链接、探索和综合原子笔记 | [SAFE](https://agentskillshub.top/skill/entanglr/zettelkasten-mcp/?utm_source=github&utm_medium=awesome-list) |
| [ArihantDeva/heimdall](https://github.com/ArihantDeva/heimdall) | 133 | 仅使用 CPU 的记忆方案，支持排序检索。 | [SAFE](https://agentskillshub.top/skill/ArihantDeva/heimdall/?utm_source=github&utm_medium=awesome-list) |
| [aaronsb/knowledge-graph-system](https://github.com/aaronsb/knowledge-graph-system) | 128 | Kappa Graph — κ(G)。带知识权重的语义知识图谱：提取概念、衡量依据强度、保留分歧，并追溯至来源。 | [SAFE](https://agentskillshub.top/skill/aaronsb/knowledge-graph-system/?utm_source=github&utm_medium=awesome-list) |
| [NimaChu/my-wiki](https://github.com/NimaChu/my-wiki) | 124 | 本地优先的 AI 知识应用与 Agent Skill，提供有证据支持的 Wiki、互动知识宇宙、Viki 问答和可分享的知识星系。 | [SAFE](https://agentskillshub.top/skill/NimaChu/my-wiki/?utm_source=github&utm_medium=awesome-list) |
| [SpillwaveSolutions/agent-brain](https://github.com/SpillwaveSolutions/agent-brain) | 119 | 本地优先的 AI agent RAG 记忆：混合与 GraphRAG 搜索，支持 OAuth 2.1 的 MCP server，适用于 Claude Code… | [SAFE](https://agentskillshub.top/skill/SpillwaveSolutions/agent-brain/?utm_source=github&utm_medium=awesome-list) |
| [HiAi-gg/docsmint](https://github.com/HiAi-gg/docsmint) | 118 | 面向人和 AI agent 的开源知识库，支持富文本编辑、混合搜索、GraphRAG 和 MCP。可用 Docker 自托管或使用 DocsMint Clou… | [SAFE](https://agentskillshub.top/skill/HiAi-gg/docsmint/?utm_source=github&utm_medium=awesome-list) |
| [dimknaf/braindb](https://github.com/dimknaf/braindb) | 110 | “LLM wiki”升级为真正的数据库：类型化实体、图关系、HTTP API 和内置自然语言 agent。 | [SAFE](https://agentskillshub.top/skill/dimknaf/braindb/?utm_source=github&utm_medium=awesome-list) |
| [mtrnix/metronix-memory](https://github.com/mtrnix/metronix-memory) | 106 | 自托管 AI agent 记忆——支持持久召回的 MCP 记忆服务器 | [SAFE](https://agentskillshub.top/skill/mtrnix/metronix-memory/?utm_source=github&utm_medium=awesome-list) |
| [iurykrieger/claude-bedrock](https://github.com/iurykrieger/claude-bedrock) | 103 | Obsidian 知识库第二大脑自动化：通过 Claude Code skills 管理实体、导入、压缩和同步 | [SAFE](https://agentskillshub.top/skill/iurykrieger/claude-bedrock/?utm_source=github&utm_medium=awesome-list) |
| [MarcoPorcellato/matryca-plumber](https://github.com/MarcoPorcellato/matryca-plumber) | 98 | Logseq OG 本地 AI 守护进程：语义索引、链接整理、agent CLI/MCP；编辑磁盘 Markdown，无云端、无 Logseq API。 | [SAFE](https://agentskillshub.top/skill/MarcoPorcellato/matryca-plumber/?utm_source=github&utm_medium=awesome-list) |
| [talirezun/the-curator](https://github.com/talirezun/the-curator) | 97 | 将文档整理成互联的 Markdown wiki，存于私有 GitHub 仓库，可在 Obsidian 阅读和共享。agents 可跨会话、模型和设备继续工作。 | [SAFE](https://agentskillshub.top/skill/talirezun/the-curator/?utm_source=github&utm_medium=awesome-list) |
| [trapoom555/claude-paperloom](https://github.com/trapoom555/claude-paperloom) | 96 | 用于 Claude Code + Obsidian 自维护研究知识图谱的插件 | [SAFE](https://agentskillshub.top/skill/trapoom555/claude-paperloom/?utm_source=github&utm_medium=awesome-list) |
| [HKUST-KnowComp/DeepRefine-Skill](https://github.com/HKUST-KnowComp/DeepRefine-Skill) | 92 | 用于在测试时提升 LLM-Wiki（Graphify）质量的 agent skill。 | [SAFE](https://agentskillshub.top/skill/HKUST-KnowComp/DeepRefine-Skill/?utm_source=github&utm_medium=awesome-list) |
| [The-AI-Alliance/semiont](https://github.com/The-AI-Alliance/semiont) | 92 | Semiont支持人与AI协作知识工作，可用作Wiki、知识库、上下文图、语义层或Agentic Memory。 | [SAFE](https://agentskillshub.top/skill/The-AI-Alliance/semiont/?utm_source=github&utm_medium=awesome-list) |
| [jshph/enzyme](https://github.com/jshph/enzyme) | 86 | Local-first compile step for knowledge bases. Save 350x cost, 1000x speed vs. frontier models | [SAFE](https://agentskillshub.top/skill/jshph/enzyme/?utm_source=github&utm_medium=awesome-list) |
| [useenzyme/enzyme](https://github.com/useenzyme/enzyme) | 86 | Local-first compile step for knowledge bases. Save 350x cost, 1000x speed vs. frontier models | [SAFE](https://agentskillshub.top/skill/useenzyme/enzyme/?utm_source=github&utm_medium=awesome-list) |
| [kangise/ecommerce-ai-skills](https://github.com/kangise/ecommerce-ai-skills) | 80 | 跨境电商AI知识库：69三语指南、878提示词、100实体/322约束本体、9个skill，Claude Code插件或MCP；事实标日期并CI验证，CC0。 | [SAFE](https://agentskillshub.top/skill/kangise/ecommerce-ai-skills/?utm_source=github&utm_medium=awesome-list) |
| [streamient/streamient](https://github.com/streamient/streamient) | 79 | 面向 AI 与人类的开源记忆基础设施，将分散知识转为适用于 Claude、Cursor、ChatGPT 和 MCP 客户端的上下文。 | [SAFE](https://agentskillshub.top/skill/streamient/streamient/?utm_source=github&utm_medium=awesome-list) |
| [SenolIsci/mykg](https://github.com/SenolIsci/mykg) | 75 | MyKG 知识图谱引擎：将原始文件转化为带归纳本体的知识图谱 | [SAFE](https://agentskillshub.top/skill/SenolIsci/mykg/?utm_source=github&utm_medium=awesome-list) |
| [cybaea/obsidian-vault-intelligence](https://github.com/cybaea/obsidian-vault-intelligence) | 66 | Obsidian 知识库智能 | [SAFE](https://agentskillshub.top/skill/cybaea/obsidian-vault-intelligence/?utm_source=github&utm_medium=awesome-list) |
| [MihaiBuilds/memory-vault](https://github.com/MihaiBuilds/memory-vault) | 65 | 本地优先的 AI 记忆系统，支持混合搜索、MCP 集成和知识图谱。 | [SAFE](https://agentskillshub.top/skill/MihaiBuilds/memory-vault/?utm_source=github&utm_medium=awesome-list) |
| [2015xli/clangd-graph-rag](https://github.com/2015xli/clangd-graph-rag) | 63 | 基于 clang/clangd 的 C/C++ 开发源码图 RAG（GraphRAG） | [SAFE](https://agentskillshub.top/skill/2015xli/clangd-graph-rag/?utm_source=github&utm_medium=awesome-list) |
| [ThreatRecall/zettelforge](https://github.com/ThreatRecall/zettelforge) | 63 | 用于 CTI 的 Python agent 记忆：STIX 知识图谱、威胁行为者别名解析、离线优先 RAG，以及面向 Claude Code 和 LangCh… | [SAFE](https://agentskillshub.top/skill/ThreatRecall/zettelforge/?utm_source=github&utm_medium=awesome-list) |
| [rolandpg/zettelforge](https://github.com/rolandpg/zettelforge) | 63 | Agentic memory for CTI in Python — STIX knowledge graphs, threat-actor alias resolution, offline-first RAG, MCP server for Claude Code and LangChain… | [SAFE](https://agentskillshub.top/skill/rolandpg/zettelforge/?utm_source=github&utm_medium=awesome-list) |
| [AndrewNgo-ini/memoose](https://github.com/AndrewNgo-ini/memoose) | 58 | A dual-path memory system for proactive agents. Facts and procedures in a local knowledge graph, exposed as a CLI, MCP tools and skills. No API key. | [SAFE](https://agentskillshub.top/skill/AndrewNgo-ini/memoose/?utm_source=github&utm_medium=awesome-list) |
| [ZengLiangYi/ChatCrystal](https://github.com/ZengLiangYi/ChatCrystal) | 58 | 本地优先的 AI 编程对话知识库：导入 Claude Code、Cursor、Codex，提炼笔记、语义搜索、标签图谱和 MCP memory。 | [SAFE](https://agentskillshub.top/skill/ZengLiangYi/ChatCrystal/?utm_source=github&utm_medium=awesome-list) |
| [iikarus/Dragon-Brain](https://github.com/iikarus/Dragon-Brain) | 51 | Dragon Brain — persistent long-term memory for AI agents via MCP (Model Context Protocol). Knowledge graph (FalkorDB) + vector search (Qdrant) + CUDA… | [SAFE](https://agentskillshub.top/skill/iikarus/Dragon-Brain/?utm_source=github&utm_medium=awesome-list) |
| [boykush/scraps](https://github.com/boykush/scraps) | 46 | The Wiki-link doc compiler for the LLM era. | [SAFE](https://agentskillshub.top/skill/boykush/scraps/?utm_source=github&utm_medium=awesome-list) |
| [mshtawythug/second-brain](https://github.com/mshtawythug/second-brain) | 14 | Local-first personal knowledge base CLI — hybrid FTS + pgvector search, a GraphRAG entity graph, and LLM enrichment over your notes, transcripts, Sla… | [SAFE](https://agentskillshub.top/skill/mshtawythug/second-brain/?utm_source=github&utm_medium=awesome-list) |

<a id="type-personal"></a>
## 🧠 个人知识库

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/knowledge-base/?utm_source=github&utm_medium=awesome-list#type-personal)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [tianma-if/edgeever](https://github.com/tianma-if/edgeever) | 2.0k | 开源 AI 原生知识库与 Evernote 替代品，原生支持 MCP，可部署于 Cloudflare 或 Docker。 | [SAFE](https://agentskillshub.top/skill/tianma-if/edgeever/?utm_source=github&utm_medium=awesome-list) |
| [rahilp/second-brain-cloudflare](https://github.com/rahilp/second-brain-cloudflare) | 800 | 一个记忆层，适用于所有 AI 工具。内容存一次，即可在 Claude、ChatGPT、Cursor 或任意 MCP 客户端中调用。支持部署在 Cloudfla… | [SAFE](https://agentskillshub.top/skill/rahilp/second-brain-cloudflare/?utm_source=github&utm_medium=awesome-list) |
| [smixs/agent-second-brain](https://github.com/smixs/agent-second-brain) | 390 | 可随时对话的第二大脑。Telegram语音笔记转为Obsidian中的文字和关联知识，使用现有Claude订阅全天运行。 | [SAFE](https://agentskillshub.top/skill/smixs/agent-second-brain/?utm_source=github&utm_medium=awesome-list) |
| [shenmintao/marginalia](https://github.com/shenmintao/marginalia) | 247 | 受图书馆学启发的个人知识管理系统，配备 LLM agents | [SAFE](https://agentskillshub.top/skill/shenmintao/marginalia/?utm_source=github&utm_medium=awesome-list) |
| [xingranya/GitHub-Stars-AI-Tools](https://github.com/xingranya/GitHub-Stars-AI-Tools) | 110 | 本地优先的 AI 桌面应用，用于同步、摘要、标记、搜索和发现 GitHub Stars 项目。 | [SAFE](https://agentskillshub.top/skill/xingranya/GitHub-Stars-AI-Tools/?utm_source=github&utm_medium=awesome-list) |
| [The-Flash-7/open-note](https://github.com/The-Flash-7/open-note) | 58 | 一款跨平台智能笔记 Agent 应用，支持多格式笔记、本地知识库、AI 智能助手、向量语义检索 。 | [SAFE](https://agentskillshub.top/skill/The-Flash-7/open-note/?utm_source=github&utm_medium=awesome-list) |

**安全评级**是 Agent Skills Hub 对仓库 README 和安装步骤的评级。*待评级*表示目录还没评到它。

预览图是各项目 README 里图片的缩小副本,只收录采用宽松许可证的项目,版权归原作者所有。来源和许可证见 [assets/previews/NOTICE.md](assets/previews/NOTICE.md)。如需移除请提 issue。

## 相关合集

- [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills), [zhuyansen/awesome-codex-ppt-skills](https://github.com/zhuyansen/awesome-codex-ppt-skills) —— 同样做法的合集。

## 推荐仓库

提一个 issue 附上 GitHub 链接。它会走和每个条目一样的评审;决定上不上榜的是上面的规则,不是星数。

---

机器可读版本:[`data/skills.json`](data/skills.json)。生成于 2026-10-04。
