<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
  <img src="assets/logo-light.svg" alt="Delta MCP" width="260">
</picture>

<h1 align="center">Delta MCP: check and undo your AI’s changes to your tools</h1>

<p><strong>Delta MCP is a free app between your AI and your tools (Notion, GitHub, your files…). It checks each task, makes every change or none, and lets you undo it.</strong></p>

<p><a href="https://github.com/mcpdelta/mcpdelta"><img src="https://img.shields.io/github/stars/mcpdelta/mcpdelta?style=for-the-badge&logo=github&logoColor=white&color=16794F&labelColor=0E2E21" alt="GitHub stars"></a></p>

<p>Every change recorded, with Undo · Free, no account · Runs on your computer</p>

<p>🌐 <b>English</b> · <a href="README.zh.md">中文</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.es.md">Español</a> · <a href="README.ar.md">العربية</a> · <a href="README.fr.md">Français</a> · <a href="README.bn.md">বাংলা</a> · <a href="README.pt.md">Português</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.ur.md">اردو</a> · <a href="README.ru.md">Русский</a> · <a href="README.de.md">Deutsch</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.el.md">Ελληνικά</a></p>

<p>
  <a href="https://www.mcpdelta.com">Website</a> ·
  <a href="https://www.mcpdelta.com/how-it-works">How it works</a> ·
  <a href="https://www.mcpdelta.com/benchmarks">Benchmarks</a> ·
  <a href="https://www.mcpdelta.com/docs">Docs</a> ·
  <a href="https://www.mcpdelta.com/guides">Guides</a> ·
  <a href="https://www.mcpdelta.com/download">Download: coming soon</a>
</p>

</div>

> ⭐ **Back Delta MCP with a star.** Click **Star** at the top right of this page. It takes one second, it’s free, and it helps other people who use MCP find Delta MCP before launch.

