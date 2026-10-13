<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
  <img src="assets/logo-light.svg" alt="Delta MCP" width="260">
</picture>

<h1 align="center">Delta MCP：检查并撤销你的 AI 对工具做的改动</h1>

<p><strong>Delta MCP 是一款免费应用，位于你的 AI 和你的工具（Notion、GitHub、你的文件……）之间。它检查每个任务，要么全部生效，要么一概不动，并让你可以撤销。</strong></p>

<p><a href="https://github.com/mcpdelta/mcpdelta"><img src="https://img.shields.io/github/stars/mcpdelta/mcpdelta?style=for-the-badge&logo=github&logoColor=white&color=16794F&labelColor=0E2E21" alt="GitHub stars"></a></p>

<p>每处改动都有记录，可撤销 · 免费，无需账号 · 在你的电脑上运行</p>

<p>🌐 <a href="README.md">English</a> · <b>中文</b> · <a href="README.hi.md">हिन्दी</a> · <a href="README.es.md">Español</a> · <a href="README.ar.md">العربية</a> · <a href="README.fr.md">Français</a> · <a href="README.bn.md">বাংলা</a> · <a href="README.pt.md">Português</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.ur.md">اردو</a> · <a href="README.ru.md">Русский</a> · <a href="README.de.md">Deutsch</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.el.md">Ελληνικά</a></p>

<p>
  <a href="https://www.mcpdelta.com/zh">官网</a> ·
  <a href="https://www.mcpdelta.com/zh/how-it-works">工作原理</a> ·
  <a href="https://www.mcpdelta.com/zh/benchmarks">基准测试</a> ·
  <a href="https://www.mcpdelta.com/docs">Docs</a> ·
  <a href="https://www.mcpdelta.com/zh/guides">指南</a> ·
  <a href="https://www.mcpdelta.com/zh/download">下载：即将发布</a>
</p>

</div>

> ⭐ **用一个星标支持 Delta MCP。** 点击本页右上角的 **Star**。只需一秒，免费，还能帮助其他使用 MCP 的人在正式发布前找到 Delta MCP。

