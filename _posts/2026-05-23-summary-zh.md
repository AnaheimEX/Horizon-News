---
layout: default
title: "Horizon Summary: 2026-05-23 (ZH)"
date: 2026-05-23
lang: zh
---

> From 48 items, 20 important content pieces were selected

---

1. [苹果开源 corecrypto 密码库，附形式化验证量子安全算法](#item-1) ⭐️ 9.0/10
2. [Anthropic 更新 Project Glasswing，漏洞检测准确率极高](#item-2) ⭐️ 8.0/10
3. [数十年睡眠研究催生新睡眠呼吸暂停药物](#item-3) ⭐️ 8.0/10
4. [微软取消 Claude Code 许可，力推 Copilot CLI](#item-4) ⭐️ 8.0/10
5. [承包商在 GitHub 上泄露秘密，CISA 数据泄露](#item-5) ⭐️ 8.0/10
6. [Antigravity 2.0 在 OpenSCAD LLM 建筑 3D 模型基准测试中夺冠](#item-6) ⭐️ 8.0/10
7. [AI 需求导致内存短缺，消费电子涨价](#item-7) ⭐️ 8.0/10
8. [Datasette Agent：数据查询的 AI 助手](#item-8) ⭐️ 8.0/10
9. [字节跳动开源 3B 统一多模态模型 Lance](#item-9) ⭐️ 8.0/10
10. [腾讯收购喜马拉雅获批，附带放弃独家版权条件](#item-10) ⭐️ 8.0/10
11. [中国八部门整治非法跨境证券，立案调查老虎、富途](#item-11) ⭐️ 8.0/10
12. [Cloudflare 全球故障 25 分钟，影响 28% HTTP 流量](#item-12) ⭐️ 8.0/10
13. [将笔记本电脑运往乌干达难民营的官僚磨难](#item-13) ⭐️ 7.0/10
14. [日本公司为何如此多元化](#item-14) ⭐️ 7.0/10
15. [Deno 2.8 发布，新增 pack 命令，权限模型引发讨论](#item-15) ⭐️ 7.0/10
16. [Kanbots：开源看板应用，每张卡片并行运行 AI 代理](#item-16) ⭐️ 7.0/10
17. [FBI 局长的服装网站遭遇 ClickFix 恶意软件攻击](#item-17) ⭐️ 7.0/10
18. [FTC 对 Cox Media Group 虚假 AI 监听广告罚款近 100 万美元](#item-18) ⭐️ 7.0/10
19. [智谱发布 GLM-5.1 高速版，输出速度达 400 tokens/s](#item-19) ⭐️ 7.0/10
20. [微软内部大规模推广 Claude Code，鼓励非技术员工使用](#item-20) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [苹果开源 corecrypto 密码库，附形式化验证量子安全算法](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

苹果已开源其 corecrypto 密码库，其中包含后量子算法 ML-KEM 和 ML-DSA 的实现，并附有形式化验证证明，确保 C 代码和 ARM64 汇编与 NIST 标准一致。 这对密码学领域来说是一个重大进步，因为它在数十亿台设备上提供了经过数学验证的量子安全算法实现，为行业软件保障设立了新标准。 形式化验证使用了苹果自研的验证工具和 Isabelle 理论库，源代码已在 GitHub 上发布。corecrypto 为超过 25 亿台活跃设备提供基础加密运算。

telegram · zaihuapd · May 23, 04:49

**背景**: ML-KEM（基于模块格的密钥封装机制）和 ML-DSA（基于模块格的数字签名算法）是 NIST 在 2024 年选定的后量子密码标准，旨在抵抗未来量子计算机的攻击。形式化验证使用数学证明来确保软件实现严格遵循预期规范，从而消除整类漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ML-KEM">ML-KEM</a></li>
<li><a href="https://en.wikipedia.org/wiki/ML-DSA">ML-DSA</a></li>

</ul>
</details>

**标签**: `#post-quantum cryptography`, `#formal verification`, `#apple`, `#cryptography`, `#open source`

---

<a id="item-2"></a>
## [Anthropic 更新 Project Glasswing，漏洞检测准确率极高](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 8.0/10

Anthropic 发布了 Project Glasswing 的初步更新，报告其 AI 模型在代码漏洞检测中达到了 90.6% 的真阳性率（针对高危或严重漏洞），且由独立安全公司验证。 这有望显著提升软件漏洞的自动检测能力，特别是能捕获静态分析工具遗漏的关键问题，并改变安全团队将 AI 集成到工作流程中的方式。 在经评估的 1,752 个高危或严重漏洞中，90.6%（1,587 个）为真阳性，62.4%（1,094 个）被确认为高危或严重等级；该模型是 Claude Mythos，隶属于 Anthropic 的网络安全倡议。

hackernews · louiereederson · May 22, 19:31 · [社区讨论](https://news.ycombinator.com/item?id=48240419)

**背景**: Project Glasswing 是 Anthropic 于 2026 年 4 月发起的全行业网络安全倡议，旨在利用先进 AI 保护关键软件。Claude Mythos 是 Anthropic 训练的前沿模型，专用于代码分析。传统静态分析工具能捕获常见漏洞，但常遗漏复杂逻辑问题，导致生产代码存在潜在安全缺陷。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Glasswing">Project Glasswing</a></li>
<li><a href="https://grokipedia.com/page/Project_Glasswing">Project Glasswing</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 评论反应不一：用户 mdeeks 称赞该工具的准确性和集成度，而 curl 维护者 Daniel Steinberg 表示怀疑，称未看到超越现有工具的显著证据。其他评论讨论了其与传统 lint 工具的成本收益，指出许多团队甚至未使用基本静态分析。

**标签**: `#AI`, `#cybersecurity`, `#vulnerability detection`, `#code analysis`, `#Anthropic`

---

<a id="item-3"></a>
## [数十年睡眠研究催生新睡眠呼吸暂停药物](https://temertymedicine.utoronto.ca/news/how-decades-sleep-research-led-new-sleep-apnea-drug) ⭐️ 8.0/10

研究人员基于数十年的睡眠研究，开发出一种新型睡眠呼吸暂停药物，可能成为 CPAP 疗法的替代方案。该药物作用于特定神经回路，在睡眠期间维持气道肌肉张力。 睡眠呼吸暂停影响着全球数百万人，而当前标准治疗 CPAP 的长期依从性较低。药物疗法有望显著改善患者预后和生活质量。 该药物每小时仅减少 4 次呼吸暂停事件，可能对轻度睡眠呼吸暂停最有效，而非中重度病例。它是通过绘制控制气道肌肉的神经回路而发现的。

hackernews · colinprince · May 22, 22:05 · [社区讨论](https://news.ycombinator.com/item?id=48242278)

**背景**: 睡眠呼吸暂停是一种睡眠期间呼吸反复停止和开始的状况，通常由气道塌陷引起。CPAP 呼吸机通过加压空气保持气道通畅，但许多患者觉得不舒服。一种能激活气道肌肉的药物可能提供更简便的治疗。

**社区讨论**: 社区评论显示反应不一：一些用户分享 CPAP 个人经历和技巧，而另一些用户质疑药物有效性，指出它每小时仅减少 4 次事件，可能只对轻度病例有帮助。还有关于姿势矫正等替代疗法的讨论。

**标签**: `#sleep apnea`, `#drug discovery`, `#medical research`, `#health`, `#CPAP`

---

<a id="item-4"></a>
## [微软取消 Claude Code 许可，力推 Copilot CLI](https://www.theverge.com/tech/930447/microsoft-claude-code-discontinued-notepad) ⭐️ 8.0/10

微软已开始取消其为开发者提供的 Claude Code 许可，自 2026 年 6 月 30 日起生效，引导他们转向自家的 GitHub Copilot CLI 工具。 此举标志着微软战略性地放弃第三方 AI 编码工具，可能重塑开发者的工具选择，并引发关于 AI 自主工具与人机协作模式经济性的讨论。 据报道，2025 年 12 月启动的 Claude Code 试点在短时间内消耗了微软 2026 年全年的 AI 预算，导致取消。GitHub Copilot CLI 是一个命令行代理，可处理问题、拉取请求以及并行化子代理。

hackernews · robertkarl · May 22, 17:32 · [社区讨论](https://news.ycombinator.com/item?id=48238896)

**背景**: Claude Code 是 Anthropic 开发的 AI 编码助手，运行在终端中，帮助开发者生成代码、修复 bug 和自动化任务。GitHub Copilot CLI 是微软的竞争性命令行工具，与 GitHub 工作流集成。微软的决定反映了平台供应商倾向于自家 AI 工具而非第三方替代品的行业趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/overview">Overview - Claude Code Docs</a></li>
<li><a href="https://github.com/features/copilot/cli/">GitHub Copilot CLI</a></li>
<li><a href="https://developer.microsoft.com/blog/get-started-with-github-copilot-cli-a-free-hands-on-course">Get started with GitHub Copilot CLI: A free, hands-on course</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出 Claude Code 的令牌消耗高昂，有用户称试点在一周内用完了月度配额，而 DeepSeek 则经济得多。另一用户质疑用昂贵的 AI 工具替代开发者薪酬的经济性，还有评论透露该试点消耗了微软 2026 年全年的 AI 支出目标。

**标签**: `#Microsoft`, `#Claude Code`, `#Copilot CLI`, `#AI coding tools`, `#token economy`

---

<a id="item-5"></a>
## [承包商在 GitHub 上泄露秘密，CISA 数据泄露](https://krebsonsecurity.com/2026/05/lawmakers-demand-answers-as-cisa-tries-to-contain-data-leak/) ⭐️ 8.0/10

一名与 CISA 合作的承包商意外地将敏感数据暴露，原因是使用了 GitHub 仓库作为工作草稿本，导致数据泄露。立法者要求给出解释，CISA 正在努力控制泄露范围。 这一事件凸显了政府网络安全中持续存在的风险，尤其是当人为错误绕过技术控制时。它可能削弱公众对 CISA 保护自身数据能力的信任，并促使采取更严格的安全措施。 泄露涉及存储在 GitHub 仓库中的秘密信息，该仓库用于同步工作。CISA 声称没有敏感数据被泄露，但社区成员根据泄露信息的性质对这一说法提出质疑。

hackernews · speckx · May 22, 16:54 · [社区讨论](https://news.ycombinator.com/item?id=48238429)

**背景**: CISA（网络安全和基础设施安全局）是美国负责保护关键基础设施的政府机构。Git 仓库通常用于代码版本控制，但在其中存储秘密是众所周知的安全风险。承包商通常有权访问敏感系统，因此他们的安全实践至关重要。

**社区讨论**: 评论表达了对 CISA 保证的怀疑，一位用户回忆起之前 SF-86 表格的泄露。另一位用户质疑为什么基本的 Git 安全实践被忽视。一些人在讨论问题到底是技术性的还是人为的，一条评论引用了一种观点，即技术控制无法完全防止此类人为错误。

**标签**: `#cybersecurity`, `#data breach`, `#CISA`, `#government`, `#GitHub`

---

<a id="item-6"></a>
## [Antigravity 2.0 在 OpenSCAD LLM 建筑 3D 模型基准测试中夺冠](https://modelrift.com/blog/openscad-llm-benchmark/) ⭐️ 8.0/10

一项新的基准测试——OpenSCAD LLM 基准测试，测试 AI 模型生成万神殿 OpenSCAD 代码的能力；Google 的 Antigravity 2.0 代理获得最高分，甚至实现了室内天花板细节。 该基准测试为参数化 3D 建模中的 LLM 引入了一种新颖的、视觉驱动的评估方式，凸显了 AI 辅助建筑设计以及便捷 3D 打印工作流的潜力。 Antigravity 2.0 是唯一一个实现了通过穹顶眼可见的万神殿标志性室内方形藻井的自主代理。该基准测试评估了六个模型，包括 Gemini、Claude 和 GPT-4，依据其对参考图像的遵循程度。

hackernews · jetter · May 22, 10:38 · [社区讨论](https://news.ycombinator.com/item?id=48234090)

**背景**: OpenSCAD 是一种仅通过脚本进行 3D CAD 建模的软件，使用自己的描述语言来定义几何体元和操作。该基准测试要求 LLM 根据复杂建筑结构的图像生成 OpenSCAD 代码，同时测试代码生成和空间推理能力。Antigravity 2.0 是 Google 在 IO 2026 上发布的最新代理式编码工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenSCAD">OpenSCAD</a></li>
<li><a href="https://modelrift.com/blog/openscad-llm-benchmark/">OpenSCAD LLM Benchmark: Building the Pantheon | ModelRift Blog</a></li>
<li><a href="https://techcrunch.com/2026/05/19/google-launches-antigravity-2-0-with-an-updated-desktop-app-and-cli-tool/">Google launches Antigravity 2.0 with an updated desktop app and CLI tool at IO 2026 | TechCrunch</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了不同的经历：有人称赞 Claude 从照片中生成了可用的 OpenSCAD 部件，另有人批评 Antigravity 的部署问题，每次使用都需要浏览器登录。一些人对该基准测试的单模型测试方法提出了质疑，指出在他们自己的测试中，Gemini 模型表现最平稳。

**标签**: `#OpenSCAD`, `#LLM`, `#benchmark`, `#3D modeling`, `#AI agent`

---

<a id="item-7"></a>
## [AI 需求导致内存短缺，消费电子涨价](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

人工智能对 HBM 内存的需求正将晶圆产能从 DDR/LPDDR 重新分配给 HBM，HBM 的份额预计从 2%上升到 2026 年的 20%，导致智能手机等消费电子产品价格上涨。 这种结构性转变将推高消费电子产品价格，尤其影响非洲和南亚等市场的廉价设备；内存短缺预计至少持续到 2030 年。 每 GB HBM 消耗的晶圆产能是 DDR 或 LPDDR 的三倍以上，且内存制造商吸取过去竞争对手破产的教训，刻意控制产能以避免过剩。

rss · Simon Willison · May 22, 22:01

**背景**: 内存制造商拥有固定的晶圆产能，需分配给 DDR（台式机/服务器）、LPDDR（移动/低功耗）和 HBM（用于 GPU 的高带宽内存）。HBM 通过堆叠多个 DRAM 芯片实现更高带宽，对 AI 工作负载至关重要。AI 数据中心的快速增长大幅提高了 HBM 需求，挤压了其他内存类型的供应，从而推高消费电子成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HBM_memory_shortage">HBM memory shortage</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**标签**: `#memory shortage`, `#HBM`, `#AI`, `#consumer electronics`, `#supply chain`

---

<a id="item-8"></a>
## [Datasette Agent：数据查询的 AI 助手](https://simonwillison.net/2026/May/21/datasette-agent/#atom-everything) ⭐️ 8.0/10

Simon Willison 宣布了 Datasette Agent 的首个版本，这是一个 AI 助手，为存储在 Datasette 中的数据提供对话式查询界面，并可通过 datasette-agent-charts 插件生成图表。 此版本通过将 LLM 能力直接集成到 Datasette 中，使用户无需编写 SQL 即可用自然语言提问并生成可视化，降低了数据探索的门槛，具有重要意义。 Datasette Agent 可通过插件扩展；演示实例 agent.datasette.io 使用廉价且快速的 Gemini 3.1 Flash-Lite。已发布的插件包括 datasette-agent-charts（基于 Observable Plot）和 datasette-agent-openai-imagegen（基于 ChatGPT 图像生成）。

rss · Simon Willison · May 21, 19:52

**背景**: Datasette 是一个基于 SQLite 的开源多功能工具，用于探索和发布数据。LLM 是一个用于与大型语言模型交互的 Python 库和命令行工具。Datasette Agent 将这两个项目结合在一起，提供了一个对话界面，根据用户提示自动编写并执行 SQL 查询。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2026/May/21/datasette-agent/">Datasette Agent - simonwillison.net</a></li>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and ...</a></li>
<li><a href="https://github.com/datasette/datasette-agent-charts">GitHub - datasette/datasette-agent-charts: Observable Plot ...</a></li>

</ul>
</details>

**标签**: `#Datasette`, `#AI`, `#data analysis`, `#LLM`, `#open source`

---

<a id="item-9"></a>
## [字节跳动开源 3B 统一多模态模型 Lance](https://mp.weixin.qq.com/s/Xbfq72cr1796RZxJIs3L1A) ⭐️ 8.0/10

字节跳动开源了激活参数量仅 3B 的多模态模型 Lance，该模型统一了图像和视频的理解与生成任务，采用 Apache 2.0 许可，权重已在 Hugging Face 开放。 Lance 展示了仅 3B 参数的模型就能在理解和生成任务上取得领先结果，有望降低多模态 AI 研究和应用的门槛。 Lance 采用双流专家架构（Dual-Stream MoE），分别由 Qwen2.5-VL 处理理解、Wan2.2 处理生成，并引入模态感知位置编码解决序列边界混淆。它在 GenEval 和 VBench 基准上取得领先成绩。

telegram · zaihuapd · May 22, 06:40

**背景**: 同时处理理解和生成任务的多模态模型常面临能力冲突问题。双流架构将不同任务的处理路径分离，而模态感知位置编码确保了对混合图像、视频和文本序列的正确编码。GenEval 和 VBench 是评估文本到图像及视频生成质量的常用基准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.agentren.cn/2026/0522/15846.shtml">字节跳动开源Lance 3B：实现图像与视频理解与生成_A³·爱力方</a></li>
<li><a href="https://kexue.fm/archives/10352">“闭门造车”之多模态思路浅谈（三）：位置编码 - 科学空间|Scientific Spaces</a></li>
<li><a href="https://arxiv.org/abs/2310.11513">[2310.11513] GenEval: An Object-Focused Framework for ... GenEval: A Benchmark Suite for Evaluating Generative Models GenEval Benchmark | showlab/DIM | DeepWiki GenEval Benchmark Overview - emergentmind.com GenEval Benchmark Table GenEval — Image generation benchmark · Codesota | CodeSOTA</a></li>

</ul>
</details>

**标签**: `#multimodal`, `#AI`, `#open source`, `#image generation`, `#video generation`

---

<a id="item-10"></a>
## [腾讯收购喜马拉雅获批，附带放弃独家版权条件](https://mp.weixin.qq.com/s/xnx31SOS6NMozZXnHeaaQg) ⭐️ 8.0/10

国家市场监管总局批准了腾讯对音频平台喜马拉雅的收购，但要求腾讯放弃在线音频版权独家授权，并在限期内解除现有独家合同。 这一决定打破了喜马拉雅的独家内容壁垒，可能为其他音频平台创造更公平的竞争环境，并方便用户跨平台收听内容。 腾讯必须承诺未来不再达成或变相达成在线音频版权独家授权，并逐步解除现有独家合同，但可以继续寻求非独家合作。

telegram · zaihuapd · May 22, 10:33

**背景**: 喜马拉雅是中国领先的音频分享平台，提供播客、有声书和音频直播。独家版权曾是平台吸引用户的关键竞争策略，但监管机构日益针对此类行为以促进竞争和消费者选择。

**标签**: `#tencent`, `#regulation`, `#audio`, `#competition`, `#china`

---

<a id="item-11"></a>
## [中国八部门整治非法跨境证券，立案调查老虎、富途](https://t.me/zaihuapd/41525) ⭐️ 8.0/10

中国八部门联合印发整治方案，打击非法跨境证券、期货和基金经营，要求存量投资者在 2 年清理期内仅能单向卖出并转出资金。证监会已对老虎证券、富途证券和长桥证券的跨境违规展业立案调查。 这一监管行动严重冲击跨境金融科技平台，限制了内地投资者投资海外市场的渠道，同时引导其通过港股通、QDII 和跨境理财通等合法途径投资。这表明中国正加强资本外流管控和金融安全。 方案设定了 2 年集中整治期，期间存量投资者仅能单向卖出并转出资金，期满后相关境内网站、交易软件和配套服务器必须全面关停。证监会已对老虎、富途和长桥发出行政处罚事先告知，拟没收全部违法所得并处以严厉罚款。

telegram · zaihuapd · May 22, 13:55

**背景**: 中国投资者长期通过老虎证券、富途等境外券商买卖港股和美股，绕开了中国的资本管制。合法境外投资渠道包括港股通（允许交易港股）、QDII（合格境内机构投资者）基金，以及粤港澳大湾区居民的跨境理财通。此次整治旨在引导投资者转向这些受监管的渠道。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/665528722">一文搞懂港股通开通条件及交易规则 - 知乎</a></li>
<li><a href="https://grokipedia.com/page/qualified_domestic_institutional_investor">Qualified Domestic Institutional Investor</a></li>
<li><a href="https://research.hktdc.com/tc/article/MTYyOTc5OTI0Ng">新版「 跨 境 理 財 通 」啓動 | 香港貿易發展局經貿研究</a></li>

</ul>
</details>

**标签**: `#regulation`, `#fintech`, `#cross-border investment`, `#China`, `#securities`

---

<a id="item-12"></a>
## [Cloudflare 全球故障 25 分钟，影响 28% HTTP 流量](https://t.me/zaihuapd/41527) ⭐️ 8.0/10

2025 年 12 月 5 日，Cloudflare 发生全球性故障，持续 25 分钟（UTC 时间 08:47 至 09:12），影响约 28%的 HTTP 流量；起因是为修复 Next.js 安全漏洞（CVE-2025-55182）而部署的 WAF 更新存在缺陷。 此次故障凸显了关键互联网基础设施在部署安全补丁时若测试不足的脆弱性，影响了依赖 Cloudflare CDN 和安全服务的数百万用户和企业。 仅使用 Cloudflare 旧版 FL1 代理且启用了 Cloudflare 托管规则集的客户受到影响，收到 HTTP 500 错误；根本原因是应用在 execute-action 规则上的 killswitch 触发了 Lua 空指针缺陷。

telegram · zaihuapd · May 22, 16:15

**背景**: Cloudflare 的 FL1 代理是其旧一代反向代理基础设施，而托管规则集提供了由 Cloudflare 安全团队维护的预配置 WAF 规则。此次故障发生在为了修复 Next.js 漏洞（CVE-2025-55182）进行配置更改时，暴露了 WAF 规则引擎中的 Lua 空指针缺陷，导致请求失败。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.cloudflare.com/5-december-2025-outage/">Cloudflare outage on December 5, 2025</a></li>
<li><a href="https://www.ascii.co.uk/news/article/news-20251208-71fe2ccb/cloudflare-25-minute-outage-lua-nil-bug-in-waf-rules-engine">Cloudflare 25-Minute Outage: Lua Nil Bug in WAF Rules Engine</a></li>
<li><a href="https://convergedigest.com/cloudflare-outage-on-december-5-hits-28-of-global-http-traffic/">Cloudflare Outage on December 5 Hits 28% of Global HTTP ...</a></li>

</ul>
</details>

**标签**: `#Cloudflare`, `#outage`, `#WAF`, `#security`, `#Next.js`

---

<a id="item-13"></a>
## [将笔记本电脑运往乌干达难民营的官僚磨难](https://notesbylex.com/shipping-a-laptop-to-a-refugee-camp-in-uganda) ⭐️ 7.0/10

作者讲述了将笔记本电脑运往乌干达难民营时遇到的复杂官僚主义和腐败问题，包括意外税收、贿赂和物流障碍。 这个故事揭示了向欠发达地区提供技术援助时面临的系统性障碍，展示了腐败和低效率如何阻碍发展并增加善意努力的成本。 作者最初以为标准运输可行，但面临进口税、仓储费和贿赂的要求，最终需要一位名为 Django 的当地联系人帮忙应对系统。

hackernews · lexandstuff · May 22, 21:36 · [社区讨论](https://news.ycombinator.com/item?id=48241997)

**背景**: 国际运输电子产品通常涉及海关申报和税收，但在许多发展中国家，额外的官僚层级和腐败很常见。作者的经历说明了西方物流期望与乌干达等国实际情况之间的脱节。

**社区讨论**: 评论者指出了系统性腐败，赞扬了 Django 的韧性，并提出了如随身携带物品等替代方案。一位乌干达评论者承认系统存在问题，但批评了作者认为西方方法可行的傲慢。

**标签**: `#developing countries`, `#logistics`, `#bureaucracy`, `#corruption`, `#tech for good`

---

<a id="item-14"></a>
## [日本公司为何如此多元化](https://davidoks.blog/p/why-japanese-companies-do-so-many) ⭐️ 7.0/10

这篇文章解释了日本公司广泛多元化的原因，包括终身雇佣制、公司特有技能，以及优先考虑员工利益而非股东利益的公司治理。 它从文化和结构角度解释了日本企业战略的独特特征，并与西方注重股东价值和专业化的模式形成对比。 作者认为，这种体系只有在公司不受外部压力影响的情况下才有效，从而使公司可以为员工而非股东而存在。

hackernews · d0ks · May 22, 15:22 · [社区讨论](https://news.ycombinator.com/item?id=48237163)

**背景**: 日本的终身雇佣制（终身雇用）是一种员工期望在一家公司工作到退休、公司大力投资于公司特有技能的体系。这鼓励了多元化，作为保留和重新调配员工到不同业务领域的一种方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jobs.guidable.co/en/articles/what-is-the-current-state-of-japans-lifetime-employment-system">What Is the Current State of Japan ’s Lifetime | Guidable Jobs</a></li>
<li><a href="https://www.zenterninternships.com/blog/how-japanese-companies-handle-skill-development">How Japanese Companies Handle Skill Development</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，西方公司过去也曾多元化，而且日本体系导致了低就业流动性，使中期职业招聘变得困难。一些东亚读者提醒不要浪漫化这种模式。

**标签**: `#business-culture`, `#organizational-structure`, `#japan`, `#corporate-strategy`, `#management`

---

<a id="item-15"></a>
## [Deno 2.8 发布，新增 pack 命令，权限模型引发讨论](https://deno.com/blog/v2.8) ⭐️ 7.0/10

Deno 2.8 新增了 `deno pack` 命令用于打包应用，并对性能和权限模型进行了增量改进。该版本继续强调安全性和原生 TypeScript 支持。 此版本引发了社区关于 Deno 独特权限模型与 Node.js 生态便利性及 Bun 速度之间的持续讨论。这种比较凸显了 JavaScript 运行时格局的演变，其中安全性、性能和开发者体验是关键差异点。 `deno pack` 命令简化了 Deno 项目的打包过程，无需外部工具。权限模型保持细粒度，但未扩展至模块级控制，这是部分用户希望改进之处。

hackernews · roflcopter69 · May 22, 11:23 · [社区讨论](https://news.ycombinator.com/item?id=48234380)

**背景**: Deno 是一个基于 V8 和 Rust 的 JavaScript/TypeScript 运行时，旨在解决 Node.js 在安全性和模块管理方面的不足。其权限模型要求用户明确授权文件、网络和环境访问，增强了安全性但有时增加了使用复杂度。Bun 是一个较新的运行时，注重速度和一体化工具链，而 Node.js 仍是业界标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.deno.com/runtime/fundamentals/security/">Security and permissions - Deno</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区对 Deno 的安全性和理念总体上持正面态度，但用户质疑其相对于 Bun 和 Node 的生态系统发展。一些用户称赞 `deno pack` 的加入，另一些人则对资金可持续性和功能对等性表示担忧。

**标签**: `#Deno`, `#JavaScript runtime`, `#TypeScript`, `#permission model`, `#Node.js`

---

<a id="item-16"></a>
## [Kanbots：开源看板应用，每张卡片并行运行 AI 代理](https://www.kanbots.dev/) ⭐️ 7.0/10

Kanbots 是一款新推出的开源桌面看板应用，允许用户在每张任务卡片上并行派遣 AI 代理，每个代理在自己的 Git 工作树中运行，并支持自动驾驶模式，代理自动拆分并执行工作。 该工具通过将 AI 代理直接集成到看板工作流中，突破了项目管理的边界，可能实现大规模任务并行化。但它也引发了关于是否违反看板核心原则（如限制在制品和尊重流动）的争论。 Kanbots 采用本地优先、无服务器架构，所有数据（SQLite、配置、工作树）存储在仓库旁的 .kanbots/ 目录中，无需云账户或遥测。每个代理在隔离的工作树中运行，自动驾驶功能使用角色自动拆分和审查工作。

hackernews · vitriapp · May 22, 18:17 · [社区讨论](https://news.ycombinator.com/item?id=48239413)

**背景**: 看板是一种敏捷项目管理方法，通过可视化工作流程、限制在制品（WIP）并专注于持续交付来管理卡片流动，避免系统过载。而这款新工具通过鼓励在大量卡片上并行执行，对这一传统理念提出了挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kanbots.dev/">KanBots — a kanban that runs parallel agents</a></li>
<li><a href="https://topaihubs.com/articles/the-rise-of-parallel-ai-agents-in-open-source-kanban-a-new-era-for-productivity">The Rise of Parallel AI Agents in Open Source Kanban: A New ...</a></li>
<li><a href="https://teamhood.com/kanban-resources/kanban-principles/">4 Kanban Principles & 6 Practices for Better Workflows - Teamhood What is Kanban - Principles and Implementation - GeeksforGeeks Kanban Principles: The 4 Core Principles & 6 Key Practices 6 Core Kanban principles — and How to Apply Them - Miro Core Principles of Kanban: A Complete Guide for Agile Teams Kanban Principles & Practices: Guide to Agile Workflow</a></li>

</ul>
</details>

**社区讨论**: 社区成员反应不一：有人批评该工具鼓励并行工作，与看板核心理念相悖；也有人担心审查 AI 生成的代码和管理隔离工作树的可操作性。还有人与 Vibe Kanban 进行比较，后者曾因维护停滞而出现问题。

**标签**: `#kanban`, `#AI agents`, `#open-source`, `#project management`

---

<a id="item-17"></a>
## [FBI 局长的服装网站遭遇 ClickFix 恶意软件攻击](https://www.pcmag.com/news/kash-patels-apparel-site-is-trying-to-trick-visitors-into-installing-malware) ⭐️ 7.0/10

FBI 局长的服装网站 BasedApparel.com 被黑客入侵，利用 ClickFix 攻击诱骗访问者下载恶意软件。 此事件凸显了 ClickFix 攻击在现实中的普遍性，并表明即使是知名网站也可能被入侵，给访问者带来严重的安全风险。 该 ClickFix 攻击专门针对 macOS 用户，通过显示虚假的‘验证您是真人’提示，点击后会下载恶意负载。

hackernews · bilalq · May 23, 00:34 · [社区讨论](https://news.ycombinator.com/item?id=48243293)

**背景**: ClickFix 攻击是一种社会工程学技术，攻击者诱骗用户运行系统命令以解决一个并不存在的问题。本例中，虚假的 CAPTCHA 提示欺骗访客执行命令来下载恶意软件。微软等安全公司已报告此类攻击日益增多。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/security/blog/2025/08/21/think-before-you-clickfix-analyzing-the-clickfix-social-engineering-technique/">Think before you Click ( Fix ): Analyzing the ClickFix social engineering...</a></li>
<li><a href="https://hoxhunt.com/blog/what-is-a-clickfix-attack">What Is a ClickFix Attack ? What Security Teams Need to... - Hoxhunt</a></li>

</ul>
</details>

**社区讨论**: 社区评论对此表示惊讶和幽默，有人质疑 FBI 局长为何开服装店。一位用户澄清该商店是 Kash Patel 在担任局长之前拥有的，攻击目标是 macOS 用户。

**标签**: `#security`, `#malware`, `#phishing`, `#FBI`, `#ClickFix`

---

<a id="item-18"></a>
## [FTC 对 Cox Media Group 虚假 AI 监听广告罚款近 100 万美元](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 7.0/10

美国联邦贸易委员会（FTC）责令 Cox Media Group、MindSift 和 1010 Digital Works 支付近 100 万美元，原因是他们虚假声称其“主动聆听”AI 服务能够通过智能设备实时监听对话来投放定向广告。 这一和解标志着针对欺骗性 AI 营销的重大执法行动，强化了公司不能误导消费者关于侵入性监控能力而不受处罚的立场。 FTC 透露，该服务从未实际监听对话；相反，这些公司以高额加价转售从数据经纪人处获取的电子邮件列表。FTC 还警告称，将选择同意隐藏在服务条款中并不构成充分同意。

rss · Simon Willison · May 22, 04:48

**背景**: 多年来，一直有阴谋论称智能手机和智能音箱秘密监听对话以进行广告定向。Cox Media Group 在 2024 年关于“主动聆听”的营销材料助长了这些担忧，声称使用语音数据进行超精准广告投放。FTC 的调查揭穿了其技术可行性，并揭露这些声明是欺诈性的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wired.com/story/creepy-listening-tool-for-targeted-ads-didnt-actually-work-ftc-says/">‘Creepy’ Listening Tool for Targeted Ads Didn’t Actually Work ...</a></li>
<li><a href="https://thecyberexpress.com/ftc-ai-powered-active-listening-case/">AI-Powered Marketing Service “Active Listening” Deceived ...</a></li>
<li><a href="https://cipaworld.com/2026/05/21/ftc-to-require-cox-media-group-two-other-firms-to-pay-nearly-1-million-to-settle-charges-they-deceived-customers-about-active-listening-ai-powered-marketing-service/">FTC Settles with Marketing Firms for Deceptive AI Advertising</a></li>

</ul>
</details>

**标签**: `#AI`, `#privacy`, `#FTC`, `#advertising`, `#deception`

---

<a id="item-19"></a>
## [智谱发布 GLM-5.1 高速版，输出速度达 400 tokens/s](https://docs.bigmodel.cn/cn/guide/models/text/glm-5.1-highspeed) ⭐️ 7.0/10

智谱 AI 发布了 GLM-5.1-HighSpeed 高速版本，输出速度达到每秒 400 tokens，目前已通过 BigModel 开放平台面向部分企业客户开放。 这一显著的速度提升使实时应用如编程代理、语音助手和实时客服成为可能，将 GLM-5.1-HighSpeed 定位为企业市场中低延迟 AI 任务的竞争选择。 该模型支持函数调用（Function Call）、JSON 结构化输出以及模型上下文协议（MCP），非常适合多轮代码生成、实时 UI 构建和运营问答等低延迟场景；但访问仅限于企业客户。

telegram · zaihuapd · May 22, 04:45

**背景**: GLM-5.1 是智谱 AI（中国领先的人工智能公司之一）开发的大语言模型。函数调用（Function Calling）允许模型调用外部 API 或函数以执行文本生成之外的任务。MCP（模型上下文协议）是一种标准化协议，简化了与外部工具和数据源的集成，类似于 AI 模型的通用适配器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://www.getfrontline.ai/glossary/what-is-function-calling">Frontline | Glossary | Function Calling</a></li>
<li><a href="https://gradientflow.com/expanding-ai-horizons-the-rise-of-function-calling-in-llms/">Expanding AI Horizons: The Rise of Function Calling ... - Gradient Flow</a></li>

</ul>
</details>

**标签**: `#GLM`, `#AI model`, `#low-latency`, `#enterprise`, `#function call`

---

<a id="item-20"></a>
## [微软内部大规模推广 Claude Code，鼓励非技术员工使用](https://t.me/zaihuapd/41535) ⭐️ 7.0/10

微软正在其核心工程团队中广泛推广 Anthropic 的 Claude Code，包括 CoreAI 团队以及负责 Windows、Microsoft 365 和 Outlook 的体验与设备部门。公司要求软件工程师同时使用 Claude Code 和 GitHub Copilot 并提供对比反馈，同时鼓励没有编程经验的员工使用 Claude Code 进行原型设计。 这一举动标志着微软 AI 编程策略的重大转变，在某些场景下接受竞争对手的工具而非自家的 GitHub Copilot。这可能会重塑 AI 辅助开发的格局，并影响其他企业针对不同用户群体采用多种 AI 编程助手的方式。 推广范围不仅包括经验丰富的工程师，还包括非技术员工进行原型设计。微软工程师现在需要提供直接反馈，对比 Anthropic 的 Claude Code 和微软的 GitHub Copilot 这两个竞争的 AI 编程工具。

telegram · zaihuapd · May 23, 06:05

**背景**: Claude Code 是 Anthropic（Claude 大型语言模型背后的公司）开发的 AI 编程代理。GitHub Copilot 是微软自己的 AI 编程助手，集成在其开发生态中。通过在内部测试两种工具，微软旨在评估它们的相对优势，并可能改进自己的产品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**标签**: `#微软`, `#Claude Code`, `#AI编程`, `#GitHub Copilot`, `#行业动态`

---