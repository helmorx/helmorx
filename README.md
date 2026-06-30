<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:06080D,50:0E1724,100:19C37D&text=HELMOR%20X&fontColor=EAF1FF&fontSize=58&fontAlignY=38&desc=Local-first%20AI%20development%20engine&descAlignY=58&descSize=18" alt="HELMOR X banner" />
</p>

<h2 align="center">AI coding agents need a project operating layer.</h2>

<p align="center">
  HELMOR builds local-first tools that reduce wasted tokens, project drift, hallucinated changes, and unsafe agent actions.
</p>

<p align="center">
  <a href="https://github.com/helmorx/devsuite"><img src="https://img.shields.io/badge/Open-DevSuite-19C37D?style=for-the-badge&logo=github&logoColor=06080D" alt="Open DevSuite"></a>
  <a href="https://github.com/helmorx/devsuite/releases"><img src="https://img.shields.io/badge/Install-v0.1.0-0E1724?style=for-the-badge" alt="Install v0.1.0"></a>
  <a href="https://github.com/helmorx/devsuite/blob/main/LICENSE"><img src="https://img.shields.io/badge/Apache--2.0-local--first-0E1724?style=for-the-badge" alt="Apache-2.0 local-first"></a>
</p>

---

## Start here

```bash
brew tap helmorx/devsuite https://github.com/helmorx/devsuite
brew install helmor
helmor install
helmor dashboard
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

## Project

| Repository | What it is |
|---|---|
| [helmorx/devsuite](https://github.com/helmorx/devsuite) | The local development engine for AI-assisted coding |

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
