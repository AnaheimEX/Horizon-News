---
layout: default
title: "Horizon Summary: 2026-05-23 (EN)"
date: 2026-05-23
lang: en
---

> From 48 items, 20 important content pieces were selected

---

1. [Apple Open-Sources corecrypto with Formal Verification of Quantum-Safe Algorithms](#item-1) ⭐️ 9.0/10
2. [Anthropic Updates Project Glasswing with High Accuracy Vulnerability Detection](#item-2) ⭐️ 8.0/10
3. [Decades of sleep research yield new sleep apnea drug](#item-3) ⭐️ 8.0/10
4. [Microsoft cancels Claude Code licenses, pushes Copilot CLI](#item-4) ⭐️ 8.0/10
5. [CISA data leak after contractor exposes secrets on GitHub](#item-5) ⭐️ 8.0/10
6. [Antigravity 2.0 Tops OpenSCAD LLM Benchmark for Architectural 3D Models](#item-6) ⭐️ 8.0/10
7. [Memory shortage from AI demand reprices consumer electronics](#item-7) ⭐️ 8.0/10
8. [Datasette Agent: AI Assistant for Data Querying](#item-8) ⭐️ 8.0/10
9. [ByteDance open-sources 3B multimodal model Lance](#item-9) ⭐️ 8.0/10
10. [Tencent's Ximalaya Acquisition Approved with Exclusive Rights Condition](#item-10) ⭐️ 8.0/10
11. [China cracks down on illegal cross-border securities, probes Tiger Brokers, Futu](#item-11) ⭐️ 8.0/10
12. [Cloudflare 25-Minute Global Outage Hits 28% of HTTP Traffic](#item-12) ⭐️ 8.0/10
13. [Shipping a laptop to a Ugandan refugee camp: bureaucratic ordeal](#item-13) ⭐️ 7.0/10
14. [Why Japanese companies diversify so much](#item-14) ⭐️ 7.0/10
15. [Deno 2.8 released with new pack command and permission debate](#item-15) ⭐️ 7.0/10
16. [Kanbots: open-source Kanban app runs parallel AI agents on every card](#item-16) ⭐️ 7.0/10
17. [FBI Director's Apparel Site Hit by ClickFix Malware Attack](#item-17) ⭐️ 7.0/10
18. [FTC Fines Cox Media Group $1M for Fake AI Listening Ads](#item-18) ⭐️ 7.0/10
19. [Zhipu AI Launches GLM-5.1-HighSpeed at 400 Tokens/s](#item-19) ⭐️ 7.0/10
20. [Microsoft widely promotes Claude Code internally, encourages non-technical staff](#item-20) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Apple Open-Sources corecrypto with Formal Verification of Quantum-Safe Algorithms](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

Apple has open-sourced its corecrypto library, which includes implementations of the post-quantum algorithms ML-KEM and ML-DSA, along with formal verification proofs that the C code and ARM64 assembly match the NIST standards. This is a major step for cryptography, as it provides mathematically verified implementations of quantum-safe algorithms running on billions of devices, setting a new standard for software assurance in the industry. The formal verification was done using Apple's custom verification tools and Isabelle theory libraries, and the source code is available on GitHub. corecrypto underpins cryptographic operations on over 2.5 billion active devices.

telegram · zaihuapd · May 23, 04:49

**Background**: ML-KEM (Module-Lattice-Based Key-Encapsulation Mechanism) and ML-DSA (Module-Lattice-Based Digital Signature Algorithm) are post-quantum cryptographic standards selected by NIST in 2024 to resist attacks from future quantum computers. Formal verification uses mathematical proofs to ensure that software implementations exactly follow the intended specification, eliminating entire classes of bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ML-KEM">ML-KEM</a></li>
<li><a href="https://en.wikipedia.org/wiki/ML-DSA">ML-DSA</a></li>

</ul>
</details>

**Tags**: `#post-quantum cryptography`, `#formal verification`, `#apple`, `#cryptography`, `#open source`

---

<a id="item-2"></a>
## [Anthropic Updates Project Glasswing with High Accuracy Vulnerability Detection](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 8.0/10

Anthropic released an initial update on Project Glasswing, reporting that its AI model achieved a 90.6% true positive rate for high- or critical-severity vulnerabilities in code, verified by independent security firms. This could significantly improve automated vulnerability detection in software, potentially catching critical issues that static analysis tools miss, and shift how security teams integrate AI into their workflows. Out of 1,752 assessed high- or critical-rated vulnerabilities, 90.6% (1,587) were true positives, and 62.4% (1,094) were confirmed as high or critical severity; the model, Claude Mythos, is part of Anthropic's cybersecurity initiative.

hackernews · louiereederson · May 22, 19:31 · [Discussion](https://news.ycombinator.com/item?id=48240419)

**Background**: Project Glasswing is Anthropic's industry-wide cybersecurity initiative launched in April 2026 to secure critical software using advanced AI. Claude Mythos is a frontier model trained by Anthropic for code analysis. Traditional static analysis tools can catch common vulnerabilities but often miss complex logic issues, leading to potential security flaws in production code.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Glasswing">Project Glasswing</a></li>
<li><a href="https://grokipedia.com/page/Project_Glasswing">Project Glasswing</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Comments show mixed reactions: user mdeeks praised the tool's accuracy and integration, while curl maintainer Daniel Steinberg expressed skepticism, stating he saw no evidence of extraordinary performance over existing tools. Other comments debated the cost-benefit versus traditional linters, noting that many teams don't even use basic static analysis.

**Tags**: `#AI`, `#cybersecurity`, `#vulnerability detection`, `#code analysis`, `#Anthropic`

---

<a id="item-3"></a>
## [Decades of sleep research yield new sleep apnea drug](https://temertymedicine.utoronto.ca/news/how-decades-sleep-research-led-new-sleep-apnea-drug) ⭐️ 8.0/10

Researchers have developed a novel drug for sleep apnea based on decades of sleep research, potentially offering an alternative to CPAP therapy. The drug targets specific neural circuits to maintain airway muscle tone during sleep. Sleep apnea affects millions worldwide and current standard treatment CPAP has low long-term adherence. A pharmaceutical option could significantly improve patient outcomes and quality of life. The drug reduces apnea events by only 4 per hour, which may be most beneficial for mild sleep apnea rather than moderate to severe cases. It was discovered by mapping the neural circuits that control airway muscles.

hackernews · colinprince · May 22, 22:05 · [Discussion](https://news.ycombinator.com/item?id=48242278)

**Background**: Sleep apnea is a condition where breathing repeatedly stops and starts during sleep, often due to airway collapse. CPAP machines keep the airway open with pressurized air but many patients find them uncomfortable. A drug that activates airway muscles could provide a simpler treatment.

**Discussion**: Community comments show mixed reactions: some users share personal CPAP experiences and tips, while others question the drug's efficacy noting it only reduces events by 4 per hour, suggesting it may only help mild cases. There is also discussion about alternative treatments like posture correction.

**Tags**: `#sleep apnea`, `#drug discovery`, `#medical research`, `#health`, `#CPAP`

---

<a id="item-4"></a>
## [Microsoft cancels Claude Code licenses, pushes Copilot CLI](https://www.theverge.com/tech/930447/microsoft-claude-code-discontinued-notepad) ⭐️ 8.0/10

Microsoft has begun canceling Claude Code licenses for its developers, effective June 30, 2026, steering them toward its own GitHub Copilot CLI tool. This move signals Microsoft's strategic shift away from third-party AI coding tools, potentially reshaping developer tooling choices and raising questions about the economics of AI agentic tools versus human-in-the-loop approaches. The Claude Code pilot launched in December 2025 reportedly consumed Microsoft's 2026 yearly AI budget spend within a short period, leading to the cancellation. GitHub Copilot CLI is a command-line agent that works with issues, pull requests, and parallelized subagents.

hackernews · robertkarl · May 22, 17:32 · [Discussion](https://news.ycombinator.com/item?id=48238896)

**Background**: Claude Code is an AI-powered coding assistant from Anthropic that runs in the terminal, helping developers generate code, fix bugs, and automate tasks. GitHub Copilot CLI is Microsoft's competing command-line tool that integrates with GitHub workflows. Microsoft's decision reflects a broader industry trend of platform vendors favoring their own AI tools over third-party alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://code.claude.com/docs/en/overview">Overview - Claude Code Docs</a></li>
<li><a href="https://github.com/features/copilot/cli/">GitHub Copilot CLI</a></li>
<li><a href="https://developer.microsoft.com/blog/get-started-with-github-copilot-cli-a-free-hands-on-course">Get started with GitHub Copilot CLI: A free, hands-on course</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that Claude Code is token-expensive, with one user noting a pilot burned through monthly allowance in a week, while DeepSeek was far more cost-effective. Another user questioned the economics of replacing developer salaries with expensive AI tools, and a comment revealed the pilot consumed Microsoft's 2026 yearly AI spend target.

**Tags**: `#Microsoft`, `#Claude Code`, `#Copilot CLI`, `#AI coding tools`, `#token economy`

---

<a id="item-5"></a>
## [CISA data leak after contractor exposes secrets on GitHub](https://krebsonsecurity.com/2026/05/lawmakers-demand-answers-as-cisa-tries-to-contain-data-leak/) ⭐️ 8.0/10

A contractor working with CISA accidentally exposed sensitive data by using a GitHub repository as a scratchpad, leading to a data leak. Lawmakers are demanding answers, and CISA is working to contain the breach. This incident highlights ongoing risks in government cybersecurity, especially when human error bypasses technical controls. It could undermine trust in CISA's ability to protect its own data and prompt stricter security measures. The leak involved secrets stored in a GitHub repository used for synchronization. CISA stated no sensitive data was compromised, but community members dispute that claim given the nature of the exposed information.

hackernews · speckx · May 22, 16:54 · [Discussion](https://news.ycombinator.com/item?id=48238429)

**Background**: CISA, the Cybersecurity and Infrastructure Security Agency, is a U.S. government agency responsible for protecting critical infrastructure. Git repositories are commonly used for code version control, but storing secrets in them is a well-known security risk. Contractors often have access to sensitive systems, making their security practices crucial.

**Discussion**: Comments express skepticism about CISA's assurances, with one user recalling a prior leak of SF-86 forms. Another user questions why fundamental Git security practices were ignored. Some debate whether the problem is technical or human, with a comment quoting a perspective that technical controls cannot fully prevent such human errors.

**Tags**: `#cybersecurity`, `#data breach`, `#CISA`, `#government`, `#GitHub`

---

<a id="item-6"></a>
## [Antigravity 2.0 Tops OpenSCAD LLM Benchmark for Architectural 3D Models](https://modelrift.com/blog/openscad-llm-benchmark/) ⭐️ 8.0/10

A new benchmark, the OpenSCAD LLM Benchmark, tests AI models on generating OpenSCAD code for the Pantheon; Google's Antigravity 2.0 agent achieved the highest score, including implementing interior ceiling details. This benchmark introduces a novel, visually-driven evaluation for LLMs in parametric 3D modeling, highlighting the potential for AI-assisted architectural design and accessible 3D printing workflows. Antigravity 2.0 was the only autonomous agent that implemented the Pantheon's signature interior square coffers visible through the oculus. The benchmark evaluated six models, including Gemini, Claude, and GPT-4, based on adherence to reference images.

hackernews · jetter · May 22, 10:38 · [Discussion](https://news.ycombinator.com/item?id=48234090)

**Background**: OpenSCAD is a script-only 3D CAD modeller that uses its own description language to define geometric primitives and operations. This benchmark tasks LLMs with producing OpenSCAD code from images of a complex architectural structure, testing both code generation and spatial reasoning. Antigravity 2.0 is Google's latest agentic coding tool, updated at IO 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenSCAD">OpenSCAD</a></li>
<li><a href="https://modelrift.com/blog/openscad-llm-benchmark/">OpenSCAD LLM Benchmark: Building the Pantheon | ModelRift Blog</a></li>
<li><a href="https://techcrunch.com/2026/05/19/google-launches-antigravity-2-0-with-an-updated-desktop-app-and-cli-tool/">Google launches Antigravity 2.0 with an updated desktop app and CLI tool at IO 2026 | TechCrunch</a></li>

</ul>
</details>

**Discussion**: Community members shared mixed experiences: one praised Claude for generating a functional OpenSCAD part from photos, while another criticized Antigravity's rollout issues, requiring browser login each time. Some questioned the benchmark's conclusiveness due to single-model testing, noting that Gemini models showed the least jagged performance in their own tests.

**Tags**: `#OpenSCAD`, `#LLM`, `#benchmark`, `#3D modeling`, `#AI agent`

---

<a id="item-7"></a>
## [Memory shortage from AI demand reprices consumer electronics](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

AI's demand for HBM memory is reallocating wafer capacity from DDR/LPDDR to HBM, with HBM's share rising from 2% to an expected 20% by 2026, causing consumer electronics like smartphones to become more expensive. This structural shift will increase prices for consumer electronics, particularly affecting budget devices in markets like Africa and South Asia; the memory shortage is expected to persist until at least 2030. HBM consumes over three times the wafer capacity per gigabyte compared to DDR or LPDDR, and memory manufacturers deliberately under-provision capacity to avoid overbuilding, as learned from past rival bankruptcies.

rss · Simon Willison · May 22, 22:01

**Background**: Memory manufacturers have fixed wafer capacity split among DDR (desktops/servers), LPDDR (mobile/low-power), and HBM (high-bandwidth memory for GPUs). HBM stacks multiple DRAM dies for higher bandwidth and is essential for AI workloads. The rapid growth of AI data centers has dramatically increased HBM demand, squeezing supply for other memory types and driving up costs for consumer electronics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HBM_memory_shortage">HBM memory shortage</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#memory shortage`, `#HBM`, `#AI`, `#consumer electronics`, `#supply chain`

---

<a id="item-8"></a>
## [Datasette Agent: AI Assistant for Data Querying](https://simonwillison.net/2026/May/21/datasette-agent/#atom-everything) ⭐️ 8.0/10

Simon Willison announced the first release of Datasette Agent, an AI assistant that provides a conversational interface for querying data stored in Datasette, with optional chart generation via the datasette-agent-charts plugin. This release marks a significant milestone by integrating LLM capabilities directly into Datasette, enabling users to ask natural language questions and generate visualizations without writing SQL, which lowers the barrier for data exploration. Datasette Agent is extensible via plugins; the demo instance at agent.datasette.io uses Gemini 3.1 Flash-Lite, which is cheap and fast. Plugins already available include datasette-agent-charts (Observable Plot) and datasette-agent-openai-imagegen (ChatGPT image generation).

rss · Simon Willison · May 21, 19:52

**Background**: Datasette is an open-source multi-tool for exploring and publishing data, built on SQLite. LLM is a Python library and CLI tool for interacting with large language models. Datasette Agent brings these two projects together, offering a conversational interface that writes and runs SQL queries automatically based on user prompts.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/May/21/datasette-agent/">Datasette Agent - simonwillison.net</a></li>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and ...</a></li>
<li><a href="https://github.com/datasette/datasette-agent-charts">GitHub - datasette/datasette-agent-charts: Observable Plot ...</a></li>

</ul>
</details>

**Tags**: `#Datasette`, `#AI`, `#data analysis`, `#LLM`, `#open source`

---

<a id="item-9"></a>
## [ByteDance open-sources 3B multimodal model Lance](https://mp.weixin.qq.com/s/Xbfq72cr1796RZxJIs3L1A) ⭐️ 8.0/10

ByteDance has open-sourced Lance, a 3B-parameter multimodal model that unifies image/video understanding and generation under the Apache 2.0 license, with weights available on Hugging Face. Lance demonstrates that a relatively small 3B model can achieve competitive performance in both understanding and generation, potentially lowering the barrier for multimodal AI research and applications. Lance uses a dual-stream Mixture-of-Experts (MoE) architecture with Qwen2.5-VL for understanding and Wan2.2 for generation, plus modality-aware positional encoding (PE) to resolve sequence boundary ambiguity. It achieves top results on GenEval and VBench benchmarks.

telegram · zaihuapd · May 22, 06:40

**Background**: Multimodal models that handle both understanding and generation often suffer from capability conflict. Dual-stream architectures separate processing paths for different tasks, while modality-aware PE ensures proper encoding of mixed image, video, and text sequences. GenEval and VBench are standard benchmarks for evaluating text-to-image and video generation quality.

<details><summary>References</summary>
<ul>
<li><a href="https://www.agentren.cn/2026/0522/15846.shtml">字节跳动开源Lance 3B：实现图像与视频理解与生成_A³·爱力方</a></li>
<li><a href="https://kexue.fm/archives/10352">“闭门造车”之多模态思路浅谈（三）：位置编码 - 科学空间|Scientific Spaces</a></li>
<li><a href="https://arxiv.org/abs/2310.11513">[2310.11513] GenEval: An Object-Focused Framework for ... GenEval: A Benchmark Suite for Evaluating Generative Models GenEval Benchmark | showlab/DIM | DeepWiki GenEval Benchmark Overview - emergentmind.com GenEval Benchmark Table GenEval — Image generation benchmark · Codesota | CodeSOTA</a></li>

</ul>
</details>

**Tags**: `#multimodal`, `#AI`, `#open source`, `#image generation`, `#video generation`

---

<a id="item-10"></a>
## [Tencent's Ximalaya Acquisition Approved with Exclusive Rights Condition](https://mp.weixin.qq.com/s/xnx31SOS6NMozZXnHeaaQg) ⭐️ 8.0/10

China's market regulator approved Tencent's acquisition of audio platform Ximalaya, but required Tencent to relinquish exclusive online audio copyrights and terminate existing exclusive contracts within a set timeframe. This decision dismantles Ximalaya's exclusive content barriers, potentially leveling the competitive landscape for other audio platforms and improving cross-platform access for users. Tencent must commit to not reaching or disguising exclusive online audio copyright arrangements in the future, and is required to phase out existing exclusive deals, though it can still pursue non-exclusive partnerships.

telegram · zaihuapd · May 22, 10:33

**Background**: Ximalaya is China's leading audio-sharing platform, offering podcasts, audiobooks, and live audio. Exclusive copyrights have been a key competitive strategy for platforms to attract users, but regulators have increasingly targeted such practices to promote competition and consumer choice.

**Tags**: `#tencent`, `#regulation`, `#audio`, `#competition`, `#china`

---

<a id="item-11"></a>
## [China cracks down on illegal cross-border securities, probes Tiger Brokers, Futu](https://t.me/zaihuapd/41525) ⭐️ 8.0/10

China's eight departments issued a plan to crack down on illegal cross-border securities, futures, and fund operations, requiring existing investors to only sell and withdraw funds within a 2-year cleanup period. The CSRC has initiated investigations against Tiger Brokers, Futu, and Changqiao for conducting unapproved cross-border business. This regulatory action severely impacts cross-border fintech platforms and restricts Chinese investors' access to overseas markets, while promoting legal channels like Stock Connect, QDII, and Cross-border Wealth Management Connect. It signals China's tightening control over capital outflows and financial security. The plan sets a 2-year cleanup period during which only one-way selling and fund withdrawal are allowed for existing investors; all related domestic websites, trading software, and servers must be shut down after the period. The CSRC has issued administrative penalty notices against Tiger, Futu, and Changqiao, intending to confiscate all illegal gains and impose severe fines.

telegram · zaihuapd · May 22, 13:55

**Background**: Chinese investors have long used foreign brokerages like Tiger Brokers and Futu to trade Hong Kong and US stocks, bypassing China's capital controls. Legal channels for overseas investment include the Stock Connect program (allowing trading of Hong Kong stocks), QDII (Qualified Domestic Institutional Investor) funds, and the Cross-border Wealth Management Connect for residents in the Greater Bay Area. The crackdown aims to direct investors to these regulated channels.

<details><summary>References</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/665528722">一文搞懂港股通开通条件及交易规则 - 知乎</a></li>
<li><a href="https://grokipedia.com/page/qualified_domestic_institutional_investor">Qualified Domestic Institutional Investor</a></li>
<li><a href="https://research.hktdc.com/tc/article/MTYyOTc5OTI0Ng">新版「 跨 境 理 財 通 」啓動 | 香港貿易發展局經貿研究</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#fintech`, `#cross-border investment`, `#China`, `#securities`

---

<a id="item-12"></a>
## [Cloudflare 25-Minute Global Outage Hits 28% of HTTP Traffic](https://t.me/zaihuapd/41527) ⭐️ 8.0/10

On December 5, 2025, Cloudflare experienced a 25-minute global outage from 08:47 to 09:12 UTC, affecting approximately 28% of HTTP traffic due to a flawed WAF update intended to patch a Next.js security vulnerability (CVE-2025-55182). This outage underscores the fragility of critical internet infrastructure when security patches are deployed without sufficient testing, impacting millions of users and businesses relying on Cloudflare's CDN and security services. Only customers using Cloudflare's older FL1 proxy with the Cloudflare Managed Ruleset enabled were affected, receiving HTTP 500 errors; the root cause was a Lua nil-pointer bug triggered by a killswitch applied to an execute-action rule.

telegram · zaihuapd · May 22, 16:15

**Background**: Cloudflare's FL1 proxy is an older generation of its reverse proxy infrastructure, while the Managed Ruleset provides pre-configured WAF rules maintained by Cloudflare's security team. The outage occurred when a configuration change to patch a Next.js vulnerability (CVE-2025-55182) exposed a Lua nil-pointer bug in the WAF rules engine, causing request failures.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.cloudflare.com/5-december-2025-outage/">Cloudflare outage on December 5, 2025</a></li>
<li><a href="https://www.ascii.co.uk/news/article/news-20251208-71fe2ccb/cloudflare-25-minute-outage-lua-nil-bug-in-waf-rules-engine">Cloudflare 25-Minute Outage: Lua Nil Bug in WAF Rules Engine</a></li>
<li><a href="https://convergedigest.com/cloudflare-outage-on-december-5-hits-28-of-global-http-traffic/">Cloudflare Outage on December 5 Hits 28% of Global HTTP ...</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#outage`, `#WAF`, `#security`, `#Next.js`

---

<a id="item-13"></a>
## [Shipping a laptop to a Ugandan refugee camp: bureaucratic ordeal](https://notesbylex.com/shipping-a-laptop-to-a-refugee-camp-in-uganda) ⭐️ 7.0/10

The author recounts the complex bureaucracy and corruption encountered when trying to ship a laptop to a refugee camp in Uganda, involving unexpected taxes, bribes, and logistical hurdles. This story highlights systemic barriers to delivering technology aid to underserved regions, revealing how corruption and inefficiency hinder development and increase costs for well-intentioned efforts. The author initially assumed standard shipping would work, but faced demands for import taxes, storage fees, and bribes, eventually requiring a local contact named Django to navigate the system.

hackernews · lexandstuff · May 22, 21:36 · [Discussion](https://news.ycombinator.com/item?id=48241997)

**Background**: International shipping of electronics typically involves customs declarations and taxes, but in many developing countries, additional bureaucratic layers and corruption are common. The author's experience illustrates the disconnect between Western logistical expectations and on-the-ground realities in countries like Uganda.

**Discussion**: Commenters noted the systemic corruption, praised Django's resilience, and suggested alternatives like hand-carrying items. One Ugandan commenter acknowledged the broken system but critiqued the author's hubris in assuming Western methods would work.

**Tags**: `#developing countries`, `#logistics`, `#bureaucracy`, `#corruption`, `#tech for good`

---

<a id="item-14"></a>
## [Why Japanese companies diversify so much](https://davidoks.blog/p/why-japanese-companies-do-so-many) ⭐️ 7.0/10

This article explains that Japanese companies' extensive diversification is driven by lifetime employment, firm-specific skills, and governance that prioritizes employee interests over shareholders. It provides a cultural and structural explanation for a distinctive feature of Japanese corporate strategy, contrasting with Western focus on shareholder value and specialization. The author argues that the system only works if the company is insulated from outside pressure, allowing it to exist for its employees rather than shareholders.

hackernews · d0ks · May 22, 15:22 · [Discussion](https://news.ycombinator.com/item?id=48237163)

**Background**: Japanese lifetime employment (shushin koyo) is a system where employees expect to stay with one company until retirement, and companies invest heavily in firm-specific skills. This encourages diversification as a way to retain and redeploy employees across different business lines.

<details><summary>References</summary>
<ul>
<li><a href="https://jobs.guidable.co/en/articles/what-is-the-current-state-of-japans-lifetime-employment-system">What Is the Current State of Japan ’s Lifetime | Guidable Jobs</a></li>
<li><a href="https://www.zenterninternships.com/blog/how-japanese-companies-handle-skill-development">How Japanese Companies Handle Skill Development</a></li>

</ul>
</details>

**Discussion**: Commenters note that Western companies also diversified in the past, and that the Japanese system creates low job fluidity, making mid-career hiring difficult. Some East Asian readers caution against romanticizing the model.

**Tags**: `#business-culture`, `#organizational-structure`, `#japan`, `#corporate-strategy`, `#management`

---

<a id="item-15"></a>
## [Deno 2.8 released with new pack command and permission debate](https://deno.com/blog/v2.8) ⭐️ 7.0/10

Deno 2.8 introduces a new `deno pack` command for packaging applications, along with incremental improvements to performance and the permission model. The release continues to emphasize security and native TypeScript support. This release fuels ongoing community debate about Deno's unique permission model versus the ecosystem convenience of Node.js and the speed of Bun. The comparison highlights the evolving JavaScript runtime landscape where security, performance, and developer experience are key differentiators. The `deno pack` command simplifies packaging Deno projects without requiring external tools. The permission model remains granular but does not extend to module-level controls, a point some users wish for.

hackernews · roflcopter69 · May 22, 11:23 · [Discussion](https://news.ycombinator.com/item?id=48234380)

**Background**: Deno is a JavaScript/TypeScript runtime built on V8 and Rust, designed to address Node.js shortcomings such as security and module management. Its permission model requires explicit opt-in for file, network, and environment access, enhancing security but sometimes complicating usage. Bun, a newer runtime, focuses on speed and all-in-one tooling, while Node.js remains the established standard.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.deno.com/runtime/fundamentals/security/">Security and permissions - Deno</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community sentiment is generally positive toward Deno's security and ideology, but users question its ecosystem growth relative to Bun and Node. Some praise the `deno pack` addition, while others express concern about funding sustainability and feature parity.

**Tags**: `#Deno`, `#JavaScript runtime`, `#TypeScript`, `#permission model`, `#Node.js`

---

<a id="item-16"></a>
## [Kanbots: open-source Kanban app runs parallel AI agents on every card](https://www.kanbots.dev/) ⭐️ 7.0/10

Kanbots is a newly launched open-source desktop Kanban application that allows users to dispatch parallel AI agents on each task card, each operating in its own Git worktree, and supports an autopilot mode where agents automatically split and execute work. This tool pushes the boundaries of project management by integrating AI agents directly into Kanban workflows, potentially enabling massive task parallelization. However, it sparks debate about whether it violates core Kanban principles like limiting work-in-progress and respecting flow. Kanbots is local-first and serverless, storing everything in a .kanbots/ directory next to the repository (SQLite, configs, worktrees), with no cloud account or telemetry. Each agent runs in an isolated worktree, and the autopilot feature uses personas to split and review work autonomously.

hackernews · vitriapp · May 22, 18:17 · [Discussion](https://news.ycombinator.com/item?id=48239413)

**Background**: Kanban is an Agile project management method that visualizes workflow, limits work-in-progress (WIP), and focuses on continuous delivery. Traditional Kanban boards manage card flow to avoid overloading the system. This new tool challenges that by encouraging parallel execution on many cards simultaneously.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kanbots.dev/">KanBots — a kanban that runs parallel agents</a></li>
<li><a href="https://topaihubs.com/articles/the-rise-of-parallel-ai-agents-in-open-source-kanban-a-new-era-for-productivity">The Rise of Parallel AI Agents in Open Source Kanban: A New ...</a></li>
<li><a href="https://teamhood.com/kanban-resources/kanban-principles/">4 Kanban Principles & 6 Practices for Better Workflows - Teamhood What is Kanban - Principles and Implementation - GeeksforGeeks Kanban Principles: The 4 Core Principles & 6 Key Practices 6 Core Kanban principles — and How to Apply Them - Miro Core Principles of Kanban: A Complete Guide for Agile Teams Kanban Principles & Practices: Guide to Agile Workflow</a></li>

</ul>
</details>

**Discussion**: Community members express mixed feelings: some criticize the tool for contradicting Kanban's core principles by encouraging parallel work, while others are concerned about the feasibility of reviewing AI-generated code and managing isolated worktrees. There is also comparison to Vibe Kanban, which faced abandonment issues.

**Tags**: `#kanban`, `#AI agents`, `#open-source`, `#project management`

---

<a id="item-17"></a>
## [FBI Director's Apparel Site Hit by ClickFix Malware Attack](https://www.pcmag.com/news/kash-patels-apparel-site-is-trying-to-trick-visitors-into-installing-malware) ⭐️ 7.0/10

The FBI director's apparel website, BasedApparel.com, was compromised with a ClickFix attack that tricks visitors into downloading malware. This incident underscores the real-world prevalence of ClickFix attacks and highlights that even high-profile websites can be compromised, posing a significant security risk to visitors. The ClickFix attack specifically targeted macOS users by presenting a fake 'verify you are human' prompt that would download a malicious payload if clicked.

hackernews · bilalq · May 23, 00:34 · [Discussion](https://news.ycombinator.com/item?id=48243293)

**Background**: A ClickFix attack is a social engineering technique where attackers trick users into running a system command to fix a nonexistent problem. In this case, the fake CAPTCHA prompt deceives visitors into executing a command that downloads malware. Such attacks have been increasingly reported by security firms like Microsoft.

<details><summary>References</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/security/blog/2025/08/21/think-before-you-clickfix-analyzing-the-clickfix-social-engineering-technique/">Think before you Click ( Fix ): Analyzing the ClickFix social engineering...</a></li>
<li><a href="https://hoxhunt.com/blog/what-is-a-clickfix-attack">What Is a ClickFix Attack ? What Security Teams Need to... - Hoxhunt</a></li>

</ul>
</details>

**Discussion**: Community comments expressed surprise and humor at the situation, with some questioning why the FBI director has a merchandise store. One user clarified that the store was owned by Kash Patel before he became FBI director, and the attack targeted macOS users.

**Tags**: `#security`, `#malware`, `#phishing`, `#FBI`, `#ClickFix`

---

<a id="item-18"></a>
## [FTC Fines Cox Media Group $1M for Fake AI Listening Ads](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 7.0/10

The FTC ordered Cox Media Group, MindSift, and 1010 Digital Works to pay nearly $1 million for falsely claiming their 'Active Listening' AI service could target ads based on real-time voice data from smart devices. This settlement marks a significant enforcement action against deceptive AI marketing, reinforcing that companies cannot mislead consumers about invasive surveillance capabilities without facing penalties. The FTC revealed that the service never actually listened to conversations; instead, the companies resold email lists from data brokers at a high markup. The FTC also warned that burying opt-in consent in terms of service does not constitute adequate consent.

rss · Simon Willison · May 22, 04:48

**Background**: For years, a conspiracy theory has persisted that smartphones and smart speakers secretly listen to conversations for ad targeting. Cox Media Group's 2024 marketing materials for 'Active Listening' fueled these fears, claiming to use voice data for hyper-targeted ads. The FTC investigation debunked the technical feasibility and revealed the claims were fraudulent.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wired.com/story/creepy-listening-tool-for-targeted-ads-didnt-actually-work-ftc-says/">‘Creepy’ Listening Tool for Targeted Ads Didn’t Actually Work ...</a></li>
<li><a href="https://thecyberexpress.com/ftc-ai-powered-active-listening-case/">AI-Powered Marketing Service “Active Listening” Deceived ...</a></li>
<li><a href="https://cipaworld.com/2026/05/21/ftc-to-require-cox-media-group-two-other-firms-to-pay-nearly-1-million-to-settle-charges-they-deceived-customers-about-active-listening-ai-powered-marketing-service/">FTC Settles with Marketing Firms for Deceptive AI Advertising</a></li>

</ul>
</details>

**Tags**: `#AI`, `#privacy`, `#FTC`, `#advertising`, `#deception`

---

<a id="item-19"></a>
## [Zhipu AI Launches GLM-5.1-HighSpeed at 400 Tokens/s](https://docs.bigmodel.cn/cn/guide/models/text/glm-5.1-highspeed) ⭐️ 7.0/10

Zhipu AI has released GLM-5.1-HighSpeed, a high-speed version of its GLM-5.1 model, achieving an output speed of 400 tokens per second, and is now available to select enterprise customers via the BigModel open platform. This significant speed improvement enables real-time applications such as coding agents, voice assistants, and live customer service, positioning GLM-5.1-HighSpeed as a competitive option for low-latency AI tasks in the enterprise market. The model supports Function Call, JSON structured output, and the Model Context Protocol (MCP), making it ideal for low-latency scenarios like multi-turn code generation, real-time UI building, and operational Q&A; however, access is restricted to enterprise customers.

telegram · zaihuapd · May 22, 04:45

**Background**: GLM-5.1 is a large language model by Zhipu AI, one of China's leading AI companies. Function Calling allows the model to invoke external APIs or functions to perform tasks beyond text generation. MCP (Model Context Protocol) is a standardized protocol that simplifies integration with external tools and data sources, similar to a universal adapter for AI models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://www.getfrontline.ai/glossary/what-is-function-calling">Frontline | Glossary | Function Calling</a></li>
<li><a href="https://gradientflow.com/expanding-ai-horizons-the-rise-of-function-calling-in-llms/">Expanding AI Horizons: The Rise of Function Calling ... - Gradient Flow</a></li>

</ul>
</details>

**Tags**: `#GLM`, `#AI model`, `#low-latency`, `#enterprise`, `#function call`

---

<a id="item-20"></a>
## [Microsoft widely promotes Claude Code internally, encourages non-technical staff](https://t.me/zaihuapd/41535) ⭐️ 7.0/10

Microsoft is broadly rolling out Anthropic's Claude Code across its core engineering teams, including the CoreAI team and the Experiences & Devices division responsible for Windows, Microsoft 365, and Outlook. The company is requiring software engineers to use both Claude Code and GitHub Copilot and provide comparative feedback, while also encouraging employees without programming experience to use Claude Code for prototyping. This move signals a significant shift in Microsoft's AI coding strategy, as it embraces a competitor's tool over its own GitHub Copilot in some contexts. It could reshape the AI-assisted development landscape and influence how other enterprises adopt multiple AI coding assistants for different user groups. The promotion covers not only experienced engineers but also non-technical staff for prototyping. Microsoft engineers are now required to provide direct feedback comparing Claude Code and GitHub Copilot, which are competing AI coding tools from Anthropic and Microsoft respectively.

telegram · zaihuapd · May 23, 06:05

**Background**: Claude Code is an AI-powered coding agent developed by Anthropic, the company behind the Claude large language model. GitHub Copilot, Microsoft's own AI coding assistant, is integrated into its development ecosystem. By testing both tools internally, Microsoft aims to evaluate their relative strengths and potentially improve its own offerings.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**Tags**: `#微软`, `#Claude Code`, `#AI编程`, `#GitHub Copilot`, `#行业动态`

---