# Awesome AI Reverse Engineering

[English](README.md)

给 Claude Code、Codex 等 agent 用的开源 **AI 逆向工程工具**:Ghidra MCP、IDA Pro MCP、移动端的 jadx 与 Frida、逆向 skill、REA,以及用它重建出来的项目。共 63 个仓库,每个都由 [Agent Skills Hub](https://agentskillshub.top?utm_source=github&utm_medium=awesome-list) 读过 README 并做了安全评级。

带类型筛选的在线页面:**[https://agentskillshub.top/best/ai-reverse-engineering/](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list)** · 每 8 小时刷新

## 这些工具长什么样

<table>
<tr>
<td align="center" valign="top" width="33%"><b>🔬 反汇编与反编译 MCP</b><br><sub>38 个仓库</sub><br><br><sub>让 agent 操作 Ghidra、IDA Pro、Binary Ninja、radare2 或 x64dbg 的服务和插件。</sub><br><a href="#type-mcp"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>📱 移动端逆向</b><br><sub>9 个仓库</sub><br><br><sub>接给 agent 的 jadx、apktool 和 Frida,面向 Android、iOS 和鸿蒙应用。</sub><br><a href="#type-mobile"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🌐 Web、JS 与协议逆向</b><br><sub>1 个仓库</sub><br><br><sub>混淆 JavaScript、请求签名和流量分析。</sub><br><a href="#type-web"><b>查看列表 →</b></a></td>
</tr>
<tr>
<td align="center" valign="top" width="33%"><b>🧩 逆向 Skill</b><br><sub>14 个仓库</sub><br><br><sub>教 agent 怎么做逆向的 skill 和流程。</sub><br><a href="#type-skill"><b>查看列表 →</b></a></td>
<td align="center" valign="top" width="33%"><b>🕹 AI 逆向出来的项目</b><br><sub>1 个仓库</sub><br><br><sub>用 REA 重建或分析出来的程序,README 里都写明了。</sub><br><a href="#type-case"><b>查看列表 →</b></a></td>
</tr>
</table>

## 目录

- [🔬 反汇编与反编译 MCP](#type-mcp) (38)
- [📱 移动端逆向](#type-mobile) (9)
- [🌐 Web、JS 与协议逆向](#type-web) (1)
- [🧩 逆向 Skill](#type-skill) (14)
- [🕹 AI 逆向出来的项目](#type-case) (1)

## 什么样的仓库能上榜

1. 用 AI agent 做逆向是它的主要用途。通用安全扫描器、链接清单、照搬别人的仓库、以游戏作弊或破解为卖点的工具不算。
2. 它是能安装或运行的软件,不是链接合集或空仓库。
3. 它有 README。没有 README 就没法评级。
4. 50 星及以上只看是否切题;50 星以下还要过 README 质量线(展示效果、一条命令上手、说清产出、文档完整),并且至少 5 星。

这些问题由决策模型逐个读 README 回答,不是人工挑选。卡在线上的仓库可能判到任一边,归错了请提 issue。

<a id="type-mcp"></a>
## 🔬 反汇编与反编译 MCP

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-mcp)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [morluto/rea](https://github.com/morluto/rea) | 182.5k | 用 agent 逆向分析任意对象，从应用行为到原生二进制。 | [SAFE](https://agentskillshub.top/skill/morluto/rea/?utm_source=github&utm_medium=awesome-list) |
| [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) | 12.7k | 通过 MCP 连接 IDA Pro 与语言模型的 AI 逆向工程助手。 | [SAFE](https://agentskillshub.top/skill/mrexodia/ida-pro-mcp/?utm_source=github&utm_medium=awesome-list) |
| [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | 11.2k | MCP Server for Ghidra | [SAFE](https://agentskillshub.top/skill/LaurieWired/GhidraMCP/?utm_source=github&utm_medium=awesome-list) |
| [bethington/ghidra-mcp](https://github.com/bethington/ghidra-mcp) | 5.5k | Ghidra MCP Server：面向 AI 逆向工程，支持 GUI 插件、无头服务器、延迟加载、批量操作、Ghidra Server 集成和 Docker… | [SAFE](https://agentskillshub.top/skill/bethington/ghidra-mcp/?utm_source=github&utm_medium=awesome-list) |
| [duty1g/x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server) | 2.5k | x64dbg-MCP Server是x64dbg的原生MCP插件，通过HTTP控制x64dbg，支持断点、单步、读内存和寄存器转储。 | [SAFE](https://agentskillshub.top/skill/duty1g/x64dbg-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [LING71671/open-reverselab](https://github.com/LING71671/open-reverselab) | 1.3k | 开源 AI 逆向工程 agent 平台及 MCP server，支持 Ghidra、Frida、x64dbg 和 Rizin，用于 PE/APK/二进制分析、… | [SAFE](https://agentskillshub.top/skill/LING71671/open-reverselab/?utm_source=github&utm_medium=awesome-list) |
| [cyberkaida/reverse-engineering-assistant](https://github.com/cyberkaida/reverse-engineering-assistant) | 871 | 用于在 Ghidra 中进行逆向工程任务的 MCP 服务器 | [SAFE](https://agentskillshub.top/skill/cyberkaida/reverse-engineering-assistant/?utm_source=github&utm_medium=awesome-list) |
| [blacktop/ida-mcp-rs](https://github.com/blacktop/ida-mcp-rs) | 864 | 无界面 IDA Pro MCP Server | [SAFE](https://agentskillshub.top/skill/blacktop/ida-mcp-rs/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) | 770 | Ghidra 的原生 MCP 服务器扩展 | [SAFE](https://agentskillshub.top/skill/symgraph/GhidrAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [Wasdubya/x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP) | 594 | 用于 x64dbg 和 x32dbg 的 Model Context Protocol | [SAFE](https://agentskillshub.top/skill/Wasdubya/x64dbgMCP/?utm_source=github&utm_medium=awesome-list) |
| [MxIris-Reverse-Engineering/ida-mcp-server](https://github.com/MxIris-Reverse-Engineering/ida-mcp-server) | 547 | 用于 IDA 的 Model Context Protocol 服务器 | [SAFE](https://agentskillshub.top/skill/MxIris-Reverse-Engineering/ida-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [SetsunaYukiOvO/x64dbg-mcp](https://github.com/SetsunaYukiOvO/x64dbg-mcp) | 520 | x64dbg 调试器的 MCP server 插件，供 AI agent 和外部工具通过 HTTP/SSE 控制调试 | [SAFE](https://agentskillshub.top/skill/SetsunaYukiOvO/x64dbg-mcp/?utm_source=github&utm_medium=awesome-list) |
| [Claude-Reverser/IDA-instances-MCP](https://github.com/Claude-Reverser/IDA-instances-MCP) | 459 | ida-pro-mcp 定制版——用于托管无头 IDA Pro 实例的稳定性增强 MCP 服务器 | [SAFE](https://agentskillshub.top/skill/Claude-Reverser/IDA-instances-MCP/?utm_source=github&utm_medium=awesome-list) |
| [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) | 452 | 包含 MCP 服务器的 Binary Ninja 插件，可与 LLM/MCP 客户端集成。 | [SAFE](https://agentskillshub.top/skill/fosdickio/binary_ninja_mcp/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/agentic-malware-analysis](https://github.com/mrphrazer/agentic-malware-analysis) | 311 | 面向 Claude Code 和 Codex CLI 的智能体恶意软件分析环境，集成 MCP 反汇编器、逆向工具和结构化工作流。 | [SAFE](https://agentskillshub.top/skill/mrphrazer/agentic-malware-analysis/?utm_source=github&utm_medium=awesome-list) |
| [mrphrazer/binary-ninja-headless-mcp](https://github.com/mrphrazer/binary-ninja-headless-mcp) | 256 | 无界面 Binary Ninja MCP 服务器，通过 180 个工具为 AI agents 提供逆向工程能力。 | [SAFE](https://agentskillshub.top/skill/mrphrazer/binary-ninja-headless-mcp/?utm_source=github&utm_medium=awesome-list) |
| [JameZUK/Arkana](https://github.com/JameZUK/Arkana) | 248 | Arkana：用一个 AI 提示词进行恶意软件分析，提供 250+ 个 MCP 工具，支持 Claude Code 或其他 MCP | [SAFE](https://agentskillshub.top/skill/JameZUK/Arkana/?utm_source=github&utm_medium=awesome-list) |
| [akiselev/ghidra-cli](https://github.com/akiselev/ghidra-cli) | 240 | 从命令行自动执行 Ghidra 逆向工程：无头分析、反编译并为 Claude Code 等 AI agent 输出结构化 JSON | [SAFE](https://agentskillshub.top/skill/akiselev/ghidra-cli/?utm_source=github&utm_medium=awesome-list) |
| [banteg/bn](https://github.com/banteg/bn) | 219 | 面向编码 agent 的 Binary Ninja CLI | [SAFE](https://agentskillshub.top/skill/banteg/bn/?utm_source=github&utm_medium=awesome-list) |
| [OwenPawl/ghidra-re-skill](https://github.com/OwenPawl/ghidra-re-skill) | 215 | 用于 Ghidra 逆向工程的 Codex skill，支持无头工作流、漏洞挖掘套件和 Apple Mach-O 实时桥接器。 | [SAFE](https://agentskillshub.top/skill/OwenPawl/ghidra-re-skill/?utm_source=github&utm_medium=awesome-list) |
| [dariushoule/x64dbg-skills](https://github.com/dariushoule/x64dbg-skills) | 209 | 为 Claude Code 提供 x64dbg 调试器自动化技能的插件 | [SAFE](https://agentskillshub.top/skill/dariushoule/x64dbg-skills/?utm_source=github&utm_medium=awesome-list) |
| [sjkim1127/Reversecore_MCP](https://github.com/sjkim1127/Reversecore_MCP) | 208 | 面向安全的MCP服务器，支持AI agent自动化逆向工程、恶意软件分析、取证、漏洞研究和SAST，基于Radare2、YARA、LIEF、Capstone等。 | [SAFE](https://agentskillshub.top/skill/sjkim1127/Reversecore_MCP/?utm_source=github&utm_medium=awesome-list) |
| [taida957789/ida-mcp-server-plugin](https://github.com/taida957789/ida-mcp-server-plugin) | 189 | 为 cursor / claude 提供 MCP SSE 服务器的 IDA Pro 插件 | [SAFE](https://agentskillshub.top/skill/taida957789/ida-mcp-server-plugin/?utm_source=github&utm_medium=awesome-list) |
| [index-login/MobileRE-Skill](https://github.com/index-login/MobileRE-Skill) | 171 | AI agent 驱动的移动端逆向 skill：Frida hook、脱壳、反检测绕过、内存 DEX dump、Ghidra MCP 符号/结构恢复。 | [SAFE](https://agentskillshub.top/skill/index-login/MobileRE-Skill/?utm_source=github&utm_medium=awesome-list) |
| [tearhacker/UE4Dump_imGui_AnalyseToolsForMCP](https://github.com/tearhacker/UE4Dump_imGui_AnalyseToolsForMCP) | 164 | 泪心UE4Dump逆向分析MCP工具 | [SAFE](https://agentskillshub.top/skill/tearhacker/UE4Dump_imGui_AnalyseToolsForMCP/?utm_source=github&utm_medium=awesome-list) |
| [bromoket/x64dbg_mcp](https://github.com/bromoket/x64dbg_mcp) | 131 | 用 AI 驱动 x64dbg。MCP server：23 个工具、153 个端点，支持断点、内存、反汇编、跟踪、反调试和 PE 转储。Claude/Curso… | [SAFE](https://agentskillshub.top/skill/bromoket/x64dbg_mcp/?utm_source=github&utm_medium=awesome-list) |
| [TsingShui/ida-agent-bridge](https://github.com/TsingShui/ida-agent-bridge) | 109 | 基于 Unix 哲学的 CLI 优先、无头、AI 原生 IDA Pro 桥接工具。 | [SAFE](https://agentskillshub.top/skill/TsingShui/ida-agent-bridge/?utm_source=github&utm_medium=awesome-list) |
| [president-xd/revula](https://github.com/president-xd/revula) | 83 | A fully functional and production-grade reverse engineering MCP Server | [SAFE](https://agentskillshub.top/skill/president-xd/revula/?utm_source=github&utm_medium=awesome-list) |
| [r0ysue/r0idamcp](https://github.com/r0ysue/r0idamcp) | 82 | r0idamcp 是采用 SSE 协议的 MCP server IDA Pro 插件，用于 LLM assistant 辅助的自动逆向工程 | [SAFE](https://agentskillshub.top/skill/r0ysue/r0idamcp/?utm_source=github&utm_medium=awesome-list) |
| [icloudza/algokiller-plugin](https://github.com/icloudza/algokiller-plugin) | 79 | ARM64 跟踪证据分析与密码算法恢复——Claude Desktop 插件，配备 skills 和本地 MCP server，驱动原生 ak_search… | [SAFE](https://agentskillshub.top/skill/icloudza/algokiller-plugin/?utm_source=github&utm_medium=awesome-list) |
| [elliottophellia/Ryuumonbuchi](https://github.com/elliottophellia/Ryuumonbuchi) | 75 | 或许是你要找的无头 Ghidra MCP。 | [SAFE](https://agentskillshub.top/skill/elliottophellia/Ryuumonbuchi/?utm_source=github&utm_medium=awesome-list) |
| [HLND2T/CS2_VibeSignatures](https://github.com/HLND2T/CS2_VibeSignatures) | 67 | 通过 Agent SKILLS 和 ida-pro-mcp 生成 CS2 特征码 | [SAFE](https://agentskillshub.top/skill/HLND2T/CS2_VibeSignatures/?utm_source=github&utm_medium=awesome-list) |
| [Invoke-RE/binja-lattice-mcp](https://github.com/Invoke-RE/binja-lattice-mcp) | 66 | 用于与 Binary Ninja 数据库远程通信及通过 MCP server 与 LLMs 交互的插件接口。 | [SAFE](https://agentskillshub.top/skill/Invoke-RE/binja-lattice-mcp/?utm_source=github&utm_medium=awesome-list) |
| [trailofbits/idac](https://github.com/trailofbits/idac) | 57 | idac - 面向 agents 和人类的 IDA Pro 命令行工具 | [SAFE](https://agentskillshub.top/skill/trailofbits/idac/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/IDAssistMCP](https://github.com/symgraph/IDAssistMCP) | 52 | IDA Pro 的独立 MCP 服务器插件 | [SAFE](https://agentskillshub.top/skill/symgraph/IDAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [symgraph/BinAssistMCP](https://github.com/symgraph/BinAssistMCP) | 51 | 提供 MCP 功能的 Binary Ninja 插件。 | [SAFE](https://agentskillshub.top/skill/symgraph/BinAssistMCP/?utm_source=github&utm_medium=awesome-list) |
| [cycloarcane/ghidra-mcp-setup](https://github.com/cycloarcane/ghidra-mcp-setup) | 5 | 通过 MCP 将 Ghidra 接入 Claude、gemini-cli 或 Ollama 的安装程序和教程 | [CAUTION](https://agentskillshub.top/skill/cycloarcane/ghidra-mcp-setup/?utm_source=github&utm_medium=awesome-list) |
| [zboralski/ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) | 2 | 通过 Model Context Protocol 进行无界面 IDA Pro 二进制分析 | [SAFE](https://agentskillshub.top/skill/zboralski/ida-headless-mcp/?utm_source=github&utm_medium=awesome-list) |

<a id="type-mobile"></a>
## 📱 移动端逆向

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-mobile)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) | 2.9k | Plugin for JADX to integrate MCP server | [SAFE](https://agentskillshub.top/skill/zinja-coder/jadx-ai-mcp/?utm_source=github&utm_medium=awesome-list) |
| [zinja-coder/jadx-mcp-server](https://github.com/zinja-coder/jadx-mcp-server) | 798 | JADX-AI Plugin 的 MCP 服务器 | [SAFE](https://agentskillshub.top/skill/zinja-coder/jadx-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) | 673 | APK Tool 的 MCP Server（Android 逆向工程 MCP 套件组成部分） | [SAFE](https://agentskillshub.top/skill/zinja-coder/apktool-mcp-server/?utm_source=github&utm_medium=awesome-list) |
| [flankerhqd/jebmcp](https://github.com/flankerhqd/jebmcp) | 261 | JEB Pro 的简易 MCP server 和 Plugin，已在 Cline、Cursor、RooCode 上测试。需要 Python >= 3.11 和… | [SAFE](https://agentskillshub.top/skill/flankerhqd/jebmcp/?utm_source=github&utm_medium=awesome-list) |
| [kggzs/ApkMCP-Auto](https://github.com/kggzs/ApkMCP-Auto) | 221 | Android 逆向工程工具集合，通过 MCP 连接 Claude 与反编译工具，支持 APK 分析与修改。 | [SAFE](https://agentskillshub.top/skill/kggzs/ApkMCP-Auto/?utm_source=github&utm_medium=awesome-list) |
| [ZSA233/frida-analykit](https://github.com/ZSA233/frida-analykit) | 155 | Frida 工具包：面向安卓逆向，管理 Frida 环境版本，封装 Agent 常用底层工具，支持 MCP。 | [SAFE](https://agentskillshub.top/skill/ZSA233/frida-analykit/?utm_source=github&utm_medium=awesome-list) |
| [mobilehackinglab/jadx-mcp-plugin](https://github.com/mobilehackinglab/jadx-mcp-plugin) | 104 |  | [SAFE](https://agentskillshub.top/skill/mobilehackinglab/jadx-mcp-plugin/?utm_source=github&utm_medium=awesome-list) |
| [TheQmaks/areclaw](https://github.com/TheQmaks/areclaw) | 71 | Android 逆向工程命令行自动化工作区，使用 Claude Code 进行安全分析。 | [SAFE](https://agentskillshub.top/skill/TheQmaks/areclaw/?utm_source=github&utm_medium=awesome-list) |
| [crissyfield/super-trouper](https://github.com/crissyfield/super-trouper) | 51 | Frida 的 MCP 服务器。 | [SAFE](https://agentskillshub.top/skill/crissyfield/super-trouper/?utm_source=github&utm_medium=awesome-list) |

<a id="type-web"></a>
## 🌐 Web、JS 与协议逆向

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-web)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [vmoranv/jshookmcp](https://github.com/vmoranv/jshookmcp) | 2.0k | 面向 AI agents 的搜索优先、结合用户配置的逆向工程工作区，一个 MCP server 集成 36 个领域的 735 个工具。 | [SAFE](https://agentskillshub.top/skill/vmoranv/jshookmcp/?utm_source=github&utm_medium=awesome-list) |

<a id="type-skill"></a>
## 🧩 逆向 Skill

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-skill)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 41.5k | 逆向/授权渗透测试/安全研究 skill 路由包，支持 AI 路由、按需工具链和知识库，兼容 Claude Code、Kiro、Cursor、Cline等 A… | [SAFE](https://agentskillshub.top/skill/zhaoxuya520/reverse-skill/?utm_source=github&utm_medium=awesome-list) |
| [SimoneAvogadro/android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) | 8.1k | 用于 Android 应用逆向工程的 Claude Code skill | [SAFE](https://agentskillshub.top/skill/SimoneAvogadro/android-reverse-engineering-skill/?utm_source=github&utm_medium=awesome-list) |
| [P4nda0s/reverse-skills](https://github.com/P4nda0s/reverse-skills) | 2.3k | Claude Code 逆向工程 skill 插件 | [SAFE](https://agentskillshub.top/skill/P4nda0s/reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [Dryxio/auto-re-agent](https://github.com/Dryxio/auto-re-agent) | 2.1k | 使用 Ghidra 和 LLM 从二进制文件重构并验证 C/C++ 函数的开源 AI 逆向工程 agent | [SAFE](https://agentskillshub.top/skill/Dryxio/auto-re-agent/?utm_source=github&utm_medium=awesome-list) |
| [Dryxio/reagent](https://github.com/Dryxio/reagent) | 2.1k | 用 AI 从编译后的程序重构并验证 C/C++ 代码。 | [SAFE](https://agentskillshub.top/skill/Dryxio/reagent/?utm_source=github&utm_medium=awesome-list) |
| [2akouwu/reverify](https://github.com/2akouwu/reverify) | 1.3k | AI 提出方案，确定性工具决策，每条结论都以证据对照真实情况核验。事实和上下文在重置后保留。逆向工程用于验证。MCP server + CLI。 | [SAFE](https://agentskillshub.top/skill/2akouwu/reverify/?utm_source=github&utm_medium=awesome-list) |
| [CreditTone/android-reverse-engineering-skill](https://github.com/CreditTone/android-reverse-engineering-skill) | 544 | Codex 专用 Android 逆向分析 skill，支持 APK 等文件反编译，分析 Manifest、网络层和调用链，辅助接口提取与安全研究。 | [SAFE](https://agentskillshub.top/skill/CreditTone/android-reverse-engineering-skill/?utm_source=github&utm_medium=awesome-list) |
| [miunasu/IDA-Skill](https://github.com/miunasu/IDA-Skill) | 235 | 用 skill 让 AI Agent 使用 IDA Pro 自动分析恶意样本 | [SAFE](https://agentskillshub.top/skill/miunasu/IDA-Skill/?utm_source=github&utm_medium=awesome-list) |
| [Ablation-Tool/ablation](https://github.com/Ablation-Tool/ablation) | 210 | Ablation 是一个自主逆向工程系统。 | [SAFE](https://agentskillshub.top/skill/Ablation-Tool/ablation/?utm_source=github&utm_medium=awesome-list) |
| [incogbyte/android-reverse-engineering-claude-skill](https://github.com/incogbyte/android-reverse-engineering-claude-skill) | 125 | 用于自动化 Android 应用逆向工程的 Claude Code skill | [SAFE](https://agentskillshub.top/skill/incogbyte/android-reverse-engineering-claude-skill/?utm_source=github&utm_medium=awesome-list) |
| [pardeike/DecompilerServer](https://github.com/pardeike/DecompilerServer) | 118 | A powerful MCP (Model Context Protocol) server for decompiling and analyzing .NET assemblies, with specialized support for Unity's Assembly-CSharp.dl… | [SAFE](https://agentskillshub.top/skill/pardeike/DecompilerServer/?utm_source=github&utm_medium=awesome-list) |
| [haikow/claude-reverse-skills](https://github.com/haikow/claude-reverse-skills) | 116 | Claude Code 逆向工程 skill 集合（apk/IDA/radare2/js），支持 IDA MCP，跨平台 Linux/Mac/Windows | [SAFE](https://agentskillshub.top/skill/haikow/claude-reverse-skills/?utm_source=github&utm_medium=awesome-list) |
| [incogbyte/iOS-reverse-engineering-claude-skill](https://github.com/incogbyte/iOS-reverse-engineering-claude-skill) | 102 | Claude Code skill that enables Claude to extract, analyze, reverse engineer iOS apps | [SAFE](https://agentskillshub.top/skill/incogbyte/iOS-reverse-engineering-claude-skill/?utm_source=github&utm_medium=awesome-list) |
| [blacktop/ipsw-skill](https://github.com/blacktop/ipsw-skill) | 95 | 适用于 ipsw 的 SKILL.md | [SAFE](https://agentskillshub.top/skill/blacktop/ipsw-skill/?utm_source=github&utm_medium=awesome-list) |

<a id="type-case"></a>
## 🕹 AI 逆向出来的项目

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/ai-reverse-engineering/?utm_source=github&utm_medium=awesome-list#type-case)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [N0zoM1z0/dx-ball](https://github.com/N0zoM1z0/dx-ball) | 46 | 使用 REA 重构 DX-Ball 1.07，由 original-x86 差分测试和固定的 MSVC 字节级精确预言机支持。 | [SAFE](https://agentskillshub.top/skill/N0zoM1z0/dx-ball/?utm_source=github&utm_medium=awesome-list) |

**安全评级**是 Agent Skills Hub 对仓库 README 和安装步骤的评级。*待评级*表示目录还没评到它。

预览图是各项目 README 里图片的缩小副本,只收录采用宽松许可证的项目,版权归原作者所有。来源和许可证见 [assets/previews/NOTICE.md](assets/previews/NOTICE.md)。如需移除请提 issue。

## 相关合集

- [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills), [zhuyansen/awesome-codex-ppt-skills](https://github.com/zhuyansen/awesome-codex-ppt-skills) —— 同样做法的合集。

## 推荐仓库

提一个 issue 附上 GitHub 链接。它会走和每个条目一样的评审;决定上不上榜的是上面的规则,不是星数。

---

机器可读版本:[`data/skills.json`](data/skills.json)。生成于 2026-10-13。
