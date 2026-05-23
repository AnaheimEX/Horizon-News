---
layout: default
title: "Horizon Summary: 2026-05-23 (ZH)"
date: 2026-05-23
lang: zh
---

> From 37 items, 11 important content pieces were selected

---

1. [Anthropic Glasswing 更新：AI 漏洞验证准确率 90.6%](#item-1) ⭐️ 9.0/10
2. [字节跳动开源 Lance：3B 参数统一多模态模型](#item-2) ⭐️ 9.0/10
3. [苹果开源 corecrypto，形式化验证量子安全算法](#item-3) ⭐️ 9.0/10
4. [Antigravity 2.0 在 OpenSCAD 建筑 3D LLM 基准测试中夺冠](#item-4) ⭐️ 8.0/10
5. [yt-dlp 弃用 Bun 支持，指兼容性与安全问题](#item-5) ⭐️ 8.0/10
6. [安娜的档案馆要求 LLMs 为其数据使用捐款](#item-6) ⭐️ 8.0/10
7. [DeepSeek 永久降低 V4 Pro 价格至四分之一](#item-7) ⭐️ 8.0/10
8. [AI 内存需求推高消费电子产品价格](#item-8) ⭐️ 8.0/10
9. [FTC 因虚假 AI 监听服务对 Cox Media Group 罚款 93 万美元](#item-9) ⭐️ 8.0/10
10. [中国八部门整治非法跨境证券，立案调查老虎、富途、长桥](#item-10) ⭐️ 8.0/10
11. [微软内部推广 Claude Code，与 Copilot 对标](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Anthropic Glasswing 更新：AI 漏洞验证准确率 90.6%](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 9.0/10

Anthropic 发布了 Project Glasswing 的初步更新，报告称由独立安全公司评估的 1752 个高危或严重漏洞中，90.6% 被确认为真实阳性，其中 62.4% 被认定高危或严重。 这表明 AI 驱动的漏洞检测在实际代码库中可以达到高准确率，有望改变关键基础设施和大型软件项目的自动化安全审计方式。 90.6% 的真实阳性率和 62.4% 的高/严重严重性确认基于六家安全研究公司的独立评估。该更新仅涵盖迄今报告的高严重性漏洞候选。

hackernews · louiereederson · May 22, 19:31 · [社区讨论](https://news.ycombinator.com/item?id=48240419)

**背景**: Project Glasswing 是 Anthropic 的一项倡议，利用其 AI 助手 Claude 分析关键开源项目的源代码以寻找安全漏洞。传统的静态分析工具能发现常见缺陷，但往往遗漏复杂的逻辑错误或难以检测的漏洞。该更新提供了 AI 补充现有安全工作流程有效性的早期证据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/glasswing-initial-update">Project Glasswing: An initial update - Anthropic</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing: Securing critical software for the AI era - Anthropic</a></li>
<li><a href="https://www.anthropic.com/project/glasswing">Project Glasswing - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 评论褒贬不一：一些用户分享了类似工具实现约 90% 准确率的积极经验，而其他人（包括 curl 维护者 Daniel Stenberg）对该工具相比现有静态分析器的改进表示怀疑。此外，一些人质疑团队是否应先采用更便宜的静态分析，再投资昂贵的基于 LLM 的工具。

**标签**: `#AI safety`, `#cybersecurity`, `#code analysis`, `#Anthropic`

---

<a id="item-2"></a>
## [字节跳动开源 Lance：3B 参数统一多模态模型](https://mp.weixin.qq.com/s/Xbfq72cr1796RZxJIs3L1A) ⭐️ 9.0/10

字节跳动开源了 Lance，一个仅 3B 激活参数的统一多模态模型，能够同时处理图像理解、视频理解、图像生成、视频生成和跨模态编辑。 Lance 仅用 3B 参数就在 GenEval 和 VBench 等基准上取得了领先结果，表明高效统一的多模态模型是可行的，并可能减少对更大、资源密集型模型的依赖。 Lance 采用从 Qwen2.5-VL 初始化的双流混合专家架构，并使用模态感知位置编码解决序列边界混淆。该模型以 Apache 2.0 许可发布在 Hugging Face 上。

telegram · zaihuapd · May 22, 06:40

**背景**: 多模态 AI 模型通常需要单独的模型来处理理解（如描述）和生成（如图像合成）任务，导致流程碎片化。Lance 通过共享上下文和专用专家路径将这两类任务统一到一个模型中，实现了联合学习和高效推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.18678">Lance: Unified Multimodal Modeling by Multi-Task Synergy</a></li>
<li><a href="https://www.marktechpost.com/2026/05/21/one-model-three-modalities-bytedance-releases-lance-for-image-and-video-understanding-generation-and-editing/">One Model, Three Modalities: ByteDance Releases Lance for ...</a></li>
<li><a href="https://www.mlhive.com/2026/05/bytedance-lance-unified-multimodal-architecture">Why ByteDance Lance is the Next Evolution in Multimodal AI</a></li>

</ul>
</details>

**标签**: `#multimodal`, `#open-source`, `#image-generation`, `#video-generation`, `#ByteDance`

---

<a id="item-3"></a>
## [苹果开源 corecrypto，形式化验证量子安全算法](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

5 月 22 日，苹果开源了 corecrypto 密码库，其中包括量子安全算法 ML-KEM 和 ML-DSA 的实现，并附带了端到端的形式化验证证明，从数学上保证了其正确性。 这标志着大规模部署后量子密码学的重要一步：形式化验证确保实现与 NIST 标准精确匹配，为依赖 corecrypto 进行安全通信的数十亿苹果设备提供了高水平的保证。 形式化验证涵盖了 C 实现和手工优化的 ARM64 汇编代码，与 NIST 的 ML-KEM（FIPS 203）和 ML-DSA（FIPS 204）标准保持一致。苹果还发布了定制验证工具和 Isabelle 理论库，供独立专家评估。

telegram · zaihuapd · May 23, 04:49

**背景**: ML-KEM（基于模格的关键封装机制）和 ML-DSA（基于模格的数字签名算法）是 NIST 于 2024 年标准化的后量子密码算法，旨在抵御未来量子计算机的攻击。形式化验证通过数学证明（通常借助 Isabelle 等定理证明器）来确保代码完全符合其规范，从而消除整类错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ML-KEM">ML-KEM - Wikipedia</a></li>
<li><a href="https://www.nist.gov/news-events/news/2024/08/nist-releases-first-3-finalized-post-quantum-encryption-standards">NIST Releases First 3 Finalized Post-Quantum Encryption ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isabelle_(proof_assistant)">Isabelle (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#cryptography`, `#formal verification`, `#quantum-safe`, `#Apple`, `#open source`

---

<a id="item-4"></a>
## [Antigravity 2.0 在 OpenSCAD 建筑 3D LLM 基准测试中夺冠](https://modelrift.com/blog/openscad-llm-benchmark/) ⭐️ 8.0/10

一项针对 LLM 生成的 OpenSCAD 建筑模型的新基准测试公布，谷歌的 Antigravity 2.0 智能体夺得第一，它生成的万神殿模型包括通过圆顶可见的内部天花藻井图案，令人印象深刻。 该基准测试为 AI 代码生成在 3D 建模领域的评估引入了新方法，凸显了 LLM 创建复杂建筑几何体的潜力。Antigravity 2.0 实现的内部细节展现了向自主 3D 设计迈出的重要一步。 该基准测试仅以万神殿作为单个测试用例，每个模型只有一次尝试机会，部分评论者认为不足以泛化。Antigravity 2.0 是唯一实现了万神殿标志性内部天花图案的自主智能体。

hackernews · jetter · May 22, 10:38 · [社区讨论](https://news.ycombinator.com/item?id=48234090)

**背景**: OpenSCAD 是一款免费的、基于脚本的 3D CAD 软件，使用自己的编程语言定义几何形状，这使得 LLM 能够以代码形式生成 3D 模型。该基准测试评估 AI 智能体在 OpenSCAD 中生成准确建筑模型的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenSCAD">OpenSCAD</a></li>
<li><a href="https://antigravity.google/blog/introducing-google-antigravity-2-0">Google Antigravity Blog: introducing-google- antigravity - 2 - 0</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户对内部细节表示印象深刻，而另一些人则批评 Antigravity 强制替换 Gemini CLI 以及 IDE 更新问题。还有评论者质疑基准测试的设计，指出单个测试用例和一次尝试并不能提供有力证据。

**标签**: `#LLM`, `#OpenSCAD`, `#3D modeling`, `#benchmark`, `#AI code generation`

---

<a id="item-5"></a>
## [yt-dlp 弃用 Bun 支持，指兼容性与安全问题](https://github.com/yt-dlp/yt-dlp/issues/16766) ⭐️ 8.0/10

yt-dlp 已弃用对 Bun JavaScript 运行时的支持，理由是可预见的兼容性和安全问题。此决定源于 Bun 正从 Zig 重写为 Rust 所带来的不确定性。 此次弃用影响那些依赖 yt-dlp 与 Bun 配合使用的用户，可能迫使他们转向 Node.js 或 Deno。这也突显了开源社区在运行时选择上的紧张局势，以及企业收购（Anthropic 收购 Bun）对项目方向的影响。 弃用在 GitHub issue #16766 中宣布，已有超过 450 条评论。yt-dlp 维护者未提供具体技术细节，但提及与 Bun 的 Rust 重写相关的安全问题。该重写尚未发布，导致部分社区成员质疑该决定的工程基础。

hackernews · tamnd · May 22, 17:24 · [社区讨论](https://news.ycombinator.com/item?id=48238789)

**背景**: yt-dlp 是一个流行的开源 YouTube 下载工具。Bun 是一个快速、全功能的 JavaScript 运行时，最初用 Zig 编写，旨在直接替代 Node.js。近期，Bun 背后的公司 Oven-sh 被 Anthropic 收购，并宣布将 Baz 重写为 Rust，引发了关于代码库可维护性和安全性的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>

</ul>
</details>

**社区讨论**: 社区意见分歧。部分用户支持该决定，认为与快速变化的运行时保持兼容不可持续。另一些用户如 johnfn 则认为此举更多是政治而非技术层面的，因为 Rust 重写尚未发布。用户 hootz 对 Anthropic 收购后 Bun 的发展方向表示遗憾。

**标签**: `#yt-dlp`, `#Bun`, `#runtime`, `#deprecation`, `#Rust rewrite`

---

<a id="item-6"></a>
## [安娜的档案馆要求 LLMs 为其数据使用捐款](https://annas-archive.gl/blog/llms-txt.html) ⭐️ 8.0/10

安娜的档案馆发布了一篇博客文章，以幽默的方式向 LLMs 喊话，要求它们为使用其受版权保护的数据捐款，凸显了 AI 训练数据获取中的伦理和法律问题。 这篇文章重新点燃了关于 AI 训练数据伦理、版权侵权以及影子图书馆角色的讨论，可能影响 AI 公司的数据获取实践和开放知识运动。 博客文章虽以幽默方式呈现，但传递了严肃信息，指出 LLMs 很可能使用了安娜的档案馆的数据进行训练。安娜的档案馆曾因被指控向 AI 公司收取费用以提供盗版材料的快速访问而受到批评。

hackernews · janandonly · May 22, 11:28 · [社区讨论](https://news.ycombinator.com/item?id=48234413)

**背景**: 影子图书馆是未经授权的在线存储库，提供通常需要付费的书籍和学术论文的免费副本。安娜的档案馆是一个元搜索引擎，聚合了 Z-Library、Sci-Hub 和 Library Genesis 等来源的记录，于 2022 年 Z-Library 被取缔后推出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anna's_Archive">Anna's Archive - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Shadow_library">Shadow library - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论反应不一：一些人觉得这一请求有趣并支持安娜的档案馆帮助学生，而另一些人则批评其向 AI 公司出售访问权限，突显了自由知识与伦理考量之间的张力。

**标签**: `#AI training data`, `#copyright`, `#piracy`, `#data ethics`, `#LLM`

---

<a id="item-7"></a>
## [DeepSeek 永久降低 V4 Pro 价格至四分之一](https://api-docs.deepseek.com/quick_start/pricing) ⭐️ 8.0/10

DeepSeek 已将 V4 Pro 模型的 API 定价永久降至原价的四分之一，使之前的 75%折扣在 2026 年 5 月 31 日后成为固定价格。 这一激进的定价策略可能扰乱 AI API 市场，使高性能模型对开发者和小公司更加可及，同时迫使竞争对手降低价格。 降价适用于 2026 年 5 月 31 日促销结束后的 V4 Pro 模型；此外，输入缓存命中价格已降至 V4 Pro 输入价格的 0.8%，为缓存请求提供了极低的成本。

hackernews · Tiberium · May 22, 15:59 · [社区讨论](https://news.ycombinator.com/item?id=48237663)

**背景**: DeepSeek 是一家以开源模型和发表研究著称的中国 AI 研究公司。其 V4 Pro 是一个大型语言模型，与 OpenAI、Google 等公司的产品竞争。API 定价通常按 token 计费，缓存折扣奖励重复使用相同提示的用户。

**社区讨论**: 评论者对这一价值表示兴奋，许多人注意到模型的高质量和低价格。但也有人对隐私表示担忧，因为 DeepSeek 的政策允许使用用户数据进行训练，并对低价缓存背后的单位经济效益提出质疑。

**标签**: `#DeepSeek`, `#AI pricing`, `#API`, `#large language models`, `#machine learning`

---

<a id="item-8"></a>
## [AI 内存需求推高消费电子产品价格](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

内存制造商正在将晶圆产能从 DDR 和 LPDDR 重新分配给 HBM 以满足 AI 需求，导致消费设备供应减少并推高价格。这一转变已开始影响 100 美元以下的智能手机市场。 消费电子产品，尤其是低成本智能手机，将在未来几年大幅涨价，影响发展中地区的可负担性。这也凸显了 AI 基础设施投资如何间接给无关市场带来压力。 目前仅有三家 DRAM 晶圆制造商，HBM 每吉字节消耗的晶圆产能是 DDR 或 LPDDR 的三倍以上。预计到 2026 年底，HBM 的晶圆分配比例将从 2%上升至 20%。

rss · Simon Willison · May 22, 22:01

**背景**: DRAM 主要分为三种类型：用于台式机/服务器的 DDR、用于移动/低功耗设备的 LPDDR，以及用于 AI GPU 的 HBM（高带宽内存）。HBM 采用 3D 堆叠和硅通孔（TSV）技术提供高带宽，但每吉字节所需晶圆面积显著更大。内存制造商严格控制产能以避免供应过剩，因此增加产能的速度很慢。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://octopart.com/pulse/p/what-allocation-semiconductor-industry">What Is Allocation in the Semiconductor Industry? - Octopart</a></li>
<li><a href="https://uomolab.com/en/hbm-memory-technology-deep-dive-the-memory-revolution-in-the-ai-era/">HBM Memory Technology Deep Dive: The Memory Revolution in the ...</a></li>

</ul>
</details>

**标签**: `#memory`, `#hardware`, `#AI`, `#semiconductors`, `#consumer electronics`

---

<a id="item-9"></a>
## [FTC 因虚假 AI 监听服务对 Cox Media Group 罚款 93 万美元](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 8.0/10

FTC 与 Cox Media Group、MindSift 和 1010 Digital Works 达成总计 93 万美元的和解协议，原因是它们虚假宣传一款名为“Active Listening”的 AI 驱动广告服务，声称通过智能设备监听消费者，但实际上只是转售电子邮件列表。 此次执法表明 FTC 正在积极监管涉及隐私侵扰技术的虚假 AI 营销宣传，为 AI 驱动广告的问责制和消费者保护树立了先例。 这些公司的“Active Listening”服务实际上并未监听对话或使用语音数据，而是以高额加价转售其他数据经纪商的电子邮件列表。FTC 还明确表示，强制性的服务协议条款并不构成对此类侵入性数据收集的充分同意。

rss · Simon Willison · May 22, 04:48

**背景**: “Active Listening”概念被营销为一种利用 AI 从智能设备麦克风捕获实时意图数据以投放广告的服务。这助长了长期存在的阴谋论——手机一直在监听以投放广告。FTC 的行动驳斥了这一谣言，并强调此类做法需要明确的主动同意。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thecyberexpress.com/ftc-ai-powered-active-listening-case/">AI-Powered Marketing Service “Active Listening” Deceived ...</a></li>
<li><a href="https://cipaworld.com/2026/05/21/ftc-to-require-cox-media-group-two-other-firms-to-pay-nearly-1-million-to-settle-charges-they-deceived-customers-about-active-listening-ai-powered-marketing-service/">FTC Settles with Marketing Firms for Deceptive AI Advertising</a></li>

</ul>
</details>

**标签**: `#AI`, `#privacy`, `#FTC`, `#regulation`, `#ethics`

---

<a id="item-10"></a>
## [中国八部门整治非法跨境证券，立案调查老虎、富途、长桥](https://mp.weixin.qq.com/s?__biz=MzA4NzAzMDgwMw==&amp;mid=2651090403&amp;idx=3&amp;sn=bca72a940ac72bef356f29b5b9576ac1&amp;chksm=8a1670281e2bc67d2df3608a313ba9fdaf0fcd2f43ce44475c6bf273b386af2e4f9d8e8e2e2b&amp;scene=0&amp;xtrack=1) ⭐️ 8.0/10

中国八部门联合印发整治方案，打击非法跨境证券、期货和基金经营活动，只允许存量投资者单向卖出并转出资金。证监会已对老虎证券、富途证券和长桥证券的非法跨境展业行为立案调查。 此次监管行动针对为内地居民提供跨境投资服务的主要金融科技平台，影响数百万用户。它标志着资本管制执法趋严，旨在引导境外投资通过港股通、QDII 等合法渠道进行。 方案设定了 2 年集中整治期清理存量业务，期满后相关境内网站、交易软件和配套服务器需全面关停。证监会已对老虎、富途、长桥境内外主体作出行政处罚事先告知，拟没收全部违法所得并严厉处罚，因其未经许可从事证券经纪、融资融券等业务。

telegram · zaihuapd · May 22, 08:26

**背景**: 未经许可的境外平台从事跨境证券交易在中国一直处于灰色地带，因为中国实行资本管制限制对外投资。内地投资者合法投资海外市场的渠道包括港股通（股票）和合格境内机构投资者（QDII）机制。被针对的平台如老虎证券和富途证券，通过其热门应用允许中国用户交易美股和港股，但缺少在中国的必要监管批准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://baike.baidu.com/item/港股通/13611865">港股通（内地与香港股票市场交易互联互通机制）_百度百科 港股通交易规则全解：从时间、机制到费用，一文看懂实操要点 沪港通 - 上海证券交易所 港股通是什么?开通条件与流程全解析 (2025 最新版)|内地股市|融资融券... 港股通开户指南：条件、线上流程与费用全解析（2025版） 科普：什么是港股通？ “ 港股通 ”是沪深港通机制的重要组成部分，它为...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Qualified_Domestic_Institutional_Investor">Qualified Domestic Institutional Investor - Wikipedia</a></li>

</ul>
</details>

**标签**: `#regulation`, `#fintech`, `#cross-border investing`, `#China`, `#securities`

---

<a id="item-11"></a>
## [微软内部推广 Claude Code，与 Copilot 对标](https://t.me/zaihuapd/41535) ⭐️ 8.0/10

微软正在其核心工程团队（包括 CoreAI 和体验与设备部门）广泛部署 Anthropic 的 Claude Code，并鼓励没有编程经验的员工使用它进行原型设计。工程师被要求同时使用 Claude Code 和 GitHub Copilot 并提供对比反馈。 此举标志着微软 AI 战略的重大转变——它在内部采用竞争对手的编程工具与自家 Copilot 并列，验证了 Claude Code 的能力。同时也凸显了 AI 辅助软件开发向非技术用户普及的广泛趋势。 微软软件工程师现在必须同时使用 Claude Code 和 GitHub Copilot，并提供对比反馈，尽管微软向客户销售 Copilot。Claude Code 是一个智能代理编程工具，能读取代码库、编辑文件、运行命令并交付已提交的代码，即使没有工程背景的人也能使用。

telegram · zaihuapd · May 23, 06:05

**背景**: Claude Code 是由 Anthropic 公司开发的 AI 编程工具，Anthropic 是 Claude 系列大语言模型的开发商。与传统代码助手不同，Claude Code 作为智能代理，能理解整个代码库、跨文件修改并运行测试。GitHub Copilot 是微软自家的 AI 结对编程工具，基于 OpenAI 的模型。微软决定内部测试竞品，体现了评估最佳 AI 工具的务实态度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://www.anthropic.com/product/claude-code">Claude Code | Anthropic's agentic coding system</a></li>

</ul>
</details>

**标签**: `#AI coding`, `#Microsoft`, `#Claude Code`, `#GitHub Copilot`, `#industry trends`

---