---
layout: default
title: "Horizon Summary: 2026-05-23 (ZH)"
date: 2026-05-23
lang: zh
---

> From 42 items, 20 important content pieces were selected

---

1. [从芯片照片拆解 80386 微码](#item-1) ⭐️ 9.0/10
2. [AI 在 Glasswing 项目中找出逾万高危漏洞](#item-2) ⭐️ 9.0/10
3. [苹果开源 corecrypto 并提供量子安全算法形式化验证](#item-3) ⭐️ 9.0/10
4. [向乌干达寄送笔记本电脑：腐败与教训](#item-4) ⭐️ 8.0/10
5. [日本企业多元化：终身雇佣与员工治理](#item-5) ⭐️ 8.0/10
6. [微软取消 Claude Code 许可，力推 Copilot CLI](#item-6) ⭐️ 8.0/10
7. [AI 对 HBM 的需求挤压消费级内存，推高价格](#item-7) ⭐️ 8.0/10
8. [FTC 对 Cox Media Group 虚假“主动监听”AI 服务罚款近百万美元](#item-8) ⭐️ 8.0/10
9. [Datasette Agent: LLM 驱动的数据探索 AI 助手](#item-9) ⭐️ 8.0/10
10. [腾讯收购喜马拉雅获批，附加放弃独家版权条件](#item-10) ⭐️ 8.0/10
11. [中国八部门整治非法跨境证券经营](#item-11) ⭐️ 8.0/10
12. [Cloudflare 故障影响 28% HTTP 流量，持续 25 分钟](#item-12) ⭐️ 8.0/10
13. [微软内部推广 Claude Code，鼓励非技术员工使用](#item-13) ⭐️ 8.0/10
14. [微软披露 OpenAI 单季亏损 115 亿美元](#item-14) ⭐️ 8.0/10
15. [BambuStudio 被指控违反 PrusaSlicer 的 AGPL 许可证](#item-15) ⭐️ 7.0/10
16. [李彦宏：AI 大模型已近应用爆发点](#item-16) ⭐️ 7.0/10
17. [海盗船采用长鑫存储 DRAM，DDR5 价格有望下调](#item-17) ⭐️ 7.0/10
18. [我国日均词元调用量两年增超千倍，2025 年 3 月突破 140 万亿](#item-18) ⭐️ 7.0/10
19. [深入探讨 HTML <dl>元素的语义](#item-19) ⭐️ 6.0/10
20. [Rubish：用纯 Ruby 编写的 Unix shell](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [从芯片照片拆解 80386 微码](https://www.reenigne.org/blog/80386-microcode-disassembled/) ⭐️ 9.0/10

一位逆向工程师通过高分辨率芯片照片成功拆解了 Intel 80386 处理器的微码，揭示了其内部控制逻辑和微指令。 这项逆向工程为最具影响力的 x86 处理器之一的微架构提供了罕见的详细洞察，对计算机体系结构研究和复古计算爱好者有益。 拆解过程包括从晶体管级图像中识别微码 ROM 布局和解码微指令格式，对于这款 32 位处理器的内部状态机来说是一项复杂的任务。

hackernews · nand2mario · May 23, 12:11 · [社区讨论](https://news.ycombinator.com/item?id=48247004)

**背景**: 微码是 CPU 中实现高级机器指令的底层指令层。Intel 80386 于 1985 年发布，是标志性的 32 位处理器，奠定了 x86 架构。芯片摄影使逆向工程师能够检查晶体管的物理布局，并重构存储在 ROM 中的微码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microcode">Microcode - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Intel_Microcode">Intel microcode - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区对这项技术的难度和成果表示赞赏。一些用户询问从芯片图像提取微码的过程，而另一些用户分享了微编程书籍和 nand2tetris 课程等教育资源。

**标签**: `#reverse engineering`, `#microcode`, `#x86`, `#computer architecture`, `#Intel 80386`

---

<a id="item-2"></a>
## [AI 在 Glasswing 项目中找出逾万高危漏洞](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 9.0/10

Anthropic 公布了 Project Glasswing 的初期成果，其 Claude Mythos Preview 模型与 50 多个合作伙伴合作，在一个月内从关键软件中发现了超过 1 万个高危或严重漏洞，漏洞发现速率相比传统方法提高了十倍以上。 这一突破将瓶颈从漏洞发现转移到了验证、披露和修补上，暴露了关键的人力缺口。随着 AI 驱动的漏洞检测越来越普及，软件行业必须缩短补丁周期，以应对快速增加的风险。 AI 扫描了数千个开源项目，识别出 6202 个高危漏洞，其中 1752 个经过审查，真阳性率为 90.6%。包括 Cloudflare 在内的合作伙伴报告漏洞发现速度提高了十倍。然而，开源维护者请求放慢报告速度，因为验证和修补工作负担过重。

telegram · zaihuapd · May 23, 03:16

**背景**: Project Glasswing 是 Anthropic 的一项防御性网络安全计划，利用名为 Claude Mythos Preview 的新型前沿模型，该模型在代码分析和漏洞发现方面展现出卓越能力。传统的漏洞发现依赖人工审计或静态分析工具，常常遗漏细微或复杂的漏洞。像 Claude Mythos 这样的 AI 模型能够大规模分析代码，发现人类专家可能忽视的漏洞，有可能改变安全领域格局。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>
<li><a href="https://red.anthropic.com/2026/mythos-preview/">Claude Mythos Preview \ red.anthropic.com</a></li>

</ul>
</details>

**标签**: `#AI安全`, `#漏洞发现`, `#网络安全`, `#Anthropic`

---

<a id="item-3"></a>
## [苹果开源 corecrypto 并提供量子安全算法形式化验证](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

5 月 22 日，苹果开源了 corecrypto 密码库，其中包含 ML-KEM 和 ML-DSA 算法的实现，并附有端到端的形式化验证证明，确保 C 代码和 ARM64 汇编代码与 NIST 标准严格一致。 这是后量子密码学的重要一步，因为 corecrypto 为超过 25 亿台 Apple 设备提供基础加密运算，而形式化验证为量子安全实现的正确性提供了前所未有的保证，可能影响行业采用类似的验证实践。 苹果还公开了验证工具和 Isabelle 理论库，供独立专家评估。已验证的算法包括 ML-KEM（密钥封装机制）和 ML-DSA（数字签名算法），两者均于 2024 年由 NIST 标准化。

telegram · zaihuapd · May 23, 04:49

**背景**: 量子计算机对当前公钥密码学构成威胁，因为 RSA 和 ECC 等算法可能被 Shor 算法破解。为此，NIST 标准化了后量子算法：用于密钥交换的 ML-KEM（FIPS 203）和用于数字签名的 ML-DSA（FIPS 204），两者均基于格密码。形式化验证使用 Isabelle 等定理证明器从数学上证明代码符合其规范，提供比传统测试更强的保证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ML-KEM">ML-KEM - Wikipedia</a></li>
<li><a href="https://www.digicert.com/insights/post-quantum-cryptography/mldsa">ML-DSA | Post-Quantum Cryptography | DigiCert Insights</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isabelle_(proof_assistant)">Isabelle (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#密码学`, `#形式化验证`, `#量子安全`, `#苹果`, `#开源`

---

<a id="item-4"></a>
## [向乌干达寄送笔记本电脑：腐败与教训](https://notesbylex.com/shipping-a-laptop-to-a-refugee-camp-in-uganda) ⭐️ 8.0/10

作者讲述了在尝试向乌干达的一个难民营寄送笔记本电脑时遭遇的极端困难和系统性腐败，包括高昂的税费和官僚障碍。 这个故事揭示了阻碍向发展中地区运送援助和个人物品的破碎物流和腐败问题，影响了人道主义努力和个人。 作者尝试了 DHL 和乌干达邮政等多个承运商，遭遇索贿，最终通过一个被称为“灰色市场”经纪人的本地货运代理成功寄送。

hackernews · lexandstuff · May 22, 21:36 · [社区讨论](https://news.ycombinator.com/item?id=48241997)

**背景**: 由于高额进口关税、腐败和不可靠的邮政系统，向许多非洲国家寄送电子产品是出了名的困难。许多外籍人士和当地人依赖非正式的货运代理，这些代理利用航空旅客的行李额度运输货物，绕过官方渠道。

**社区讨论**: 评论者大多同意作者的评估，许多乌干达人证实了系统性腐败的存在。他们建议使用灰色市场货运代理或在旅行时亲自携带物品，并批评作者最初假设西方运输方法会有效的想法。

**标签**: `#logistics`, `#Uganda`, `#corruption`, `#aid`, `#practical lessons`

---

<a id="item-5"></a>
## [日本企业多元化：终身雇佣与员工治理](https://davidoks.blog/p/why-japanese-companies-do-so-many) ⭐️ 8.0/10

一篇文章指出，日本企业广泛多元化源于终身雇佣和员工主导的治理模式，企业更注重生存和员工利益而非股东价值。 这一分析挑战了西方以股东为中心的治理模式，提供了一个以员工为中心的治理驱动多元化和长期稳定的替代方案。 文章指出，拥有公司特定技能的终身员工不能被轻易解雇，而该系统只有在不受外部股东压力影响的情况下才能运作。

hackernews · d0ks · May 22, 15:22 · [社区讨论](https://news.ycombinator.com/item?id=48237163)

**背景**: 终身雇佣是一种日本实践，约 30-40%的工人实际上在一家公司终生受雇。员工主导的治理意味着公司由员工而非仅仅股东运营，注重长期生存。这与西方优先考虑股东价值和短期利润的模式形成对比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bls.gov/opub/mlr/1984/08/rpt4full.pdf">Lifetime employment in Japan : three models of the concept</a></li>
<li><a href="https://eprints.whiterose.ac.uk/id/eprint/43581/1/MatanleMatsuiEPJHRM2011_Deposit.pdf">Lifetime Employment in 21st Century Japan : Stability and Resilience...</a></li>
<li><a href="https://www.nishimura.com/sites/default/files/articles/file/478.pdf">Corporate Governance and Directors' Duties in Japan: Overview</a></li>

</ul>
</details>

**社区讨论**: 评论指出，这种体系导致职业流动性低，对中途求职者不利，同时一些人注意到西方公司过去也曾多元化。另一些人则警告不要美化日本模式，指出其社会和经济弊端。

**标签**: `#Japanese business`, `#corporate strategy`, `#organizational culture`, `#economic systems`

---

<a id="item-6"></a>
## [微软取消 Claude Code 许可，力推 Copilot CLI](https://www.theverge.com/tech/930447/microsoft-claude-code-discontinued-notepad) ⭐️ 8.0/10

微软正在撤销开发者的 Claude Code 许可，并引导他们使用 GitHub Copilot CLI，这是一款命令行 AI 编码工具。 此举表明微软正战略性地推动自家 AI 编码助手 Copilot CLI 的采用，牺牲了受欢迎的竞争对手，可能限制开发者选择并引发反弹。 根据文章，微软最初向开发者提供两种工具用于比较，但开发者 overwhelmingly 偏好 Claude Code 而非 Copilot，导致许可被取消。

hackernews · robertkarl · May 22, 17:32 · [社区讨论](https://news.ycombinator.com/item?id=48238896)

**背景**: Claude Code 是 Anthropic 开发的智能编码工具，可在终端中使用，理解代码库并自动化任务。GitHub Copilot CLI 是微软自家的命令行 AI 编码助手。两者都旨在帮助开发者更快编码，但 Claude Code 常被认为更有效。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://www.anthropic.com/product/claude-code">Claude Code | Anthropic's agentic coding system</a></li>
<li><a href="https://awesome-copilot.github.com/learning-hub/cli-for-beginners/">GitHub Copilot CLI for Beginners</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了沮丧，指出微软希望 Copilot 优于 Claude Code 的期望适得其反。一些人强调小心、有监督地使用 Claude Code 可以节省成本，而另一些人则批评 Copilot 在政府云环境中的糟糕表现。

**标签**: `#Microsoft`, `#Claude Code`, `#Copilot`, `#AI coding assistants`, `#developer tools`

---

<a id="item-7"></a>
## [AI 对 HBM 的需求挤压消费级内存，推高价格](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

AI 对 HBM 内存的激增需求预计将其晶圆分配比例从 2%提升至 2026 年底的 20%，挤压了 DDR 和 LPDDR 内存的生产，导致消费电子产品（尤其是 100 美元以下的智能手机）价格上涨。 这一转变凸显了 AI 基础设施与平价消费设备之间的结构性权衡，可能影响新兴市场依赖廉价智能手机的数十亿用户。内存厂商优先考虑高利润的 HBM 而非消费级 RAM，这一趋势可能持续数年。 每 GB HBM 消耗的晶圆容量是 DDR 或 LPDDR 的三倍以上。内存制造商从过去的行业整合中吸取教训，始终倾向于产能不足，进一步限制了供应。

rss · Simon Willison · May 22, 22:01

**背景**: HBM（高带宽内存）是一种 3D 堆叠 DRAM 技术，专为高速数据传输和低功耗而优化，对 GPU 和 AI 加速器至关重要。晶圆容量指晶圆厂能处理的硅晶圆数量，在不同内存类型间分配。DDR 和 LPDDR 分别是用于台式机/服务器和移动设备的标准内存类型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://semiengineering.com/high-bandwidth-memory-hbm-everything-you-need-to-know/">High Bandwidth Memory (HBM): Everything You Need To Know</a></li>
<li><a href="https://www.semi.org/en/news-media-press-releases/semi-press-releases/global-semiconductor-fab-capacity-projected-to-expand-6%-in-2024-and-7%-in-2025-semi-reports">Global Semiconductor Fab Capacity Projected to Expand 6% in ...</a></li>

</ul>
</details>

**标签**: `#memory shortage`, `#AI`, `#consumer electronics`, `#semiconductors`, `#pricing`

---

<a id="item-8"></a>
## [FTC 对 Cox Media Group 虚假“主动监听”AI 服务罚款近百万美元](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 8.0/10

美国联邦贸易委员会宣布，Cox Media Group、MindSift 和 1010 Digital Works 将支付近 100 万美元，以和解关于其“主动监听”AI 服务虚假宣传的指控。该服务声称通过智能设备窃听对话来投放广告，但实际只是转售电子邮件列表并加价。 此案凸显了 FTC 对虚假 AI 营销和隐私声明日益严格的审查，开创了公司不得在 AI 监控能力上误导消费者的先例。同时也为驳斥智能手机利用麦克风进行广告定位的阴谋论提供了有力证据。 FTC 明确指出，在服务条款中隐藏的“选择加入”条款并不构成对此类侵入性行为的充分同意。此外，这些公司未能按承诺投放定向广告，而是转售数据经纪商提供的列表。

rss · Simon Willison · May 22, 04:48

**背景**: “主动监听”是一种有争议的营销技术，声称利用 AI 分析智能设备的实时语音数据进行广告定向。FTC 负责执行消费者保护法，打击欺骗性行为。此次和解确认该服务并未实际监听对话，揭穿了常见的阴谋论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thecyberexpress.com/ftc-ai-powered-active-listening-case/">AI-Powered Marketing Service “Active Listening” Deceived ...</a></li>
<li><a href="https://www.newsweek.com/phone-voice-assistants-active-listening-consent-targeted-ads-1949251">Is Your Phone Really Listening to You? Here’s What We Know FTC: Cox Media Group and 2 others to pay nearly $1M over ... Is your phone listening? Marketing firm confirms tech behind ... Is Your Device Always Listening? How It Fuels Targeted Ads FTC: Cox Media Group Sold Bogus AI Ad Service, Now Must... Marketer that claimed it could tap devices for ad targeting ...</a></li>

</ul>
</details>

**标签**: `#FTC`, `#AI`, `#privacy`, `#advertising`, `#enforcement`

---

<a id="item-9"></a>
## [Datasette Agent: LLM 驱动的数据探索 AI 助手](https://simonwillison.net/2026/May/21/datasette-agent/#atom-everything) ⭐️ 8.0/10

Simon Willison 宣布了 Datasette Agent 的首个版本，这是一个可扩展的 AI 助手，通过插件将大语言模型与 Datasette 集成，支持对话式数据查询和图表生成。 Datasette Agent 连接了大语言模型和结构化数据，使非技术用户更容易进行数据探索，并支持与 SQLite 数据库的自然语言交互。 实时演示使用 Gemini 3.1 Flash-Lite 进行廉价快速的推理，插件生态目前包括通过 Observable Plot 生成图表和通过 ChatGPT 生成图像。

rss · Simon Willison · May 21, 19:52

**背景**: Datasette 是一个开源工具，能将 SQLite 数据库发布为交互式网页界面和 JSON API。LLM 库是一个命令行工具和 Python 库，用于与各种大语言模型交互。Datasette Agent 将这两者结合，允许对数据进行自然语言查询。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and ...</a></li>
<li><a href="https://llm.datasette.io/">LLM: A CLI utility and Python library for interacting with Large Language Models</a></li>
<li><a href="https://github.com/simonw/datasette">GitHub - simonw/datasette: An open source multi-tool for ... Datasette Review (2026) - MakerStack Introduction to Datasette, a Frontend to Tabulated Data Commodore Datasette - Wikipedia datasette · PyPI Datasette - skills.network</a></li>

</ul>
</details>

**标签**: `#Datasette`, `#LLM`, `#AI Assistant`, `#Data Exploration`, `#Python`

---

<a id="item-10"></a>
## [腾讯收购喜马拉雅获批，附加放弃独家版权条件](https://mp.weixin.qq.com/s/xnx31SOS6NMozZXnHeaaQg) ⭐️ 8.0/10

国家市场监管总局批准腾讯收购喜马拉雅，要求腾讯停止达成在线音频版权独家授权，并在限期内解除现有独家合同。 此举打破了喜马拉雅的内容垄断，可能重塑在线音频市场，让其他平台也能获取相同版权内容，促进竞争并方便用户跨平台收听。 腾讯不得达成或续签在线音频版权独家授权协议，并需在规定期限内解除所有现有独家合同。腾讯表示将配合解除独家合同，后续寻求非独家合作。

telegram · zaihuapd · May 22, 10:33

**背景**: 喜马拉雅是中国最大的在线音频平台，拥有庞大的有声书、播客和广播节目库。独家版权协议是其关键竞争优势，将内容锁定在喜马拉雅平台。腾讯的收购引发反垄断担忧，因为可能导致市场主导地位。

**标签**: `#Tencent`, `#Ximalaya`, `#Antitrust`, `#Online Audio`, `#Regulation`

---

<a id="item-11"></a>
## [中国八部门整治非法跨境证券经营](https://t.me/zaihuapd/41525) ⭐️ 8.0/10

中国八部门联合发文整治非法跨境证券、期货、基金经营，要求存量投资者只能单向卖出资产并转出资金。证监会已对老虎证券、富途证券和长桥证券非法跨境展业立案调查。 这一监管行动对跨境投资平台及其用户产生重大影响，可能迫使许多金融科技公司停止在华服务。这标志着对资本外流和无牌金融活动采取更强硬立场，影响数百万使用这些平台的中国投资者。 方案设定了两年集中整治期，期间只允许存量投资者卖出资产并转出资金，期满后相关境内网站、交易软件和配套服务器须全面关停。整治对象包括境外机构、境内关联方以及提供开户通道和营销引流的信息平台。

telegram · zaihuapd · May 22, 13:55

**背景**: 老虎证券（TIGR）、富途控股（FUTU）和长桥证券是在线券商，允许中国居民交易全球股票和衍生品，但通常未获得中国监管机构的适当批准。中国证券法要求任何在中国境内招揽客户或执行交易的实体必须获得中国证监会许可。此次整治是在多年监管警告之后进行的，反映了北京控制跨境资本流动和保护投资者的努力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Futu">Futu - Wikipedia</a></li>
<li><a href="https://www.futuholdings.com/en-us/profile">About Us | FUTU | Futu Holdings Limited 富途控股</a></li>
<li><a href="https://grokipedia.com/page/Tiger_Brokers">Tiger Brokers</a></li>

</ul>
</details>

**标签**: `#regulation`, `#cross-border investment`, `#China`, `#fintech`, `#securities`

---

<a id="item-12"></a>
## [Cloudflare 故障影响 28% HTTP 流量，持续 25 分钟](https://t.me/zaihuapd/41527) ⭐️ 8.0/10

2025 年 12 月 5 日，Cloudflare 全球网络发生 25 分钟故障，影响约 28% 的 HTTP 流量，原因是为修复 Next.js 中的 React Server Components 漏洞 CVE-2025-55182 而部署的修复存在缺陷。 此次故障影响了通过 Cloudflare 路由的相当一部分互联网流量，作为最大的内容分发网络之一，凸显了在关键基础设施上部署安全补丁的级联风险。 故障特别影响了使用旧版 FL1 代理并部署了 Cloudflare 托管规则集的客户，返回 HTTP 500 错误。根本原因是在修复 CVE 期间对执行动作规则集应用 killswitch 时触发了 Lua nil 指针错误。

telegram · zaihuapd · May 22, 16:15

**背景**: Cloudflare 是一家主要的内容分发网络和安全服务提供商，处理全球大量网络流量。其 FL1 代理是一个较旧的请求处理层。CVE-2025-55182 是 React Server Components 中的一个严重预认证远程代码执行漏洞，影响版本 19.0.0 至 19.2.0。Cloudflare 的 Web 应用防火墙（WAF）规则包含托管规则集以阻止此类利用，但一个有缺陷的更新导致了此次故障。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.cloudflare.com/5-december-2025-outage/">Cloudflare outage on December 5, 2025</a></li>
<li><a href="https://www.ascii.co.uk/news/article/news-20251208-71fe2ccb/cloudflare-25-minute-outage-lua-nil-bug-in-waf-rules-engine">Cloudflare 25-Minute Outage: Lua Nil Bug in WAF Rules Engine</a></li>
<li><a href="https://nvd.nist.gov/vuln/detail/CVE-2025-55182">NVD - CVE-2025-55182</a></li>

</ul>
</details>

**标签**: `#Cloudflare`, `#outage`, `#CVE-2025-55182`, `#Next.js`, `#WAF`

---

<a id="item-13"></a>
## [微软内部推广 Claude Code，鼓励非技术员工使用](https://t.me/zaihuapd/41535) ⭐️ 8.0/10

微软正在其 CoreAI 团队以及负责 Windows、Microsoft 365 和 Outlook 的体验与设备部门中推广 Anthropic 的 Claude Code。软件工程师需同时使用 Claude Code 和 GitHub Copilot，并提供对比反馈。 此举标志着 AI 编程工具市场的竞争动态，并验证了 AI 编程助手对非技术员工的价值。同时，这也给微软自家的 GitHub Copilot 带来了压力，因为公司正在评估替代工具。 Claude Code 是一款可在终端或 IDE 中运行的 AI 编程代理，具备代码生成、重构和调试等功能。微软的推广对象包括没有编程经验的员工，鼓励他们使用 Claude Code 进行原型设计。

telegram · zaihuapd · May 23, 06:05

**背景**: Claude Code 是 Anthropic 开发的一款工具，利用 Claude 语言模型辅助编程任务，可在终端中使用或集成到 IDE。GitHub Copilot 由微软和 GitHub 开发，是一款通过自动补全代码来辅助编程的竞争产品。微软内部对两款工具进行评估，表明其愿意采用最佳解决方案，而非仅使用自家产品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**标签**: `#AI coding`, `#Microsoft`, `#Claude Code`, `#GitHub Copilot`, `#software engineering`

---

<a id="item-14"></a>
## [微软披露 OpenAI 单季亏损 115 亿美元](https://t.me/zaihuapd/41537) ⭐️ 8.0/10

微软最新财报披露，其采用权益法核算对 OpenAI 约 27%的股权投资，导致单季度净利润减少 31 亿美元，据此推算 OpenAI 该季度净亏损约 115 亿美元。 这一披露凸显了在人工智能领域领先所需的巨大且持续的烧钱速度，对即使是头部 AI 企业的长期经济可持续性提出了质疑。 微软采用权益法计算：其持有 OpenAI 约 27%股权（按税前口径约 32.5%），暗示 OpenAI 税前单季亏损超过 120 亿美元。这一亏损规模是 OpenAI 今年上半年 43 亿美元营收的近三倍。

telegram · zaihuapd · May 23, 07:40

**背景**: 权益法是一种会计方法，当投资方对被投资方具有重大影响（通常持股 20%-50%）时使用。根据该方法，投资方按持股比例确认被投资方的利润或亏损作为投资收益或损失，并相应调整长期股权投资的账面价值。此次披露揭示了 AI 领域所需的巨大投资规模，微软已向 OpenAI 承诺投入 130 亿美元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/496165358">长期股权投资——权益法（干货总结） - 知乎</a></li>
<li><a href="https://baike.baidu.com/item/权益法/9289851">权益法_百度百科 采用权益法核算的长期股权投资账务处理流程（附案例详解） 一文搞懂长期股权投资的核算方法：成本法、权益法和合并法 在阅读||#20998;... 权益法核算的长期股权投资收益_东奥会计在线 【老丁解税】权益法下投资收益的所得税处理解析 【老丁解税】权益法下投资收益的所得税处理解析|股权|纳税|权益性_网...</a></li>

</ul>
</details>

**标签**: `#Microsoft`, `#OpenAI`, `#financial loss`, `#AI`, `#investment`

---

<a id="item-15"></a>
## [BambuStudio 被指控违反 PrusaSlicer 的 AGPL 许可证](https://xcancel.com/josefprusa/status/2054602354851254330) ⭐️ 7.0/10

Prusa Research 创始人 Josef Prusa 公开指控 BambuStudio 在从 PrusaSlicer 分叉后未能遵守 AGPL 许可证的开源要求，构成侵权。 这一指控凸显了开源许可证在执行过程中的持续挑战，特别是在 3D 打印软件的二次开发中，同时引发了对知识产权保护和封闭源代码分支可能进行数据挖掘的担忧。 BambuStudio 是 PrusaSlicer 的专有分支，后者采用 AGPLv3 许可证，要求任何通过网络分发的修改版本也必须开源。被指控的违规行为包括未发布源代码修改以及可能包含数据挖掘功能。

hackernews · Tomte · May 23, 08:24 · [社区讨论](https://news.ycombinator.com/item?id=48245862)

**背景**: GNU Affero General Public License（AGPLv3）是一种强版权的开源许可证，要求任何通过网络分发修改版软件的用户必须公开完整的源代码。PrusaSlicer 是 Prusa Research 开发的流行开源 3D 打印切片软件。Bambu Studio 是用于 Bambu Lab 打印机的切片软件，最初基于 PrusaSlicer。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GNU_Affero_General_Public_License">GNU Affero General Public License - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/PrusaSlicer">PrusaSlicer - Wikipedia</a></li>
<li><a href="https://bambulab.com/en/download/studio">Software Bambu Studio | Bambu Lab</a></li>

</ul>
</details>

**社区讨论**: 评论者强烈关注知识产权和数据隐私，有人指出维护开源许可证成本高昂且违规行为难以证明。其他人则讨论了中国和美国政府进行数据挖掘的风险，一些用户表示将避免使用封闭源代码打印机来制作商业原型。

**标签**: `#open source`, `#license violation`, `#3D printing`, `#AGPL`, `#intellectual property`

---

<a id="item-16"></a>
## [李彦宏：AI 大模型已近应用爆发点](https://t.me/zaihuapd/41538) ⭐️ 7.0/10

百度 CEO 李彦宏表示，AI 大模型的发展已接近应用爆发的临界点，并透露百度搜索中 65%的结果已包含生成式内容，且这些内容被置于优先位置。 这标志着搜索引擎功能的重大转变，表明百度正在积极将生成式 AI 融入其核心产品，可能引领行业趋势。 百度两年前便启动所有产品的 AI 重构，李彦宏称这次搜索引擎改造是全球所有搜索引擎中最激进的。生成式内容不仅出现在搜索结果中，还被置于优先位置。

telegram · zaihuapd · May 23, 08:40

**背景**: AI 大模型如 GPT 系列和百度的文心一言，是在海量数据上训练、能生成类人文本的深度学习模型。将它们集成到搜索引擎中，可以提供直接答案和摘要，而不仅仅是链接，类似于微软的 Copilot 集成。

**标签**: `#AI`, `#large language models`, `#Baidu`, `#generative AI`, `#search engine`

---

<a id="item-17"></a>
## [海盗船采用长鑫存储 DRAM，DDR5 价格有望下调](https://thenextweb.com/news/chinese-dram-cxmt-corsair-ddr5-memory-prices) ⭐️ 7.0/10

美商海盗船已开始在其 DDR5 内存模组中使用中国长鑫存储（CXMT）的 DRAM 芯片，这是主流品牌首次在消费级产品中采用中国制造的 DRAM。 这一转变引入了 DRAM 市场的新竞争者，该市场原本由三星、SK 海力士和美光主导，有望在 AI 对高带宽内存需求导致全球供应紧张的情况下，降低消费者的 DDR5 内存价格。 这款采用长鑫芯片的海盗船复仇者 DDR5 16GB 内存条运行速度为 6000 MT/s，时序 CL36，性能与主流产品一致。长鑫存储计划于 2026 年上市，并进一步扩大产能。

telegram · zaihuapd · May 23, 11:17

**背景**: 全球 DRAM 市场长期由三星、SK 海力士和美光三大巨头主导。近年来，AI 加速器所需的高带宽内存需求激增，导致消费级 DDR5 模组的产能被挤占，出现供应短缺。长鑫存储（CXMT）是一家中国 DRAM 制造商，于 2024 年底开始量产 DDR5 芯片，提供了替代供应来源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>
<li><a href="https://www.tomshardware.com/pc-components/ddr5/chinese-memory-maker-cxmt-enters-the-mainstream-consumer-memory-with-corsair-vengeance-ddr5-kit-chinese-made-dram-emerges-as-an-antidote-for-crushing-shortages">Chinese memory maker CXMT enters mainstream... | Tom's Hardware</a></li>
<li><a href="https://www.digitalfoundry.net/news/2026/05/corsair-taps-chinese-ddr5-for-its-ram-modules-while-china-developed-gpus-are-improving-fast">Corsair Taps Chinese DDR5 for Its RAM Modules... | Digital Foundry</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的社区讨论表达了谨慎乐观，指出即使美国出口限制阻止长鑫芯片进入美国市场，增加的全球供应也能降低其他地区的价格并缓解整体需求压力。一些用户质疑长期可靠性和兼容性，但早期测试显示性能相当。

**标签**: `#DRAM`, `#DDR5`, `#Corsair`, `#CXMT`, `#memory`, `#supply chain`

---

<a id="item-18"></a>
## [我国日均词元调用量两年增超千倍，2025 年 3 月突破 140 万亿](https://t.me/zaihuapd/41542) ⭐️ 7.0/10

国家数据局披露，我国日均词元（Token）调用量在 2025 年 3 月突破 140 万亿，而 2024 年初仅为 1000 亿，两年内增长超千倍。 这一爆发式增长表明中国 AI 商业化的快速推进，以及围绕词元调用的新价值体系正在形成，对 AI 产业商业模式和数据经济至关重要。 2025 年底词元调用量已达 100 万亿，国家数据局强调词元具有可计量、可定价、可交易特征，推动数据市场化。这一增长反映了数据要素市场化配置改革的进展。

telegram · zaihuapd · May 23, 14:36

**背景**: 在大语言模型（LLM）中，词元（Token）是模型处理文本的最小单元，可以是一个词、子词或字符。分词（Tokenization）将输入文本切分为词元供模型处理。词元调用量的激增意味着 AI 服务使用量的大幅上升，因为每次向 LLM 的请求都会消耗大量词元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mexc.co/news/985902">令牌、代币、通证还 是 词 元 ？— — Token ... | MEXC News</a></li>
<li><a href="https://codebitwave.com/artificial-intelligence-101-tokenizer-and-one-hot/">Artificial Intelligence 101: Tokenizer and One-Hot – CODEBITWAVE</a></li>
<li><a href="https://paper.people.com.cn/rmrb/pc/attachement/202604/03/ebaa4672-39f2-4da9-a084-e137dd7f95de.pdf">paper.people.com.cn/rmrb/pc/attachement/202604/03/ebaa4672-39...</a></li>

</ul>
</details>

**标签**: `#AI`, `#China`, `#tokenization`, `#data economy`, `#AI infrastructure`

---

<a id="item-19"></a>
## [深入探讨 HTML <dl>元素的语义](https://benmyers.dev/blog/on-the-dl/) ⭐️ 6.0/10

这篇文章澄清了 HTML5 中 <dl> 的正确语义用法（常被误解为仅仅是定义列表），并强调了其在可访问性和清晰标记方面的重要性。 <dl> 元素在 HTML5 中不再仅仅是“定义列表”，现在表示名称-值组的“关联列表”。文章还探讨了 ARIA 角色限制和实际的嵌套模式。

hackernews · ravenical · May 23, 13:03 · [社区讨论](https://news.ycombinator.com/item?id=48247325)

**背景**: HTML <dl> 元素传统上用于定义列表（如词汇表）。在 HTML5 中，其语义被扩展为表示任何类型的名称-值关联，例如元数据或游戏属性。这一变化对可访问性以及屏幕阅读器如何解释内容产生了影响。

**社区讨论**: 社区成员提出了几点：chrismorgan 指出了 <dl> 的 ARIA 角色限制以及 aria-label 的使用限制。jimbosis 提到世界上第一个网站大量使用了 <dl>。captn3m0 对从“定义列表”更名为“关联列表”感到惊讶。cloud-oak 询问了嵌套 <dl> 元素的问题，文章对此表示支持。Demiurge 赞扬了 <dl>，并批评了过去对表格的滥用。

**标签**: `#HTML`, `#accessibility`, `#web development`, `#semantic markup`

---

<a id="item-20"></a>
## [Rubish：用纯 Ruby 编写的 Unix shell](https://github.com/amatsuda/rubish) ⭐️ 6.0/10

一个名为 Rubish 的新 Unix shell 已在 GitHub 上发布，它完全用纯 Ruby 实现，允许用户使用 Ruby 语法编写 shell 脚本。 该项目弥合了 shell 脚本与 Ruby 之间的差距，可能使 Ruby 开发者更方便、更强大地完成 shell 任务，同时也引发了关于特定语言 shell 利弊的讨论。 Rubish 并非 bash 的直接替代品，它专注于基于 Ruby 的脚本。社区评论表达了对可能由 AI 辅助开发导致的代码质量的担忧，以及与传统 shell 相比可能存在的性能问题。

hackernews · winebarrel · May 23, 06:32 · [社区讨论](https://news.ycombinator.com/item?id=48245262)

**背景**: Unix shell 是一种用于与操作系统交互的命令行界面。传统的 shell 如 bash 使用自己的脚本语言，而 Rubish 利用了 Ruby 这一高级、可读性强的语言。这使得 Ruby 开发者可以使用熟悉的语法和库来完成 shell 任务。

**社区讨论**: 社区反应不一：一些人觉得这个概念很棒，但对速度和 vi 输入问题存疑；另一些人担心 AI 辅助编程带来的代码质量；还有一些人对巧妙的命名表示赞赏。总体而言，该项目被视为一个有趣的实验。

**标签**: `#ruby`, `#shell`, `#unix`, `#open-source`

---