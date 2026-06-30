<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:06080D,50:0E1724,100:19C37D&text=HELMOR%20Agent%20OS&fontColor=EAF1FF&fontSize=48&fontAlignY=38&desc=The%20local%20agent%20watcher%20for%20AI%20product%20development&descAlignY=58&descSize=18" alt="HELMOR Agent OS banner" />
</p>

<h2 align="center">Build with AI agents from idea to launch.</h2>

<p align="center">
  HELMOR Agent OS is a local-first devsuite that watches AI coding sessions, routes 14 built-in skills, preserves project context, reduces token waste, reduces drift, and enforces checks before handoff or release.
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
brew install helmorx/tap/helmoragent
```

Windows:

```powershell
irm https://raw.githubusercontent.com/helmorx/agent-os/main/install/install.ps1 | iex
```

Linux:

```bash
curl -fsSL https://raw.githubusercontent.com/helmorx/agent-os/main/install/install.sh | sh
```

## What HELMOR does

<table>
  <tr>
    <td width="33%">
      <h3>Watches the session</h3>
      <p>Starts agents with context, watches tool use, tracks touched areas, and preserves handoffs.</p>
    </td>
    <td width="33%">
      <h3>Routes the work</h3>
      <p>Uses 14 HELMOR skills across planning, building, verification, launch, and memory.</p>
    </td>
    <td width="33%">
      <h3>Reduces waste</h3>
      <p>Cuts repeated repo scans, reduces hallucination and drift, and keeps checks visible.</p>
    </td>
  </tr>
</table>

## Product lifecycle

`Plan` -> `Build` -> `Watch` -> `Verify` -> `Ship` -> `Remember`

## HELMOR skills

`Product Planning` · `Architecture` · `API Contracts` · `Frontend` · `Backend` · `Data` · `Infrastructure` · `UI Design` · `Testing` · `Security` · `Launch Readiness` · `Project Memory` · `Token Reduction` · `Docs & Handoff`

## Project

| Repository | What it is |
|---|---|
| [helmorx/agent-os](https://github.com/helmorx/agent-os) | Local agent watcher and operating layer for AI-assisted product development |

## Principles

- local-first
- no telemetry in v1
- observe before blocking
- deterministic checks before model guesses
- project truth over agent confidence

HELMOR is free and Apache-2.0.
