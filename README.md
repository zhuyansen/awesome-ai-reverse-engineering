# Awesome AI Reverse Engineering

[中文](README.zh-CN.md)

Open-source **AI reverse engineering tools** for Claude Code, Codex and other agents: Ghidra MCP and IDA Pro MCP servers, jadx and Frida for mobile apps, reverse engineering skills, REA, and programs rebuilt with it. 119 repos, each one read and security-graded by [Agent Skills Hub (agentskillshub.top)](https://agentskillshub.top?utm_source=github&utm_medium=awesome-list).

Live page with filters: **[https://agentskillshub.top/best/ai-reverse-engineering/](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list)** · refreshed every 8 hours

## What these tools look like

<table>
<tr>
<td align="center" valign="top" width="33%"><b>🔬 Disassembler & decompiler MCP</b><br><sub>74 repos</sub><br><br><sub>Servers and plugins that let an agent drive Ghidra, IDA Pro, Binary Ninja, radare2 or x64dbg.</sub><br><a href="#type-mcp"><b>View the list →</b></a></td>
<td align="center" valign="top" width="33%"><b>📱 Mobile app reversing</b><br><sub>18 repos</sub><br><br><sub>jadx, apktool and Frida connected to an agent, for Android, iOS and HarmonyOS apps.</sub><br><a href="#type-mobile"><b>View the list →</b></a></td>
<td align="center" valign="top" width="33%"><b>🌐 Web, JS & protocol reversing</b><br><sub>4 repos</sub><br><br><sub>Obfuscated JavaScript, request signing and traffic analysis.</sub><br><a href="#type-web"><b>View the list →</b></a></td>
</tr>
<tr>
<td align="center" valign="top" width="33%"><b>🧩 Reverse engineering skills</b><br><sub>19 repos</sub><br><br><sub>Skills and workflows that teach an agent how to reverse engineer.</sub><br><a href="#type-skill"><b>View the list →</b></a></td>
<td align="center" valign="top" width="33%"><b>🕹 Reverse-engineered with AI</b><br><sub>4 repos</sub><br><br><sub>Programs rebuilt or analysed with REA; the README of each says so.</sub><br><a href="#type-case"><b>View the list →</b></a></td>
</tr>
</table>

## Contents

- [🔬 Disassembler & decompiler MCP](#type-mcp) (74)
- [📱 Mobile app reversing](#type-mobile) (18)
- [🌐 Web, JS & protocol reversing](#type-web) (4)
- [🧩 Reverse engineering skills](#type-skill) (19)
- [🕹 Reverse-engineered with AI](#type-case) (4)

## How a repo gets on the list

1. Reverse engineering with an AI agent is its main purpose. A general security scanner, a list of links, a copy of another repository, or a tool sold on game cheating or cracking does not count.
2. It is software someone can install or run, not a list of links or a placeholder.
3. It has a README. Without one it cannot be graded.
4. At 50 stars or more it is listed on topic alone. Under 50 it must also clear a README quality bar (shows it working, one-command start, a concrete outcome, complete docs), and have 5 stars.

The questions are answered by a decision model reading each README, not by hand. A repo near a cut-off can land on either side; open an issue if one is misfiled.

<a id="type-mcp"></a>
## 🔬 Disassembler & decompiler MCP

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-mcp)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [morluto/rea](https://github.com/morluto/rea) | 300.2k | Reverse engineer anything with agents, from app behavior down to native binaries. | [SAFE](https://agentskillshub.top/skill/morluto/rea/?utm_source=github&utm_medium=awesome-list) |
| [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) | 13.0k | AI-powered reverse engineering assistant that bridges IDA Pro with language models through MCP. | [SAFE](https://agentskillshub.top/skill/mrexodia/ida-pro-mcp/?utm_source=github&utm_medium=awesome-list) |
| [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | 11.3k | MCP Server for Ghidra | [SAFE](https://agentskillshub.top/skill/LaurieWired/GhidraMCP/?utm_source=github&utm_medium=awesome-list) |
| [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) | 5.7k | Ghidra MCP Server — 200+ MCP tools for AI-powered reverse engineering. GUI plugin + headless server, lazy tool loading, convention enforcement, batch… | [SAFE](https://agentskillshub.top/skill/bethington/ghidra-mcp/?utm_source=github&utm_medium=awesome-list) |
| [duty1g/x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server) | 2.5k | x64dbg-MCP Server is a native MCP (Model Context Protocol) plugin for x64dbg that exposes the debugger's full functionality over HTTP. Connect any MC… | [SAFE](https://agentskillshub.top/skill/duty1g/x64dbg-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [P4nda0s/IDA-NO-MCP](https://github.com/P4nda0s/IDA-NO-MCP) | 2.1k | Say goodbye to the complex, verbose, and laggy interaction mode of IDA Pro MCP | [SAFE](https://agentskillshub.top/skill/P4nda0s/IDA-NO-MCP/?utm_source=github&utm_medium=awesome-list) |
| [angusdevgo/Seep-Reverse-Lab](https://github.com/angusdevgo/Seep-Reverse-Lab) | 1.6k | Agent-Native multi-platform reverse engineering and CWE-602 client-side authorization audit workbench. | [SAFE](https://agentskillshub.top/skill/angusdevgo/Seep-Reverse-Lab/?utm_source=github&utm_medium=awesome-list) |
| [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) | 1.3k | Open-source AI reverse-engineering agent platform and MCP server for Ghidra, Frida, x64dbg and Rizin — automated PE/APK/binary analysis, CTF and malw… | [SAFE](https://agentskillshub.top/skill/LING71671/open-reverselab/?utm_source=github&utm_medium=awesome-list) |
| [HexRaysSA/ida-mcp](https://github.com/HexRaysSA/ida-mcp) | 1.2k | Official Hex-Rays IDA MCP Server. | [SAFE](https://agentskillshub.top/skill/HexRaysSA/ida-mcp/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/reverser_ai](https://github.com/mrphrazer/reverser_ai) | 1.2k | Provides automated reverse engineering assistance through the use of local large language models (LLMs) on consumer hardware. | [SAFE](https://agentskillshub.top/skill/mrphrazer/reverser_ai/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/IDAssist](https://github.com/symgraph/IDAssist) | 883 | AI-Powered Reverse Engineering Plugin for IDA Pro | [SAFE](https://agentskillshub.top/skill/symgraph/IDAssist/?utm_source=github&utm_medium=awesome-list) |
| [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) | 876 | MCP server for reverse engineering tasks in Ghidra 👩‍💻 | [SAFE](https://agentskillshub.top/skill/cyberkaida/reverse-engineering-assistant/?utm_source=github&utm_medium=awesome-list) |
| [blacktop/ida-mcp-rs](https://github.com/blacktop/ida-mcp-rs) | 871 | Headless IDA Pro MCP Server | [SAFE](https://agentskillshub.top/skill/blacktop/ida-mcp-rs/?utm_source=github&utm_medium=awesome-list) |
| [weirdmachine64/GhidraGPT](https://github.com/weirdmachine64/GhidraGPT) | 828 | Integrate LLM models directly into Ghidra for AI-enhanced reverse engineering. | [SAFE](https://agentskillshub.top/skill/weirdmachine64/GhidraGPT/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) | 775 | An native MCP server extension for Ghidra | [SAFE](https://agentskillshub.top/skill/symgraph/GhidrAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [AgentSmithers/x64DbgMCPServer](https://github.com/AgentSmithers/x64DbgMCPServer) | 735 | x64DbgMCPServer made from c# with Claude, Windsurf and Cursor support | [SAFE](https://agentskillshub.top/skill/AgentSmithers/x64DbgMCPServer/?utm_source=github&utm_medium=awesome-list) |
| [buzzer-re/Rikugan](https://github.com/buzzer-re/Rikugan) | 690 | A reverse-engineering agent for IDA Pro and Binary Ninja | [SAFE](https://agentskillshub.top/skill/buzzer-re/Rikugan/?utm_source=github&utm_medium=awesome-list) |
| [Wasdubya/x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP) | 598 | Model Context Protocol for x64dbg & x32dbg | [SAFE](https://agentskillshub.top/skill/Wasdubya/x64dbgMCP/?utm_source=github&utm_medium=awesome-list) |
| [MxIris-Reverse-Engineering/ida-mcp-server](https://github.com/MxIris-Reverse-Engineering/ida-mcp-server) | 548 | A Model Context Protocol server for IDA | [SAFE](https://agentskillshub.top/skill/MxIris-Reverse-Engineering/ida-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [SetsunaYukiOvO/x64dbg-mcp](https://github.com/SetsunaYukiOvO/x64dbg-mcp) | 523 | MCP server plugin for x64dbg debugger - enables AI agents and external tools to control debugging via JSON-RPC 2.0 over HTTP/SSE | [SAFE](https://agentskillshub.top/skill/SetsunaYukiOvO/x64dbg-mcp/?utm_source=github&utm_medium=awesome-list) |
| [llnl/OGhidra](https://github.com/llnl/OGhidra) | 456 | OGhidra bridges Large Language Models (LLMs) via Ollama with the Ghidra reverse engineering platform, enabling AI-driven binary analysis through natu… | [SAFE](https://agentskillshub.top/skill/llnl/OGhidra/?utm_source=github&utm_medium=awesome-list) |
| [MeroZemory/ida-multi-mcp](https://github.com/MeroZemory/ida-multi-mcp) | 454 | Multi-instance IDA Pro MCP server — analyze multiple binaries simultaneously through a single MCP endpoint. | [SAFE](https://agentskillshub.top/skill/MeroZemory/ida-multi-mcp/?utm_source=github&utm_medium=awesome-list) |
| [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) | 454 | A Binary Ninja plugin containing an MCP server that enables seamless integration with your favorite LLM/MCP client. | [SAFE](https://agentskillshub.top/skill/fosdickio/binary_ninja_mcp/?utm_source=github&utm_medium=awesome-list) |
| [Claude-Reverser/IDA-instances-MCP](https://github.com/Claude-Reverser/IDA-instances-MCP) | 453 | Custom build of ida-pro-mcp - stability-hardened MCP server for hosting headless IDA Pro instances | [SAFE](https://agentskillshub.top/skill/Claude-Reverser/IDA-instances-MCP/?utm_source=github&utm_medium=awesome-list) |
| [clearbluejar/pyghidra-mcp](https://github.com/clearbluejar/pyghidra-mcp) | 446 | Python Command-Line Ghidra MCP | [SAFE](https://agentskillshub.top/skill/clearbluejar/pyghidra-mcp/?utm_source=github&utm_medium=awesome-list) |
| [cellebrite-labs/ghidra-rpc](https://github.com/cellebrite-labs/ghidra-rpc) | 385 | A Ghidra agentic reverse engineering skill. | [SAFE](https://agentskillshub.top/skill/cellebrite-labs/ghidra-rpc/?utm_source=github&utm_medium=awesome-list) |
| [radareorg/radare2-mcp](https://github.com/radareorg/radare2-mcp) | 325 | MCP stdio server for radare2 | [SAFE](https://agentskillshub.top/skill/radareorg/radare2-mcp/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/agentic-malware-analysis](https://github.com/mrphrazer/agentic-malware-analysis) | 316 | Agentic malware analysis environment with MCP-connected disassemblers, RE tooling, and structured workflows for Claude Code and Codex CLI. | [SAFE](https://agentskillshub.top/skill/mrphrazer/agentic-malware-analysis/?utm_source=github&utm_medium=awesome-list) |
| [Recurse-Labs/recurse](https://github.com/Recurse-Labs/recurse) | 295 | AI Native IDE for reverse engineering | [SAFE](https://agentskillshub.top/skill/Recurse-Labs/recurse/?utm_source=github&utm_medium=awesome-list) |
| [saileaxh/iida-mcp](https://github.com/saileaxh/iida-mcp) | 286 | Faster, with excellent architecture, stronger performance, and kernel access support — an ida-mcp tool | [SAFE](https://agentskillshub.top/skill/saileaxh/iida-mcp/?utm_source=github&utm_medium=awesome-list) |
| [namename333/idapromcp_333](https://github.com/namename333/idapromcp_333) | 284 | 本项目基于 [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) 二次开发，轻量化了一些功能，在大项目逆向中占用更小，消耗更少token | [SAFE](https://agentskillshub.top/skill/namename333/idapromcp_333/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/binary-ninja-headless-mcp](https://github.com/mrphrazer/binary-ninja-headless-mcp) | 257 | Headless Binary Ninja MCP server — giving AI agents deep reverse-engineering capabilities via 180 tools. | [SAFE](https://agentskillshub.top/skill/mrphrazer/binary-ninja-headless-mcp/?utm_source=github&utm_medium=awesome-list) |
| [JameZUK/Arkana](https://github.com/JameZUK/Arkana) | 248 | Arkana - Your entire malware analysis lab, behind one AI prompt. 250+ MCP tools for binary analysis with Claude Code or other MCP | [SAFE](https://agentskillshub.top/skill/JameZUK/Arkana/?utm_source=github&utm_medium=awesome-list) |
| [Captain-AI-Hub/IDA-MCP](https://github.com/Captain-AI-Hub/IDA-MCP) | 246 | IDA MCP | [SAFE](https://agentskillshub.top/skill/Captain-AI-Hub/IDA-MCP/?utm_source=github&utm_medium=awesome-list) |
| [akiselev/ghidra-cli](https://github.com/akiselev/ghidra-cli) | 246 | Automate Ghidra reverse engineering from the command line — headless analysis, decompilation, and structured JSON output for AI agents like Claude Co… | [SAFE](https://agentskillshub.top/skill/akiselev/ghidra-cli/?utm_source=github&utm_medium=awesome-list) |
| [banteg/bn](https://github.com/banteg/bn) | 219 | binary ninja cli for coding agents | [SAFE](https://agentskillshub.top/skill/banteg/bn/?utm_source=github&utm_medium=awesome-list) |
| [OwenPawl/cerberus-re-skill](https://github.com/OwenPawl/cerberus-re-skill) | 217 | cerberus-re is a local Apple-focused reverse-engineering workbench for building a repeatable three-headed static/dynamic/instrumentation loop around… | [SAFE](https://agentskillshub.top/skill/OwenPawl/cerberus-re-skill/?utm_source=github&utm_medium=awesome-list) |
| [sjkim1127/Reversecore_MCP](https://github.com/sjkim1127/Reversecore_MCP) | 211 | A security-first MCP server that empowers AI agents to perform automated reverse engineering, malware analysis, forensics, vulnerability research, an… | [SAFE](https://agentskillshub.top/skill/sjkim1127/Reversecore_MCP/?utm_source=github&utm_medium=awesome-list) |
| [bilieebiliee1-design/SOMCP](https://github.com/bilieebiliee1-design/SOMCP) | 210 | SOMCP 是一个运行在 Android 手机上的本地 SO 逆向 MCP 服务器。它通过 Streamable HTTP 暴露 MCP 工具，让客户端可以在手机上完成 ELF 结构分析、Rizin 反汇编/分析、LIEF ELF 修复/重写、补丁会话、构建导出、Cloudflare Tunnel… | [SAFE](https://agentskillshub.top/skill/bilieebiliee1-design/SOMCP/?utm_source=github&utm_medium=awesome-list) |
| [dariushoule/x64dbg-skills](https://github.com/dariushoule/x64dbg-skills) | 210 | Claude Code plugin providing skills for x64dbg debugger automation | [SAFE](https://agentskillshub.top/skill/dariushoule/x64dbg-skills/?utm_source=github&utm_medium=awesome-list) |
| [biniamf/ai-reverse-engineering](https://github.com/biniamf/ai-reverse-engineering) | 206 | AI-Assisted Reverse Engineering with Ghidra | [SAFE](https://agentskillshub.top/skill/biniamf/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list) |
| [index-login/MobileRE-Skill](https://github.com/index-login/MobileRE-Skill) | 194 | AI Agent 驱动的移动端逆向技能集：Frida hook、一键脱壳、反检测绕过、内存 DEX dump、Ghidra MCP 符号/结构恢复。AI-agent skill system for mobile reverse engineering. | [SAFE](https://agentskillshub.top/skill/index-login/MobileRE-Skill/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/ghidra-headless-mcp](https://github.com/mrphrazer/ghidra-headless-mcp) | 193 | Headless Ghidra MCP server — giving AI agents deep reverse-engineering capabilities. | [SAFE](https://agentskillshub.top/skill/mrphrazer/ghidra-headless-mcp/?utm_source=github&utm_medium=awesome-list) |
| [taida957789/ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin) | 190 | IDA Pro Plugin for serving MCP SSE server for cursor / claude | [SAFE](https://agentskillshub.top/skill/taida957789/ida-mcp-server-plugin/?utm_source=github&utm_medium=awesome-list) |
| [axelmierczuk/tenrec](https://github.com/axelmierczuk/tenrec) | 178 | A headless, extendable, multi-session, IDA Pro MCP framework. | [SAFE](https://agentskillshub.top/skill/axelmierczuk/tenrec/?utm_source=github&utm_medium=awesome-list) |
| [jtsylve/re-mcp](https://github.com/jtsylve/re-mcp) | 174 | A headless MCP server for IDA Pro and Ghidra | [SAFE](https://agentskillshub.top/skill/jtsylve/re-mcp/?utm_source=github&utm_medium=awesome-list) |
| [Fausto-404/ai-mobile-reverse-skills](https://github.com/Fausto-404/ai-mobile-reverse-skills) | 171 | 面向移动安全分析场景的 6 阶段总控 Skill。用于统一调度 APK 静态侦察、流量与代码对齐、SO/JNI 深度分析、加密与漏洞综合分析、验证设计与报告交付流程。支持 JADX MCP、Burp/Yakit MCP、IDA/Ghidra MCP。 | [SAFE](https://agentskillshub.top/skill/Fausto-404/ai-mobile-reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) | 148 | Active Socket based MCP Server for Ghidra | [SAFE](https://agentskillshub.top/skill/13bm/GhidraMCP/?utm_source=github&utm_medium=awesome-list) |
| [philsajdak/decyx](https://github.com/philsajdak/decyx) | 139 | Decyx: AI-powered Ghidra extension for enhanced reverse engineering and binary analysis. | [SAFE](https://agentskillshub.top/skill/philsajdak/decyx/?utm_source=github&utm_medium=awesome-list) |
| [bromoket/x64dbg_mcp](https://github.com/bromoket/x64dbg_mcp) | 132 | Drive x64dbg with your AI. MCP server: 23 mega-tools / 153 endpoints for breakpoints, memory, disasm, tracing, anti-debug & PE dumping. Claude/Cursor… | [SAFE](https://agentskillshub.top/skill/bromoket/x64dbg_mcp/?utm_source=github&utm_medium=awesome-list) |
| [TsingShui/ida-agent-bridge](https://github.com/TsingShui/ida-agent-bridge) | 110 | A CLI-first, headless, AI-native IDA Pro bridge built on Unix philosophy. | [SAFE](https://agentskillshub.top/skill/TsingShui/ida-agent-bridge/?utm_source=github&utm_medium=awesome-list) |
| [WPeace-HcH/WPeGPT-Analyzer](https://github.com/WPeace-HcH/WPeGPT-Analyzer) | 107 | 可移植的逆向分析 SKILL 技能，驱动 IDA + WPeGPT 插件，对 PE/ELF 进行三种模式的自动化分析（轻量/全量/漏洞），输出分析报告。支持 SKILL 技能机制的 AI Agent 均可加载使用。 | [SAFE](https://agentskillshub.top/skill/WPeace-HcH/WPeGPT-Analyzer/?utm_source=github&utm_medium=awesome-list) |
| [fdrechsler/mcp-server-idapro](https://github.com/fdrechsler/mcp-server-idapro) | 101 | A Model Context Protocol (MCP) server that enables AI assistants to interact with IDA Pro for reverse engineering and binary analysis tasks. | [SAFE](https://agentskillshub.top/skill/fdrechsler/mcp-server-idapro/?utm_source=github&utm_medium=awesome-list) |
| [themixednuts/GhidraMCP](https://github.com/themixednuts/GhidraMCP) | 90 |  | [SAFE](https://agentskillshub.top/skill/themixednuts/GhidraMCP/?utm_source=github&utm_medium=awesome-list) |
| [president-xd/revula](https://github.com/president-xd/revula) | 84 | A fully functional and production-grade reverse engineering MCP Server | [SAFE](https://agentskillshub.top/skill/president-xd/revula/?utm_source=github&utm_medium=awesome-list) |
| [sgInnora/sentinel-reverse](https://github.com/sgInnora/sentinel-reverse) | 84 | AI-Powered Autonomous Binary Reverse Engineering CLI — the native reverse engine from Innora-Sentinel. Local LLM inference (MLX), MPS GPU acceleratio… | [SAFE](https://agentskillshub.top/skill/sgInnora/sentinel-reverse/?utm_source=github&utm_medium=awesome-list) |
| [r0ysue/r0idamcp](https://github.com/r0ysue/r0idamcp) | 82 | r0idamcp is a SSE protocal MCP server IDA pro plugin designed for automatic reverse engineering with LLM assistant | [SAFE](https://agentskillshub.top/skill/r0ysue/r0idamcp/?utm_source=github&utm_medium=awesome-list) |
| [elliottophellia/Ryuumonbuchi](https://github.com/elliottophellia/Ryuumonbuchi) | 79 | Maybe the headless Ghidra MCP you are looking for. | [SAFE](https://agentskillshub.top/skill/elliottophellia/Ryuumonbuchi/?utm_source=github&utm_medium=awesome-list) |
| [icloudza/algokiller-plugin](https://github.com/icloudza/algokiller-plugin) | 78 | ARM64 trace evidence analysis & cipher algorithm recovery — Claude Desktop plugin with skills + local MCP server driving the native ak_search engine… | [SAFE](https://agentskillshub.top/skill/icloudza/algokiller-plugin/?utm_source=github&utm_medium=awesome-list) |
| [CSIT-SG/AETHER](https://github.com/CSIT-SG/AETHER) | 76 | An AI-powered reverse-engineering copilot for assisting tedious malware analysis in IDA Pro. | [SAFE](https://agentskillshub.top/skill/CSIT-SG/AETHER/?utm_source=github&utm_medium=awesome-list) |
| [Invoke-RE/binja-lattice-mcp](https://github.com/Invoke-RE/binja-lattice-mcp) | 67 | Plugin interface for remote communications with Binary Ninja database and MCP server for interfacing with LLMs. | [SAFE](https://agentskillshub.top/skill/Invoke-RE/binja-lattice-mcp/?utm_source=github&utm_medium=awesome-list) |
| [HLND2T/CS2_VibeSignatures](https://github.com/HLND2T/CS2_VibeSignatures) | 66 | Generate CS2 signatures via Agent SKILLS with ida-pro-mcp | [SAFE](https://agentskillshub.top/skill/HLND2T/CS2_VibeSignatures/?utm_source=github&utm_medium=awesome-list) |
| [pandaadir05/re-architect](https://github.com/pandaadir05/re-architect) | 66 | Advanced reverse engineering platform combining traditional static analysis with AI-powered insights. Supports multiple decompilers (Ghidra, IDA Pro,… | [SAFE](https://agentskillshub.top/skill/pandaadir05/re-architect/?utm_source=github&utm_medium=awesome-list) |
| [PhoenixHairpin/mcp-termux](https://github.com/PhoenixHairpin/mcp-termux) | 63 | MCP RE v7.0 — Android逆向工程一体化MCP服务器 \| 73个工具 \| stackplz eBPF + paradise内存 + radare2静态分析 \| ARM64 Root | [SAFE](https://agentskillshub.top/skill/PhoenixHairpin/mcp-termux/?utm_source=github&utm_medium=awesome-list) |
| [dariushoule/x64dbg-rippy](https://github.com/dariushoule/x64dbg-rippy) | 62 | AI reverse engineering assistant for x64dbg. Embeds a chat panel directly in the debugger with tool-use capabilities. | [SAFE](https://agentskillshub.top/skill/dariushoule/x64dbg-rippy/?utm_source=github&utm_medium=awesome-list) |
| [trailofbits/idac](https://github.com/trailofbits/idac) | 58 | idac - IDA Pro command line tool for agents and humans | [SAFE](https://agentskillshub.top/skill/trailofbits/idac/?utm_source=github&utm_medium=awesome-list) |
| [SuZiXunYue/ida-script-mcp](https://github.com/SuZiXunYue/ida-script-mcp) | 54 |  | [SAFE](https://agentskillshub.top/skill/SuZiXunYue/ida-script-mcp/?utm_source=github&utm_medium=awesome-list) |
| [xxipv6/IDA-PRO-MCP-multiple](https://github.com/xxipv6/IDA-PRO-MCP-multiple) | 53 | 支持ida headless 多文件分析 | [CAUTION](https://agentskillshub.top/skill/xxipv6/IDA-PRO-MCP-multiple/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/IDAssistMCP](https://github.com/symgraph/IDAssistMCP) | 52 | Standalone MCP server plugin for IDA Pro. | [SAFE](https://agentskillshub.top/skill/symgraph/IDAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [MCPPhalanx/binaryninja-mcp](https://github.com/MCPPhalanx/binaryninja-mcp) | 51 | Another™ MCP Server for Binary Ninja with superpower 🥵 | [SAFE](https://agentskillshub.top/skill/MCPPhalanx/binaryninja-mcp/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/BinAssistMCP](https://github.com/symgraph/BinAssistMCP) | 50 | Binary Ninja plugin to provide MCP functionality. | [SAFE](https://agentskillshub.top/skill/symgraph/BinAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [cycloarcane/ghidra-mcp-setup](https://github.com/cycloarcane/ghidra-mcp-setup) | 6 | Turnkey installer + tutorial for hooking Ghidra to Claude, gemini-cli, or Ollama via the Model Context Protocol. | [CAUTION](https://agentskillshub.top/skill/cycloarcane/ghidra-mcp-setup/?utm_source=github&utm_medium=awesome-list) |
| [fantay0312/ida-pro-mcp-plus](https://github.com/fantay0312/ida-pro-mcp-plus) | 6 | Enhanced IDA Pro MCP Server - multi-instance broker + bulk export for AI analysis | [SAFE](https://agentskillshub.top/skill/fantay0312/ida-pro-mcp-plus/?utm_source=github&utm_medium=awesome-list) |
| [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) | 3 | Headless IDA Pro binary analysis via Model Context Protocol | [SAFE](https://agentskillshub.top/skill/zboralski/ida-headless-mcp/?utm_source=github&utm_medium=awesome-list) |

<a id="type-mobile"></a>
## 📱 Mobile app reversing

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-mobile)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) | 2.9k | Plugin for JADX to integrate MCP server | [SAFE](https://agentskillshub.top/skill/zinja-coder/jadx-ai-mcp/?utm_source=github&utm_medium=awesome-list) |
| [zinja-coder/jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server) | 804 | MCP server for JADX-AI Plugin | [SAFE](https://agentskillshub.top/skill/zinja-coder/jadx-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [lkimuk/ReArk](https://github.com/lkimuk/ReArk) | 682 | An intelligent reverse engineering and AI-assisted analysis tool for HarmonyOS NEXT (HAP/APP/ABC), Android (APK/AAB), iOS (IPA), and native PE/ELF/Ma… | [SAFE](https://agentskillshub.top/skill/lkimuk/ReArk/?utm_source=github&utm_medium=awesome-list) |
| [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) | 672 | A MCP Server for APK Tool (Part of Android Reverse Engineering MCP Suites) | [SAFE](https://agentskillshub.top/skill/zinja-coder/apktool-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [dnakov/frida-mcp](https://github.com/dnakov/frida-mcp) | 456 | MCP stdio server for frida | [SAFE](https://agentskillshub.top/skill/dnakov/frida-mcp/?utm_source=github&utm_medium=awesome-list) |
| [flankerhqd/jebmcp](https://github.com/flankerhqd/jebmcp) | 262 |  | [SAFE](https://agentskillshub.top/skill/flankerhqd/jebmcp/?utm_source=github&utm_medium=awesome-list) |
| [kggzs/ApkMCP-Auto](https://github.com/kggzs/ApkMCP-Auto) | 223 | 本项目是一个 Android 逆向工程工具集合，通过 MCP (Model Context Protocol) 协议将 AI 助手（如 Claude）与专业的 Android 反编译工具连接起来，实现智能化的 APK 分析与修改。 | [SAFE](https://agentskillshub.top/skill/kggzs/ApkMCP-Auto/?utm_source=github&utm_medium=awesome-list) |
| [ZSA233/frida-analykit](https://github.com/ZSA233/frida-analykit) | 156 | Frida 工具包 - 主要面向安卓端逆向，解决frida环境版本管理和对Agent端常用底层工具方法封装，支持MCP。（目前主要由AI开发维护代码） | [SAFE](https://agentskillshub.top/skill/ZSA233/frida-analykit/?utm_source=github&utm_medium=awesome-list) |
| [FuzzySecurity/kahlo-mcp](https://github.com/FuzzySecurity/kahlo-mcp) | 137 | A Frida MCP server to enable autonomous AI assistance for Android instrumentation | [SAFE](https://agentskillshub.top/skill/FuzzySecurity/kahlo-mcp/?utm_source=github&utm_medium=awesome-list) |
| [zhizhuodemao/frida-mcp](https://github.com/zhizhuodemao/frida-mcp) | 121 | 一个用于frida动态调试的mcp工具，支持自定义frida路径和名称端口,自动管理frida | [SAFE](https://agentskillshub.top/skill/zhizhuodemao/frida-mcp/?utm_source=github&utm_medium=awesome-list) |
| [asLody/dexdec](https://github.com/asLody/dexdec) | 117 | Fast, accurate Android decompilation for humans and AI agents. | [SAFE](https://agentskillshub.top/skill/asLody/dexdec/?utm_source=github&utm_medium=awesome-list) |
| [mobilehackinglab/jadx-mcp-plugin](https://github.com/mobilehackinglab/jadx-mcp-plugin) | 104 |  | [SAFE](https://agentskillshub.top/skill/mobilehackinglab/jadx-mcp-plugin/?utm_source=github&utm_medium=awesome-list) |
| [1013503897/jadx-headless-mcp](https://github.com/1013503897/jadx-headless-mcp) | 94 | Headless MCP server for Android APK static analysis, built directly on jadx-core. No JADX GUI required. | [SAFE](https://agentskillshub.top/skill/1013503897/jadx-headless-mcp/?utm_source=github&utm_medium=awesome-list) |
| [samanL33T/jadx-xvision-plugin](https://github.com/samanL33T/jadx-xvision-plugin) | 72 | xVision is a plugin for the JadX decompiler that aims to integrate with Large Language Models (LLMs) to provide code analysis directly in the JAdX. | [SAFE](https://agentskillshub.top/skill/samanL33T/jadx-xvision-plugin/?utm_source=github&utm_medium=awesome-list) |
| [TheQmaks/areclaw](https://github.com/TheQmaks/areclaw) | 71 | Android Reverse Engineering Command-Line Automation Workspace. AI-driven security analysis with Claude Code. | [SAFE](https://agentskillshub.top/skill/TheQmaks/areclaw/?utm_source=github&utm_medium=awesome-list) |
| [1193776794/frida-mcp](https://github.com/1193776794/frida-mcp) | 70 |  | [SAFE](https://agentskillshub.top/skill/1193776794/frida-mcp/?utm_source=github&utm_medium=awesome-list) |
| [s4dp4nd4/frida-c2-mcp](https://github.com/s4dp4nd4/frida-c2-mcp) | 70 | Agentic C2-style MCP server for Frida instrumentation on rooted Android and jailbroken iOS. | [SAFE](https://agentskillshub.top/skill/s4dp4nd4/frida-c2-mcp/?utm_source=github&utm_medium=awesome-list) |
| [crissyfield/super-trouper](https://github.com/crissyfield/super-trouper) | 57 | MCP server for Frida. | [SAFE](https://agentskillshub.top/skill/crissyfield/super-trouper/?utm_source=github&utm_medium=awesome-list) |

<a id="type-web"></a>
## 🌐 Web, JS & protocol reversing

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-web)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [vmoranv/jshookmcp](https://github.com/vmoranv/jshookmcp) | 2.1k | A search-first, profile-aware reverse-engineering workspace for AI agents — 735 tools across 36 domains in one MCP server. | [SAFE](https://agentskillshub.top/skill/vmoranv/jshookmcp/?utm_source=github&utm_medium=awesome-list) |
| [wuji66dde/jshook-skill](https://github.com/wuji66dde/jshook-skill) | 270 | AI-powered JS reverse engineering: deobfuscation, crypto detection, CDP debugging, hook injection, anti-detection \| AI驱动JS逆向：反混淆、加密识别、CDP调试、Hook注入、反… | [SAFE](https://agentskillshub.top/skill/wuji66dde/jshook-skill/?utm_source=github&utm_medium=awesome-list) |
| [WhiteNightShadow/wx-mp-mcp](https://github.com/WhiteNightShadow/wx-mp-mcp) | 249 | 微信小程序逆向 MCP — 在线实时解包 + AI 静态分析还原接口签名/加密，产出本地 Node.js 直接能跑的脚本（零侵入，不碰微信进程） | [SAFE](https://agentskillshub.top/skill/WhiteNightShadow/wx-mp-mcp/?utm_source=github&utm_medium=awesome-list) |
| [amd2g2zz/kunglao-agent](https://github.com/amd2g2zz/kunglao-agent) | 53 | The reverse-engineering expert agent: plans its own analysis path, derives every fact from raw evidence, and converges under mechanical verification… | [SAFE](https://agentskillshub.top/skill/amd2g2zz/kunglao-agent/?utm_source=github&utm_medium=awesome-list) |

<a id="type-skill"></a>
## 🧩 Reverse engineering skills

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-skill)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 42.4k | Reverse Engineering / Authorized Penetration Testing / Security Research Skill Router Pack AI-powered routing + On-demand toolchain bootstrapping + S… | [SAFE](https://agentskillshub.top/skill/zhaoxuya520/reverse-skill/?utm_source=github&utm_medium=awesome-list) |
| [SimoneAvogadro/android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) | 8.2k | Claude Code skill to support Android app's reverse engineering | [SAFE](https://agentskillshub.top/skill/SimoneAvogadro/android-reverse-engineering-skill/?utm_source=github&utm_medium=awesome-list) |
| [P4nda0s/reverse-skills](https://github.com/P4nda0s/reverse-skills) | 2.3k | Reverse engineering skills for Claude Code \| 逆向工程 Claude Code Skills 插件 | [SAFE](https://agentskillshub.top/skill/P4nda0s/reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [Dryxio/reagent](https://github.com/Dryxio/reagent) | 2.1k | Reconstruct and validate C/C++ code from compiled programs with AI. | [SAFE](https://agentskillshub.top/skill/Dryxio/reagent/?utm_source=github&utm_medium=awesome-list) |
| [2akouwu/reverify](https://github.com/2akouwu/reverify) | 1.3k | Stop your AI from making things up — it proposes, deterministic tools decide, every claim checked against ground truth with evidence. Grounded facts… | [SAFE](https://agentskillshub.top/skill/2akouwu/reverify/?utm_source=github&utm_medium=awesome-list) |
| [CreditTone/android-reverse-engineering-skill](https://github.com/CreditTone/android-reverse-engineering-skill) | 549 | 这是一套专为 Codex 适配的 Android 逆向分析 skill，支持在 Codex 会话中反编译 APK、XAPK、JAR、AAR，并结合 jadx、Fernflower/Vineflower 梳理 Manifest、包结构、网络层和调用链。它可辅助提取接口、URL、鉴权头、token 与… | [SAFE](https://agentskillshub.top/skill/CreditTone/android-reverse-engineering-skill/?utm_source=github&utm_medium=awesome-list) |
| [schlarpc/re-shell](https://github.com/schlarpc/re-shell) | 535 | Nix-powered agentic reverse engineering environment | [CAUTION](https://agentskillshub.top/skill/schlarpc/re-shell/?utm_source=github&utm_medium=awesome-list) |
| [manyuegong33/r0crawl_skills](https://github.com/manyuegong33/r0crawl_skills) | 332 | r0crawl_skills is a massive reverse-engineering skill arsenal for web, Android, iOS, Frida, native binaries, protocols, malware, firmware, and anti-a… | [SAFE](https://agentskillshub.top/skill/manyuegong33/r0crawl_skills/?utm_source=github&utm_medium=awesome-list) |
| [miunasu/IDA-Skill](https://github.com/miunasu/IDA-Skill) | 237 | 使用skill让 AI Agent 像安全分析师一样分析恶意样本 \| AI Agent skill for automated malware analysis using IDA Pro | [SAFE](https://agentskillshub.top/skill/miunasu/IDA-Skill/?utm_source=github&utm_medium=awesome-list) |
| [Ablation-Tool/ablation](https://github.com/Ablation-Tool/ablation) | 214 | Ablation is an autonomous reverse engineering system. | [SAFE](https://agentskillshub.top/skill/Ablation-Tool/ablation/?utm_source=github&utm_medium=awesome-list) |
| [vgrichina/re-skill](https://github.com/vgrichina/re-skill) | 171 | Claude Code skill for reverse engineering retro games — disassemble, annotate, extract assets, web port | [SAFE](https://agentskillshub.top/skill/vgrichina/re-skill/?utm_source=github&utm_medium=awesome-list) |
| [incogbyte/android-reverse-engineering-claude-skill](https://github.com/incogbyte/android-reverse-engineering-claude-skill) | 126 | Claude Code skill that automates Android application reverse engineering | [SAFE](https://agentskillshub.top/skill/incogbyte/android-reverse-engineering-claude-skill/?utm_source=github&utm_medium=awesome-list) |
| [pardeike/DecompilerServer](https://github.com/pardeike/DecompilerServer) | 121 | A powerful MCP (Model Context Protocol) server for decompiling and analyzing .NET assemblies, with specialized support for Unity's Assembly-CSharp.dl… | [SAFE](https://agentskillshub.top/skill/pardeike/DecompilerServer/?utm_source=github&utm_medium=awesome-list) |
| [haikow/claude-reverse-skills](https://github.com/haikow/claude-reverse-skills) | 118 | Claude Code 逆向工程 skill 集合 (apk/ida/radare2/js) + IDA MCP 接入，跨平台 Linux/Mac/Windows | [SAFE](https://agentskillshub.top/skill/haikow/claude-reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [tihanyin/REx-skill](https://github.com/tihanyin/REx-skill) | 112 | REx@Skill - Agentic Reverse Engineering eXecution Skill for binary vulnerability discovery | [SAFE](https://agentskillshub.top/skill/tihanyin/REx-skill/?utm_source=github&utm_medium=awesome-list) |
| [incogbyte/iOS-reverse-engineering-claude-skill](https://github.com/incogbyte/iOS-reverse-engineering-claude-skill) | 107 | Claude Code skill that enables Claude to extract, analyze, reverse engineer iOS apps | [SAFE](https://agentskillshub.top/skill/incogbyte/iOS-reverse-engineering-claude-skill/?utm_source=github&utm_medium=awesome-list) |
| [Karib0u/kernagent](https://github.com/Karib0u/kernagent) | 103 | Headless AI agent for deterministic reverse engineering. | [SAFE](https://agentskillshub.top/skill/Karib0u/kernagent/?utm_source=github&utm_medium=awesome-list) |
| [blacktop/ipsw-skill](https://github.com/blacktop/ipsw-skill) | 96 | A SKILL.md for ipsw | [SAFE](https://agentskillshub.top/skill/blacktop/ipsw-skill/?utm_source=github&utm_medium=awesome-list) |
| [Mo271-del/BloxAgent-Studio-Bridge](https://github.com/Mo271-del/BloxAgent-Studio-Bridge) | 68 | BloxAgent 2026: AI-Powered Luau Reverse Engineering and Roblox Script Automation Framework | [SAFE](https://agentskillshub.top/skill/Mo271-del/BloxAgent-Studio-Bridge/?utm_source=github&utm_medium=awesome-list) |

<a id="type-case"></a>
## 🕹 Reverse-engineered with AI

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-case)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [N0zoM1z0/dx-ball](https://github.com/N0zoM1z0/dx-ball) | 63 | Reconstructing DX-Ball 1.07 with REA, backed by original-x86 differential tests and pinned MSVC byte-exact oracles. | [SAFE](https://agentskillshub.top/skill/N0zoM1z0/dx-ball/?utm_source=github&utm_medium=awesome-list) |
| [davehornik/WH3SaveEditor](https://github.com/davehornik/WH3SaveEditor) | 6 | Warhammer 3 Save Editor | [SAFE](https://agentskillshub.top/skill/davehornik/WH3SaveEditor/?utm_source=github&utm_medium=awesome-list) |
| [NullLabTests/OpenBSD_netcat_REA](https://github.com/NullLabTests/OpenBSD_netcat_REA) | 3 | Reverse-engineering the netcat-openbsd 1.234-1 binary with REA (Reverse Engineer Anything) + Ghidra | [SAFE](https://agentskillshub.top/skill/NullLabTests/OpenBSD_netcat_REA/?utm_source=github&utm_medium=awesome-list) |
| [OceanJy333/meteor-mac](https://github.com/OceanJy333/meteor-mac) | 2 | 在 Apple Silicon Mac 上直接运行原版《流星蝴蝶剑》Meteor.exe：REA 逆向 + AI 写 Win32/DirectX→Mac 接口，不用 Wine；附老 Windows 程序移植 Mac 的 AI Skill | [SAFE](https://agentskillshub.top/skill/OceanJy333/meteor-mac/?utm_source=github&utm_medium=awesome-list) |

**Security** is the grade of the repo's README and install steps on Agent Skills Hub. *pending* means the catalog has not graded it yet.

Preview images are reduced copies of pictures from each project's own README, included only for projects under a permissive license. Sources and licenses: [assets/previews/NOTICE.md](assets/previews/NOTICE.md). Open an issue to have one removed.

## Related collections

- [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills), [zhuyansen/awesome-codex-ppt-skills](https://github.com/zhuyansen/awesome-codex-ppt-skills) — lists built the same way.

## Add a repo

Open an issue with the GitHub URL. It goes through the same review as every entry; the rules above decide, stars do not.

---

Machine-readable copy: [`data/skills.json`](data/skills.json). Generated 2026-10-17.
