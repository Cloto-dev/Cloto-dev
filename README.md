## Cloto-dev

<sub><b>English</b> · <a href="#日本語">日本語</a></sub>

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
- [X: @CPersona_](https://x.com/CPersona_) — CPersona news

---

## 日本語

<sub><a href="#cloto-dev">English</a> · <b>日本語</b></sub>

AI エージェントが立つための足場を作っています。セッションをまたいで残る記憶、
根拠をたどれる検索、そしてエージェント同士が話すためのプロトコル層。
日本で個人開発しています。

公開しているものの多くは、自分が必要で作り、そのまま使い続けているものです。

### プロジェクト

| プロジェクト | 概要 | ライセンス |
| --- | --- | --- |
| **[CPersona](https://github.com/Cloto-dev/cpersona)** | MCP メモリサーバー。SQLite ファイル 1 つ、ベクトルと全文検索のハイブリッド、検索経路に LLM を使わない。Claude Desktop / Claude Code / 任意の MCP ホストで動く。 | MIT |
| **[CEmbedding](https://github.com/Cloto-dev/CEmbedding)** | ローカル優先の埋め込みサーバー。ONNX のオンデバイス実行、お好みで API バックエンドも。CPersona の参照 `/embed` サーバー。 | MIT |
| **[ClotoCore](https://github.com/Cloto-dev/ClotoCore)** | 自分の AI エージェントを動かすデスクトップ基盤。イベント駆動で拡張可能。 | BSL 1.1、2028-02-14 に MIT へ移行 |
| **[MGP](https://github.com/Cloto-dev/mgp-spec)** | Multi-Agent Gateway Protocol — エージェント間通信のための MCP 厳密スーパーセット。仕様と、[Rust](https://github.com/Cloto-dev/mgp-rs) / [Python](https://github.com/Cloto-dev/mgp-py) の参照実装。 | MIT |

### このプロジェクトを支える

上記はすべて、支援の有無にかかわらずライセンスの条件で自由に使えます。
支援者だけが使える部分はなく、issue は影響度・再現性・安全性で判断します —
それは誰に対しても同じです。

どれかが役に立って、続いてほしいと思っていただけたなら、
[GitHub Sponsors](https://github.com/sponsors/Cloto-dev) が全体をまとめて支える唯一の窓口です。
単発・月額のどちらも同じように歓迎で、どちらも必須ではありません。

金銭以外でも助かります。というより、この規模のプロジェクトではそちらの方が効きます:

- リポジトリに Star を付ける — 次の人が見つけやすくなります
- セットアップのどこで詰まったかを教える — それはドキュメントの不具合なので、知りたいです
- 再現手順つきで issue を立てる
- ドキュメントの 1 文を直す、あるいは「あってほしかった例」を足す
- これらが解く問題を抱えている人に伝える

### その他

- [ClotoHub](https://hub.cloto.dev) — MGP サーバーのマーケットプレイスと完全性検証
- [Zenn](https://zenn.dev/cloto) — 長めの文章(日本語)
- [X: @CPersona_](https://x.com/CPersona_) — CPersona のお知らせ
