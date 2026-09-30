# Hey, I'm Owen 👋

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=26&duration=3500&pause=900&color=3B82F6&center=true&vCenter=true&repeat=true&width=760&height=50&lines=AI+Engineer+%7C+AI+Agents+%7C+Automation;Claude+%7C+Claude+Code+%7C+MCP+%7C+AI+Agents;Python+%7C+Whisper+%7C+FFmpeg+%7C+HyperFrames;Turning+slow+manual+work+into+fast+AI+workflows" alt="AI Engineer: AI agents and automation. Claude, Claude Code, MCP and AI agents. Python, Whisper, FFmpeg and HyperFrames." />
</div>

**AI Engineer.** I build AI tools, agents and automations that turn slow, manual work into fast, reliable workflows: video editing, documents, research, classroom tasks and trading analysis. Most of my building now runs through Claude Code, with custom skills, MCP servers and automatic quality checks that I set up myself.

Until 2026 I taught IT in college, so a big part of my work is helping people use AI well.

Based in Pangasinan, Philippines. Open to remote work.

[![Available for Work](https://img.shields.io/badge/Available_for_Work-brightgreen?style=flat-square)](https://carlowenbelen.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-carlowenbelen-181717?style=flat-square&logo=github)](https://github.com/carlowenbelen)
[![Portfolio](https://img.shields.io/badge/Portfolio-carlowenbelen.github.io-3B82F6?style=flat-square&logo=googlechrome&logoColor=white)](https://carlowenbelen.github.io)

---

## 🤖 Building with AI

### AI tools I've built

| Project | What the AI actually does |
| --- | --- |
| **AI Video Editing Pipeline** | Turns raw footage into a finished YouTube video or Short. Whisper transcribes on the GPU, and a rough-cut engine removes fillers, stutters and retakes. It then adds HyperFrames motion graphics, captions, sound effects, music ducking and -14 LUFS loudness. Claude plans the edit, and the laptop does the rendering. |
| **TradingView MCP Upgrade** | I upgraded an open-source TradingView MCP server that lets Claude write, compile-check and chart Pine Script on a live chart. I added 5 tools: 4 self-healing browser controls and an OHLC reader. I also rewrote the backtest and timeframe tools with fallbacks after TradingView's September 2026 layout change. |
| [**Swarm AI**](https://github.com/carlowenbelen/swarm-ai) | Five Claude agents with different personas answer one hard question in parallel. A synthesizer agent then writes the consensus with an agreement score. |
| [**CVE Watchlist**](https://github.com/carlowenbelen/cve-watchlist) | Pulls new CVEs from the NIST database and keeps only the ones that hit your tech stack. Claude then turns them into a plain-English security briefing, with fixes. |
| **Faceless YouTube Automation** | Claude Code writes original stories. Free text-to-speech narrates them with synced captions, and FFmpeg builds 8 to 25 minute compilations on a daily schedule. |
| **AI Photo Enhancer** | Local Real-ESRGAN upscaling plus GFPGAN face restoration, tuned to keep faces looking natural. It runs fully offline. |

`Claude` `Claude Code` `MCP` `Whisper` `HyperFrames` `FFmpeg` `Real-ESRGAN` `GFPGAN` `PyTorch` `OpenCV`

### How I build

I use Claude Code as my main engineering tool and set it up like a small team:

- **Custom skills** for jobs I repeat. For example, an `/edit-video` skill runs the whole editing pipeline while using very few credits.
- **MCP servers and connectors** so Claude can use real tools: market data, charts, the browser, Google Drive and Canva.
- **Project memory** and `CLAUDE.md` instruction files, so every session starts with the full context.
- **"Claude plans, the machine does the heavy work."** Whisper on the GPU, FFmpeg with NVENC and local AI models all run offline, so costs stay low.
- **Automatic checks** before anything counts as done. The scripts check exact length, loudness, audio and video sync, and page counts, and render preview frames.

I test every tool on real files before I call it finished.

---

## 💻 Tech stack

**AI and agents**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-191919?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![NotebookLM](https://img.shields.io/badge/NotebookLM-000000?style=flat-square&logo=notebooklm&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-10A37F?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)
![MQL5](https://img.shields.io/badge/MQL5-4A76B8?style=flat-square)
![Pine Script](https://img.shields.io/badge/Pine_Script-131722?style=flat-square&logo=tradingview&logoColor=white)

**Media, documents and automation**

![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![HyperFrames](https://img.shields.io/badge/HyperFrames-7C3AED?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-B31B1B?style=flat-square)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white)

**Data and tools**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![NVIDIA CUDA](https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 🛠️ What I specialize in

**AI workflow automation.** I take a slow manual process, like editing a video, encoding exam questions or fixing PDFs, and turn it into a one-command tool.

**AI media pipelines.** Speech-to-text, automatic editing, captions, motion graphics and photo restoration, all running locally on a laptop GPU.

**Claude tooling.** MCP integrations, custom skills and project memory that make Claude useful for real work, not just chat.

**Security-minded building.** I'm taking a Master in IT (Cybersecurity). I keep secrets out of code and use safe defaults.

**Teaching AI.** I taught web development and security in college, with Claude, Gemini and NotebookLM built into my classes.

---

## 💼 Experience

| Period | Role | Organization | Location |
| --- | --- | --- | --- |
| 2025 - 2026 | College Instructor, College of Information Technology | **University of Eastern Pangasinan** | Binalonan, PH |
| 2022 - 2026 | AI and Web Specialist | **Freelance** | Remote |
| 2020 - 2021 | Inventory and Expenses Associate | **Jhonever Metal Corporation** | Pangasinan, PH |
| 2019 | IT Support Team Leader | **Bonsai Liga** | Binalonan, PH |

A few highlights:

- **Teaching (2025 to 2026).** I taught Web Development and Security courses with Claude, Gemini and NotebookLM built in. AI-assisted workflows cut my lesson prep time by 40%. I also built a NotebookLM research base of 50+ cybersecurity papers and virtual labs for penetration-testing practice.
- **Freelance.** I automated data-analysis and code-generation workflows with AI to cut client turnaround time. I also built a browser-based interactive learning app in JavaScript for an education client.

---

## 📌 Featured work

<table>
<tr>
<td width="50%">

**🐝 Swarm AI**

A multi-agent consensus tool. Five Claude personas analyze in parallel, then a synthesizer writes the answer and an agreement score.

**Tech**: Python, Anthropic API, asyncio

[Repo](https://github.com/carlowenbelen/swarm-ai)

</td>
<td width="50%">

**🛡️ CVE Watchlist**

A daily AI security briefing. It uses NIST NVD data filtered to your stack and explained by Claude in plain English.

**Tech**: Python, NVD API, Claude, httpx

[Repo](https://github.com/carlowenbelen/cve-watchlist)

</td>
</tr>
<tr>
<td width="50%">

**🎬 AI Video Editing Pipeline**

Raw footage to a finished video with one command: rough cut, audio cleanup, motion graphics, captions, sound design and a 9:16 reframe for Shorts.

**Tech**: Python, faster-whisper, FFmpeg, HyperFrames, GSAP

Public repo coming soon

</td>
<td width="50%">

**📄 Offline PDF Toolkit**

A desktop app with 31 PDF tools: merge, split, compress, OCR, convert, sign, redact and compare. It runs fully offline.

**Tech**: Python, PyMuPDF, RapidOCR, Ghostscript, Tkinter

Private for now

</td>
</tr>
<tr>
<td width="50%">

**🎲 Trading Strategy Monte Carlo**

A stress test for a trading strategy. It runs 10,000 simulated equity curves to show drawdowns, risk of ruin, and best and worst cases.

**Tech**: Python, NumPy, Matplotlib

[Repo](https://github.com/carlowenbelen/trading-strategy-monte-carlo)

</td>
<td width="50%">

**🎯 Portfolio Optimizer**

Markowitz efficient frontier, max-Sharpe and min-variance portfolios, and the capital market line for any basket of assets.

**Tech**: Python, SciPy, pandas, yfinance

[Repo](https://github.com/carlowenbelen/portfolio-optimizer)

</td>
</tr>
<tr>
<td width="50%">

**🧪 Bayesian A/B Calculator**

It gives the probability that B beats A, the expected lift and loss, and a ship, kill or keep-testing verdict.

**Tech**: Python, NumPy, SciPy

[Repo](https://github.com/carlowenbelen/bayesian-ab-calculator)

</td>
<td width="50%">

**📝 Question Form Automator**

A Chrome extension that fills quiz questions from text files into a school LMS and Google Forms, so no one has to type them in by hand.

**Tech**: JavaScript, Chrome Extensions (Manifest V3)

Private for now

</td>
</tr>
</table>

🌐 **More about me**: [carlowenbelen.github.io](https://carlowenbelen.github.io)

---

## 📊 By the numbers

<div align="center">

| What | Figure |
| :--- | :--- |
| Tools in my offline PDF toolkit | 31 |
| Tools I added to an open-source MCP server | 5 |
| Motion-graphic templates in my video pipeline | 10 |
| Rough cut of a 3-minute video | about 60 seconds |
| Lesson prep time saved with AI | 40% |
| Papers in my NotebookLM security research base | 50+ |

</div>

---

## 📈 Stats

### Streak and activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=carlowenbelen&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub streak stats" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/output/github-snake.svg" />
  </picture>
</div>

### Profile summary

<div align="center">
  <img src="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/main/profile-summary-card-output/tokyonight/0-profile-details.svg" alt="Profile details" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/main/profile-summary-card-output/tokyonight/1-repos-per-language.svg" width="48%" alt="Repositories per language" />
  <img src="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/main/profile-summary-card-output/tokyonight/2-most-commit-language.svg" width="48%" alt="Most committed language" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/main/profile-summary-card-output/tokyonight/3-stats.svg" width="48%" alt="GitHub stats" />
  <img src="https://raw.githubusercontent.com/carlowenbelen/carlowenbelen/main/profile-summary-card-output/tokyonight/4-productive-time.svg" width="48%" alt="Most productive time" />
</div>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random dev quote" />
</div>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=carlowenbelen&style=for-the-badge&color=3b82f6" alt="Profile views"/>
<img src="https://img.shields.io/github/stars/carlowenbelen?style=for-the-badge&logo=github&logoColor=white&color=3b82f6" alt="GitHub stars"/>

</div>

---

## 📬 Get in touch

I'm open to remote work in AI engineering, AI automation and AI video editing, and to client builds.

- **Portfolio**: [carlowenbelen.github.io](https://carlowenbelen.github.io)
- **GitHub**: [github.com/carlowenbelen](https://github.com/carlowenbelen)

---

<div align="center">

**Always learning. Always building.**

</div>
