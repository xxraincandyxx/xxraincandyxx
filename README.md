<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF4088,50:8B5CF6,100:1B365D&height=190&section=header&text=xxraincandyxx&fontSize=52&fontColor=ffffff&fontAlignY=32&desc=Liyao%20Wu%20%C2%B7%20Language%20Models%20%C2%B7%20Efficient%20Attention%20%C2%B7%20Embodied%20AI&descSize=15&descAlignY=55&animation=fadeIn" width="100%" alt="banner" />

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=400&size=16&duration=3600&pause=888&color=FF4088EE&center=true&width=560&lines=indeed%2C+the+uppermost+is+from+the+lowermost;and+the+lowermost+is+from+the+uppermost)](https://git.io/typing-svg)

<p>
  <a href="https://github.com/xxraincandyxx"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://x.com/xxraincandyxx"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
  <a href="https://blog.000666.com/research"><img src="https://img.shields.io/badge/Research%20Blog-FF4088?style=for-the-badge&logo=hugo&logoColor=white"/></a>
  <a href="https://blog.000666.com/"><img src="https://img.shields.io/badge/Blog-8B5CF6?style=for-the-badge&logo=hugo&logoColor=white"/></a>
  <a href="mailto:xxraincandyxx@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

[![GitHub followers](https://img.shields.io/github/followers/xxraincandyxx?style=social)](https://github.com/xxraincandyxx)
![Profile views](https://komarev.com/ghpvc/?username=xxraincandyxx&color=FF4088&style=flat-square)

</div>

---

## <img src="https://cdn.simpleicons.org/bookstack/FF4088" width="20" height="20" /> About Me

**Liyao Wu** — data science undergraduate at **NJUPT**, researching **long-context language models**, **efficient attention**, **ML infrastructure** and **embodied AI**. Experience spans model pretraining, reproducible evaluation, agent runtimes and robotic control — with independent implementations in **Python, C++ and Rust** (~280k lines maintained, 4,200+ commits in 12 months).

<table>
<tr>
<td width="50%" valign="top">

**Research Interests**

- Long-Context LMs & Efficient Attention (KV cache)
- Test-Time Training & State-Space Memory
- Vision-Language-Action Models & Robotics
- LLM Pretraining & Evaluation Infrastructure
- Quantization & Inference Systems

</td>
<td width="50%" valign="top">

**Currently**

- 📝 **HeadWiseKV** — AAAI 2027, Phase 1 passed
- 📝 **KV Thickets** — under review @ ICLR 2027
- 🤖 VLA + RL/IRL research at TLIBOT
- ⚙️ [Amadeus](https://github.com/xxraincandyxx/Amadeus) agent runtime

</td>
</tr>
</table>

> *"To seek the Truth, amidst the code and wire; With Will to Power, and a soul of fire."*

## <img src="https://cdn.simpleicons.org/workplace/8B5CF6" width="20" height="20" /> Experience

| | | |
| :--- | :--- | :--- |
| 🧪 | [**Tylogi AI**](https://www.tylogi.com) · Model R&D / Algorithm Intern<br><sub>Oct 2025 – Jun 2026</sub> | Pretrained a **1.3B language model**; SFT, continued pretraining, cluster deployment and agent development. Built **openbench**, a local-first evaluation platform that powered all **HeadWiseKV** comparative experiments. |
| 🦾 | [**TLIBOT**](https://www.tlibot.com) · Model R&D / Algorithm Intern<br><sub>Aug 2025 – Present</sub> | Developing **vision-language-action models**; investigating **RL & inverse RL** for robotic manipulation, targeting conference and journal submissions. |

## <img src="https://cdn.simpleicons.org/arxiv/1B365D" width="20" height="20" /> Publications

| Paper | Venue | Role |
| :--- | :--- | :--- |
| **HeadWiseKV** — Budgeted Per-Head Cache Residency for Hybrid Long-Context LMs · [arXiv:2609.02029](https://arxiv.org/abs/2609.02029) | ![AAAI 2027](https://img.shields.io/badge/AAAI_2027-Phase_1_Passed-1B365D?style=flat-square) | 3rd author |
| **KV Thickets** — Task Experts from Random Prefix-Cache Perturbations | ![ICLR 2027](https://img.shields.io/badge/ICLR_2027-Under_Review-8B5CF6?style=flat-square) | 1st author |
| **SSKV** — State-Space Key-Value Memory for Chunked Long-Context Attention · [blog preprint](https://blog.000666.com/research/sskv) | ![Preprint](https://img.shields.io/badge/Preprint-2026-FF4088?style=flat-square) | Sole author |
| Dynamic Energy Efficiency Optimization of Electromagnetic Induction Systems via Transformer-based Guided Ranking Policy Optimization | ![CCDC 2026](https://img.shields.io/badge/CCDC_2026-Accepted-20B2AA?style=flat-square) | 3rd author |

## <img src="https://cdn.simpleicons.org/rocket/FF4088" width="20" height="20" /> Featured Projects

### Research & ML Infrastructure

| Project | Description | Stack |
| :--- | :--- | :--- |
| [**HeadWiseKV**](https://arxiv.org/abs/2609.02029) | Training-free per-head KV-cache residency + deployment-aware sequential calibration (SeqCalib). Extended **Qwen3.6-27B context 114K → 161K** with **−8.59%** peak GPU memory at 112K, quality ≈ full KV cache | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![arXiv](https://img.shields.io/badge/AAAI_2027-1B365D?style=flat-square) |
| [**MFQ**](https://github.com/Tylogi/MFQ) `81★` | Tylogi AI Lab's open-source low-bit quantization & inference stack — mixed-precision calibration, C++ runtime with **CUDA + Metal** backends. Runs the **476 GB DeepSeek V4.1 Flash** checkpoint on a single Mac Studio | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) |
| [**Amadeus**](https://github.com/xxraincandyxx/Amadeus) `136★` | General-purpose agent runtime in **~128k lines of Rust** — ReAct-compatible execution, multi-provider LLMs, MCP integration, three-layer policy gates; one core powers TUI and REST adapters | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Tokio](https://img.shields.io/badge/Tokio-000000?style=flat-square&logo=rust&logoColor=white) |
| **openbench** | Local-first model evaluation workbench — CLI execution, database-backed history, multi-model comparison; **~26k lines** covering LoCoMo, LongBench & RULER | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **SSKV** | State-space KV memory for chunked long-context attention — DeltaNet-style associative writes with exact anchor lanes, unified through a Test-Time-Training lens | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **ConvLlama 1.38B** | Pretrained from scratch on **100B FineWeb-Edu tokens** (4×GPU DDP) via the `metaphor` framework — depthwise-conv + temporal-shift GQA, DeepSWA & MLA ablations | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Ori** | Vision Transformer from scratch in C++/LibTorch — MoE MLPs, RoPE, KV cache, graph tracing. **47k lines** incl. 11k core C++, hand-built without AI-generated code | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![LibTorch](https://img.shields.io/badge/LibTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) |
| **Helios** · **tinfra** · **flux** | LLM toolkit (LoRA, MoE w/ Megatron-LM, vLLM/SGLang inference, 1000+ evals) · Test-Time-Training pipeline (HF/native weights → training → RULER) · 512-agent parallel coding swarm on a Rust hypervisor | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) |

### Agents & Robotics

| Project | Description | Stack |
| :--- | :--- | :--- |
| [**EVA**](https://xxraincandyxx.github.io/EVA-oss/) | Six-DOF robotic arm platform — YOLO/ViT perception, C++ kinematics & control, Transformer VLA model, trilingual Web UI. **~44k lines**; underpins award-winning inspection project ([open demo](https://xxraincandyxx.github.io/EVA-oss/)) | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white) |
| **moscos** | Multi-agent AI social simulation — Phaser world, autonomous agents with local-LLM decisions, dialogue & memory, Drama Mode. **~29k lines** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Phaser](https://img.shields.io/badge/Phaser-FFD700?style=flat-square) |
| **rius** | Sandboxed Python execution environment — Rust/Axum REST API, workspace management, concurrency limits, Docker/nsjail wardens. **~20k lines** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Axum](https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white) |
| **argus** · **aliagent** · **0x2e** | macOS floating AI assistant with screen awareness · multimodal sprite-sheet agent · macOS dotfiles (Neovim, Kitty, Zsh) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

<sub>🔒 Unlinked repositories are private — being prepared for open-source release. Happy to walk through any of them.</sub>

## 🏆 Awards & Honors

| | | |
| :--- | :--- | :--- |
| 🥈 | **MCM/ICM** — Meritorious Winner | Feb 2026 |
| 🥈 | **iCAN** Innovation & Entrepreneurship, AI Challenge — National Second Prize | Dec 2025 |
| 🥈 | National IC Innovation & Entrepreneurship Competition — National Second Prize | Aug 2025 |
| 🥉 | **RoboCup China** — RoboCup@Home Third Prize | May 2026 |
| 🥇 | China Robot & AI Competition — Jiangsu First Prize (→ National Third, Jul 2026) | Jun 2025 |
| 🥇 | National Computer Proficiency Challenge, Big Data — East China First Prize | Nov 2024 |
| 🏅 | GDC DeepSeek-Qwen Distillation Challenge — National Top 10 · Embedded Chip Design — East China Second Prize · Lanqiao Cup · ZTE Pengyue … | 2024–2026 |

<details>
<summary><b>Full list</b></summary>

- Jul 2026 — 28th China Robot & AI Competition, robot innovation: **national third prize**
- Jun 2026 — 28th China Robot & AI Competition: **Jiangsu second prize**
- May 2026 — RoboCup China, **RoboCup@Home: third prize** · rescue robots / autonomous mapping: third prize
- Feb 2026 — **MCM/ICM: Meritorious Winner** (COMAP)
- Dec 2025 — iCAN University Innovation Competition, AI Challenge: **national second prize**
- Aug 2025 — 9th National IC Innovation & Entrepreneurship Competition: **national second prize**
- Aug 2025 — 8th Embedded Chip & System Design Competition: East China second prize
- Aug 2025 — 27th China Robot & AI Competition: national Excellence Award
- Aug 2025 — 1st ZTE Pengyue Competition, NJUPT campus contest: third prize
- Jun 2025 — 27th China Robot & AI Competition: **Jiangsu first prize**
- Jun 2025 — 18th NJUPT Physics & Experiment Technology Innovation Competition: university second prize
- May 2025 — 16th Lanqiao Cup: AI practical projects national-selection second prize · C/C++ Jiangsu second prize
- May 2025 — 15th ZTE Pengyue "Shensuanshi" Algorithm Elite Challenge: regional winner
- Mar 2025 — NJUPT Winter Holiday Challenge: **first prize**
- Feb 2025 — GDC DeepSeek-Qwen Model Distillation Challenge: **national top 10**
- Nov 2024 — 6th National Computer Proficiency Challenge, big data: **East China first prize**

</details>

## <img src="https://cdn.simpleicons.org/stackblitz/4A90D9" width="20" height="20" /> Tech Stack

<div align="center">

**Languages**
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-3D6117?style=for-the-badge&logo=latex&logoColor=white)

**ML Systems**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Megatron-LM](https://img.shields.io/badge/Megatron_LM-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-00A1E4?style=for-the-badge&logo=nvidia&logoColor=white)
![FSDP2](https://img.shields.io/badge/FSDP2-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FFF3E0?style=for-the-badge&logo=vllm&logoColor=FF6F00)
![SGLang](https://img.shields.io/badge/SGLang-FF6F00?style=for-the-badge&logo=python&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-FFFDD0?style=for-the-badge&logo=gnu&logoColor=black)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Systems & Robotics**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Web & Environment**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Axum](https://img.shields.io/badge/Axum-000000?style=for-the-badge&logo=rust&logoColor=white)
![Hugo](https://img.shields.io/badge/Hugo-FF4088?style=for-the-badge&logo=hugo&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Emacs](https://img.shields.io/badge/Emacs-7F5AB6?style=for-the-badge&logo=gnu&logoColor=white)
![Kitty](https://img.shields.io/badge/Kitty-7552CC?style=for-the-badge)
![Zsh](https://img.shields.io/badge/Zsh-F15A24?style=for-the-badge&logo=gnu&logoColor=white)

</div>

## <img src="https://cdn.simpleicons.org/obsidian/8B5CF6" width="20" height="20" /> Notes

- **Style**: Google Style in C++. Snake_case where the camel cannot tread.
- **Philosophy**: A follower of Heidegger's *Dasein* and Nietzsche's *Übermensch*.
- **Melody**: Mozart and Beethoven whilst weaving code. Cooking when the GPU cools.
- **Forged**: RoboCup@Home 2026 — national third prize. Next stop, conference deadlines.

---

<div align="center">

## <img src="https://cdn.simpleicons.org/chartdotjs/FF4088" width="20" height="20" /> Statistics

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xxraincandyxx/xxraincandyxx/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/xxraincandyxx/xxraincandyxx/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/xxraincandyxx/xxraincandyxx/output/github-contribution-grid-snake.svg">
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=xxraincandyxx&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=radical&bg_color=00000000" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=xxraincandyxx&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000" />
  <img height="165em" align="center" alt="github stats" src="https://github-readme-stats.vercel.app/api?username=xxraincandyxx&show_icons=true&include_all_commits=true&count_private=true&hide_border=true" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=xxraincandyxx&layout=compact&langs_count=8&hide_border=true&theme=radical&bg_color=00000000" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=xxraincandyxx&layout=compact&langs_count=8&hide_border=true&bg_color=00000000" />
  <img height="165em" align="center" alt="top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xxraincandyxx&layout=compact&langs_count=8&hide_border=true" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=xxraincandyxx&hide_border=true&background=00000000&ring=FF4088&fire=FF6E97&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=FF4088&sideLabels=AEB6BF&dates=8B949E" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=xxraincandyxx&hide_border=true&background=00000000&ring=FF4088&fire=FF4088&currStreakNum=24292F&sideNums=24292F&currStreakLabel=FF4088&sideLabels=57606A&dates=6E7781" />
  <img height="165em" align="center" alt="github streak" src="https://streak-stats.demolab.com?user=xxraincandyxx&hide_border=true&ring=FF4088" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=xxraincandyxx&bg_color=00000000&color=FFFFFF&title_color=FF4088&line=FF4088&point=FFFFFF&area=true&area_color=8B5CF6&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=xxraincandyxx&bg_color=00000000&color=24292F&title_color=FF4088&line=8B5CF6&point=FF4088&area=true&area_color=C4B5FD&hide_border=true" />
  <img height="180em" alt="activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=xxraincandyxx&hide_border=true" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-trophy.vercel.app/?username=xxraincandyxx&column=4&rank=-C,-B&no-bg=true&no-frame=true&margin-w=8" />
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-trophy.vercel.app/?username=xxraincandyxx&column=4&rank=-C,-B&no-bg=true&no-frame=true&margin-w=8&theme=radical" />
  <img height="180em" alt="trophies" src="https://github-profile-trophy.vercel.app/?username=xxraincandyxx&column=4&rank=-C,-B&no-bg=true&no-frame=true&theme=radical"/>
</picture>

<br/>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="random quote" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B365D,50:8B5CF6,100:FF4088&height=120&section=footer" width="100%" alt="footer" />

</div>
