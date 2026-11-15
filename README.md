<div align="center">

# Awesome Craft DeepSeek [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of official DeepSeek repositories and open-source harnesses, serving engines, eval tools and fine-tuning stacks that work with DeepSeek models.

![Tools](https://img.shields.io/badge/tools-18-6366f1?style=for-the-badge)
[![Categories](https://img.shields.io/badge/categories-6-0ea5e9?style=for-the-badge)](#contents)
[![Combined stars](https://img.shields.io/badge/combined_stars-993.1k-f59e0b?style=for-the-badge&logo=github)](#-leaderboard)
[![Stars](https://img.shields.io/github/stars/EdisonTKPcom/Awesome-Craft-DeepSeek?style=for-the-badge&color=22c55e)](https://github.com/EdisonTKPcom/Awesome-Craft-DeepSeek/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/EdisonTKPcom/Awesome-Craft-DeepSeek?style=for-the-badge&color=ec4899)](https://github.com/EdisonTKPcom/Awesome-Craft-DeepSeek/commits/main)

</div>

DeepSeek Harness (deepseek-ai/deepseek-harness) is the official agent harness from DeepSeek AI. The GitHub licence on a repository usually covers code, examples and sometimes documentation. Model weights often have a separate licence, published in the same repo or on Hugging Face. Confirm both the code licence and the model licence before commercial use. Serving engines listed here also appear in Awesome Craft AI; they are repeated because they document DeepSeek model support. Chat and coding agents that can call a DeepSeek or OpenAI-compatible API are listed in Awesome Craft Agents.

## Contents

- [Dashboard](#dashboard)
- [Official agent harness](#official-agent-harness)
- [Official models and research code](#official-models-and-research-code)
- [Official infrastructure and kernels](#official-infrastructure-and-kernels)
- [Serving engines with DeepSeek support](#serving-engines-with-deepseek-support)
- [Eval and fine-tuning](#eval-and-fine-tuning)
- [Integrations](#integrations)
- [Related lists](#related-lists)
- [Star history](#star-history)


## Dashboard

<table>
<tr>
<td align="center"><h2>18</h2>listed projects</td>
<td align="center"><h2>6</h2>categories</td>
<td align="center"><h2>993.1k</h2>combined GitHub stars</td>
<td align="center"><h2>155.2k</h2>combined forks</td>
<td align="center"><h2>13/18</h2>pushed in the last 30 days</td>
<td align="center"><h2>4</h2>languages</td>
</tr>
</table>

**FACT** (snapshot taken 2026-11-15, GitHub API): 18 listed projects, 18 of them on GitHub with public repository statistics. Official documentation and other non-GitHub entries are listed but have no stars, forks or push dates.

**ESTIMATE**: 993.1k combined GitHub stars and 155.2k combined forks, summed from those API counts on the snapshot date. Live star badges next to GitHub entries may differ.

### 🏆 Leaderboard

<table>
<tr><th>Rank</th><th>Project</th><th>Kind</th><th align="right">Stars</th><th></th></tr>
<tr><td align="center">🥇</td><td><b>DeepSeek Harness</b></td><td>Official agent harness</td><td align="right">281.3k</td><td><code>████████████████████</code></td></tr>
<tr><td align="center">🥈</td><td><b>llama.cpp</b></td><td>Inference engine</td><td align="right">135.1k</td><td><code>██████████</code></td></tr>
<tr><td align="center">🥉</td><td><b>DeepSeek-V3</b></td><td>Model repo</td><td align="right">104.8k</td><td><code>███████</code></td></tr>
<tr><td align="center">4</td><td><b>vLLM</b></td><td>GPU serving</td><td align="right">96.9k</td><td><code>███████</code></td></tr>
<tr><td align="center">5</td><td><b>DeepSeek-R1</b></td><td>Model repo</td><td align="right">92.0k</td><td><code>███████</code></td></tr>
<tr><td align="center">6</td><td><b>LLaMA-Factory</b></td><td>Fine-tuning</td><td align="right">76.0k</td><td><code>█████</code></td></tr>
<tr><td align="center">7</td><td><b>awesome-deepseek-integration</b></td><td>Integration list</td><td align="right">39.9k</td><td><code>███</code></td></tr>
<tr><td align="center">8</td><td><b>SGLang</b></td><td>GPU serving</td><td align="right">38.9k</td><td><code>███</code></td></tr>
<tr><td align="center">9</td><td><b>DeepSeek-Coder</b></td><td>Model repo</td><td align="right">24.4k</td><td><code>██</code></td></tr>
<tr><td align="center">10</td><td><b>KTransformers</b></td><td>Serving engine</td><td align="right">19.7k</td><td><code>█</code></td></tr>
</table>


### Stars by category

```mermaid
pie showData
    title Combined GitHub stars by category
    "Official agent harness" : 281309
    "Official models and research code" : 239012
    "Official infrastructure and kernels" : 44137
    "Serving engines with DeepSeek support" : 290641
    "Eval and fine-tuning" : 98112
    "Integrations" : 39872
```

### Licences

![MIT](https://img.shields.io/badge/MIT-12-64748b?style=flat-square) ![Apache-2.0](https://img.shields.io/badge/Apache--2.0-5-64748b?style=flat-square) ![CC0-1.0](https://img.shields.io/badge/CC0--1.0-1-64748b?style=flat-square)

"Custom" or "None" means GitHub could not match a standard SPDX licence, often because of extra terms or an undeclared licence. Read the project licence before you use it commercially.

## Official agent harness

- [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) - The official DeepSeek agent harness (dsh), built on an everything-is-a-plugin architecture. The project is MIT-licensed and, at the time of this research, described itself as a developer preview with compatibility-breaking changes. Review the safety notice in the repository before running it. ![Stars](https://img.shields.io/github/stars/deepseek-ai/deepseek-harness?style=flat-square&label=%E2%AD%90)

## Official models and research code

- [DeepSeek-Coder](https://github.com/deepseek-ai/DeepSeek-Coder) - Official code and resources for DeepSeek Coder models. The repository licence covers the code; check the model weight licence separately. ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Coder?style=flat-square&label=%E2%AD%90)
- [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) - Official repository for DeepSeek-R1. Confirm the model-weight licence as well as the repository code licence before commercial use or redistribution of weights. ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-R1?style=flat-square&label=%E2%AD%90)
- [DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) - Official repository for DeepSeek-V3. Confirm the model-weight licence as well as the repository code licence before commercial use or redistribution of weights. ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V3?style=flat-square&label=%E2%AD%90)
- [Janus](https://github.com/deepseek-ai/Janus) - Official Janus-series repositories for unified multimodal understanding and generation models. Model and code licences can differ; read both. ![Stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=flat-square&label=%E2%AD%90)

## Official infrastructure and kernels

- [3FS](https://github.com/deepseek-ai/3FS) - A high-performance distributed file system from DeepSeek, aimed at AI training and inference workloads. ![Stars](https://img.shields.io/github/stars/deepseek-ai/3FS?style=flat-square&label=%E2%AD%90)
- [DeepEP](https://github.com/deepseek-ai/DeepEP) - An official expert-parallel communication library from DeepSeek, used in large MoE training and inference stacks. ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepEP?style=flat-square&label=%E2%AD%90)
- [DeepGEMM](https://github.com/deepseek-ai/DeepGEMM) - An official clean and efficient GPU BLAS-style kernel library from DeepSeek. ![Stars](https://img.shields.io/github/stars/deepseek-ai/DeepGEMM?style=flat-square&label=%E2%AD%90)
- [ESFT](https://github.com/deepseek-ai/ESFT) - Official Expert Specialized Fine-Tuning code from DeepSeek. ![Stars](https://img.shields.io/github/stars/deepseek-ai/ESFT?style=flat-square&label=%E2%AD%90)
- [FlashMLA](https://github.com/deepseek-ai/FlashMLA) - Official efficient Multi-head Latent Attention kernels from DeepSeek. ![Stars](https://img.shields.io/github/stars/deepseek-ai/FlashMLA?style=flat-square&label=%E2%AD%90)

## Serving engines with DeepSeek support

- [KTransformers](https://github.com/kvcache-ai/ktransformers) - A serving stack aimed at efficiently running very large models, including DeepSeek-style MoE models, on mixed GPU and CPU setups. Confirm current model support in the project docs. ![Stars](https://img.shields.io/github/stars/kvcache-ai/ktransformers?style=flat-square&label=%E2%AD%90)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - A local inference engine with community support for running DeepSeek-family GGUF models. Also listed in Awesome Craft AI. ![Stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat-square&label=%E2%AD%90)
- [SGLang](https://github.com/sgl-project/sglang) - A high-performance serving engine with documented DeepSeek model support. Also listed in Awesome Craft AI. ![Stars](https://img.shields.io/github/stars/sgl-project/sglang?style=flat-square&label=%E2%AD%90)
- [vLLM](https://github.com/vllm-project/vllm) - A high-throughput GPU serving engine with documented DeepSeek model support. Also listed in Awesome Craft AI. ![Stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square&label=%E2%AD%90)

## Eval and fine-tuning

- [LLaMA-Factory](https://github.com/hiyouga/LlamaFactory) - A widely used open-source fine-tuning toolkit that can train and adapt many model families, including DeepSeek-related models when documented. Confirm current model support and licences. ![Stars](https://img.shields.io/github/stars/hiyouga/LlamaFactory?style=flat-square&label=%E2%AD%90)
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) - A standard open-source evaluation harness for language models, used to run many academic and community benchmarks. ![Stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness?style=flat-square&label=%E2%AD%90)
- [OpenCompass](https://github.com/open-compass/opencompass) - An open-source LLM evaluation platform from the OpenCompass project, used for large-scale model evaluation. ![Stars](https://img.shields.io/github/stars/open-compass/opencompass?style=flat-square&label=%E2%AD%90)

## Integrations

- [awesome-deepseek-integration](https://github.com/deepseek-ai/awesome-deepseek-integration) - An official curated list of software that integrates the DeepSeek API. It is a catalogue, not a runtime. ![Stars](https://img.shields.io/github/stars/deepseek-ai/awesome-deepseek-integration?style=flat-square&label=%E2%AD%90)

## Related lists

Other lists in the Awesome Craft series:

- [Awesome Craft](https://github.com/EdisonTKPcom/Awesome-Craft) - A curated list of open-source, self-hostable alternatives to popular SaaS tools.
- [Awesome Craft Agents](https://github.com/EdisonTKPcom/Awesome-Craft-Agents) - A curated list of open-source chat apps, coding agents, self-hosted agent bots, workflow automation and image-generation UIs.
- [Awesome Craft AI](https://github.com/EdisonTKPcom/Awesome-Craft-AI) - A curated list of open-source, self-hostable AI runtimes, servers, Hugging Face libraries and related infrastructure.
- [Awesome Craft BSC](https://github.com/EdisonTKPcom/Awesome-Craft-BSC) - A curated list of verified open-source clients, SDKs, dev tools and protocol code for BNB Smart Chain and opBNB.
- [Awesome Craft Creative](https://github.com/EdisonTKPcom/Awesome-Craft-Creative) - A curated list of open-source creative apps, including the storytold Craft App Suite and tools for photo, video, animation, 3D, audio and design.
- [Awesome Craft CUDA](https://github.com/EdisonTKPcom/Awesome-Craft-CUDA) - A curated list of open-source CUDA learning material, kernel libraries, tooling and portability projects.
- [Awesome Craft DevOps](https://github.com/EdisonTKPcom/Awesome-Craft-DevOps) - A curated list of open-source, self-hostable alternatives to popular DevOps and hosting SaaS tools.
- [Awesome Craft DNA](https://github.com/EdisonTKPcom/Awesome-Craft-DNA) - A curated list of open-source tools for DNA, genomics and synthetic biology.
- [Awesome Craft Ethereum](https://github.com/EdisonTKPcom/Awesome-Craft-Ethereum) - A curated list of verified open-source Ethereum clients, SDKs, dev frameworks, wallets and security tools.
- [Awesome Craft EV](https://github.com/EdisonTKPcom/Awesome-Craft-EV) - A curated list of open-source software and hardware for electric vehicles and charging.
- [Awesome Craft Hardware](https://github.com/EdisonTKPcom/Awesome-Craft-Hardware) - A curated list of open-source tools for PCB, FPGA, ASIC and chip design.
- [Awesome Craft Hyperliquid](https://github.com/EdisonTKPcom/Awesome-Craft-Hyperliquid) - A curated list of verified open-source SDKs, node tools, analytics and community libraries for the Hyperliquid ecosystem.
- [Awesome Craft Jarvis](https://github.com/EdisonTKPcom/Awesome-Craft-Jarvis) - A curated list of open-source tools to run a personal JARVIS-style AI assistant locally, including dashboards, agent runtimes, voice, MCP connections and memory.
- [Awesome Craft Malaysia](https://github.com/EdisonTKPcom/Awesome-Craft-Malaysia) - A curated list of open-source tools useful to Malaysian SMEs, with verified MyInvois support called out separately.
- [Awesome Craft Mars](https://github.com/EdisonTKPcom/Awesome-Craft-Mars) - A curated list of open-source tools and open data for Mars missions and settlement planning.
- [Awesome Craft Neuro](https://github.com/EdisonTKPcom/Awesome-Craft-Neuro) - A curated list of open-source tools for brain-computer interfaces, electrophysiology and neurotechnology.
- [Awesome Craft Robotics](https://github.com/EdisonTKPcom/Awesome-Craft-Robotics) - A curated list of open-source robotics software and hardware, including Microduck, Unitree SDKs, open humanoids, arms, simulation and middleware.
- [Awesome Craft SecondBrain](https://github.com/EdisonTKPcom/Awesome-Craft-SecondBrain) - A curated list of open-source tools for a personal second brain, including knowledge apps, LLM memory layers, RAG over notes, capture tools, MCP servers and knowledge graphs.
- [Awesome Craft Solana](https://github.com/EdisonTKPcom/Awesome-Craft-Solana) - A curated list of verified open-source Solana clients, SDKs, frameworks, explorers and program libraries.
- [Awesome Craft Space](https://github.com/EdisonTKPcom/Awesome-Craft-Space) - A curated list of open-source tools for spaceflight and rockets, covering orbit simulation, telemetry, launch data and more.
- [Awesome Craft Starlink](https://github.com/EdisonTKPcom/Awesome-Craft-Starlink) - A curated list of open-source tools for Starlink and other LEO satellite internet systems.
- [Awesome Craft Web3](https://github.com/EdisonTKPcom/Awesome-Craft-Web3) - A curated list of open-source DEX protocol code, self-custody software, indexers, frameworks and Blockchain infrastructure.

## Star history

[![Star History Chart](https://api.star-history.com/chart?repos=EdisonTKPcom/Awesome-Craft-DeepSeek&amp;type=Date)](https://www.star-history.com/#EdisonTKPcom/Awesome-Craft-DeepSeek&Date)

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

<div align="center">

If this list is useful, give it a ⭐ so others can find it.

</div>
