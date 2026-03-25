# 🖥️ Computer-Use Agents: An Overview of Terminal-Based and GUI-Based Approaches

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of papers, tools, and benchmarks on **computer-use agents**: systems that let LLMs operate computers through terminals or graphical interfaces.

We organize this collection into two families:

- **Terminal / CLI-Based Agents** interact with computers through text interfaces: shell commands, file I/O, and code execution. This category spans five stages of development: code completion, chat assistants, autonomous coding agents, general-purpose sandbox agents, and personal AI assistants.
- **GUI-Based Agents** perceive and act on graphical interfaces through mouse clicks, keyboard input, and screen observation. We cover web agents, desktop/OS agents, and mobile agents, each with distinct perception strategies and challenges.

> **Note**: This is a preliminary collection and is by no means exhaustive. Many important papers and tools are likely missing. If you know of work that should be included, please open a PR or issue. Contributions of all kinds are welcome!

We also wrote a short report discussing the development and architecture of these systems: [report (PDF)](computer_use_agent_overview.pdf).

Contributions welcome! Please open a PR.

---

## Table of Contents

- [Terminal / CLI-Based Agents](#terminal--cli-based-agents)
  - [Code Completion](#code-completion)
  - [Chat-Based Coding Assistants](#chat-based-coding-assistants)
  - [Autonomous Coding Agents](#autonomous-coding-agents)
  - [General Agents](#general-agents)
  - [Personal AI Assistants](#personal-ai-assistants)
- [GUI-Based Agents](#gui-based-agents)
  - [Web Agents](#web-agents)
  - [Desktop / OS Agents](#desktop--os-agents)
  - [Mobile Agents](#mobile-agents)
- [Benchmarks](#benchmarks)
- [Foundational Work](#foundational-work)

---

## Terminal / CLI-Based Agents

### Code Completion

| Name | Year | Type | Links |
|------|------|------|-------|
| **Codex** | 2021 | Model | [Paper](https://arxiv.org/abs/2107.03374) |
| **GitHub Copilot** | 2021 | Product | [Website](https://github.com/features/copilot) |
| **Codeium** | 2022 | Product | [Website](https://codeium.com) |

### Chat-Based Coding Assistants

| Name | Year | Type | Links |
|------|------|------|-------|
| **ChatGPT** | 2022 | Product | [Website](https://chatgpt.com) |
| **Cursor** | 2024 | Product | [Website](https://cursor.com) |
| **Aider** | 2024 | Open Source | [GitHub](https://github.com/aider-ai/aider) |

### Autonomous Coding Agents

#### Research Frameworks

| Name | Year | Type | Links |
|------|------|------|-------|
| **SWE-Agent** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2405.15793) · [GitHub](https://github.com/princeton-nlp/SWE-agent) |
| **OpenHands** (OpenDevin) | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2407.16741) · [GitHub](https://github.com/All-Hands-AI/OpenHands) |
| **AutoCodeRover** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2404.05427) · [GitHub](https://github.com/nus-apr/auto-code-rover) |
| **Agentless** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2407.01489) · [GitHub](https://github.com/OpenAutoCoder/Agentless) |
| **CodeAct** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2402.01030) |

#### Product Agents

| Name | Year | Type | Links |
|------|------|------|-------|
| **Devin** | 2024 | Product | [Website](https://devin.ai) |
| **Claude Code** | 2025 | Product | [Docs](https://docs.anthropic.com/en/docs/claude-code) |
| **Codex CLI** | 2025 | Product | [GitHub](https://github.com/openai/codex) |
| **Gemini CLI** | 2025 | Product | [GitHub](https://github.com/google-gemini/gemini-cli) |

#### IDE-Integrated

| Name | Year | Type | Links |
|------|------|------|-------|
| **Cursor Agent Mode** | 2025 | Product | [Website](https://cursor.com) |
| **Windsurf** (Codeium) | 2025 | Product | [Website](https://windsurf.com) |

### General Agents

| Name | Year | Type | Links |
|------|------|------|-------|
| **Open Interpreter** | 2023 | Open Source | [Website](https://www.openinterpreter.com) · [GitHub](https://github.com/OpenInterpreter/open-interpreter) |
| **Manus** | 2025 | Product | [Website](https://manus.im) |
| **Agent SDK** (Anthropic) | 2025 | Product | [Docs](https://platform.claude.com/docs/en/agent-sdk/overview) |
| **LLM-in-Sandbox** | 2026 | Paper + Code | [Paper](https://arxiv.org/abs/2601.16206) · [GitHub](https://github.com/llm-in-sandbox/llm-in-sandbox) |

### Personal AI Assistants

| Name | Year | Type | Links |
|------|------|------|-------|
| **OpenClaw** | 2025 | Open Source | [GitHub](https://github.com/openclaw/openclaw) · [Website](https://openclaw.ai) |

---

## GUI-Based Agents

### Web Agents

| Name | Year | Type | Links |
|------|------|------|-------|
| **Mind2Web** | 2023 | Paper + Data | [Paper](https://arxiv.org/abs/2306.06070) · [GitHub](https://github.com/OSU-NLP-Group/Mind2Web) |
| **SeeAct** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2401.01614) · [GitHub](https://github.com/OSU-NLP-Group/SeeAct) |
| **WebVoyager** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2401.13919) |
| **WebArena** | 2023 | Benchmark + Paper | [Paper](https://arxiv.org/abs/2307.13854) · [GitHub](https://github.com/web-arena-x/webarena) |
| **Browser Use** | 2025 | Open Source | [GitHub](https://github.com/browser-use/browser-use) |
| **Operator** (OpenAI) | 2025 | Product | [Blog](https://openai.com/index/introducing-operator) |
| **Project Mariner** (Google) | 2025 | Product | [Blog](https://deepmind.google/models/project-mariner/) |

### Desktop / OS Agents

| Name | Year | Type | Links |
|------|------|------|-------|
| **Computer Use** (Anthropic) | 2024 | API | [Blog](https://www.anthropic.com/news/developing-computer-use) |
| **CogAgent** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2312.08914) · [GitHub](https://github.com/THUDM/CogAgent) |
| **ScreenAgent** | 2024 | Paper | [Paper](https://arxiv.org/abs/2402.07945) |
| **UFO** (Microsoft) | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2402.07939) · [GitHub](https://github.com/microsoft/UFO) |
| **Set-of-Mark (SoM)** | 2023 | Paper | [Paper](https://arxiv.org/abs/2310.11441) |
| **OmniParser** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2408.00203) · [GitHub](https://github.com/microsoft/OmniParser) |
| **OS-Copilot** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2402.07456) |
| **UI-TARS** (ByteDance) | 2025 | Paper | [Paper](https://arxiv.org/abs/2501.12326) |
| **UI-TARS-2** | 2025 | Paper | [Paper](https://arxiv.org/abs/2509.02544) |

### Mobile Agents

| Name | Year | Type | Links |
|------|------|------|-------|
| **AppAgent** | 2024 | Paper + Code | [Paper](https://arxiv.org/abs/2312.13771) |
| **Mobile-Agent-v3** | 2025 | Paper + Code | [Paper](https://arxiv.org/abs/2508.15144) |

---

## Benchmarks

| Name | Domain | Year | Links |
|------|--------|------|-------|
| **GAIA** | General AI assistant | 2023 | [Paper](https://arxiv.org/abs/2311.12983) |
| **SWE-bench** | Coding (Python) | 2024 | [Paper](https://arxiv.org/abs/2310.06770) · [Website](https://www.swebench.com) |
| **WebArena** | Web browsing | 2023 | [Paper](https://arxiv.org/abs/2307.13854) · [Website](https://webarena.dev) |
| **VisualWebArena** | Visual web tasks | 2024 | [Paper](https://arxiv.org/abs/2401.13649) |
| **OSWorld** | Desktop OS | 2024 | [Paper](https://arxiv.org/abs/2404.07972) · [GitHub](https://github.com/xlang-ai/OSWorld) |
| **AndroidWorld** | Mobile (Android) | 2024 | [Paper](https://arxiv.org/abs/2405.14573) |
| **TheAgentCompany** | Multi-tool (company sim) | 2024 | [Paper](https://arxiv.org/abs/2412.14161) · [Website](https://the-agent-company.com/) |
| **Terminal-Bench** | CLI tasks (diverse) | 2026 | [Paper](https://arxiv.org/abs/2601.11868) · [Website](https://www.tbench.ai/) |

---

## Foundational Work

| Name | Year | Links |
|------|------|-------|
| **ReAct**: Synergizing Reasoning and Acting in Language Models | 2023 | [Paper](https://arxiv.org/abs/2210.03629) |
| **Toolformer**: Language Models Can Teach Themselves to Use Tools | 2023 | [Paper](https://arxiv.org/abs/2302.04761) |
| **Codex**: Evaluating Large Language Models Trained on Code | 2021 | [Paper](https://arxiv.org/abs/2107.03374) |
| **GPT-4** Technical Report | 2023 | [Paper](https://arxiv.org/abs/2303.08774) |
| **Plan-and-Solve** Prompting | 2023 | [Paper](https://arxiv.org/abs/2305.04091) |
| **AdaPlanner**: Adaptive Planning from Feedback | 2023 | [Paper](https://arxiv.org/abs/2305.16653) |
| **Tree of Thoughts** | 2023 | [Paper](https://arxiv.org/abs/2305.10601) |
| **LLM Debate**: Improving Factuality through Multiagent Debate | 2024 | [Paper](https://arxiv.org/abs/2305.14325) |

---

## Contributing

PRs welcome! When adding an entry, please include:
- Name, year, and type (Paper / Product / Open Source)
- Links to paper (arXiv preferred), code (GitHub), and website

## License

[MIT](LICENSE)

## Citation

If you find this list helpful, please give it a ⭐!

```bibtex
@misc{cheng2026awesomecomputeruseagents,
  title={Awesome Computer-Use Agents},
  author={Cheng, Daixuan},
  year={2026},
  howpublished={\url{https://github.com/cdxeve/awesome-computer-use-agents}},
}
```
