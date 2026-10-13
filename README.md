# Awesome AI Reverse Engineering

[中文](README.zh-CN.md)

Open-source **AI reverse engineering tools** for Claude Code, Codex and other agents: Ghidra MCP and IDA Pro MCP servers, jadx and Frida for mobile apps, reverse engineering skills, REA, and programs rebuilt with it. 63 repos, each one read and security-graded by [Agent Skills Hub](https://agentskillshub.top?utm_source=github&utm_medium=awesome-list).

Live page with filters: **[https://agentskillshub.top/best/ai-reverse-engineering/](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list)** · refreshed every 8 hours

## What these tools look like

<table>
<tr>
<td align="center" valign="top" width="33%"><b>🔬 Disassembler & decompiler MCP</b><br><sub>38 repos</sub><br><br><sub>Servers and plugins that let an agent drive Ghidra, IDA Pro, Binary Ninja, radare2 or x64dbg.</sub><br><a href="#type-mcp"><b>View the list →</b></a></td>
<td align="center" valign="top" width="33%"><b>📱 Mobile app reversing</b><br><sub>9 repos</sub><br><br><sub>jadx, apktool and Frida connected to an agent, for Android, iOS and HarmonyOS apps.</sub><br><a href="#type-mobile"><b>View the list →</b></a></td>
<td align="center" valign="top" width="33%"><b>🌐 Web, JS & protocol reversing</b><br><sub>1 repos</sub><br><br><sub>Obfuscated JavaScript, request signing and traffic analysis.</sub><br><a href="#type-web"><b>View the list →</b></a></td>
</tr>
<tr>
<td align="center" valign="top" width="33%"><b>🧩 Reverse engineering skills</b><br><sub>14 repos</sub><br><br><sub>Skills and workflows that teach an agent how to reverse engineer.</sub><br><a href="#type-skill"><b>View the list →</b></a></td>
<td align="center" valign="top" width="33%"><b>🕹 Reverse-engineered with AI</b><br><sub>1 repos</sub><br><br><sub>Programs rebuilt or analysed with REA; the README of each says so.</sub><br><a href="#type-case"><b>View the list →</b></a></td>
</tr>
</table>

## Contents

- [🔬 Disassembler & decompiler MCP](#type-mcp) (38)
- [📱 Mobile app reversing](#type-mobile) (9)
- [🌐 Web, JS & protocol reversing](#type-web) (1)
- [🧩 Reverse engineering skills](#type-skill) (14)
- [🕹 Reverse-engineered with AI](#type-case) (1)

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
| [morluto/rea](https://github.com/morluto/rea) | 182.5k | Reverse engineer anything with agents, from app behavior down to native binaries. | [SAFE](https://agentskillshub.top/skill/morluto/rea/?utm_source=github&utm_medium=awesome-list) |
| [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) | 12.7k | AI-powered reverse engineering assistant that bridges IDA Pro with language models through MCP. | [SAFE](https://agentskillshub.top/skill/mrexodia/ida-pro-mcp/?utm_source=github&utm_medium=awesome-list) |
| [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | 11.2k | MCP Server for Ghidra | [SAFE](https://agentskillshub.top/skill/LaurieWired/GhidraMCP/?utm_source=github&utm_medium=awesome-list) |
| [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) | 5.5k | Ghidra MCP Server — 200+ MCP tools for AI-powered reverse engineering. GUI plugin + headless server, lazy tool loading, convention enforcement, batch… | [SAFE](https://agentskillshub.top/skill/bethington/ghidra-mcp/?utm_source=github&utm_medium=awesome-list) |
| [duty1g/x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server) | 2.5k | x64dbg-MCP Server is a native MCP (Model Context Protocol) plugin for x64dbg that exposes the debugger's full functionality over HTTP. Connect any MC… | [SAFE](https://agentskillshub.top/skill/duty1g/x64dbg-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) | 1.3k | Open-source AI reverse-engineering agent platform and MCP server for Ghidra, Frida, x64dbg and Rizin — automated PE/APK/binary analysis, CTF and malw… | [SAFE](https://agentskillshub.top/skill/LING71671/open-reverselab/?utm_source=github&utm_medium=awesome-list) |
| [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) | 871 | MCP server for reverse engineering tasks in Ghidra 👩‍💻 | [SAFE](https://agentskillshub.top/skill/cyberkaida/reverse-engineering-assistant/?utm_source=github&utm_medium=awesome-list) |
| [blacktop/ida-mcp-rs](https://github.com/blacktop/ida-mcp-rs) | 864 | Headless IDA Pro MCP Server | [SAFE](https://agentskillshub.top/skill/blacktop/ida-mcp-rs/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) | 770 | An native MCP server extension for Ghidra | [SAFE](https://agentskillshub.top/skill/symgraph/GhidrAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [Wasdubya/x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP) | 594 | Model Context Protocol for x64dbg & x32dbg | [SAFE](https://agentskillshub.top/skill/Wasdubya/x64dbgMCP/?utm_source=github&utm_medium=awesome-list) |
| [MxIris-Reverse-Engineering/ida-mcp-server](https://github.com/MxIris-Reverse-Engineering/ida-mcp-server) | 547 | A Model Context Protocol server for IDA | [SAFE](https://agentskillshub.top/skill/MxIris-Reverse-Engineering/ida-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [SetsunaYukiOvO/x64dbg-mcp](https://github.com/SetsunaYukiOvO/x64dbg-mcp) | 520 | MCP server plugin for x64dbg debugger - enables AI agents and external tools to control debugging via JSON-RPC 2.0 over HTTP/SSE | [SAFE](https://agentskillshub.top/skill/SetsunaYukiOvO/x64dbg-mcp/?utm_source=github&utm_medium=awesome-list) |
| [Claude-Reverser/IDA-instances-MCP](https://github.com/Claude-Reverser/IDA-instances-MCP) | 459 | Custom build of ida-pro-mcp - stability-hardened MCP server for hosting headless IDA Pro instances | [SAFE](https://agentskillshub.top/skill/Claude-Reverser/IDA-instances-MCP/?utm_source=github&utm_medium=awesome-list) |
| [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) | 452 | A Binary Ninja plugin containing an MCP server that enables seamless integration with your favorite LLM/MCP client. | [SAFE](https://agentskillshub.top/skill/fosdickio/binary_ninja_mcp/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/agentic-malware-analysis](https://github.com/mrphrazer/agentic-malware-analysis) | 311 | Agentic malware analysis environment with MCP-connected disassemblers, RE tooling, and structured workflows for Claude Code and Codex CLI. | [SAFE](https://agentskillshub.top/skill/mrphrazer/agentic-malware-analysis/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/binary-ninja-headless-mcp](https://github.com/mrphrazer/binary-ninja-headless-mcp) | 256 | Headless Binary Ninja MCP server — giving AI agents deep reverse-engineering capabilities via 180 tools. | [SAFE](https://agentskillshub.top/skill/mrphrazer/binary-ninja-headless-mcp/?utm_source=github&utm_medium=awesome-list) |
| [JameZUK/Arkana](https://github.com/JameZUK/Arkana) | 248 | Arkana - Your entire malware analysis lab, behind one AI prompt. 250+ MCP tools for binary analysis with Claude Code or other MCP | [SAFE](https://agentskillshub.top/skill/JameZUK/Arkana/?utm_source=github&utm_medium=awesome-list) |
| [akiselev/ghidra-cli](https://github.com/akiselev/ghidra-cli) | 240 | Automate Ghidra reverse engineering from the command line — headless analysis, decompilation, and structured JSON output for AI agents like Claude Co… | [SAFE](https://agentskillshub.top/skill/akiselev/ghidra-cli/?utm_source=github&utm_medium=awesome-list) |
| [banteg/bn](https://github.com/banteg/bn) | 219 | binary ninja cli for coding agents | [SAFE](https://agentskillshub.top/skill/banteg/bn/?utm_source=github&utm_medium=awesome-list) |
| [OwenPawl/ghidra-re-skill](https://github.com/OwenPawl/ghidra-re-skill) | 215 | cerberus-re is a local Apple-focused reverse-engineering workbench for building a repeatable three-headed static/dynamic/instrumentation loop around… | [SAFE](https://agentskillshub.top/skill/OwenPawl/ghidra-re-skill/?utm_source=github&utm_medium=awesome-list) |
| [dariushoule/x64dbg-skills](https://github.com/dariushoule/x64dbg-skills) | 209 | Claude Code plugin providing skills for x64dbg debugger automation | [SAFE](https://agentskillshub.top/skill/dariushoule/x64dbg-skills/?utm_source=github&utm_medium=awesome-list) |
| [sjkim1127/Reversecore_MCP](https://github.com/sjkim1127/Reversecore_MCP) | 208 | A security-first MCP server that empowers AI agents to perform automated reverse engineering, malware analysis, forensics, vulnerability research, an… | [SAFE](https://agentskillshub.top/skill/sjkim1127/Reversecore_MCP/?utm_source=github&utm_medium=awesome-list) |
| [taida957789/ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin) | 189 | IDA Pro Plugin for serving MCP SSE server for cursor / claude | [SAFE](https://agentskillshub.top/skill/taida957789/ida-mcp-server-plugin/?utm_source=github&utm_medium=awesome-list) |
| [index-login/MobileRE-Skill](https://github.com/index-login/MobileRE-Skill) | 171 | AI Agent 驱动的移动端逆向技能集：Frida hook、一键脱壳、反检测绕过、内存 DEX dump、Ghidra MCP 符号/结构恢复。AI-agent skill system for mobile reverse engineering. | [SAFE](https://agentskillshub.top/skill/index-login/MobileRE-Skill/?utm_source=github&utm_medium=awesome-list) |
| [tearhacker/UE4Dump_imGui_AnalyseToolsForMCP](https://github.com/tearhacker/UE4Dump_imGui_AnalyseToolsForMCP) | 164 | 泪心UE4Dump逆向分析MCP工具 | [SAFE](https://agentskillshub.top/skill/tearhacker/UE4Dump_imGui_AnalyseToolsForMCP/?utm_source=github&utm_medium=awesome-list) |
| [bromoket/x64dbg_mcp](https://github.com/bromoket/x64dbg_mcp) | 131 | Drive x64dbg with your AI. MCP server: 23 mega-tools / 153 endpoints for breakpoints, memory, disasm, tracing, anti-debug & PE dumping. Claude/Cursor… | [SAFE](https://agentskillshub.top/skill/bromoket/x64dbg_mcp/?utm_source=github&utm_medium=awesome-list) |
| [TsingShui/ida-agent-bridge](https://github.com/TsingShui/ida-agent-bridge) | 109 | A CLI-first, headless, AI-native IDA Pro bridge built on Unix philosophy. | [SAFE](https://agentskillshub.top/skill/TsingShui/ida-agent-bridge/?utm_source=github&utm_medium=awesome-list) |
| [president-xd/revula](https://github.com/president-xd/revula) | 83 | A fully functional and production-grade reverse engineering MCP Server | [SAFE](https://agentskillshub.top/skill/president-xd/revula/?utm_source=github&utm_medium=awesome-list) |
| [r0ysue/r0idamcp](https://github.com/r0ysue/r0idamcp) | 82 | r0idamcp is a SSE protocal MCP server IDA pro plugin designed for automatic reverse engineering with LLM assistant | [SAFE](https://agentskillshub.top/skill/r0ysue/r0idamcp/?utm_source=github&utm_medium=awesome-list) |
| [icloudza/algokiller-plugin](https://github.com/icloudza/algokiller-plugin) | 79 | ARM64 trace evidence analysis & cipher algorithm recovery — Claude Desktop plugin with skills + local MCP server driving the native ak_search engine… | [SAFE](https://agentskillshub.top/skill/icloudza/algokiller-plugin/?utm_source=github&utm_medium=awesome-list) |
| [elliottophellia/Ryuumonbuchi](https://github.com/elliottophellia/Ryuumonbuchi) | 75 | Maybe the headless Ghidra MCP you are looking for. | [SAFE](https://agentskillshub.top/skill/elliottophellia/Ryuumonbuchi/?utm_source=github&utm_medium=awesome-list) |
| [HLND2T/CS2_VibeSignatures](https://github.com/HLND2T/CS2_VibeSignatures) | 67 | Generate CS2 signatures via Agent SKILLS with ida-pro-mcp | [SAFE](https://agentskillshub.top/skill/HLND2T/CS2_VibeSignatures/?utm_source=github&utm_medium=awesome-list) |
| [Invoke-RE/binja-lattice-mcp](https://github.com/Invoke-RE/binja-lattice-mcp) | 66 | Plugin interface for remote communications with Binary Ninja database and MCP server for interfacing with LLMs. | [SAFE](https://agentskillshub.top/skill/Invoke-RE/binja-lattice-mcp/?utm_source=github&utm_medium=awesome-list) |
| [trailofbits/idac](https://github.com/trailofbits/idac) | 57 | idac - IDA Pro command line tool for agents and humans | [SAFE](https://agentskillshub.top/skill/trailofbits/idac/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/IDAssistMCP](https://github.com/symgraph/IDAssistMCP) | 52 | Standalone MCP server plugin for IDA Pro. | [SAFE](https://agentskillshub.top/skill/symgraph/IDAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/BinAssistMCP](https://github.com/symgraph/BinAssistMCP) | 51 | Binary Ninja plugin to provide MCP functionality. | [SAFE](https://agentskillshub.top/skill/symgraph/BinAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [cycloarcane/ghidra-mcp-setup](https://github.com/cycloarcane/ghidra-mcp-setup) | 5 | Turnkey installer + tutorial for hooking Ghidra to Claude, gemini-cli, or Ollama via the Model Context Protocol. | [CAUTION](https://agentskillshub.top/skill/cycloarcane/ghidra-mcp-setup/?utm_source=github&utm_medium=awesome-list) |
| [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) | 2 | Headless IDA Pro binary analysis via Model Context Protocol | [SAFE](https://agentskillshub.top/skill/zboralski/ida-headless-mcp/?utm_source=github&utm_medium=awesome-list) |

<a id="type-mobile"></a>
## 📱 Mobile app reversing

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-mobile)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) | 2.9k | Plugin for JADX to integrate MCP server | [SAFE](https://agentskillshub.top/skill/zinja-coder/jadx-ai-mcp/?utm_source=github&utm_medium=awesome-list) |
| [zinja-coder/jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server) | 798 | MCP server for JADX-AI Plugin | [SAFE](https://agentskillshub.top/skill/zinja-coder/jadx-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) | 673 | A MCP Server for APK Tool (Part of Android Reverse Engineering MCP Suites) | [SAFE](https://agentskillshub.top/skill/zinja-coder/apktool-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [flankerhqd/jebmcp](https://github.com/flankerhqd/jebmcp) | 261 |  | [SAFE](https://agentskillshub.top/skill/flankerhqd/jebmcp/?utm_source=github&utm_medium=awesome-list) |
| [kggzs/ApkMCP-Auto](https://github.com/kggzs/ApkMCP-Auto) | 221 | 本项目是一个 Android 逆向工程工具集合，通过 MCP (Model Context Protocol) 协议将 AI 助手（如 Claude）与专业的 Android 反编译工具连接起来，实现智能化的 APK 分析与修改。 | [SAFE](https://agentskillshub.top/skill/kggzs/ApkMCP-Auto/?utm_source=github&utm_medium=awesome-list) |
| [ZSA233/frida-analykit](https://github.com/ZSA233/frida-analykit) | 155 | Frida 工具包 - 主要面向安卓端逆向，解决frida环境版本管理和对Agent端常用底层工具方法封装，支持MCP。（目前主要由AI开发维护代码） | [SAFE](https://agentskillshub.top/skill/ZSA233/frida-analykit/?utm_source=github&utm_medium=awesome-list) |
| [mobilehackinglab/jadx-mcp-plugin](https://github.com/mobilehackinglab/jadx-mcp-plugin) | 104 |  | [SAFE](https://agentskillshub.top/skill/mobilehackinglab/jadx-mcp-plugin/?utm_source=github&utm_medium=awesome-list) |
| [TheQmaks/areclaw](https://github.com/TheQmaks/areclaw) | 71 | Android Reverse Engineering Command-Line Automation Workspace. AI-driven security analysis with Claude Code. | [SAFE](https://agentskillshub.top/skill/TheQmaks/areclaw/?utm_source=github&utm_medium=awesome-list) |
| [crissyfield/super-trouper](https://github.com/crissyfield/super-trouper) | 51 | MCP server for Frida. | [SAFE](https://agentskillshub.top/skill/crissyfield/super-trouper/?utm_source=github&utm_medium=awesome-list) |

<a id="type-web"></a>
## 🌐 Web, JS & protocol reversing

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-web)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [vmoranv/jshookmcp](https://github.com/vmoranv/jshookmcp) | 2.0k | A search-first, profile-aware reverse-engineering workspace for AI agents — 735 tools across 36 domains in one MCP server. | [SAFE](https://agentskillshub.top/skill/vmoranv/jshookmcp/?utm_source=github&utm_medium=awesome-list) |

<a id="type-skill"></a>
## 🧩 Reverse engineering skills

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-skill)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 41.5k | Reverse Engineering / Authorized Penetration Testing / Security Research Skill Router Pack AI-powered routing + On-demand toolchain bootstrapping + S… | [SAFE](https://agentskillshub.top/skill/zhaoxuya520/reverse-skill/?utm_source=github&utm_medium=awesome-list) |
| [SimoneAvogadro/android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) | 8.1k | Claude Code skill to support Android app's reverse engineering | [SAFE](https://agentskillshub.top/skill/SimoneAvogadro/android-reverse-engineering-skill/?utm_source=github&utm_medium=awesome-list) |
| [P4nda0s/reverse-skills](https://github.com/P4nda0s/reverse-skills) | 2.3k | Reverse engineering skills for Claude Code \| 逆向工程 Claude Code Skills 插件 | [SAFE](https://agentskillshub.top/skill/P4nda0s/reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [Dryxio/auto-re-agent](https://github.com/Dryxio/auto-re-agent) | 2.1k | Reconstruct and validate C/C++ code from compiled programs with AI. | [SAFE](https://agentskillshub.top/skill/Dryxio/auto-re-agent/?utm_source=github&utm_medium=awesome-list) |
| [Dryxio/reagent](https://github.com/Dryxio/reagent) | 2.1k | Reconstruct and validate C/C++ code from compiled programs with AI. | [SAFE](https://agentskillshub.top/skill/Dryxio/reagent/?utm_source=github&utm_medium=awesome-list) |
| [2akouwu/reverify](https://github.com/2akouwu/reverify) | 1.3k | Stop your AI from making things up — it proposes, deterministic tools decide, every claim checked against ground truth with evidence. Grounded facts… | [SAFE](https://agentskillshub.top/skill/2akouwu/reverify/?utm_source=github&utm_medium=awesome-list) |
| [CreditTone/android-reverse-engineering-skill](https://github.com/CreditTone/android-reverse-engineering-skill) | 544 | 这是一套专为 Codex 适配的 Android 逆向分析 skill，支持在 Codex 会话中反编译 APK、XAPK、JAR、AAR，并结合 jadx、Fernflower/Vineflower 梳理 Manifest、包结构、网络层和调用链。它可辅助提取接口、URL、鉴权头、token 与… | [SAFE](https://agentskillshub.top/skill/CreditTone/android-reverse-engineering-skill/?utm_source=github&utm_medium=awesome-list) |
| [miunasu/IDA-Skill](https://github.com/miunasu/IDA-Skill) | 235 | 使用skill让 AI Agent 像安全分析师一样分析恶意样本 \| AI Agent skill for automated malware analysis using IDA Pro | [SAFE](https://agentskillshub.top/skill/miunasu/IDA-Skill/?utm_source=github&utm_medium=awesome-list) |
| [Ablation-Tool/ablation](https://github.com/Ablation-Tool/ablation) | 210 | Ablation is an autonomous reverse engineering system. | [SAFE](https://agentskillshub.top/skill/Ablation-Tool/ablation/?utm_source=github&utm_medium=awesome-list) |
| [incogbyte/android-reverse-engineering-claude-skill](https://github.com/incogbyte/android-reverse-engineering-claude-skill) | 125 | Claude Code skill that automates Android application reverse engineering | [SAFE](https://agentskillshub.top/skill/incogbyte/android-reverse-engineering-claude-skill/?utm_source=github&utm_medium=awesome-list) |
| [pardeike/DecompilerServer](https://github.com/pardeike/DecompilerServer) | 118 | A powerful MCP (Model Context Protocol) server for decompiling and analyzing .NET assemblies, with specialized support for Unity's Assembly-CSharp.dl… | [SAFE](https://agentskillshub.top/skill/pardeike/DecompilerServer/?utm_source=github&utm_medium=awesome-list) |
| [haikow/claude-reverse-skills](https://github.com/haikow/claude-reverse-skills) | 116 | Claude Code 逆向工程 skill 集合 (apk/ida/radare2/js) + IDA MCP 接入，跨平台 Linux/Mac/Windows | [SAFE](https://agentskillshub.top/skill/haikow/claude-reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [incogbyte/iOS-reverse-engineering-claude-skill](https://github.com/incogbyte/iOS-reverse-engineering-claude-skill) | 102 | Claude Code skill that enables Claude to extract, analyze, reverse engineer iOS apps | [SAFE](https://agentskillshub.top/skill/incogbyte/iOS-reverse-engineering-claude-skill/?utm_source=github&utm_medium=awesome-list) |
| [blacktop/ipsw-skill](https://github.com/blacktop/ipsw-skill) | 95 | A SKILL.md for ipsw | [SAFE](https://agentskillshub.top/skill/blacktop/ipsw-skill/?utm_source=github&utm_medium=awesome-list) |

<a id="type-case"></a>
## 🕹 Reverse-engineered with AI

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-case)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [N0zoM1z0/dx-ball](https://github.com/N0zoM1z0/dx-ball) | 46 | Reconstructing DX-Ball 1.07 with REA, backed by original-x86 differential tests and pinned MSVC byte-exact oracles. | [SAFE](https://agentskillshub.top/skill/N0zoM1z0/dx-ball/?utm_source=github&utm_medium=awesome-list) |

**Security** is the grade of the repo's README and install steps on Agent Skills Hub. *pending* means the catalog has not graded it yet.

Preview images are reduced copies of pictures from each project's own README, included only for projects under a permissive license. Sources and licenses: [assets/previews/NOTICE.md](assets/previews/NOTICE.md). Open an issue to have one removed.

## Related collections

- [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills), [zhuyansen/awesome-codex-ppt-skills](https://github.com/zhuyansen/awesome-codex-ppt-skills) — lists built the same way.

## Add a repo

Open an issue with the GitHub URL. It goes through the same review as every entry; the rules above decide, stars do not.

---

Machine-readable copy: [`data/skills.json`](data/skills.json). Generated 2026-10-13.
