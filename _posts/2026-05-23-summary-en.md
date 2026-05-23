---
layout: default
title: "Horizon Summary: 2026-05-23 (EN)"
date: 2026-05-23
lang: en
---

> From 42 items, 20 important content pieces were selected

---

1. [80386 Microcode Disassembled from Die Photos](#item-1) ⭐️ 9.0/10
2. [AI finds over 10,000 critical vulnerabilities in Project Glasswing](#item-2) ⭐️ 9.0/10
3. [Apple Open-Sources corecrypto with Formal Verification for Quantum-Safe Algorithms](#item-3) ⭐️ 9.0/10
4. [Shipping a Laptop to Uganda: Corruption and Lessons](#item-4) ⭐️ 8.0/10
5. [Why Japanese Companies Diversify: Lifetime Employment & Employee Governance](#item-5) ⭐️ 8.0/10
6. [Microsoft cancels Claude Code licenses, pushes Copilot CLI](#item-6) ⭐️ 8.0/10
7. [AI Demand for HBM Squeezes Consumer Memory, Raising Prices](#item-7) ⭐️ 8.0/10
8. [FTC Fines Cox Media Group $1M Over Bogus 'Active Listening' AI](#item-8) ⭐️ 8.0/10
9. [Datasette Agent: LLM-Powered AI Assistant for Data Exploration](#item-9) ⭐️ 8.0/10
10. [Tencent's Acquisition of Ximalaya Approved with Condition](#item-10) ⭐️ 8.0/10
11. [China cracks down on illegal cross-border securities platforms](#item-11) ⭐️ 8.0/10
12. [Cloudflare Outage Hits 28% HTTP Traffic for 25 Minutes](#item-12) ⭐️ 8.0/10
13. [Microsoft pushes Claude Code internally, nudges non-tech staff to code](#item-13) ⭐️ 8.0/10
14. [Microsoft reveals OpenAI's $11.5B quarterly loss](#item-14) ⭐️ 8.0/10
15. [BambuStudio Accused of Violating PrusaSlicer's AGPL License](#item-15) ⭐️ 7.0/10
16. [Robin Li: AI large models near explosion point](#item-16) ⭐️ 7.0/10
17. [Corsair Adopts CXMT DRAM for DDR5, Prices Expected to Drop](#item-17) ⭐️ 7.0/10
18. [China's daily token calls surge over 1000x in 2 years, hit 140 trillion in March 2025](#item-18) ⭐️ 7.0/10
19. [Deep Dive into the HTML <dl> Element Semantics](#item-19) ⭐️ 6.0/10
20. [Rubish: A Unix shell written in pure Ruby](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [80386 Microcode Disassembled from Die Photos](https://www.reenigne.org/blog/80386-microcode-disassembled/) ⭐️ 9.0/10

A reverse engineer has successfully disassembled the microcode of the Intel 80386 processor from high-resolution die photographs, revealing the internal control logic and microinstructions. This reverse engineering feat provides rare and detailed insights into the microarchitecture of one of the most influential x86 processors, benefiting computer architecture research and vintage computing enthusiasts. The disassembly process involves identifying the microcode ROM layout and decoding the microinstruction format from the transistor-level image, a complex task given the 32-bit processor's internal state machine.

hackernews · nand2mario · May 23, 12:11 · [Discussion](https://news.ycombinator.com/item?id=48247004)

**Background**: Microcode is a layer of low-level instructions that implement the higher-level machine code instructions in a CPU. The Intel 80386, released in 1985, was a landmark 32-bit processor that established the x86 architecture. Die photography allows reverse engineers to examine the physical layout of transistors and reconstruct the microcode stored in ROM.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microcode">Microcode - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Intel_Microcode">Intel microcode - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community expressed admiration for the technical difficulty and the rewarding nature of the work. Some users asked about the process of extracting microcode from die images, while others shared educational resources like the book on microprogramming and the nand2tetris course.

**Tags**: `#reverse engineering`, `#microcode`, `#x86`, `#computer architecture`, `#Intel 80386`

---

<a id="item-2"></a>
## [AI finds over 10,000 critical vulnerabilities in Project Glasswing](https://www.anthropic.com/research/glasswing-initial-update) ⭐️ 9.0/10

Anthropic announced initial results from Project Glasswing, where their Claude Mythos Preview model, in collaboration with 50+ partners, discovered over 10,000 high-severity and critical vulnerabilities in critical software within one month. The vulnerability discovery rate increased more than tenfold compared to traditional methods. This breakthrough shifts the bottleneck from vulnerability discovery to validation, disclosure, and patching, revealing a critical human resource gap. As AI-powered vulnerability detection becomes more widespread, the software industry must accelerate patch cycles to keep pace with the rising risk. The AI scanned thousands of open-source projects and identified 6,202 high-severity vulnerabilities, of which 1,752 were reviewed with a 90.6% true positive rate. Partners including Cloudflare reported a tenfold increase in vulnerability discovery speed. However, open-source maintainers requested to slow down reporting due to overwhelming validation and patching workloads.

telegram · zaihuapd · May 23, 03:16

**Background**: Project Glasswing is a defensive cybersecurity initiative by Anthropic, leveraging a new frontier model called Claude Mythos Preview, which demonstrates exceptional capabilities in code analysis and vulnerability discovery. Traditional vulnerability discovery relies on manual auditing or static analysis tools, often missing subtle or complex bugs. AI models like Claude Mythos can analyze code at scale and find vulnerabilities that human experts might overlook, potentially transforming the security landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing : Securing critical software for the AI era \ Anthropic</a></li>
<li><a href="https://red.anthropic.com/2026/mythos-preview/">Claude Mythos Preview \ red.anthropic.com</a></li>

</ul>
</details>

**Tags**: `#AI安全`, `#漏洞发现`, `#网络安全`, `#Anthropic`

---

<a id="item-3"></a>
## [Apple Open-Sources corecrypto with Formal Verification for Quantum-Safe Algorithms](https://security.apple.com/blog/formal-verification-corecrypto/) ⭐️ 9.0/10

On May 22, Apple open-sourced the corecrypto cryptographic library, including implementations of ML-KEM and ML-DSA with end-to-end formal verification proofs that ensure the C and ARM64 assembly code exactly matches the NIST standards. This is a major step for post-quantum cryptography, as corecrypto powers over 2.5 billion Apple devices and the formal verification provides unprecedented assurance that the quantum-safe implementations are correct, potentially influencing industry adoption of similar verification practices. Apple also released custom verification tools and the Isabelle theory library used in the proofs, allowing independent experts to evaluate the correctness. The verified algorithms include ML-KEM (key encapsulation) and ML-DSA (digital signatures), both standardized by NIST in 2024.

telegram · zaihuapd · May 23, 04:49

**Background**: Quantum computers pose a threat to current public-key cryptography, as algorithms like RSA and ECC could be broken by Shor's algorithm. In response, NIST standardized post-quantum algorithms: ML-KEM (FIPS 203) for key exchange and ML-DSA (FIPS 204) for digital signatures, both based on lattice cryptography. Formal verification uses theorem provers like Isabelle to mathematically prove that code matches its specification, offering stronger guarantees than traditional testing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ML-KEM">ML-KEM - Wikipedia</a></li>
<li><a href="https://www.digicert.com/insights/post-quantum-cryptography/mldsa">ML-DSA | Post-Quantum Cryptography | DigiCert Insights</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isabelle_(proof_assistant)">Isabelle (proof assistant) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#密码学`, `#形式化验证`, `#量子安全`, `#苹果`, `#开源`

---

<a id="item-4"></a>
## [Shipping a Laptop to Uganda: Corruption and Lessons](https://notesbylex.com/shipping-a-laptop-to-a-refugee-camp-in-uganda) ⭐️ 8.0/10

The author recounts the extreme difficulties and systemic corruption encountered when trying to ship a laptop to a refugee camp in Uganda, including exorbitant taxes and bureaucratic hurdles. This story exposes the broken logistics and corruption that hinder aid and personal shipments to developing regions, affecting both humanitarian efforts and individuals. The author tried multiple carriers including DHL and Uganda Post, faced demands for bribes, and finally succeeded through a local freight forwarder known as a "grey market" broker.

hackernews · lexandstuff · May 22, 21:36 · [Discussion](https://news.ycombinator.com/item?id=48241997)

**Background**: Shipping electronics to many African countries is notoriously difficult due to high import duties, corruption, and unreliable postal systems. Many expatriates and locals rely on informal freight forwarders who use airline passengers' luggage allowance to transport goods, bypassing official channels.

**Discussion**: Commenters largely agree with the author's assessment, with many Ugandans confirming the systemic corruption. They recommend using grey-market freight forwarders or personally carrying items when traveling, and criticize the author's initial assumption that Western shipping methods would work.

**Tags**: `#logistics`, `#Uganda`, `#corruption`, `#aid`, `#practical lessons`

---

<a id="item-5"></a>
## [Why Japanese Companies Diversify: Lifetime Employment & Employee Governance](https://davidoks.blog/p/why-japanese-companies-do-so-many) ⭐️ 8.0/10

An essay argues that Japanese companies' broad diversification stems from lifetime employment and employee-led governance, where firms prioritize survival and employee interests over shareholder value. This analysis challenges Western corporate focus on shareholder primacy, offering an alternative model where employee-centric governance drives diversification and long-term stability. The article notes that lifetime employees with firm-specific skills cannot be easily fired, and the system only works if insulated from external shareholder pressure.

hackernews · d0ks · May 22, 15:22 · [Discussion](https://news.ycombinator.com/item?id=48237163)

**Background**: Lifetime employment is a Japanese practice where about 30-40% of workers are effectively employed for their entire career at one firm. Employee-led governance means companies are run by employees, not just shareholders, focusing on long-term survival. This contrasts with Western models that prioritize shareholder value and short-term profits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bls.gov/opub/mlr/1984/08/rpt4full.pdf">Lifetime employment in Japan : three models of the concept</a></li>
<li><a href="https://eprints.whiterose.ac.uk/id/eprint/43581/1/MatanleMatsuiEPJHRM2011_Deposit.pdf">Lifetime Employment in 21st Century Japan : Stability and Resilience...</a></li>
<li><a href="https://www.nishimura.com/sites/default/files/articles/file/478.pdf">Corporate Governance and Directors' Duties in Japan: Overview</a></li>

</ul>
</details>

**Discussion**: Comments highlight that this system creates low job fluidity and challenges for mid-career hires, while some note Western companies also diversified in the past. Others caution against romanticizing the Japanese model, pointing out its social and economic downsides.

**Tags**: `#Japanese business`, `#corporate strategy`, `#organizational culture`, `#economic systems`

---

<a id="item-6"></a>
## [Microsoft cancels Claude Code licenses, pushes Copilot CLI](https://www.theverge.com/tech/930447/microsoft-claude-code-discontinued-notepad) ⭐️ 8.0/10

Microsoft is revoking Claude Code licenses from its developers and directing them to use GitHub Copilot CLI instead, a command-line AI coding tool. This move signals Microsoft's strategic push to drive adoption of its own AI coding assistant, Copilot CLI, at the expense of a popular competitor, potentially limiting developer choice and sparking backlash. According to the article, Microsoft initially offered both tools to developers for comparison, but developers overwhelmingly preferred Claude Code over Copilot, leading to the license cancellations.

hackernews · robertkarl · May 22, 17:32 · [Discussion](https://news.ycombinator.com/item?id=48238896)

**Background**: Claude Code is an agentic coding tool by Anthropic that works in the terminal, understanding codebases and automating tasks. GitHub Copilot CLI is Microsoft's own command-line AI coding assistant. Both aim to help developers code faster, but Claude Code is often seen as more effective.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://www.anthropic.com/product/claude-code">Claude Code | Anthropic's agentic coding system</a></li>
<li><a href="https://awesome-copilot.github.com/learning-hub/cli-for-beginners/">GitHub Copilot CLI for Beginners</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration, noting that Microsoft's hope for Copilot to outperform Claude Code backfired. Some highlighted that careful, supervised use of Claude Code can be cost-effective, while others criticized Copilot's poor performance in government cloud environments.

**Tags**: `#Microsoft`, `#Claude Code`, `#Copilot`, `#AI coding assistants`, `#developer tools`

---

<a id="item-7"></a>
## [AI Demand for HBM Squeezes Consumer Memory, Raising Prices](https://simonwillison.net/2026/May/22/memory-shortage/#atom-everything) ⭐️ 8.0/10

AI's surging demand for HBM memory is expected to increase its wafer allocation from 2% to 20% by end of 2026, squeezing production of DDR and LPDDR memory and causing price hikes for consumer electronics, especially sub-$100 smartphones. This shift highlights a structural trade-off between AI infrastructure and affordable consumer devices, potentially impacting billions of users in emerging markets who rely on low-cost smartphones. Memory companies are prioritizing high-margin HBM over consumer RAM, a trend likely to persist for years. A single gigabyte of HBM consumes more than three times the wafer capacity of a gigabyte of DDR or LPDDR. Memory manufacturers have learned from past industry consolidation to always under-provision capacity, further constraining supply.

rss · Simon Willison · May 22, 22:01

**Background**: HBM (High Bandwidth Memory) is a 3D-stacked DRAM technology optimized for high-speed data transfer and low power, essential for GPUs and AI accelerators. Wafer capacity refers to the number of silicon wafers a fab can process, split among different memory types. DDR and LPDDR are standard memory types used in desktops/servers and mobile devices, respectively.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://semiengineering.com/high-bandwidth-memory-hbm-everything-you-need-to-know/">High Bandwidth Memory (HBM): Everything You Need To Know</a></li>
<li><a href="https://www.semi.org/en/news-media-press-releases/semi-press-releases/global-semiconductor-fab-capacity-projected-to-expand-6%-in-2024-and-7%-in-2025-semi-reports">Global Semiconductor Fab Capacity Projected to Expand 6% in ...</a></li>

</ul>
</details>

**Tags**: `#memory shortage`, `#AI`, `#consumer electronics`, `#semiconductors`, `#pricing`

---

<a id="item-8"></a>
## [FTC Fines Cox Media Group $1M Over Bogus 'Active Listening' AI](https://simonwillison.net/2026/May/22/ftc-active-listening/#atom-everything) ⭐️ 8.0/10

The FTC announced that Cox Media Group, MindSift, and 1010 Digital Works will pay nearly $1 million to settle charges of falsely claiming their 'Active Listening' AI service eavesdropped on smart devices to target ads. The service actually just resold email lists at a markup. This case underscores increasing FTC scrutiny of deceptive AI marketing and false privacy claims, setting a precedent that companies cannot mislead consumers about AI-powered surveillance capabilities. It also provides ammunition against conspiracy theories that smartphones use microphones for ad targeting. The FTC clarified that hidden opt-in clauses in terms of service do not constitute adequate consent for such invasive practices. Additionally, the firms failed to deliver targeted ads as promised, instead reselling data broker lists.

rss · Simon Willison · May 22, 04:48

**Background**: 'Active Listening' refers to a controversial marketing technique that claims to use AI to analyze real-time voice data from smart devices for ad targeting. The FTC enforces consumer protection laws against deceptive practices. The recent settlement confirms that the service did not actually listen to conversations, debunking common conspiracy theories.

<details><summary>References</summary>
<ul>
<li><a href="https://thecyberexpress.com/ftc-ai-powered-active-listening-case/">AI-Powered Marketing Service “Active Listening” Deceived ...</a></li>
<li><a href="https://www.newsweek.com/phone-voice-assistants-active-listening-consent-targeted-ads-1949251">Is Your Phone Really Listening to You? Here’s What We Know FTC: Cox Media Group and 2 others to pay nearly $1M over ... Is your phone listening? Marketing firm confirms tech behind ... Is Your Device Always Listening? How It Fuels Targeted Ads FTC: Cox Media Group Sold Bogus AI Ad Service, Now Must... Marketer that claimed it could tap devices for ad targeting ...</a></li>

</ul>
</details>

**Tags**: `#FTC`, `#AI`, `#privacy`, `#advertising`, `#enforcement`

---

<a id="item-9"></a>
## [Datasette Agent: LLM-Powered AI Assistant for Data Exploration](https://simonwillison.net/2026/May/21/datasette-agent/#atom-everything) ⭐️ 8.0/10

Simon Willison announced the first release of Datasette Agent, an extensible AI assistant that integrates large language models with Datasette for conversational data queries and chart generation via plugins. Datasette Agent bridges LLMs and structured data, making data exploration more accessible to non-technical users and enabling natural language interaction with SQLite databases. The live demo runs on Gemini 3.1 Flash-Lite for cheap, fast inference, and the plugin ecosystem currently includes chart generation via Observable Plot and image generation via ChatGPT.

rss · Simon Willison · May 21, 19:52

**Background**: Datasette is an open-source tool that publishes SQLite databases as interactive web interfaces and JSON APIs. The LLM library is a CLI tool and Python library for interacting with various large language models. Datasette Agent combines these two tools to allow natural language queries over data.

<details><summary>References</summary>
<ul>
<li><a href="https://datasette.io/">Datasette: An open source multi-tool for exploring and ...</a></li>
<li><a href="https://llm.datasette.io/">LLM: A CLI utility and Python library for interacting with Large Language Models</a></li>
<li><a href="https://github.com/simonw/datasette">GitHub - simonw/datasette: An open source multi-tool for ... Datasette Review (2026) - MakerStack Introduction to Datasette, a Frontend to Tabulated Data Commodore Datasette - Wikipedia datasette · PyPI Datasette - skills.network</a></li>

</ul>
</details>

**Tags**: `#Datasette`, `#LLM`, `#AI Assistant`, `#Data Exploration`, `#Python`

---

<a id="item-10"></a>
## [Tencent's Acquisition of Ximalaya Approved with Condition](https://mp.weixin.qq.com/s/xnx31SOS6NMozZXnHeaaQg) ⭐️ 8.0/10

China's State Administration for Market Regulation approved Tencent's acquisition of Ximalaya, requiring Tencent to stop exclusive online audio copyright agreements and cancel existing exclusive contracts within a deadline. This breaks Ximalaya's content monopoly, potentially reshaping the online audio market by allowing other platforms to access the same copyrighted content, benefiting competition and user convenience. Tencent must not enter or renew exclusive licensing agreements for online audio copyrights, and must dismantle all existing exclusive deals within a set period. Tencent stated it will comply and seek non-exclusive partnerships moving forward.

telegram · zaihuapd · May 22, 10:33

**Background**: Ximalaya is China's largest online audio platform, with a vast library of audiobooks, podcasts, and radio shows. Exclusive copyright agreements were a key competitive advantage, locking content to Ximalaya. Tencent's acquisition raised antitrust concerns due to potential market dominance.

**Tags**: `#Tencent`, `#Ximalaya`, `#Antitrust`, `#Online Audio`, `#Regulation`

---

<a id="item-11"></a>
## [China cracks down on illegal cross-border securities platforms](https://t.me/zaihuapd/41525) ⭐️ 8.0/10

China's eight government departments jointly issued a plan to crack down on illegal cross-border securities, futures, and fund operations, requiring existing investors to only sell assets and withdraw funds. The CSRC has initiated investigations against Tiger Brokers, Futu, and Changqiao for illegal cross-border business. This regulatory action significantly impacts cross-border investment platforms and their users, likely forcing many fintech companies to halt services in China. It signals a tougher stance on capital outflows and unlicensed financial activities, affecting millions of Chinese investors using these platforms. The plan sets a two-year rectification period during which only existing investors can sell assets and withdraw funds, after which all relevant websites, trading software, and servers must be shut down. Targets include overseas institutions, domestic associates, and platforms providing account opening channels or marketing lead generation.

telegram · zaihuapd · May 22, 13:55

**Background**: Tiger Brokers (TIGR), Futu Holdings (FUTU), and Changqiao are online brokerages that allowed Chinese residents to trade global stocks and derivatives, often without proper regulatory approval from Chinese authorities. China's securities laws require any entity soliciting clients or executing trades within the country to be licensed by the CSRC. This crackdown follows years of regulatory warnings and reflects Beijing's efforts to control cross-border capital flows and protect investors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Futu">Futu - Wikipedia</a></li>
<li><a href="https://www.futuholdings.com/en-us/profile">About Us | FUTU | Futu Holdings Limited 富途控股</a></li>
<li><a href="https://grokipedia.com/page/Tiger_Brokers">Tiger Brokers</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#cross-border investment`, `#China`, `#fintech`, `#securities`

---

<a id="item-12"></a>
## [Cloudflare Outage Hits 28% HTTP Traffic for 25 Minutes](https://t.me/zaihuapd/41527) ⭐️ 8.0/10

On December 5, 2025, Cloudflare experienced a 25-minute global network outage that affected approximately 28% of HTTP traffic, caused by a flawed fix for the React Server Components vulnerability CVE-2025-55182 in Next.js. This outage impacted a significant portion of internet traffic routed through Cloudflare, one of the largest content delivery networks, highlighting the cascading risks of security patch deployments on critical infrastructure. The outage specifically affected customers using the older FL1 proxy with Cloudflare's Managed Ruleset deployed, returning HTTP 500 errors. The root cause was a Lua nil-pointer bug triggered when a killswitch was applied to an execute-action ruleset during the CVE fix.

telegram · zaihuapd · May 22, 16:15

**Background**: Cloudflare is a major content delivery network and security provider that handles a large share of global web traffic. Its FL1 proxy is an older request handling layer. CVE-2025-55182 is a critical pre-authentication remote code execution vulnerability in React Server Components, affecting versions 19.0.0 to 19.2.0. Cloudflare's Web Application Firewall (WAF) rules include managed rulesets to block such exploits, but a flawed update caused the outage.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.cloudflare.com/5-december-2025-outage/">Cloudflare outage on December 5, 2025</a></li>
<li><a href="https://www.ascii.co.uk/news/article/news-20251208-71fe2ccb/cloudflare-25-minute-outage-lua-nil-bug-in-waf-rules-engine">Cloudflare 25-Minute Outage: Lua Nil Bug in WAF Rules Engine</a></li>
<li><a href="https://nvd.nist.gov/vuln/detail/CVE-2025-55182">NVD - CVE-2025-55182</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#outage`, `#CVE-2025-55182`, `#Next.js`, `#WAF`

---

<a id="item-13"></a>
## [Microsoft pushes Claude Code internally, nudges non-tech staff to code](https://t.me/zaihuapd/41535) ⭐️ 8.0/10

Microsoft is now deploying Anthropic's Claude Code across its major engineering teams, including CoreAI and the Experiences & Devices team for Windows, Microsoft 365, and Outlook. Engineers are required to use both Claude Code and GitHub Copilot and provide comparative feedback. This move signals competitive dynamics in the AI coding tool market and validates the usefulness of AI coding agents for non-technical employees. It also puts pressure on GitHub Copilot, Microsoft's own product, as the company evaluates alternative tools. Claude Code is an AI coding agent that runs in the terminal or IDE, with capabilities like code generation, refactoring, and debugging. Microsoft's push includes employees without prior programming experience, who are encouraged to use Claude Code for prototyping.

telegram · zaihuapd · May 23, 06:05

**Background**: Claude Code is a tool developed by Anthropic that leverages Claude language models to assist with coding tasks. It can be used in the terminal or integrated into IDEs. GitHub Copilot, developed by Microsoft and GitHub, is a competing AI coding assistant that autocompletes code. Microsoft's internal evaluation of both tools suggests a willingness to adopt best-in-class solutions rather than exclusively using its own products.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>

</ul>
</details>

**Tags**: `#AI coding`, `#Microsoft`, `#Claude Code`, `#GitHub Copilot`, `#software engineering`

---

<a id="item-14"></a>
## [Microsoft reveals OpenAI's $11.5B quarterly loss](https://t.me/zaihuapd/41537) ⭐️ 8.0/10

Microsoft's latest earnings report disclosed that OpenAI suffered a net loss of approximately $11.5 billion in a single quarter, based on the equity method accounting for its 27% stake, which reduced Microsoft's net profit by $3.1 billion. This revelation underscores the enormous and sustained cash burn required to lead in AI development, challenging the long-term economic viability of even the most prominent AI firms. Microsoft calculated the loss using the equity method: it owns roughly 27% of OpenAI (or 32.5% on a pre-tax basis), implying a quarterly loss exceeding $12 billion on a pre-tax basis. The loss is nearly three times OpenAI's $4.3 billion revenue in the first half of the year.

telegram · zaihuapd · May 23, 07:40

**Background**: The equity method is an accounting approach used when an investor has significant influence over a company (typically 20-50% ownership). Under this method, the investor records its share of the investee's profits or losses as investment income or loss, adjusting the investment's carrying value accordingly. This disclosure reveals the immense scale of investment needed in AI, as Microsoft has already committed $13 billion to OpenAI.

<details><summary>References</summary>
<ul>
<li><a href="https://zhuanlan.zhihu.com/p/496165358">长期股权投资——权益法（干货总结） - 知乎</a></li>
<li><a href="https://baike.baidu.com/item/权益法/9289851">权益法_百度百科 采用权益法核算的长期股权投资账务处理流程（附案例详解） 一文搞懂长期股权投资的核算方法：成本法、权益法和合并法 在阅读||#20998;... 权益法核算的长期股权投资收益_东奥会计在线 【老丁解税】权益法下投资收益的所得税处理解析 【老丁解税】权益法下投资收益的所得税处理解析|股权|纳税|权益性_网...</a></li>

</ul>
</details>

**Tags**: `#Microsoft`, `#OpenAI`, `#financial loss`, `#AI`, `#investment`

---

<a id="item-15"></a>
## [BambuStudio Accused of Violating PrusaSlicer's AGPL License](https://xcancel.com/josefprusa/status/2054602354851254330) ⭐️ 7.0/10

Josef Prusa, founder of Prusa Research, publicly accused BambuStudio of violating the AGPL license by failing to comply with its open-source requirements since forking PrusaSlicer. This accusation highlights ongoing challenges in enforcing open-source licenses, especially for dual-use software in 3D printing, and raises concerns about intellectual property protection and potential data mining by closed-source forks. BambuStudio is a proprietary fork of PrusaSlicer, which is licensed under AGPLv3, requiring any modified version distributed over a network to also be open-source. The alleged violation includes failure to release source code changes and possible inclusion of data-mining features.

hackernews · Tomte · May 23, 08:24 · [Discussion](https://news.ycombinator.com/item?id=48245862)

**Background**: The GNU Affero General Public License (AGPLv3) is a strong copyleft license that requires users who modify and distribute the software over a network to release the complete source code. PrusaSlicer is a popular open-source 3D printing slicer developed by Prusa Research. Bambu Studio is slicing software for Bambu Lab printers, initially based on PrusaSlicer.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GNU_Affero_General_Public_License">GNU Affero General Public License - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/PrusaSlicer">PrusaSlicer - Wikipedia</a></li>
<li><a href="https://bambulab.com/en/download/studio">Software Bambu Studio | Bambu Lab</a></li>

</ul>
</details>

**Discussion**: Commenters expressed strong concerns about intellectual property and data privacy, with some noting that defending open-source licenses is costly and violations are hard to prove. Others debated the risk of data mining by governments, both in China and the US, and some users vowed to avoid closed-source printers for business prototypes.

**Tags**: `#open source`, `#license violation`, `#3D printing`, `#AGPL`, `#intellectual property`

---

<a id="item-16"></a>
## [Robin Li: AI large models near explosion point](https://t.me/zaihuapd/41538) ⭐️ 7.0/10

Baidu CEO Robin Li stated that development of AI large models is near a critical point for application explosion, and revealed that 65% of Baidu's search results now contain generative content, which are prioritized. This signals a major shift in search engine functionality and indicates Baidu's aggressive push to integrate generative AI into its core products, potentially setting a trend for the industry. Baidu started AI reconstruction of all products two years ago, and Li described the search engine overhaul as the most radical among global search engines. The generative content is not only present but prioritized in search results.

telegram · zaihuapd · May 23, 08:40

**Background**: AI large models, such as GPT series and Baidu's ERNIE, are deep learning models trained on vast data to generate human-like text. Integrating them into search engines allows for direct answers and summarizations instead of just links, resembling Microsoft's Copilot integration.

**Tags**: `#AI`, `#large language models`, `#Baidu`, `#generative AI`, `#search engine`

---

<a id="item-17"></a>
## [Corsair Adopts CXMT DRAM for DDR5, Prices Expected to Drop](https://thenextweb.com/news/chinese-dram-cxmt-corsair-ddr5-memory-prices) ⭐️ 7.0/10

Corsair has begun using DRAM chips from China's ChangXin Memory Technologies (CXMT) in its DDR5 memory modules, marking the first mainstream adoption of Chinese-made DRAM in a major brand's consumer products. This shift introduces a new competitor to the DRAM market dominated by Samsung, SK Hynix, and Micron, potentially lowering DDR5 prices for consumers as global supply tightens due to AI-driven demand for high-bandwidth memory. The Corsair Vengeance DDR5 16GB stick using CXMT chips runs at 6,000 MT/s with CL36 timings, matching mainstream performance. CXMT aims for an IPO in 2026 and expects to increase production capacity further.

telegram · zaihuapd · May 23, 11:17

**Background**: The global DRAM market has long been controlled by three major players: Samsung, SK Hynix, and Micron. In recent years, demand for high-bandwidth memory used in AI accelerators has surged, diverting production away from consumer DDR5 modules and causing shortages. ChangXin Memory Technologies (CXMT) is a Chinese DRAM manufacturer that started mass-producing DDR5 chips in late 2024, offering an alternative supply source.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>
<li><a href="https://www.tomshardware.com/pc-components/ddr5/chinese-memory-maker-cxmt-enters-the-mainstream-consumer-memory-with-corsair-vengeance-ddr5-kit-chinese-made-dram-emerges-as-an-antidote-for-crushing-shortages">Chinese memory maker CXMT enters mainstream... | Tom's Hardware</a></li>
<li><a href="https://www.digitalfoundry.net/news/2026/05/corsair-taps-chinese-ddr5-for-its-ram-modules-while-china-developed-gpus-are-improving-fast">Corsair Taps Chinese DDR5 for Its RAM Modules... | Digital Foundry</a></li>

</ul>
</details>

**Discussion**: Community discussions on Reddit highlight cautious optimism, noting that even if US export restrictions block CXMT chips from entering the US market, the increased global supply could lower prices elsewhere and reduce overall demand pressure. Some users question long-term reliability and compatibility, but early tests show equivalent performance.

**Tags**: `#DRAM`, `#DDR5`, `#Corsair`, `#CXMT`, `#memory`, `#supply chain`

---

<a id="item-18"></a>
## [China's daily token calls surge over 1000x in 2 years, hit 140 trillion in March 2025](https://t.me/zaihuapd/41542) ⭐️ 7.0/10

The National Data Administration announced that China's daily token (Token) call volume exceeded 140 trillion in March 2025, up from 100 billion in early 2024, marking a more than 1000-fold increase in two years. This explosive growth signals rapid commercialization of AI in China and the formation of a new value system around token-based data exchange, which is crucial for the AI industry's business model and data economy. The token call volume reached 100 trillion by the end of 2025, and the National Data Administration highlighted that tokens are measurable, pricable, and tradable, facilitating data marketization. The growth reflects progress in reforming data element marketization.

telegram · zaihuapd · May 23, 14:36

**Background**: In the context of large language models (LLMs), a token is the smallest unit of text that a model processes, such as a word, subword, or character. Tokenization breaks down input text into tokens for model processing. The rapid increase in token calls indicates soaring usage of AI services, as each request to an LLM consumes numerous tokens.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mexc.co/news/985902">令牌、代币、通证还 是 词 元 ？— — Token ... | MEXC News</a></li>
<li><a href="https://codebitwave.com/artificial-intelligence-101-tokenizer-and-one-hot/">Artificial Intelligence 101: Tokenizer and One-Hot – CODEBITWAVE</a></li>
<li><a href="https://paper.people.com.cn/rmrb/pc/attachement/202604/03/ebaa4672-39f2-4da9-a084-e137dd7f95de.pdf">paper.people.com.cn/rmrb/pc/attachement/202604/03/ebaa4672-39...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#China`, `#tokenization`, `#data economy`, `#AI infrastructure`

---

<a id="item-19"></a>
## [Deep Dive into the HTML <dl> Element Semantics](https://benmyers.dev/blog/on-the-dl/) ⭐️ 6.0/10

Ben Myers published a detailed blog post exploring the HTML <dl> element, its semantics, and proper usage in modern web development, including examples like a D&D stat sheet. This article clarifies the correct semantic use of <dl> in HTML5, which is often misunderstood as merely a definition list, and emphasizes its role in accessibility and clean markup. The <dl> element is no longer just a 'definition list' in HTML5; it now represents an 'association list' of name-value groups. The article also addresses ARIA role restrictions and practical nesting patterns.

hackernews · ravenical · May 23, 13:03 · [Discussion](https://news.ycombinator.com/item?id=48247325)

**Background**: The HTML <dl> element was traditionally used for definition lists (e.g., glossaries). In HTML5, its semantics were broadened to represent any kind of name-value association, such as metadata or game stats. This change has implications for accessibility and how screen readers interpret the content.

**Discussion**: Community members raised several points: chrismorgan noted ARIA role limitations for <dl> and restrictions on aria-label. jimbosis pointed out the world's first website extensively uses <dl>. captn3m0 expressed surprise about the name change from 'definition list' to 'association list'. cloud-oak asked about nesting <dl> elements, which the article supports. Demiurge praised <dl> and criticized past misuse of tables.

**Tags**: `#HTML`, `#accessibility`, `#web development`, `#semantic markup`

---

<a id="item-20"></a>
## [Rubish: A Unix shell written in pure Ruby](https://github.com/amatsuda/rubish) ⭐️ 6.0/10

A new Unix shell called Rubish, implemented entirely in pure Ruby, has been released on GitHub, enabling users to write shell scripts using Ruby syntax. This project bridges the gap between shell scripting and Ruby, potentially making shell tasks more accessible and powerful for Ruby developers, while also fueling discussions about the pros and cons of language-specific shells. Rubish is not a drop-in replacement for bash; it focuses on Ruby-based scripting. Community comments express concerns about code quality due to possible AI-assisted development and potential performance issues compared to traditional shells.

hackernews · winebarrel · May 23, 06:32 · [Discussion](https://news.ycombinator.com/item?id=48245262)

**Background**: A Unix shell is a command-line interface for interacting with the operating system. Traditional shells like bash use their own scripting languages, but Rubish leverages Ruby, a high-level, readable language. This allows Ruby developers to use familiar syntax and libraries for shell tasks.

**Discussion**: Reactions are mixed: some find the concept amazing but question practicality due to speed and vi input issues; others worry about code quality from AI-assisted coding, while a few appreciate the clever naming. Overall, the project is seen as an interesting experiment.

**Tags**: `#ruby`, `#shell`, `#unix`, `#open-source`

---