---
layout: default
title: "Horizon Summary: 2026-05-23 (EN)"
date: 2026-05-23
lang: en
---

> From 37 items, 11 important content pieces were selected

---

1. [Anthropic Glasswing Update: 90.6% AI Vulnerability Validation Rate](#item-1) ⭐️ 9.0/10
2. [ByteDance Open-Sources Lance: 3B Unified Multimodal Model](#item-2) ⭐️ 9.0/10
3. [Apple open-sources corecrypto with formal verification for quantum-safe algorithms](#item-3) ⭐️ 9.0/10
4. [Antigravity 2.0 Tops OpenSCAD Architectural 3D LLM Benchmark](#item-4) ⭐️ 8.0/10
5. [yt-dlp deprecates Bun support, citing compatibility and security](#item-5) ⭐️ 8.0/10
6. [Anna's Archive asks LLMs to donate for using its data](#item-6) ⭐️ 8.0/10
7. [DeepSeek Makes V4 Pro Price Cut Permanent](#item-7) ⭐️ 8.0/10
8. [AI memory demand raises consumer electronics prices](#item-8) ⭐️ 8.0/10
9. [FTC Fines Cox Media Group $930K for Fake AI Listening Service](#item-9) ⭐️ 8.0/10
10. [China Cracks Down on Illegal Cross-Border Securities, Investigating Tiger, Futu, Changqiao](#item-10) ⭐️ 8.0/10
11. [Microsoft Internally Rolls Out Claude Code, Pitches vs Copilot](#item-11) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Anthropic Glasswing Update: 90.6% AI Vulnerability Validation Rate](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 9.0/10

Anthropic released an initial update for Project Glasswing, reporting that out of 1,752 high- or critical-rated vulnerability assessments by independent security firms, 90.6% were confirmed as true positives, with 62.4% deemed high or critical severity. This demonstrates that AI-powered vulnerability detection can achieve high accuracy in real-world codebases, potentially transforming automated security auditing for critical infrastructure and large-scale software projects. The true positive rate of 90.6% and high/critical severity confirmation of 62.4% were based on independent assessments by six security research firms. The update covers only high-severity vulnerability candidates reported so far.

hackernews · louiereederson · May 22, 19:31 · [Discussion](https://news.ycombinator.com/item?id=48240419)

**Background**: Project Glasswing is an Anthropic initiative using Claude, their AI assistant, to analyze source code for security vulnerabilities in critical open-source projects. Traditional static analysis tools can catch common flaws but often miss complex logic errors or hard-to-detect vulnerabilities. This update provides early evidence of AI's effectiveness in supplementing existing security workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/glasswing-initial-update">Project Glasswing: An initial update - Anthropic</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing: Securing critical software for the AI era - Anthropic</a></li>
<li><a href="https://www.anthropic.com/project/glasswing">Project Glasswing - Anthropic</a></li>

</ul>
</details>

**Discussion**: Comments are mixed: some users share positive experiences with similar tools achieving ~90% accuracy, while others, including curl's maintainer Daniel Stenberg, express skepticism about the tool's improvement over existing static analyzers. Additionally, some question whether teams should first adopt cheaper static analysis before investing in expensive LLM-based tools.

**Tags**: `#AI safety`, `#cybersecurity`, `#code analysis`, `#Anthropic`

---

<a id="item-2"></a>
## [ByteDance Open-Sources Lance: 3B Unified Multimodal Model](https://mp.weixin.qq.com/s/Xbfq72cr1796RZxJIs3L1A) ⭐️ 9.0/10

ByteDance has open-sourced Lance, a 3B-parameter unified multimodal model that handles image understanding, video understanding, image generation, video generation, and cross-modal editing in a single architecture. Lance achieves state-of-the-art results on GenEval and VBench benchmarks with only 3B parameters, demonstrating that efficient unified multimodal models are feasible and could reduce dependency on larger, resource-intensive models. Lance employs a dual-stream mixture-of-experts architecture initialized from Qwen2.5-VL and uses modality-aware position encoding to resolve sequence boundary confusion. The model is released under the Apache 2.0 license on Hugging Face.

telegram · zaihuapd · May 22, 06:40

**Background**: Multimodal AI models typically require separate models for understanding (e.g., captioning) and generation (e.g., image synthesis), leading to fragmented pipelines. Lance unifies these tasks in a single model by using a shared context with specialized expert pathways, enabling joint learning and efficient inference.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.18678">Lance: Unified Multimodal Modeling by Multi-Task Synergy</a></li>
<li><a href="https://www.marktechpost.com/2026/05/21/one-model-three-modalities-bytedance-releases-lance-for-image-and-video-understanding-generation-and-editing/">One Model, Three Modalities: ByteDance Releases Lance for ...</a></li>
<li><a href="https://www.mlhive.com/2026/05/bytedance-lance-unified-multimodal-architecture">Why ByteDance Lance is the Next Evolution in Multimodal AI</a></li>

</ul>
</details>

**Tags**: `#multimodal`, `#open-source`, `#image-generation`, `#video-generation`, `#ByteDance`

---

<a id="item-3"></a>
## [Apple open-sources corecrypto with formal verification for quantum-safe algorithms](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

On May 22, Apple open-sourced the corecrypto library, which includes implementations of the quantum-safe algorithms ML-KEM and ML-DSA, along with end-to-end formal verification proofs that mathematically guarantee their correctness. This marks a significant step for deploying post-quantum cryptography at scale: the formal verification ensures that the implementations precisely match NIST standards, providing a high level of assurance for the billions of Apple devices that rely on corecrypto for secure communications. The formal verification covers both the C implementation and hand-optimized ARM64 assembly code, aligning with NIST's ML-KEM (FIPS 203) and ML-DSA (FIPS 204) standards. Apple also released custom verification tools and Isabelle theory libraries for independent expert review.

telegram · zaihuapd · May 23, 04:49

**Background**: ML-KEM (Module-Lattice-Based Key-Encapsulation Mechanism) and ML-DSA (Module-Lattice-Based Digital Signature Algorithm) are post-quantum cryptographic algorithms standardized by NIST in 2024 to resist attacks from future quantum computers. Formal verification uses mathematical proofs, often via theorem provers like Isabelle, to ensure that code exactly implements its specification, eliminating entire classes of bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ML-KEM">ML-KEM - Wikipedia</a></li>
<li><a href="https://www.nist.gov/news-events/news/2024/08/nist-releases-first-3-finalized-post-quantum-encryption-standards">NIST Releases First 3 Finalized Post-Quantum Encryption ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isabelle_(proof_assistant)">Isabelle (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#cryptography`, `#formal verification`, `#quantum-safe`, `#Apple`, `#open source`

---

<a id="item-4"></a>
## [Antigravity 2.0 Tops OpenSCAD Architectural 3D LLM Benchmark](https://modelrift.com/blog/openscad-llm-benchmark/) ⭐️ 8.0/10

A new benchmark for LLM-generated OpenSCAD architectural models has been topped by Google's Antigravity 2.0 agent, which produced a model of the Pantheon with impressive interior ceiling coffers visible through the oculus. This benchmark introduces a novel evaluation for AI code generation in 3D modeling, highlighting the potential of LLMs to create complex architectural geometry. The interior detailing achieved by Antigravity 2.0 demonstrates a significant step toward autonomous 3D design. The benchmark uses the Pantheon as a single test case with one attempt per model, which some commenters argue is insufficient for generalization. Antigravity 2.0 was the only autonomous agent to implement the Pantheon's signature interior ceiling pattern.

hackernews · jetter · May 22, 10:38 · [Discussion](https://news.ycombinator.com/item?id=48234090)

**Background**: OpenSCAD is a free, script-based 3D CAD software that uses its own programming language to define geometric shapes. This makes it suitable for LLMs to generate 3D models as code. The benchmark evaluates how well AI agents can produce accurate architectural models in OpenSCAD.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenSCAD">OpenSCAD</a></li>
<li><a href="https://antigravity.google/blog/introducing-google-antigravity-2-0">Google Antigravity Blog: introducing-google- antigravity - 2 - 0</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users are impressed by the interior detailing, while others criticize Antigravity's forced replacement of Gemini CLI and IDE update issues. Several commenters also question the benchmark's design, noting that a single test case and one attempt do not provide robust evidence.

**Tags**: `#LLM`, `#OpenSCAD`, `#3D modeling`, `#benchmark`, `#AI code generation`

---

<a id="item-5"></a>
## [yt-dlp deprecates Bun support, citing compatibility and security](https://github.com/yt-dlp/yt-dlp/issues/16766) ⭐️ 8.0/10

yt-dlp has deprecated support for the Bun JavaScript runtime, citing foreseeable compatibility and security issues. The decision was made in response to Bun's ongoing rewrite from Zig to Rust, which introduces uncertainty. This deprecation affects users who rely on yt-dlp with Bun, potentially forcing them to switch to Node.js or Deno. It also highlights growing tensions in the open-source community around runtime choices and the impact of corporate acquisitions (Bun's acquisition by Anthropic) on project direction. The deprecation was announced in GitHub issue #16766, with over 450 comments. The yt-dlp maintainers did not provide specific technical details but mentioned security concerns tied to Bun's Rust rewrite. The rewrite has not yet been released, leading some community members to question the engineering basis of the decision.

hackernews · tamnd · May 22, 17:24 · [Discussion](https://news.ycombinator.com/item?id=48238789)

**Background**: yt-dlp is a popular open-source YouTube downloader. Bun is a fast, all-in-one JavaScript runtime originally written in Zig, designed as a drop-in replacement for Node.js. Recently, Oven-sh (the company behind Bun) was acquired by Anthropic, and Bun announced a rewrite from Zig to Rust, sparking concerns about codebase maintainability and security.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>

</ul>
</details>

**Discussion**: Community opinions are divided. Some users support the decision, noting that maintaining compatibility with a rapidly changing runtime is unsustainable. Others, like user johnfn, argue the move is more political than technical, as the Rust rewrite hasn't landed yet. User hootz expressed sadness about Bun's trajectory after the Anthropic acquisition.

**Tags**: `#yt-dlp`, `#Bun`, `#runtime`, `#deprecation`, `#Rust rewrite`

---

<a id="item-6"></a>
## [Anna's Archive asks LLMs to donate for using its data](https://annas-archive.gl/blog/llms-txt.html) ⭐️ 8.0/10

Anna's Archive published a blog post humorously addressing LLMs, asking them to donate in exchange for using their copyrighted data, highlighting the ethical and legal issues of AI training data sourcing. This post reignites the debate on AI training data ethics, copyright infringement, and the role of shadow libraries, potentially impacting AI companies' data acquisition practices and the open knowledge movement. The blog post is humorous but carries a serious message, referencing how LLMs likely trained on Anna's Archive data. Anna's Archive has faced criticism for reportedly charging AI companies for expedited access to pirated materials.

hackernews · janandonly · May 22, 11:28 · [Discussion](https://news.ycombinator.com/item?id=48234413)

**Background**: Shadow libraries are unauthorized online repositories that host free copies of paywalled content like books and academic papers. Anna's Archive is a metasearch engine aggregating records from Z-Library, Sci-Hub, and Library Genesis, launched in 2022 after Z-Library was taken down.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anna's_Archive">Anna's Archive - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Shadow_library">Shadow library - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Comments show mixed reactions: some find the request humorous and support Anna's Archive for helping students, while others criticize it for selling access to AI companies, highlighting the tension between free knowledge and ethical concerns.

**Tags**: `#AI training data`, `#copyright`, `#piracy`, `#data ethics`, `#LLM`

---

<a id="item-7"></a>
## [DeepSeek Makes V4 Pro Price Cut Permanent](https://api-docs.deepseek.com/quick_start/pricing) ⭐️ 8.0/10

DeepSeek has permanently reduced the API pricing for its V4 Pro model to one-quarter of the original price, making the previous 75% discount permanent after May 31, 2026. This aggressive pricing strategy could disrupt the AI API market, making high-performance models more accessible to developers and smaller companies, while putting pressure on competitors to match the low cost. The price cut applies to the V4 Pro model after a promotional period ending on May 31, 2026; additionally, input cache hit prices have been reduced to as low as 0.8% of the input price for V4 Pro, offering extremely low costs for cached requests.

hackernews · Tiberium · May 22, 15:59 · [Discussion](https://news.ycombinator.com/item?id=48237663)

**Background**: DeepSeek is a Chinese AI research company known for open-sourcing models and publishing research. Its V4 Pro is a large language model (LLM) that competes with offerings from OpenAI, Google, and others. API pricing is typically per token, and caching discounts reward repeated use of the same prompts.

**Discussion**: Commenters expressed excitement over the value, with many noting the model's high quality and low price. However, some raised concerns about privacy, as DeepSeek's policy allows use of user data for training, and questioned the unit economics behind the cheap caching rates.

**Tags**: `#DeepSeek`, `#AI pricing`, `#API`, `#large language models`, `#machine learning`

---

<a id="item-8"></a>
## [AI memory demand raises consumer electronics prices](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

Memory manufacturers are reallocating wafer capacity from DDR and LPDDR to HBM to meet AI demand, reducing supply for consumer devices and driving up prices. This shift is already affecting sub-$100 smartphones. Consumer electronics, especially low-cost smartphones, will become significantly more expensive in the next few years, impacting affordability in developing regions. It also highlights how AI infrastructure investment indirectly strains unrelated markets. Only three companies produce DRAM wafers, and HBM consumes over three times the wafer capacity per gigabyte compared to DDR or LPDDR. HBM's wafer allocation is expected to rise from 2% to 20% by the end of 2026.

rss · Simon Willison · May 22, 22:01

**Background**: DRAM comes in three main types: DDR for desktops/servers, LPDDR for mobile/low-power devices, and HBM (High Bandwidth Memory) for GPUs used in AI. HBM uses 3D stacking and Through-Silicon Vias (TSVs) to provide high bandwidth, but requires significantly more wafer area per gigabyte. Memory manufacturers keep production tight to avoid oversupply, making them slow to add capacity.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://octopart.com/pulse/p/what-allocation-semiconductor-industry">What Is Allocation in the Semiconductor Industry? - Octopart</a></li>
<li><a href="https://uomolab.com/en/hbm-memory-technology-deep-dive-the-memory-revolution-in-the-ai-era/">HBM Memory Technology Deep Dive: The Memory Revolution in the ...</a></li>

</ul>
</details>

**Tags**: `#memory`, `#hardware`, `#AI`, `#semiconductors`, `#consumer electronics`

---

<a id="item-9"></a>
## [FTC Fines Cox Media Group $930K for Fake AI Listening Service](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 8.0/10

The FTC reached settlements totaling $930,000 with Cox Media Group, MindSift, and 1010 Digital Works for falsely marketing an 'Active Listening' AI-powered advertising service that they claimed listened to consumers via smart devices but actually resold email lists. This enforcement signals that the FTC is actively policing deceptive AI marketing claims, particularly those involving privacy-invasive technologies, setting a precedent for accountability in AI-powered advertising and consumer protection. The companies' 'Active Listening' service did not actually listen to conversations or use voice data; instead, it resold email lists from other data brokers at a significant markup. The FTC also clarified that mandatory terms-of-service agreements do not constitute adequate consent for such invasive data collection.

rss · Simon Willison · May 22, 04:48

**Background**: The 'Active Listening' concept was marketed as a service that used AI to capture real-time intent data from smart device microphones to target ads. This fed into a long-standing conspiracy theory that phones are always listening to serve ads. The FTC's action debunks this myth and reinforces that such practices would require explicit opt-in consent.

<details><summary>References</summary>
<ul>
<li><a href="https://thecyberexpress.com/ftc-ai-powered-active-listening-case/">AI-Powered Marketing Service “Active Listening” Deceived ...</a></li>
<li><a href="https://cipaworld.com/2026/05/21/ftc-to-require-cox-media-group-two-other-firms-to-pay-nearly-1-million-to-settle-charges-they-deceived-customers-about-active-listening-ai-powered-marketing-service/">FTC Settles with Marketing Firms for Deceptive AI Advertising</a></li>

</ul>
</details>

**Tags**: `#AI`, `#privacy`, `#FTC`, `#regulation`, `#ethics`

---

<a id="item-10"></a>
## [China Cracks Down on Illegal Cross-Border Securities, Investigating Tiger, Futu, Changqiao](https://mp.weixin.qq.com/s?__biz=MzA4NzAzMDgwMw==&amp;mid=2651090403&amp;idx=3&amp;sn=bca72a940ac72bef356f29b5b9576ac1&amp;chksm=8a1670281e2bc67d2df3608a313ba9fdaf0fcd2f43ce44475c6bf273b386af2e4f9d8e8e2e2b&amp;scene=0&amp;xtrack=1) ⭐️ 8.0/10

China's eight government departments jointly issued a remediation plan to crack down on illegal cross-border securities, futures, and fund operations, allowing only existing investors to sell and withdraw funds. The China Securities Regulatory Commission has filed investigations against Tiger Brokers, Futu, and Changqiao for illegal cross-border business operations. This regulatory action targets major fintech platforms that facilitate cross-border investing for mainland Chinese residents, affecting millions of users. It signals a stricter enforcement of capital controls and aims to channel offshore investments through legal avenues like Hong Kong Stock Connect and QDII. The plan sets a two-year centralized rectification period to clear existing business, after which domestic websites, trading software, and servers must be fully shut down. The CSFC has issued administrative penalty notices against Tiger, Futu, and Changqiao, intending to confiscate all illegal gains and impose severe penalties for unlicensed securities brokerage and margin trading.

telegram · zaihuapd · May 22, 08:26

**Background**: Cross-border securities trading by unlicensed foreign platforms has been a gray area in China, where capital controls restrict outward investments. Legal channels for mainland investors to access overseas markets include the Hong Kong Stock Connect (for stocks) and the Qualified Domestic Institutional Investor (QDII) scheme. The targeted platforms, such as Tiger Brokers and Futu, have popular apps that allow Chinese users to trade US and Hong Kong stocks, but they lack necessary regulatory approvals in China.

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/港股通/13611865">港股通（内地与香港股票市场交易互联互通机制）_百度百科 港股通交易规则全解：从时间、机制到费用，一文看懂实操要点 沪港通 - 上海证券交易所 港股通是什么?开通条件与流程全解析 (2025 最新版)|内地股市|融资融券... 港股通开户指南：条件、线上流程与费用全解析（2025版） 科普：什么是港股通？ “ 港股通 ”是沪深港通机制的重要组成部分，它为...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Qualified_Domestic_Institutional_Investor">Qualified Domestic Institutional Investor - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#fintech`, `#cross-border investing`, `#China`, `#securities`

---

<a id="item-11"></a>
## [Microsoft Internally Rolls Out Claude Code, Pitches vs Copilot](https://t.me/zaihuapd/41535) ⭐️ 8.0/10

Microsoft is widely deploying Anthropic's Claude Code across its key engineering teams, including CoreAI and the Experiences & Devices division, and encouraging non-technical employees to use it for prototyping. Engineers are required to use both Claude Code and GitHub Copilot and provide comparative feedback. This move signals a major shift in Microsoft's AI strategy, as it internally adopts a competitor's coding tool alongside its own Copilot, validating Claude Code's capabilities. It also highlights the broader trend of AI-assisted software development becoming accessible to non-technical users. Microsoft's software engineers must now use both Claude Code and GitHub Copilot and provide comparative feedback, though Microsoft commercially sells Copilot to customers. Claude Code is an agentic coding tool that can read codebases, edit files, run commands, and deliver committed code, making it accessible even to those without an engineering background.

telegram · zaihuapd · May 23, 06:05

**Background**: Claude Code is an AI-powered coding tool developed by Anthropic, the company behind the Claude series of large language models. Unlike traditional code assistants, Claude Code acts as an agent that can understand an entire codebase, make changes across files, and run tests. GitHub Copilot is Microsoft's own AI pair programmer powered by OpenAI's models. Microsoft's decision to internally test a competing product suggests a pragmatic approach to evaluating best-in-class AI tools.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Claude_Code">Claude Code</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://www.anthropic.com/product/claude-code">Claude Code | Anthropic's agentic coding system</a></li>

</ul>
</details>

**Tags**: `#AI coding`, `#Microsoft`, `#Claude Code`, `#GitHub Copilot`, `#industry trends`

---