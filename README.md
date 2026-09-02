## Cloto-dev

I build tools that give AI agents something to stand on: memory that survives a
session, retrieval that can be reasoned about, and a protocol layer for agents
that have to talk to each other. Solo developer, in Japan.

Most of what I publish starts as something I needed myself and kept using.

### Projects

| Project | What it is | Licence |
| --- | --- | --- |
| **[CPersona](https://github.com/Cloto-dev/cpersona)** | An MCP memory server. One SQLite file, hybrid search over vectors and full text, no LLM in the retrieval path. Runs against Claude Desktop, Claude Code, or any MCP host. | MIT |
| **[CEmbedding](https://github.com/Cloto-dev/CEmbedding)** | A local-first embedding server — ONNX on-device, or an API backend if you prefer. The reference `/embed` server for CPersona. | MIT |
| **[ClotoCore](https://github.com/Cloto-dev/ClotoCore)** | A desktop platform for running your own AI agents, event-driven and extensible. | BSL 1.1, converting to MIT on 2028-02-14 |
| **[MGP](https://github.com/Cloto-dev/mgp-spec)** | The Multi-Agent Gateway Protocol: a strict MCP superset for agent-to-agent work. Specification, with reference implementations in [Rust](https://github.com/Cloto-dev/mgp-rs) and [Python](https://github.com/Cloto-dev/mgp-py). | MIT |

### Supporting this work

Everything above is free to use under its licence, sponsored or not. Nothing is
held back for sponsors, and issues are triaged by impact, reproducibility and
safety — the same for everyone.

If one of these projects has been useful and you would like the work to
continue, [GitHub Sponsors](https://github.com/sponsors/Cloto-dev) is the one
place that covers all of it. One-time and monthly are equally welcome, and
neither is expected.

Money is not the only thing that helps, and for projects this size it is not the
thing that helps most:

- star a repository, so the next person finds it;
- say which part of the setup was confusing — that is a documentation defect, and I want to know;
- file an issue with steps that reproduce it;
- fix a sentence in the docs, or add the example you wished had been there;
- tell someone who has the problem these tools solve.

### Elsewhere

- [ClotoHub](https://hub.cloto.dev) — server marketplace and integrity verification for MGP
- [Zenn](https://zenn.dev/cloto) — longer writing, in Japanese
- [X](https://x.com/cloto_dev)
