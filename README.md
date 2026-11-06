# APACHE STAR — Building AI Ops in Public

APACHE STAR is a founder-run American brand from Jackson, Wyoming. It grew out of
a powerboat world-record heritage and now sells fashion and supplements.
I'm building the company's day-to-day operations around one AI agent,
in public.

## Meet Boris
Boris is the AI co-founder I'm building: a single agent with tools, plus
scheduled background jobs, running on our own server. It drafts email replies,
social posts and outreach, and it watches the store, the ad feeds and the books.
**Boris drafts, I approve, then it sends.** Outbound posts and emails go through
a compliance check first. Boris's own code is private. The gate pattern is open source.

## What's public
- 🚦 **[agent-compliance-gate](https://github.com/APACHE-STAR/agent-compliance-gate)**
  [![tests](https://github.com/APACHE-STAR/agent-compliance-gate/actions/workflows/ci.yml/badge.svg)](https://github.com/APACHE-STAR/agent-compliance-gate/actions/workflows/ci.yml) —
  the compliance-gate pattern as a small MIT-licensed Python package with a test
  suite (`pip install git+https://github.com/APACHE-STAR/agent-compliance-gate`).
  Drafting and sending are separate.
- 🗺️ **[Public roadmap](https://github.com/users/APACHE-STAR/projects/1)**: what
  has shipped and what's next. Boris can add cards to this board.

## What runs behind it (private)
- 🎙️ A brand-voice review step ("Keel") checks the tone of posts before they reach me.
- 📲 A morning briefing and approvals on my phone.

## The honest part
One outreach agent once sent emails signed by people who don't exist. We didn't
hide it — we built a hard compliance gate so nothing ships unchecked, and
open-sourced the pattern.

**Autonomous AI should act — but never without a gate.**

## Follow the build
- 𝕏 [@JesseFruehbrodt](https://x.com/JesseFruehbrodt): building in public
- 🦞 Moltbook: [apachestarboris](https://www.moltbook.com/u/apachestarboris)
- 🌐 [apachestar.com](https://apachestar.com)
- ✉️ [info@apachestar.com](mailto:info@apachestar.com)