> **Coming soon** for macOS, Windows and Linux: free, no account. Follow the launch and you’ll know the moment it’s out, with no email address: [RSS](https://www.mcpdelta.com/feed.xml), or **Watch → Custom → Releases** on this repository.

<p align="center">
  <img src="assets/demo.gif" alt="Delta MCP’s mark is drawn by a small circle rolling inside a larger one. The name and “Coming soon” appear, then the app’s Activity window: each task in one sentence, its changes before and after, and Undo." width="100%">
</p>

## Decide before. See after. Go back.

1. **You decide before.** For each tool, choose what your AI may do alone: only read, ask before deleting or sending, or ask every time. When it asks, you see each change before and after.
2. **You see what happened.** Every change is recorded with its before and after, written by Delta MCP, not by your AI. It checks results in the tool when it can, and if a connection drops it checks before doing anything twice.
3. **You can go back.** Undo puts back what can be put back, and tells you before you click what can’t, like a message already sent.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/activity-dark.webp">
    <img src="assets/activity-light.webp" alt="Delta MCP’s Activity window: a task your AI did, its changes before and after, a note on what can’t be undone, and the Undo button." width="100%">
  </picture>
</p>

> ⭐ **Like what you see? A star is the simplest way to back Delta MCP.** It tells us this is worth finishing.

## Ctrl+Z for your AI’s work.

Every task shows each change before and after. Undo it right away, and in some cases later, by you or by your AI.

- **Before and after.** Changes are shown as they were and as they are now, read back from the service wherever it can be read.
- **One step or the whole task.** Your AI writes how to undo each step. If a later step fails, or you click Undo, they run in reverse order.
- **Honest about what can’t come back.** Before you click, you see what will be put back and what can’t, like a message already sent. It never says everything is undone without proof.

## Automate the tasks you repeat.

Set it once. Delta MCP runs it every day, on weekdays, every Monday or every hour, at a very low cost, and your AI steps in only when the task needs thinking.

- **Reports and routines.** Analyze last night’s Grafana logs and send your team a report. Follow the market every morning. Close finished tickets every Friday.
- **Free, or with your AI.** Delta MCP runs it for free, no AI needed. When it needs analysis, your AI takes the run at the time you set, then reports, emails or acts on what it finds.
- **Ask your AI to set it up.** Tell your AI what to automate and it creates it in Delta MCP. You test it, sign once, and it pauses and tells you after two failures.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/automations-dark.webp">
    <img src="assets/automations-light.webp" alt="Delta MCP’s Automations list: Daily report every day at 8:00 with its last run and the next one, Weekly cleanup on Mondays, and one automation paused." width="100%">
  </picture>
</p>

## Measured: up to 24.1× fewer tokens

Same result, far fewer tokens. On tasks with several steps, Delta MCP uses fewer tokens, costs less and finishes as fast or faster, with the same end result, checked in the service itself. 8 scenarios, each run with and without Delta MCP, in Claude Code with Sonnet 5.5. A single one-step question costs more: the gain is on tasks with several steps.

| 3.3–24.1× | 1.4–8.1× | up to 4.4× | 100% |
|:--|:--|:--|:--|
| fewer billed tokens on multi-step tasks | lower cost on multi-step tasks, even in the strictest cache case | faster on multi-step tasks, and no scenario is slower | of the tools kept: every original tool stays callable through Delta MCP |

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/bench-dark.png">
    <img src="assets/bench-light.png" alt="Bar chart of billed tokens for the same task, with direct MCP calls and through Delta MCP, on eight scenarios: from 24.1 times fewer tokens to fix a release as text, down to 1.2 times fewer on a documentation question. On a one-step question it uses 1.25 times more." width="100%">
  </picture>
</p>

**[All benchmarks, with the method →](https://www.mcpdelta.com/benchmarks)**

## Works with 12 AI apps

Claude Desktop, Claude Code, Cursor, VS Code, Windsurf, Gemini CLI, Cline, Roo Code, LM Studio, Amazon Q, Codex and Zed. Delta MCP switches the first ten over for you; Codex and Zed are set up by hand for now. Your MCP servers stay exactly as they are. [How each app is switched over](https://www.mcpdelta.com/docs/supported-apps).

## Download: coming soon

The free app for macOS, Windows and Linux is coming soon. There is nothing to install yet, and this repository does not contain the app.

| Option | Where |
|:--|:--|
| **Download page** | [mcpdelta.com/download](https://www.mcpdelta.com/download) |
| **Follow with RSS** | [mcpdelta.com/feed.xml](https://www.mcpdelta.com/feed.xml) |
| **Watch releases here** | **Watch → Custom → Releases**, on this repository |

### Set up in two minutes

1. **Download and open Delta MCP.** Free, for Mac, Windows and Linux.
2. **It finds the tools your AI uses.** Its MCP servers, in Claude Desktop, Claude Code, Cursor, VS Code and 8 more apps, checked live.
3. **Click Optimize.** Your AI uses them through Delta MCP from then on. Put everything back whenever you like.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/first-launch-dark.webp">
    <img src="assets/first-launch-light.webp" alt="Delta MCP’s first launch: it found 4 tools your AI uses; Optimize 3 tools." width="420">
  </picture>
</p>

## MCP guides

Straight answers about MCP: undoing an AI’s changes, safe access, timeouts, costs and your AI apps, each with its sources.

- [How to undo what an AI agent did in Notion, GitHub and files](https://www.mcpdelta.com/guides/undo-ai-agent-changes)
- [AI agent deleted or changed data? What to do first](https://www.mcpdelta.com/guides/ai-agent-costly-change)
- [How to give an AI access to your tools safely (MCP)](https://www.mcpdelta.com/guides/safe-ai-access-mcp)
- [MCP tool call timed out? Check the write before retrying](https://www.mcpdelta.com/guides/mcp-write-timeout)
- [MCP gateway vs proxy vs Delta MCP: which do you need?](https://www.mcpdelta.com/guides/mcp-gateway-vs-proxy)
- [When to use MCP, and when copy-paste is faster](https://www.mcpdelta.com/guides/when-to-use-mcp)
- [How to reduce MCP token usage, and why MCP burns tokens](https://www.mcpdelta.com/guides/reduce-mcp-token-usage)
- [Claude Code usage limit reached? What your MCP servers cost](https://www.mcpdelta.com/guides/claude-code-usage-limit-mcp)
- [MCP config file locations: Claude, Cursor, VS Code and more](https://www.mcpdelta.com/guides/mcp-clients)
- [MCP vs CLI for AI agents: where the token bill comes from](https://www.mcpdelta.com/guides/mcp-vs-cli)

## Questions about Delta MCP

<details>
<summary><strong>What is Delta MCP?</strong></summary>

Delta MCP is a free app that sits between your AI apps (Claude, Cursor, VS Code…) and the tools they use, like Notion, GitHub or your files. It checks each task before it runs, makes every change or none, keeps a record of every change and lets you undo what can be undone. Technically, your AI writes each task as one program; Delta MCP checks it before the first call, applies it all or nothing, reads the result back and talks to your MCP servers as they are, with far fewer tokens on tasks of several steps.

</details>

<details>
<summary><strong>What is MCP?</strong></summary>

MCP (Model Context Protocol) is the standard that lets AI apps like Claude, Cursor or VS Code use other apps and services, such as Notion or GitHub. Each service offers its tools through an MCP server, also called a connector. Delta MCP sits between your AI and those servers; you don’t need to know more than that to use it.

</details>

<details>
<summary><strong>Is Delta MCP really free?</strong></summary>

Yes. Every feature is in the free app, with no account and no limit on servers. See [pricing](https://www.mcpdelta.com/pricing).

</details>

<details>
<summary><strong>Do I need to know how to code to use Delta MCP?</strong></summary>

No. You ask your AI as usual; it writes the program, and Activity shows each change in plain words, with Undo.

</details>

<details>
<summary><strong>What happens if a task fails halfway?</strong></summary>

Changes to things like a status, a label or a page are put back and checked, so nothing is left half done. A step already made through a tool as it is stays made, and Delta MCP lists it so your AI doesn’t make it twice. If an answer gets lost on the way, Delta MCP checks, when it can, whether the change happened before anything is redone, and never resends a message on its own. Undo puts back what can be put back and says what can’t, like a message already sent.

</details>

<details>
<summary><strong>My AI app already asks before it acts. What does Delta MCP add?</strong></summary>

When you want a yes first, Delta MCP’s card shows what will change, before and after, instead of only naming the tool that will run. Then it makes every change or none, checks the result and keeps an Undo. You choose, for each tool, what needs your yes and what your AI may do alone.

</details>

<details>
<summary><strong>Does Delta MCP save tokens?</strong></summary>

Yes, on tasks with several steps: 3.3 to 24.1 times fewer tokens in our measurements. A single one-step question costs more (about 1.25 times the tokens), because your AI reads Delta MCP’s short description on every call.

</details>

<details>
<summary><strong>Do I need to change my MCP servers?</strong></summary>

No. Delta MCP uses them exactly as they are. Every original tool stays callable by name: 152 of 152 on the largest server we tried.

</details>

<details>
<summary><strong>Does Delta MCP send my data anywhere?</strong></summary>

No. Delta MCP runs on your computer and talks to your servers directly; your tools, tasks and history never leave it. Besides a check for new versions, which sends nothing about you, the only thing that can be sent is one anonymous number a day, your tokens saved: you choose at first launch, and it’s off in Settings in one click.

</details>

<details>
<summary><strong>Is Delta MCP open source?</strong></summary>

No. Delta MCP is a free app, and its source code is not public. How it works is written out in the docs, how it is measured is on the benchmarks page, and everything it does on your computer is recorded in Activity.

</details>

<details>
<summary><strong>How do I stop using Delta MCP?</strong></summary>

Settings, then Put everything back. Each connector returns to your AI apps exactly as it was; Delta MCP keeps a copy of every file it changed.

</details>

<details>
<summary><strong>Which AI apps does Delta MCP work with?</strong></summary>

Delta MCP works with 12 AI apps: Claude Desktop, Claude Code, Cursor, VS Code, Windsurf, Gemini CLI, Cline, Roo Code, LM Studio, Amazon Q, Codex and Zed. It switches the first ten over for you; Codex and Zed are set up by hand for now.

</details>

<details>
<summary><strong>Do I still need Delta MCP if my AI app has Tool Search?</strong></summary>

Yes, on tasks with several steps. Tool Search keeps the list of tools short, but every step is still a separate request to the model. Delta MCP removes those requests: your AI writes the task as one program. Our measurements were taken with Tool Search on, so the savings come on top of it.

</details>

<details>
<summary><strong>Is Delta MCP an MCP gateway or proxy?</strong></summary>

It sits where a gateway does: one entry in your AI apps in front of all your MCP servers, so your AI doesn’t load every tool of every server. It runs on your own computer, free, with no service to run, so it is closer to a local proxy than to an enterprise gateway. What it adds is what a plain gateway doesn’t do: your AI writes each task as one typed program, Delta MCP checks it before the first call, applies it all or nothing, reads it back, keeps it in Activity with Undo, and can keep it as a shortcut or run it on a schedule.

</details>

<details>
<summary><strong>What can I automate with Delta MCP?</strong></summary>

Any task you repeat: read last night’s Grafana logs and send your team a report, follow the market and send a daily summary, close finished tickets every Friday. Choose when it runs: every day, on weekdays, every Monday or every hour. Every run lands in Activity, and the menu bar shows the next run and the last run.

</details>

<details>
<summary><strong>Does an automation need my AI?</strong></summary>

Not always. Delta MCP can run it itself, for free, with no AI and no tokens. When the task needs analysis, it hands the run to your AI at the time you set: a short AI session that writes the report, sends the email or acts on the results, with your AI app open or a command-line AI like Claude Code installed.

</details>

<details>
<summary><strong>Can my AI set up an automation for me?</strong></summary>

Yes. Tell your AI what to automate and it creates the automation in Delta MCP. You test it first, then sign once, and it pauses and tells you after two failures. An automation can send only what you signed, listed on its card.

</details>

## ⭐ Back Delta MCP with a star

Delta MCP is free and built to earn your trust. If it sounds like what you need, star this repository: it is the simplest way to support it, it helps others find it, and it lets you find it again at launch. Thank you.

<p align="center"><a href="https://github.com/mcpdelta/mcpdelta"><img src="https://img.shields.io/github/stars/mcpdelta/mcpdelta?style=for-the-badge&logo=github&logoColor=white&color=16794F&labelColor=0E2E21" alt="GitHub stars"></a></p>

## Delta MCP in your language

Each language has its own README and its own website.

<p><b>English</b> · <a href="README.zh.md">中文</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.es.md">Español</a> · <a href="README.ar.md">العربية</a> · <a href="README.fr.md">Français</a> · <a href="README.bn.md">বাংলা</a> · <a href="README.pt.md">Português</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.ur.md">اردو</a> · <a href="README.ru.md">Русский</a> · <a href="README.de.md">Deutsch</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.el.md">Ελληνικά</a></p>

## Security

To report a problem, write to us privately at [contact@mcpdelta.com](mailto:contact@mcpdelta.com). See [SECURITY.md](SECURITY.md).

## License

Delta MCP is proprietary software and is not open source. This repository only presents the app: it contains no source code. See [NOTICE](NOTICE).

---

<p align="center">© 2026 Delta MCP. All rights reserved.<br>This repository only presents the app.</p>
