# Brian Lathe

**Applied AI systems builder — Minneapolis area, Minnesota**

I build and operate autonomous AI systems that run around the clock on
hardware I own. My main project, **SuccessBrian OS**, is a working
multi-agent operating system for a one-person business: it watches a
fleet of machines, processes its own work queues, prepares decisions
for human ruling, and keeps a permanent, queryable record of
everything it does — 24 hours a day, whether I'm at the keyboard or
not.

## See it running

- **Live operations dashboard:** https://successbrianvps.com/pm/
  — the system's own public window: work queues, decisions, and
  system health, updated by the machines themselves.
- **Flagship repo:** [successbrian-os](https://github.com/successbrian/successbrian-os)
  — 300+ commits of deterministic Python, PostgreSQL, and local LLM
  inference. No framework-of-the-week; the boring, reliable parts are
  code, and small local models are used only at defined judgment
  points, with their outputs validated before anything acts on them.

## What the system does

- **Runs a real fleet:** 10+ machines — mini PCs, X79 and DL380
  servers, and a cloud VPS — running local inference (35B-class
  models) on my own hardware.
- **Keeps its own memory:** a knowledge graph of 2,500+ nodes plus a
  decision stream that records what was decided, by whom, and why —
  so nothing depends on anyone's recollection.
- **Repairs itself first:** watchers restart failed workers, silent
  processes get hunted down by their own logs, and only what the
  system genuinely can't fix reaches me.
- **Knows who decides:** the software proposes, ranks, and prepares.
  I rule. That separation is the design, not a disclaimer.

## How I work

Deterministic code first; models where judgment is actually needed;
every claim the system makes carries its evidence. I document
decisions the way I want them read — for intent, so the next reader
(human or machine) understands what was meant, not just what was
said.

## Currently

Open to full-time roles in **applied AI, AI operations, and agentic
systems** — especially teams putting local or hybrid LLM systems
into real production work. The best way to evaluate me is above:
the dashboard is live, and the code is public.

📍 Minnesota · US Navy veteran
