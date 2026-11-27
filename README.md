### Hi, I'm Gautham 👋

Software engineer working on **AI agent frameworks** and **streaming data infrastructure**, mostly in Python.

## Open source

I contribute fixes to agent and data frameworks. Each fix starts from a bug I can reproduce. It ships with a regression test that fails before the fix and passes after it, and with an issue filed first when the change needs maintainer agreement.

| Project | Contribution | Status |
|---|---|---|
| [**Apache Flink Agents**](https://github.com/apache/flink-agents) <br><sub>Apache Flink sub-project (ASF)</sub> | Reject `None` request timeouts consistently across the Python model connections · [#1457](https://github.com/apache/flink-agents/pull/1457) | ![](https://img.shields.io/github/pulls/detail/state/apache/flink-agents/1457) |
| [**Apache Flink Agents**](https://github.com/apache/flink-agents) | Replace pickled MCP server auth, which could run code from config, with typed JSON auth that matches the Java API, and move off a deprecated MCP client · [#1468](https://github.com/apache/flink-agents/pull/1468) | ![](https://img.shields.io/github/pulls/detail/state/apache/flink-agents/1468) |
| [**Haystack**](https://github.com/deepset-ai/haystack) <br><sub>deepset</sub> | Keep non-dict tool results in agent state when `outputs_to_state` has no `source` · [#13950](https://github.com/deepset-ai/haystack/pull/13950) | ![](https://img.shields.io/github/pulls/detail/state/deepset-ai/haystack/13950) |
| [**Temporal Python SDK**](https://github.com/temporalio/sdk-python) | Support the `PAUSED` workflow status, so `describe()` no longer fails on paused workflows · [#2169](https://github.com/temporalio/sdk-python/pull/2169) | ![](https://img.shields.io/github/pulls/detail/state/temporalio/sdk-python/2169) |
| [**Docling**](https://github.com/docling-project/docling) | Stop dropping EPUB chapters whose file names are UTF-8 without the ZIP UTF-8 flag · [#5618](https://github.com/docling-project/docling/pull/5618) | ![](https://img.shields.io/github/pulls/detail/state/docling-project/docling/5618) |
| [**Pathway**](https://github.com/pathwaycom/pathway) | Report the right indexing status per document when a `DocumentStore` query filters · [#290](https://github.com/pathwaycom/pathway/pull/290) | ![](https://img.shields.io/github/pulls/detail/state/pathwaycom/pathway/290) |
| [**Quix Streams**](https://github.com/quixio/quix-streams) | Pass each split row its own Kafka timestamp in the timestamp extractor · [#1209](https://github.com/quixio/quix-streams/pull/1209) | ![](https://img.shields.io/github/pulls/detail/state/quixio/quix-streams/1209) |

<sub>Status badges update automatically. [All my open source pull requests →](https://github.com/search?q=author%3Amjolnir-strike+is%3Apr+-user%3Amjolnir-strike&type=pullrequests)</sub>
