<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:06080D,50:0E1724,100:19C37D&text=HELMOR%20Agent%20OS&fontColor=EAF1FF&fontSize=48&fontAlignY=38&desc=Local-first%20operating%20layer%20for%20AI%20coding%20agents&descAlignY=58&descSize=18" alt="HELMOR Agent OS banner" />
</p>

<h2 align="center">AI coding agents need a project operating layer.</h2>

<p align="center">
  HELMOR helps AI coding agents spend fewer tokens, remember repo context, route 14 built-in skills, avoid project drift, and stop unsafe actions before they ship.
</p>

<p align="center">
  <a href="https://helmor.io"><img src="https://img.shields.io/badge/Website-helmor.io-19C37D?style=for-the-badge" alt="helmor.io"></a>
  <a href="https://github.com/helmorx/agent-os"><img src="https://img.shields.io/badge/Open-Agent%20OS-0E1724?style=for-the-badge&logo=github&logoColor=19C37D" alt="Open Agent OS"></a>
  <a href="https://x.com/helmorlabs"><img src="https://img.shields.io/badge/X-@helmorlabs-0E1724?style=for-the-badge&logo=x&logoColor=19C37D" alt="@helmorlabs on X"></a>
</p>

---

## Start here

macOS:

```bash
brew install --formula https://raw.githubusercontent.com/helmorx/agent-os/main/Formula/helmor.rb
```

Windows:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "irm https://raw.githubusercontent.com/helmorx/agent-os/main/install/install.ps1 | iex"
```

Linux:

```bash
curl -fsSL https://raw.githubusercontent.com/helmorx/agent-os/main/install/install.sh | sh
```

## What HELMOR does

<table>
  <tr>
    <td width="33%">
      <h3>Token discipline</h3>
      <p>Compact output, context cards, handoffs, graph-first discovery, and fewer repeated repo scans.</p>
    </td>
    <td width="33%">
      <h3>Agent grounding</h3>
      <p>Project profiles, truth files, checks, modes, and local state keep agents aligned to the repo.</p>
    </td>
    <td width="33%">
      <h3>Safety rails</h3>
      <p>Detector packs catch secrets, destructive commands, runner drift, unsafe deploys, and UI drift.</p>
    </td>
  </tr>
</table>

## HELMOR skills

HELMOR Agent OS is a local devsuite for AI-assisted software work. Its built-in skills help agents choose the right behavior before they spend tokens or touch code.

`Project Memory` · `Token Reduction` · `Architecture` · `API Contracts` · `Testing` · `Security` · `Launch Readiness` · `UI Design` · `Frontend` · `Backend` · `Data` · `Infrastructure` · `Docs & Handoff` · `Product Planning`

## Project

| Repository | What it is |
|---|---|
| [helmorx/agent-os](https://github.com/helmorx/agent-os) | Local operating layer for AI coding agents |

## Built for

- Codex
- Claude Code
- Cursor
- Windsurf
- developers shipping real projects with AI agents

## Principles

- local-first
- no telemetry in v1
- observe before blocking
- deterministic checks before model guesses
- project truth over agent confidence

HELMOR is free and Apache-2.0.
