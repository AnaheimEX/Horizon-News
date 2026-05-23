---
layout: default
title: "Horizon Summary: 2026-05-23 (EN)"
date: 2026-05-23
lang: en
---

> From 47 items, 21 important content pieces were selected

---

1. [Cloudflare 25-Minute Global Outage Affects 28% of HTTP Traffic](#item-1) ⭐️ 9.0/10
2. [Apple open-sources corecrypto with formal verifications for quantum-safe crypto](#item-2) ⭐️ 9.0/10
3. [Why Japanese companies diversify widely](#item-3) ⭐️ 8.0/10
4. [Anthropic's Glasswing Update: 90.6% True Positive Rate](#item-4) ⭐️ 8.0/10
5. [New Drug Shows Promise as Sleep Apnea Alternative to CPAP](#item-5) ⭐️ 8.0/10
6. [AI-Driven HBM Demand Drives Up Consumer Electronics Prices](#item-6) ⭐️ 8.0/10
7. [ByteDance Open-Sources 3B Multimodal Model Lance](#item-7) ⭐️ 8.0/10
8. [China Cracks Down on Illegal Cross-Border Securities Trading](#item-8) ⭐️ 8.0/10
9. [Tencent's Ximalaya Acquisition Approved with Condition to Drop Exclusive Audio Rights](#item-9) ⭐️ 8.0/10
10. [Bureaucratic hurdles in shipping laptop to Uganda refugee camp](#item-10) ⭐️ 7.0/10
11. [Microsoft cancels Claude Code licenses, pushes Copilot CLI](#item-11) ⭐️ 7.0/10
12. [CISA Data Leak Prompts Lawmaker Scrutiny](#item-12) ⭐️ 7.0/10
13. [Antigravity 2.0 Leads OpenSCAD Architectural 3D LLM Benchmark](#item-13) ⭐️ 7.0/10
14. [Open source Kanban app runs parallel AI agents on each card](#item-14) ⭐️ 7.0/10
15. [Datasette Agent: Conversational AI for Data Queries](#item-15) ⭐️ 7.0/10
16. [Zhipu AI Launches GLM-5.1 HighSpeed at 400 tokens/s](#item-16) ⭐️ 7.0/10
17. [Microsoft Widely Promotes Claude Code Internally, Asks for Copilot Comparison](#item-17) ⭐️ 7.0/10
18. [uv 0.11.16 released with Git archive deps and audit features](#item-18) ⭐️ 6.0/10
19. [Deno 2.8 Released with New 'deno pack' Command](#item-19) ⭐️ 6.0/10
20. [Forth-inspired language for building websites unveiled](#item-20) ⭐️ 6.0/10
21. [FTC Fines Cox Media Group for Fake AI Listening Service](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Cloudflare 25-Minute Global Outage Affects 28% of HTTP Traffic](https://t.me/zaihuapd/41527) ⭐️ 9.0/10

On December 5, 2025, Cloudflare experienced a 25-minute global outage that impacted approximately 28% of HTTP traffic, caused by a flawed WAF patch for the Next.js vulnerability CVE-2025-55182 (React2Shell). This outage is significant because Cloudflare is a major content delivery network (CDN) and security provider, and the incident disrupted a substantial portion of the web. It highlights the risks of rapid security patches and the cascading impact of vulnerabilities in widely used frameworks like Next.js. The outage primarily affected customers using the legacy FL1 proxy with Cloudflare Managed Rule Sets enabled. The flawed rule was part of an emergency response to CVE-2025-55182, a critical pre-authentication remote code execution vulnerability in React Server Components and Next.js.

telegram · zaihuapd · May 22, 16:15

**Background**: Cloudflare operates one of the world's largest content delivery networks (CDN). The FL1 proxy is an older version of Cloudflare's proxy infrastructure, which is being gradually replaced by a new Rust-based version (FL2). CVE-2025-55182 (React2Shell) is a critical vulnerability in React Server Components and Next.js exploited for remote code execution; it prompted urgent patches across the ecosystem. The flawed WAF rule intended to mitigate this vulnerability inadvertently caused the outage.

<details><summary>References</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/security/blog/2025/12/15/defending-against-the-cve-2025-55182-react2shell-vulnerability-in-react-server-components/">Defending against the CVE-2025-55182 (React2Shell) vulnerability in React Server Components | Microsoft Security Blog</a></li>
<li><a href="https://unit42.paloaltonetworks.com/cve-2025-55182-react-and-cve-2025-66478-next/">Exploitation of Critical Vulnerability in React Server Components (Updated December 12)</a></li>
<li><a href="https://www.wiz.io/blog/critical-vulnerability-in-react-cve-2025-55182">React2Shell (CVE-2025-55182): Critical React Vulnerability | Wiz Blog</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#outage`, `#CDN`, `#Next.js`, `#security`

---

<a id="item-2"></a>
## [Apple open-sources corecrypto with formal verifications for quantum-safe crypto](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

On May 22, Apple released the source code of its corecrypto library, including implementations of ML-KEM and ML-DSA with end-to-end formal verification proofs. These proofs mathematically confirm that the C code and hand-optimized ARM64 assembly exactly match the NIST standards. This is a landmark move for practical post-quantum security, as corecrypto is deployed on over 2.5 billion Apple devices. By open-sourcing the code and formal proofs, Apple sets a new standard for transparency and reliability in cryptographic implementations, which could influence the entire industry. The release includes not only the corecrypto source code but also custom verification tools and a library of Isabelle theories, allowing independent security experts to audit the proofs. The formal verification covers both C and ARM64 assembly, ensuring correctness at multiple levels.

telegram · zaihuapd · May 23, 04:49

**Background**: corecrypto is the low-level cryptographic library used by Apple's operating systems, providing primitives for Security framework, CryptoKit, and CommonCrypto. Formal verification uses mathematical reasoning (e.g., with the Isabelle theorem prover) to prove that code meets its specification, eliminating entire classes of bugs. ML-KEM (Module-Lattice Key Encapsulation Mechanism) and ML-DSA (Module-Lattice Digital Signature Algorithm) are post-quantum algorithms recently standardized by NIST to resist attacks from future quantum computers.

<details><summary>References</summary>
<ul>
<li><a href="https://security.apple.com/blog/formal-verification-corecrypto/">A blueprint for formal verification of Apple corecrypto - Apple Security Research</a></li>
<li><a href="https://github.com/apple/corecrypto">GitHub - apple/corecrypto: Apple corecrypto · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isabelle_(proof_assistant)">Isabelle (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#cryptography`, `#formal verification`, `#quantum-safe`, `#Apple`, `#open source`

---

<a id="item-3"></a>
## [Why Japanese companies diversify widely](https://davidoks.blog/p/why-japanese-companies-do-so-many) ⭐️ 8.0/10

The article 'Why Japanese companies do so many different things' explains that extensive diversification in Japanese firms is rooted in lifetime employment and firm-specific skills, which incentivize companies to retain and redeploy employees internally rather than lay them off. This analysis challenges the Western emphasis on corporate focus and shareholder value, offering a deeper understanding of alternative organizational models that prioritize employee stability. It provides valuable context for global business strategy and the persistence of diversification in Japan. Key details include that the system only works when firms are insulated from outside shareholder pressure, and that lifetime employment, though not universal, remains influential in large Japanese companies. The article also notes that Western firms historically diversified more than they do today.

hackernews · d0ks · May 22, 15:22 · [Discussion](https://news.ycombinator.com/item?id=48237163)

**Background**: Lifetime employment in Japan is a practice where employees join a company after graduation and remain until retirement, common in large firms. Firm-specific skills are knowledge and abilities that are valuable only within that particular company, making employees less mobile. These features encourage firms to invest heavily in employee training and to diversify as a way to retain staff during downturns. However, this system also reduces labor market fluidity and can create challenges for mid-career hires.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bls.gov/opub/mlr/1984/08/rpt4full.pdf">Lifetime employment in Japan : three models of the concept</a></li>
<li><a href="https://www.researchgate.net/publication/271739231_Occupational_Human_Capital_and_Wages_The_Role_of_Skills_Transferability_Across_Occupations">(PDF) Occupational Human Capital and Wages: The Role of Skills ...</a></li>
<li><a href="https://www.academia.edu/114823487/Shukko_in_Japanese_companies_and_its_economic_and_managerial_effects">(PDF) Shukko in Japanese companies and its economic and...</a></li>

</ul>
</details>

**Discussion**: Commenters offered diverse viewpoints: jdw64 cautioned against Western idealization of Japan, while BJones12 highlighted the article's core insight about employee-run firms. stymaar noted that Western companies also used to diversify more in the past, and unsignedint pointed out the downside of low job mobility in Japan.

**Tags**: `#Japanese business`, `#corporate strategy`, `#diversification`, `#organizational culture`, `#HN discussion`

---

<a id="item-4"></a>
## [Anthropic's Glasswing Update: 90.6% True Positive Rate](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 8.0/10

Anthropic released a progress update on Project Glasswing, reporting that its Claude Mythos Preview AI model achieved a 90.6% true positive rate and 62.4% high/critical severity findings in vulnerability detection, validated by six independent security research firms. This demonstrates that advanced AI can dramatically improve software vulnerability detection, potentially making codebases significantly more secure. It could shift industry practices toward relying on AI-assisted code review, especially for critical infrastructure. The model identified 1,752 high- or critical-severity vulnerabilities, of which 90.6% (1,587) were confirmed as true positives, and 62.4% (1,094) were rated high or critical. The validation was done by six independent security firms or by Anthropic in a small number of cases.

hackernews · louiereederson · May 22, 19:31 · [Discussion](https://news.ycombinator.com/item?id=48240419)

**Background**: Project Glasswing is an Anthropic initiative to deploy AI for cybersecurity, with Claude Mythos Preview as a specialized vulnerability detection model. Traditional static analysis tools catch common issues but often miss more complex or context-dependent vulnerabilities. LLMs like Claude can analyze code holistically, finding subtle flaws that rule-based tools overlook. The project includes a $100M commitment in model usage credits for participants.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>
<li><a href="https://stable-learn.com/en/anthropic-glasswing-project/">Anthropic Drops a 'Nuclear Bomb': AI Vulnerability Detection ...</a></li>

</ul>
</details>

**Discussion**: User mdeeks praised Codex Security (likely linked to Mythos) as highly accurate (~90%) and essential. However, curl maintainer Daniel Steinberg expressed skepticism, stating he saw no evidence of significant improvement over existing tools. Others debated the cost-effectiveness compared to static analysis.

**Tags**: `#AI`, `#security`, `#vulnerability detection`, `#Anthropic`, `#code analysis`

---

<a id="item-5"></a>
## [New Drug Shows Promise as Sleep Apnea Alternative to CPAP](https://temertymedicine.utoronto.ca/news/how-decades-sleep-research-led-new-sleep-apnea-drug) ⭐️ 8.0/10

Researchers have developed a new drug for sleep apnea based on decades of sleep research, offering a potential alternative to CPAP therapy. If approved, this drug could provide relief for millions of sleep apnea patients who struggle with CPAP compliance, and reduce the long-term health risks associated with untreated apnea. The drug reportedly reduces apnea-hypopnea index (AHI) events by about 4 per hour, which may be more suitable for mild cases; side effects and long-term efficacy remain under investigation.

hackernews · colinprince · May 22, 22:05 · [Discussion](https://news.ycombinator.com/item?id=48242278)

**Background**: Sleep apnea is a disorder where breathing repeatedly stops during sleep, often treated with a CPAP machine that delivers pressurized air. However, many patients find CPAP uncomfortable and discontinue use. A drug that targets the underlying mechanism could dramatically improve treatment adherence.

**Discussion**: Commenters express mixed reactions: some are excited about a drug alternative to CPAP, while others note that the modest reduction in AHI events (about 4) may only help mild cases. Personal experiences with CPAP and alternative treatments like posture correction are also shared.

**Tags**: `#sleep apnea`, `#drug research`, `#medical breakthrough`, `#health tech`, `#CPAP alternative`

---

<a id="item-6"></a>
## [AI-Driven HBM Demand Drives Up Consumer Electronics Prices](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

Memory manufacturers are reallocating wafer capacity from DDR and LPDDR to HBM, with HBM's share expected to reach 20% by end of 2026, up from 2%. This shift is causing price increases for consumer electronics, especially sub-$100 smartphones. This repricing affects billions of consumers, particularly in price-sensitive markets like Africa and South Asia, and signals a structural shift in the semiconductor industry driven by AI demand. A single gigabyte of HBM consumes more than three times the wafer capacity of a gigabyte of DDR or LPDDR. Memory companies intentionally under-provision fabrication capacity to avoid extinction, further constraining supply.

rss · Simon Willison · May 22, 22:01

**Background**: Memory chips are manufactured on silicon wafers, with fixed processing capacity per fab. High-Bandwidth Memory (HBM) is a 3D-stacked DRAM technology that offers high data bandwidth and low power, essential for AI accelerators like GPUs. The surge in AI data centers has dramatically increased HBM demand, squeezing wafer allocation for other memory types.

<details><summary>References</summary>
<ul>
<li><a href="https://luna3.ai/what-is-hbm-memory">What Is HBM Memory ? The Bottleneck Behind Every AI Chip</a></li>
<li><a href="https://www.linkedin.com/posts/techi_aichips-memoryshortage-hbm-activity-7419037939961323520-UqKt">AI Chip Demand Triggers Global Memory Shortage | LinkedIn</a></li>
<li><a href="https://www.formfactor.com/blog/2026/high-bandwidth-memory-testing-why-early-test-strategies-are-critical-for-yield-cost-and-performance/">High-Bandwidth Memory Testing – Why Early Test Strategies Are...</a></li>

</ul>
</details>

**Tags**: `#memory shortage`, `#AI`, `#consumer electronics`, `#hardware`, `#supply chain`

---

<a id="item-7"></a>
## [ByteDance Open-Sources 3B Multimodal Model Lance](https://mp.weixin.qq.com/s/Xbfq72cr1796RZxJIs3L1A) ⭐️ 8.0/10

ByteDance has released Lance, a lightweight multimodal model with 3 billion activated parameters that natively unifies image and video understanding and generation tasks. It can output text, images, and videos in a single framework. This open-source release under Apache 2.0 license significantly lowers the barrier for developers and researchers to experiment with unified multimodal AI, potentially accelerating innovation in content creation and multimodal understanding. Lance employs a shared context and dual-stream expert architecture, using Qwen2.5-VL and Wan2.2 encoders for understanding and generation respectively, with modality-aware positional encoding to resolve sequence boundary confusion. It achieves state-of-the-art results on benchmarks like GenEval for image generation and VBench for video generation.

telegram · zaihuapd · May 22, 06:40

**Background**: Multimodal AI models that both understand and generate multiple modalities (text, image, video) typically require separate systems or large parameter counts. Lance achieves unification with only 3B active parameters by leveraging a dual-stream design where understanding and generation share context but use specialized encoders. Qwen2.5-VL is a vision-language model for understanding, while Wan2.2 is an open-source MoE video generation model.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.comfy.org/tutorials/image/qwen/qwen-image-edit">Qwen -Image-Edit ComfyUI Native Workflow Example - ComfyUI</a></li>
<li><a href="https://wan22.io/">Wan 2 . 2 - Open Source MoE Video Generation | Every Shot... | wan22.io</a></li>

</ul>
</details>

**Tags**: `#multimodal`, `#open-source`, `#ByteDance`, `#image generation`, `#video generation`

---

<a id="item-8"></a>
## [China Cracks Down on Illegal Cross-Border Securities Trading](https://mp.weixin.qq.com/s?__biz=MzA4NzAzMDgwMw==&amp;mid=2651090403&amp;idx=3&amp;sn=bca72a940ac72bef356f29b5b9576ac1&amp;chksm=8a1670281e2bc67d2df3608a313ba9fdaf0fcd2f43ce44475c6bf273b386af2e4f9d8e8e2e2b&amp;scene=0&amp;xtrack=1) ⭐️ 8.0/10

Eight Chinese government departments jointly issued a plan to crack down on illegal cross-border securities, futures, and fund operations, allowing existing investors only to sell and withdraw funds. The China Securities Regulatory Commission (CSRC) has launched investigations into Tiger Brokers, Futu, and Changqiao for unauthorized cross-border business. This regulatory action directly affects millions of Chinese investors using offshore trading platforms and signals a firm stance against unlicensed cross-border financial services. It also promotes the use of legal channels like Stock Connect, QDII, and Cross-boundary Wealth Management Connect, shaping the future of China's capital account openness. The plan includes a two-year centralized rectification period during which only sell-only and fund withdrawal operations are allowed for existing investors. After the period, all related domestic websites, trading software, and supporting servers must be shut down. The CSRC has issued pre-penalty notices to the investigated entities, seeking to confiscate all illegal gains and impose severe penalties.

telegram · zaihuapd · May 22, 08:26

**Background**: Chinese regulators have long restricted cross-border securities trading by domestic investors to licensed channels such as Shanghai-Hong Kong and Shenzhen-Hong Kong Stock Connect (known as '港股通'), QDII (Qualified Domestic Institutional Investor) funds, and the Cross-boundary Wealth Management Connect in the Greater Bay Area. These mechanisms allow limited, regulated access to overseas markets while maintaining capital controls. In recent years, platforms like Tiger Brokers and Futu have grown popular by offering direct access to US and Hong Kong stocks, circumventing these rules and raising regulatory concerns over investor protection and capital flow monitoring.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-cn/沪港通">沪港通 - 维基百科，自由的百科全书</a></li>
<li><a href="https://baike.baidu.com/item/港股通/13611865">港股通</a></li>
<li><a href="https://zh.wikipedia.org/zh-sg/跨境理财通">跨境理财通 - 维基百科，自由的百科全书</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#cross-border trading`, `#China`, `#fintech`, `#securities`

---

<a id="item-9"></a>
## [Tencent's Ximalaya Acquisition Approved with Condition to Drop Exclusive Audio Rights](https://mp.weixin.qq.com/s/xnx31SOS6NMozZXnHeaaQg) ⭐️ 8.0/10

China's State Administration for Market Regulation approved Tencent's acquisition of Ximalaya, but mandated that Tencent end all exclusive online audio copyright agreements. This decision may break down exclusive content barriers in the online audio market, fostering competition and making it easier for users to listen across platforms. Tencent must commit to not entering into or indirectly establishing any new exclusive licensing agreements, and must terminate existing exclusive contracts within a specified deadline.

telegram · zaihuapd · May 22, 10:33

**Background**: Ximalaya is one of China's largest online audio platforms with a vast library of exclusive content. Tencent had previously invested in Ximalaya, and this acquisition approval with antitrust conditions reflects China's tightening regulatory stance on content exclusivity in digital platforms.

**Tags**: `#antitrust`, `#regulation`, `#audio streaming`, `#Tencent`, `#Ximalaya`

---

<a id="item-10"></a>
## [Bureaucratic hurdles in shipping laptop to Uganda refugee camp](https://notesbylex.com/shipping-a-laptop-to-a-refugee-camp-in-uganda) ⭐️ 7.0/10

The author recounts the lengthy, corrupt, and costly process of shipping a laptop to a colleague in a Ugandan refugee camp, including multiple customs delays and bribe demands. This story illustrates the systemic inefficiencies and corruption that hinder the delivery of essential technology and aid to developing regions, impacting humanitarian work and local economies. The laptop eventually arrived after months of effort, with the recipient Django remaining grateful and positive throughout the ordeal, highlighting his resilience.

hackernews · lexandstuff · May 22, 21:36 · [Discussion](https://news.ycombinator.com/item?id=48241997)

**Background**: Shipping electronics to developing countries often involves complex customs rules and unofficial fees. Many expatriates and aid workers resort to hand-carrying items to avoid such hassles, a common workaround mentioned in the comments.

**Discussion**: A Ugandan commenter confirmed the broken system and criticized the author's hubris for not asking locals for advice first. Others noted that hand-carrying items is often the most reliable method, and even in developed countries, customs can be burdensome.

**Tags**: `#logistics`, `#corruption`, `#Africa`, `#humanitarian`, `#shipping`

---

<a id="item-11"></a>
## [Microsoft cancels Claude Code licenses, pushes Copilot CLI](https://www.theverge.com/tech/930447/microsoft-claude-code-discontinued-notepad) ⭐️ 7.0/10

Microsoft is canceling most Claude Code licenses for its developers, effective June 30, and is steering them toward its own GitHub Copilot CLI tool. This move signals Microsoft's strategic shift to promote its in-house AI coding tools over third-party alternatives like Anthropic's Claude Code, potentially reshaping the developer tool ecosystem. The cancellation was a pilot launched in December that accidentally consumed the company's 2026 yearly target spend on AI, according to community comments.

hackernews · robertkarl · May 22, 17:32 · [Discussion](https://news.ycombinator.com/item?id=48238896)

**Background**: Claude Code is an AI-powered coding assistant by Anthropic that operates in the terminal, while GitHub Copilot CLI is Microsoft's command-line coding tool. Both help developers write and manage code via natural language commands.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://github.com/features/copilot/cli">GitHub Copilot CLI · GitHub</a></li>

</ul>
</details>

**Discussion**: Developers noted that Claude Code consumed tokens rapidly when used unsupervised, but was more efficient with human-in-the-loop. Some questioned the cost-effectiveness of AI tooling compared to human labor.

**Tags**: `#Microsoft`, `#Claude Code`, `#Copilot CLI`, `#AI coding tools`, `#developer tools`

---

<a id="item-12"></a>
## [CISA Data Leak Prompts Lawmaker Scrutiny](https://krebsonsecurity.com/2026/05/lawmakers-demand-answers-as-cisa-tries-to-contain-data-leak/) ⭐️ 7.0/10

CISA is attempting to contain a data leak after a contractor used GitHub as a scratchpad, potentially exposing sensitive information. Lawmakers have demanded answers about the incident and CISA's response. This incident highlights ongoing risks in government cybersecurity practices, especially regarding contractor management and data handling. The congressional scrutiny could lead to stricter oversight and policy changes. CISA stated there is no indication that sensitive data was compromised, but the method suggests an individual contractor used the repository for syncing work between machines. Security experts note that this is a human problem that technical controls alone cannot solve.

hackernews · speckx · May 22, 16:54 · [Discussion](https://news.ycombinator.com/item?id=48238429)

**Background**: CISA is the U.S. federal agency responsible for cybersecurity and infrastructure security. Data leaks from government contractors have occurred before, such as the leak of millions of SF-86 security clearance forms. Using GitHub as a personal scratchpad violates best practices like never committing credentials or sensitive data to repositories.

**Discussion**: Commenters expressed skepticism about CISA's assurance that no sensitive data was compromised, referencing past leaks like the SF-86 incident. Some questioned the technical controls and noted the irony of a cybersecurity agency suffering such a breach. Others highlighted the difficulty of preventing contractors from using such workarounds.

**Tags**: `#cybersecurity`, `#data leak`, `#CISA`, `#infosec`, `#government`

---

<a id="item-13"></a>
## [Antigravity 2.0 Leads OpenSCAD Architectural 3D LLM Benchmark](https://modelrift.com/blog/openscad-llm-benchmark/) ⭐️ 7.0/10

Antigravity 2.0 achieved the highest score in a new benchmark for generating OpenSCAD architectural 3D models using large language models, particularly excelling in reproducing complex interior details of the Pantheon. The benchmark evaluates LLM-based code generation for parametric 3D modeling. This benchmark demonstrates the growing capability of LLMs in generating functional, parametric CAD models, which could lower the barrier for 3D modeling in architecture and engineering. Antigravity's performance highlights the potential of AI-assisted design tools, though community feedback reveals ongoing concerns about rollout stability and model reliability. The benchmark used the Pantheon as a test case, requiring models to generate OpenSCAD code for the entire structure including interior coffers. Antigravity 2.0 was the only autonomous agent to implement the interior ceiling pattern correctly, while Gemini models were noted for their image understanding and creativity but sometimes lacked precision for CAD.

hackernews · jetter · May 22, 10:38 · [Discussion](https://news.ycombinator.com/item?id=48234090)

**Background**: OpenSCAD is a free, script-based 3D CAD modeling tool that uses its own description language to define geometric primitives and operations. LLMs can generate OpenSCAD code from natural language descriptions, enabling rapid prototyping of parametric designs. Antigravity 2.0 is Google's AI coding assistant that integrates with IDEs and CLI, capable of generating code across multiple languages and domains.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenSCAD">OpenSCAD</a></li>
<li><a href="https://antigravity.google/blog/introducing-google-antigravity-2-0">Google Antigravity Blog: introducing-google- antigravity - 2 - 0</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some users report successful real-world use, like generating a bike part with Claude that printed nearly perfectly, while others criticize Antigravity's forced rollouts and update issues. There is skepticism about the benchmark's representativeness due to its single-model focus, with users noting that LLM performance varies widely across different 3D model types.

**Tags**: `#LLM`, `#OpenSCAD`, `#3D Modeling`, `#Benchmark`, `#AI`

---

<a id="item-14"></a>
## [Open source Kanban app runs parallel AI agents on each card](https://www.kanbots.dev/) ⭐️ 7.0/10

Kanbots is an open-source Kanban desktop app that allows users to run parallel AI agents on each card, automating task execution within a visual workflow. This tool merges project management with AI automation, enabling developers to run multiple agents concurrently on tasks, potentially speeding up development while preserving visual oversight. Kanbots is local-first with no cloud dependency, storing everything in a .kanbots/ directory next to the repo using SQLite and worktrees. It runs agents in parallel on each card, which contradicts traditional Kanban's work-in-progress limits.

hackernews · vitriapp · May 22, 18:17 · [Discussion](https://news.ycombinator.com/item?id=48239413)

**Background**: Kanban is a visual workflow management method originating from Toyota that emphasizes limiting work-in-progress and managing flow. AI agents are programs that can autonomously execute tasks such as code generation or testing. Combining them allows automated actions directly from a Kanban board. Parallel agent execution, where multiple agents run simultaneously on independent tasks, is a common pattern in AI automation.

<details><summary>References</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/azure/architecture/ai-ml/idea/multiple-agent-workflow-automation">Build a Multiple-Agent Workflow Automation Solution by using Microsoft Agent Framework - Azure Architecture Center | Microsoft Learn</a></li>
<li><a href="https://typevar.dev/articles/BloopAI/vibe-kanban">agent - Bridging Human Intent and AI Execution with Terminal- Based ...</a></li>
<li><a href="https://github.com/KingofPoly/Kanban-MCP">GitHub - KingofPoly/ Kanban -MCP: Kanban - based task management...</a></li>

</ul>
</details>

**Discussion**: Commenters note that Kanbots violates core Kanban principles like limiting work-in-progress (kesor). Others raise practical concerns about reviewing AI-generated code output (aitchnyu). Some compare it to similar projects like Vibe Kanban, which is no longer maintained, raising sustainability concerns (KerrickStaley). There are also technical questions about managing separate worktree infrastructures for each agent (nullbio).

**Tags**: `#kanban`, `#agents`, `#open-source`, `#developer-tools`, `#AI`

---

<a id="item-15"></a>
## [Datasette Agent: Conversational AI for Data Queries](https://simonwillison.net/2026/May/21/datasette-agent/#atom-everything) ⭐️ 7.0/10

Datasette Agent, a new extensible AI assistant for Datasette, was announced on May 21, 2026, enabling natural language data queries and chart generation via plugins. This integration of LLMs with Datasette democratizes data analysis by allowing non-technical users to query databases conversationally, and its plugin architecture enables extensibility for tasks like charting and image generation. The live demo uses Gemini 3.1 Flash-Lite, a cheap and fast model, to generate SQL queries from natural language; datasette-agent-charts plugin uses Observable Plot for charting.

rss · Simon Willison · May 21, 19:52

**Background**: Datasette is an open-source multi-tool for exploring and publishing data, often used with SQLite databases. LLM is a Python library for interacting with large language models. Datasette Agent combines these to provide a conversational interface.

<details><summary>References</summary>
<ul>
<li><a href="https://datasette.io/blog/2026/datasette-agent/">Datasette Agent , an extensible AI assistant for... - Datasette Blog</a></li>
<li><a href="https://pypi.org/project/datasette-agent-charts/">datasette - agent - charts · PyPI</a></li>
<li><a href="https://simonwillison.net/2026/May/12/datasette/">Release: datasette 1.0a29 | Simon Willison’s Weblog</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#ai-assistant`, `#data-analysis`, `#llm`, `#natural-language-querying`

---

<a id="item-16"></a>
## [Zhipu AI Launches GLM-5.1 HighSpeed at 400 tokens/s](https://docs.bigmodel.cn/cn/guide/models/text/glm-5.1-highspeed) ⭐️ 7.0/10

Zhipu AI has released the GLM-5.1 HighSpeed model, achieving an output speed of 400 tokens per second, and is currently opening access to select enterprise customers on its BigModel platform. This speed milestone enables real-time applications such as coding agents, live UI construction, and voice assistants, reducing latency bottlenecks for enterprise AI deployments. The model supports structured outputs including Function Call and JSON, as well as the Model Context Protocol (MCP) for integration with external tools and data sources.

telegram · zaihuapd · May 22, 04:45

**Background**: The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 to standardize connections between AI models and external data sources. Coding agents are AI-assisted tools that automate code generation, review, and refactoring tasks. High-speed inference is critical for interactive and low-latency use cases like real-time UI building and conversational agents.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://www.anthropic.com/news/model-context-protocol">Introducing the Model Context Protocol \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI`, `#NLP`, `#model inference`, `#speed`, `#enterprise`

---

<a id="item-17"></a>
## [Microsoft Widely Promotes Claude Code Internally, Asks for Copilot Comparison](https://t.me/zaihuapd/41535) ⭐️ 7.0/10

Microsoft is now widely promoting Anthropic's Claude Code across its core engineering teams, including the CoreAI team and the Experiences & Devices division responsible for Windows, Microsoft 365, and Outlook. Software engineers are required to use both Claude Code and GitHub Copilot and provide comparative feedback. This move signals that AI coding assistants are becoming a standard tool in major tech companies, and that Anthropic's Claude Code is now a serious competitor to Microsoft's own GitHub Copilot. Encouraging non-technical employees to use AI for prototyping could also lower barriers to software development. The promotion applies to Microsoft's most important engineering teams, and even employees without prior coding experience are encouraged to use Claude Code for prototyping. Feedback from the comparison between Claude Code and Copilot will be collected.

telegram · zaihuapd · May 23, 06:05

**Background**: Claude Code is an AI-powered coding assistant developed by Anthropic, the company behind the Claude series of large language models. Claude models are trained using 'constitutional AI' to improve ethical compliance. GitHub Copilot is Microsoft's own AI coding assistant built on OpenAI's technology. The adoption of Claude Code by Microsoft, which also owns Copilot, highlights the competitive landscape in AI-assisted software development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Code">Claude Code</a></li>
<li><a href="https://code.claude.com/docs/en/overview">Overview - Claude Code Docs</a></li>

</ul>
</details>

**Tags**: `#AI编程`, `#微软`, `#Claude Code`, `#GitHub Copilot`, `#行业动态`

---

<a id="item-18"></a>
## [uv 0.11.16 released with Git archive deps and audit features](https://github.com/astral-sh/uv/releases/tag/0.11.16) ⭐️ 6.0/10

uv 0.11.16 adds support for direct archive dependencies in Git repositories, introduces preview audit features, and includes several bug fixes and configuration enhancements. This release improves uv's flexibility for projects using archived dependencies in Git, and the new audit features help detect malware and unsafe configurations, strengthening supply chain security for Python developers. The preview audit features include specialized malformed OSV error handling and rejection of locked malware installations. Additionally, the new UV_NO_SYSTEM_CONFIG environment variable allows users to disable reading system-level configuration.

github · github-actions[bot] · May 21, 22:11

**Background**: uv is a fast Python package manager written in Rust, known for its speed and reliability. Direct archive dependencies allow referencing compressed archives (like .tar.gz) within Git repositories as package sources, which is useful for projects that vendor dependencies or use custom archives.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.astral.sh/uv/guides/install-python/">Installing and managing Python | uv</a></li>

</ul>
</details>

**Tags**: `#uv`, `#python`, `#package-manager`, `#release`, `#tooling`

---

<a id="item-19"></a>
## [Deno 2.8 Released with New 'deno pack' Command](https://deno.com/blog/v2.8) ⭐️ 6.0/10

Deno 2.8 has been released, introducing a new 'deno pack' command for safe and simple packaging of JavaScript and TypeScript applications. This release reinforces Deno's position as a secure and modern runtime, particularly with its permission model and native TypeScript support, keeping it competitive against Node.js and Bun. The new 'deno pack' command simplifies bundling for distribution, though the full changelog includes other improvements and bug fixes typical of a point release.

hackernews · roflcopter69 · May 22, 11:23 · [Discussion](https://news.ycombinator.com/item?id=48234380)

**Background**: Deno is a JavaScript and TypeScript runtime built on V8, Rust, and Tokio, designed as a secure alternative to Node.js with features like a built-in permission system and native TypeScript execution. It competes with Node.js and the newer Bun runtime, which has gained attention for its speed and all-in-one toolkit.

**Discussion**: Community members praised Deno's permission model and stability, but some questioned Bun's rapid growth and noted Bun's acquisition by Anthropic. A few users expressed concerns about Deno's long-term funding, as the authors have declined donations.

**Tags**: `#deno`, `#javascript`, `#typescript`, `#runtime`, `#webdev`

---

<a id="item-20"></a>
## [Forth-inspired language for building websites unveiled](https://robida.net/entries/2026/05/21/a-forth-inspired-language-for-writing-websites) ⭐️ 6.0/10

A developer has created a new programming language inspired by Forth, designed specifically for writing websites, and shared it as a hobby project. The language uses stack-based, concatenative syntax to emit HTML directly, and was developed with LLM assistance. This project highlights the growing trend of using LLM-assisted development to quickly prototype niche languages, and it sparks community interest in concatenative programming for web development. While not groundbreaking, it demonstrates how hobbyist experiments can explore alternative paradigms for building websites. The language allows defining words like `: h1 ( s -- ) "<h1>" emit . "</h1>" emit ;` to emit HTML tags, using `.` and `emit` for output. The project compiles to native code and WebAssembly, supporting server-side and client-side rendering, and includes adaptive compression and multiple persistence types.

hackernews · speckx · May 22, 15:00 · [Discussion](https://news.ycombinator.com/item?id=48236887)

**Background**: Forth is a stack-based, extensible programming language using postfix notation and an interactive interpreter, known for its minimalism and efficiency. Concatenative programming replaces function application with function composition, where juxtaposition of expressions denotes composition, and all functions operate on a single implicit data stack. This language adapts those concepts for web development, allowing developers to write HTML in a Forth-like style.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Forth_(programming_language)">Forth (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Concatenative_programming_language">Concatenative programming language - Wikipedia</a></li>
<li><a href="https://concatenative.org/wiki/view/Concatenative+language">Concatenative language</a></li>

</ul>
</details>

**Discussion**: Comments express amusement and curiosity, with one user suggesting the language is perfect for personal blogs. Another user asks for clarification on language semantics, while a third notes the site is down due to the 'HN Hug of Death'. Overall sentiment is positive, with appreciation for the weirdness and the enabling power of LLMs.

**Tags**: `#forth`, `#web-development`, `#programming-languages`, `#hobbyist`, `#llm-assistance`

---

<a id="item-21"></a>
## [FTC Fines Cox Media Group for Fake AI Listening Service](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 6.0/10

The US Federal Trade Commission (FTC) announced that Cox Media Group and two other firms will pay nearly $1 million to settle charges that they misled customers about an AI-powered 'Active Listening' marketing service, which they claimed could eavesdrop on consumers' smart devices to target ads, but in reality did not use voice data at all. This settlement underscores the FTC's increasing scrutiny of deceptive AI marketing claims and serves as a warning to companies that exaggerate AI capabilities. It also reinforces that hiding opt-in consent in lengthy terms of service is not sufficient for invasive data collection. The companies claimed the service used 'voice data' from smart devices, but the FTC found they were merely reselling email lists at a markup. The FTC also alleged that the companies falsely represented that consumers had opted in by agreeing to app terms of service.

rss · Simon Willison · May 22, 04:48

**Background**: The 'active listening' controversy dates back to 2024 when Cox Media Group was caught pitching an advertising service based on listening to smart device conversations. The FTC's investigation revealed that the service did not actually use voice data. This case adds to the ongoing conspiracy theory that mobile devices spy on users through microphones for ad targeting, which has been consistently debunked.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emarketer.com/content/faq-on-iot-connected-devices--marketing-opportunities-with-cars--wearables--smart-home">FAQ on IoT and connected devices : Marketing opportunities with cars...</a></li>
<li><a href="https://forums.puri.sm/t/audio-from-smart-devices-used-for-advertising/24521">Audio from smart devices used for advertising ... - Purism community</a></li>

</ul>
</details>

**Tags**: `#AI`, `#regulation`, `#privacy`, `#deceptive practices`, `#FTC`

---