> **即将发布**，适用于 macOS、Windows 和 Linux：免费，无需账号。关注发布动态，一经发布你就会知道，无需留下邮箱：[RSS](https://www.mcpdelta.com/feed.xml)，或在本仓库里选择 **Watch → Custom → Releases**。

<p align="center">
  <img src="assets/demo.gif" alt="Delta MCP 的标志是一个小圆在大圆内滚动画出的图形。随后出现名称和“Coming soon”，接着是应用的 Activity 窗口：每个任务用一句话说明，显示每处改动的前后对比，以及 Undo。" width="100%">
</p>

## 事前决定。事后看清。随时撤销。

1. **事前由你决定。** 对每个工具，你来选择你的 AI 可以自行做什么：只读，删除或发送前先问，或每次都问。它来问你时，你能看到每处改动的前后对比。
2. **事后看清发生了什么。** 每处改动连同前后对比都会被记录下来，记录由 Delta MCP 写下，而不是你的 AI。能在工具里核对结果的，它就去核对；如果连接中断，它会在重做任何事情之前先检查。
3. **你可以撤销。** Undo 会还原能够还原的内容，并在你点击之前告诉你哪些无法撤销，比如已经发出的消息。

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/activity-dark.webp">
    <img src="assets/activity-light.webp" alt="Delta MCP 的 Activity 窗口：你的 AI 完成的一个任务，每处改动的前后对比，无法撤销之处的说明，以及 Undo 按钮。" width="100%">
  </picture>
</p>

> ⭐ **看了觉得不错？一个星标就是支持 Delta MCP 最简单的方式。** 它告诉我们，这件事值得做完。

## 给你的 AI 工作加上 Ctrl+Z。

每个任务都会显示每处改动的前后对比。可以立即撤销，在某些情况下也可以稍后再撤销，由你或你的 AI 来做。

- **前后对比。** 每处改动都会显示原来的样子和现在的样子，凡能从服务回读的，都以服务的结果为准。
- **一步，还是整个任务。** 你的 AI 会写好每一步怎么撤销。如果后面某一步失败，或者你点击 Undo，这些撤销操作会按相反的顺序执行。
- **诚实说明哪些无法撤销。** 在点击之前，你能看到哪些会被还原、哪些不会，比如已经发出的消息。Delta MCP 绝不会在没有证据的情况下说“全部已撤销”。

## 把你重复做的任务自动化。

设置一次即可。Delta MCP 每天、工作日、每周一或每小时运行它，成本非常低；只有任务需要思考时，你的 AI 才会介入。

- **报告与例行任务。** 分析昨晚的 Grafana 日志，把报告发给团队。每天早上跟踪市场。每周五关闭已完成的工单。
- **免费，或借助你的 AI。** Delta MCP 免费运行它，无需 AI。需要分析时，你的 AI 会在你设定的时间接手这次运行，然后写报告、发邮件，或根据发现的结果采取行动。
- **请你的 AI 帮你设置。** 告诉你的 AI 要自动化什么，它就会在 Delta MCP 里创建。你先测试，然后签署一次。失败两次后，它会暂停并告诉你。

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/automations-dark.webp">
    <img src="assets/automations-light.webp" alt="Delta MCP 的 Automations 列表：Daily report 每天 8:00 运行，显示上次和下次运行时间；Weekly cleanup 每周一运行；另有一个自动化已暂停。" width="100%">
  </picture>
</p>

## 实测：token 最多少 24.1×

结果相同，token 少得多。在多步任务上，Delta MCP 的 token 消耗更少，成本更低，速度一样快甚至更快，最终结果相同，并已在服务本身中核实。共 8 个场景，每个场景都分别在使用和不使用 Delta MCP 的情况下运行，使用 Claude Code 搭配 Sonnet 5.5。单独一个单步问题的成本更高：收益出现在多步任务上。

| 3.3–24.1× | 1.4–8.1× | 最高 4.4× | 100% |
|:--|:--|:--|:--|
| 多步任务上，计费 token 更少 | 多步任务上成本更低，即使在最严格的缓存情形下也是如此 | 多步任务上更快，没有任何一个场景更慢 | 工具被保留：每个原有工具仍可通过 Delta MCP 调用 |

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/bench-dark.png">
    <img src="assets/bench-light.png" alt="同一任务的计费 token 柱状图，分别为直接调用 MCP 和通过 Delta MCP，共 8 个场景：以文本方式修复一个 release 时少 24.1 倍，文档问题上少 1.2 倍，单步问题则多 1.25 倍。" width="100%">
  </picture>
</p>

**[全部基准测试与测量方法 →](https://www.mcpdelta.com/zh/benchmarks)**

## 支持 12 款 AI 应用

Claude Desktop、Claude Code、Cursor、VS Code、Windsurf、Gemini CLI、Cline、Roo Code、LM Studio、Amazon Q、Codex 和 Zed。Delta MCP 会替你切换前十款；Codex 和 Zed 目前需要手动设置。你的 MCP 服务器保持原样。[每款应用如何切换](https://www.mcpdelta.com/docs/supported-apps)。

## 下载：即将发布

适用于 macOS、Windows 和 Linux 的免费应用即将发布。目前还没有可以安装的东西，本仓库也不包含应用本身。

| 选项 | 在哪里 |
|:--|:--|
| **下载页面** | [mcpdelta.com/zh/download](https://www.mcpdelta.com/zh/download) |
| **通过 RSS 关注** | [mcpdelta.com/feed.xml](https://www.mcpdelta.com/feed.xml) |
| **在这里关注发布** | **Watch → Custom → Releases**，在本仓库中 |

### 两分钟完成设置

1. **下载并打开 Delta MCP。** 免费，支持 Mac、Windows 和 Linux。
2. **它会找出你的 AI 在用的工具。** 也就是它的 MCP 服务器，分布在 Claude Desktop、Claude Code、Cursor、VS Code 和另外 8 款应用里，实时检测。
3. **点击 Optimize。** 从此你的 AI 通过 Delta MCP 使用它们。随时可以全部还原。

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/first-launch-dark.webp">
    <img src="assets/first-launch-light.webp" alt="Delta MCP 首次启动：它找到了你的 AI 在用的 4 个工具；Optimize 3 tools。" width="420">
  </picture>
</p>

## MCP 指南

关于 MCP 的直接回答：撤销 AI 的改动、安全访问、超时、开销，以及你的 AI 应用，每篇都附上来源。

- [怎么撤销 AI Agent 在 Notion、GitHub 和文件里做的改动？](https://www.mcpdelta.com/zh/guides/undo-ai-agent-changes)
- [AI Agent 删除或改动了数据怎么办？先做什么](https://www.mcpdelta.com/zh/guides/ai-agent-costly-change)
- [如何安全地让 AI 访问你的工具（MCP）](https://www.mcpdelta.com/zh/guides/safe-ai-access-mcp)
- [MCP 工具调用超时了？重试前先检查改动有没有生效](https://www.mcpdelta.com/zh/guides/mcp-write-timeout)
- [MCP 网关、代理与 Delta MCP：你需要哪一个？](https://www.mcpdelta.com/zh/guides/mcp-gateway-vs-proxy)
- [什么时候用 MCP，什么时候复制粘贴更快？](https://www.mcpdelta.com/zh/guides/when-to-use-mcp)
- [怎么减少 MCP token 消耗？MCP 为什么这么耗 token](https://www.mcpdelta.com/zh/guides/reduce-mcp-token-usage)
- [Claude Code 额度用完了？看看 MCP 服务器花了多少](https://www.mcpdelta.com/zh/guides/claude-code-usage-limit-mcp)
- [MCP 配置文件在哪？Claude、Cursor、VS Code 等应用一览](https://www.mcpdelta.com/zh/guides/mcp-clients)
- [MCP vs CLI 有什么区别？AI Agent 的 token 开销出在哪里](https://www.mcpdelta.com/zh/guides/mcp-vs-cli)

## 关于 Delta MCP 的常见问题

<details>
<summary><strong>什么是 Delta MCP？</strong></summary>

Delta MCP 是一款免费应用，位于你的 AI 应用（Claude、Cursor、VS Code……）和它们使用的工具（比如 Notion、GitHub 或你的文件）之间。它在每个任务运行之前检查，要么全部生效，要么一概不动，记录每一处改动，并让你撤销能够撤销的部分。从技术上讲，你的 AI 把每个任务写成一个程序；Delta MCP 在第一次调用之前检查它，以全有或全无的方式执行，回读结果，并原样使用你的 MCP 服务器；在有多个步骤的任务上，token 消耗要少得多。

</details>

<details>
<summary><strong>MCP 是什么？</strong></summary>

MCP（Model Context Protocol，模型上下文协议）是一项标准，让 Claude、Cursor 或 VS Code 这类 AI 应用能够使用 Notion、GitHub 等其他应用和服务。每项服务通过一个 MCP 服务器提供它的工具，这种服务器也叫连接器。Delta MCP 位于你的 AI 和这些服务器之间；用它，你只需要知道这些。

</details>

<details>
<summary><strong>Delta MCP 真的免费吗？</strong></summary>

是的。所有功能都在免费应用里，无需账号，服务器数量不限。详见[价格](https://www.mcpdelta.com/zh/pricing)。

</details>

<details>
<summary><strong>使用 Delta MCP 需要会写代码吗？</strong></summary>

不需要。你照常向你的 AI 提问；程序由它来写，Activity 用平实的语言列出每处改动，并提供 Undo。

</details>

<details>
<summary><strong>任务做到一半失败了会怎样？</strong></summary>

状态、标签或页面这类内容的改动会被还原并核对，因此不会留下做了一半的内容。已经通过工具完成的步骤保持原样，Delta MCP 会把它们列出来，以免你的 AI 再做一遍。如果回答在途中丢失，Delta MCP 会在能够判断的情况下，先核对改动是否已经发生，然后才重做任何事情，并且从不自行重发消息。Undo 会还原能够还原的内容，并说明哪些无法还原，比如已经发出的消息。

</details>

<details>
<summary><strong>我的 AI 应用已经会先问我，Delta MCP 还多做什么？</strong></summary>

如果你想先由你同意，Delta MCP 的确认卡片会显示将要改动的内容，包括前后对比，而不只是写出将要运行的工具名。然后它要么全部生效，要么一概不动，核对结果，并提供 Undo。你可以为每个工具选择：哪些需要你同意，哪些你的 AI 可以自行完成。

</details>

<details>
<summary><strong>Delta MCP 能省 token 吗？</strong></summary>

能，在有多个步骤的任务上：在我们的测量里，token 消耗少了 3.3 到 24.1 倍。单独一个单步问题则更费（约为 1.25 倍的 token），因为你的 AI 每次调用都要读一遍 Delta MCP 的简短说明。

</details>

<details>
<summary><strong>我需要改动我的 MCP 服务器吗？</strong></summary>

不需要。Delta MCP 原样使用它们。每个原有工具仍可按名称调用：在我们试过的最大的服务器上，152 个工具中的 152 个都能调用。

</details>

<details>
<summary><strong>Delta MCP 会把我的数据发到别处吗？</strong></summary>

不会。Delta MCP 运行在你的电脑上，直接和你的服务器通信；你的工具、任务和历史记录都不会离开电脑。除了检查新版本（不会发送任何关于你的信息），唯一可能发出的是每天一个匿名数字，也就是你节省的 token 数：首次启动时由你选择，之后可在 Settings 里一键关闭。

</details>

<details>
<summary><strong>Delta MCP 是开源的吗？</strong></summary>

不是。Delta MCP 是一款免费应用，源代码不公开。它的工作原理写在文档里，测量方法在基准测试页，它在你电脑上做的一切都记录在 Activity 里。

</details>

<details>
<summary><strong>怎样停止使用 Delta MCP？</strong></summary>

打开 Settings，点 Put everything back（全部还原）。每个连接器都会原样回到你的 AI 应用里；Delta MCP 保留了它改动过的每个文件的副本。

</details>

<details>
<summary><strong>Delta MCP 支持哪些 AI 应用？</strong></summary>

Delta MCP 支持 12 款 AI 应用：Claude Desktop、Claude Code、Cursor、VS Code、Windsurf、Gemini CLI、Cline、Roo Code、LM Studio、Amazon Q、Codex 和 Zed。前十款它会替你切换过去；Codex 和 Zed 目前需要手动设置。

</details>

<details>
<summary><strong>我的 AI 应用已经有 Tool Search，还需要 Delta MCP 吗？</strong></summary>

需要，在有多个步骤的任务上。Tool Search 让工具列表保持简短，但每一步仍然是对模型的一次单独请求。Delta MCP 去掉了这些请求：你的 AI 把任务写成一个程序。我们的测量是在开启 Tool Search 的情况下做的，所以节省的部分是叠加在它之上的。

</details>

<details>
<summary><strong>Delta MCP 是 MCP 网关或代理吗？</strong></summary>

它和网关处在同一个位置：在你的 AI 应用里，所有 MCP 服务器前面只有一个入口，这样你的 AI 就不必加载每个服务器的每一个工具。它是装在你自己电脑上的免费应用，没有需要单独启动的服务，所以更像本地代理，而不是企业级网关。它额外做的，是普通网关不做的事：你的 AI 把每个任务写成一个带类型的程序，Delta MCP 在第一次调用之前检查它，以全有或全无的方式执行，再回读结果，留在 Activity 里，随时可以撤销，还可以存成快捷指令，或者按固定时间运行。

</details>

<details>
<summary><strong>Delta MCP 能自动化哪些任务？</strong></summary>

任何你重复做的任务：读取昨晚的 Grafana 日志并把报告发给团队，跟踪市场并发送每日摘要，每周五关闭已完成的工单。选择运行时间：每天、工作日、每周一或每小时。每次运行都会进入 Activity，菜单栏会显示下次运行和上次运行。

</details>

<details>
<summary><strong>自动化需要我的 AI 吗？</strong></summary>

不一定。Delta MCP 可以自己运行它，免费，无需 AI，也不消耗 token。任务需要分析时，它会在你设定的时间把这次运行交给你的 AI：一段简短的 AI 会话，写出报告、发送邮件，或根据结果采取行动。这需要你的 AI 应用处于打开状态，或已安装命令行 AI，例如 Claude Code。

</details>

<details>
<summary><strong>我的 AI 能帮我设置自动化吗？</strong></summary>

能。告诉你的 AI 要自动化什么，它就会在 Delta MCP 里创建这个自动化。你先测试，然后签署一次。失败两次后，它会暂停并告诉你。一个自动化只能发送你签署过的内容，并列在它的卡片上。

</details>

## ⭐ 用一个星标支持 Delta MCP

Delta MCP 免费，并为赢得你的信任而打造。如果它正合你所需，请为这个仓库加一个星标：这是支持它最简单的方式，能帮助其他人找到它，也能让你在正式发布时再次找到它。谢谢。

<p align="center"><a href="https://github.com/mcpdelta/mcpdelta"><img src="https://img.shields.io/github/stars/mcpdelta/mcpdelta?style=for-the-badge&logo=github&logoColor=white&color=16794F&labelColor=0E2E21" alt="GitHub stars"></a></p>

## 用你的语言了解 Delta MCP

每种语言都有自己的 README 和网站。

<p><a href="README.md">English</a> · <b>中文</b> · <a href="README.hi.md">हिन्दी</a> · <a href="README.es.md">Español</a> · <a href="README.ar.md">العربية</a> · <a href="README.fr.md">Français</a> · <a href="README.bn.md">বাংলা</a> · <a href="README.pt.md">Português</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.ur.md">اردو</a> · <a href="README.ru.md">Русский</a> · <a href="README.de.md">Deutsch</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.el.md">Ελληνικά</a></p>

## 安全

如需报告问题，请私下发邮件至 [contact@mcpdelta.com](mailto:contact@mcpdelta.com)。详见 [SECURITY.md](SECURITY.md)。

## 许可证

Delta MCP 是专有软件，不是开源软件。本仓库只介绍应用：不含任何源代码。详见 [NOTICE](NOTICE)。

---

<p align="center">© 2026 Delta MCP。保留所有权利。<br>本仓库只介绍应用。</p>
