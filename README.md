# Erin Krasniqi

I try to build tests that AI can't game. So far the AI keeps winning, and the reasons are the interesting part.

From September to October 2026 I led **JUMP**: one person and three AI systems (ChatGPT Pro, Codex and Claude) trying to build a benchmark of autonomous physics research that models couldn't saturate without genuinely getting better.

```text
rounds of design and review ...... about 48
model episodes ................... 162
designs that survived ............ 0
```

Why every design failed is in the paper: **[Who Writes the Answer Key?](https://doi.org/10.5281/zenodo.23579090)** ([on GitHub](https://github.com/dlowzzxx/who-writes-the-answer-key))

### Physics, built with AI coding assistance

- **[NOETHER](https://github.com/dlowzzxx/NOETHER)**: turns physics intuitions into testable predictions, so evidence decides what survives.
- **[KeplerLab](https://github.com/dlowzzxx/KeplerLab)**: a physics-informed neural network for orbital dynamics, built to show where it fails and why.
- **[Artemis II simulator](https://github.com/dlowzzxx/artemis-ii-orbital-sim)**: an Earth–Moon N-body simulation of the Artemis II mission profile ([run it in your browser](https://artemis-ii-orbital-sim.vercel.app)).

### Merged upstream

[35 merged pull requests across 14 open-source repositories](https://github.com/search?q=author%3Adlowzzxx+is%3Apr+is%3Amerged+-user%3Adlowzzxx&type=pullrequests) as of October 2026. Codex wrote most of the code; I pick the issue, scope the change and see it through review. A few:

- [OpenInference #3662](https://github.com/Arize-ai/openinference/pull/3662): tracing context now survives coroutines and generators.
- [OpenTelemetry Python #5631](https://github.com/open-telemetry/opentelemetry-python/pull/5631): named metric views without an instrument name now raise an error, with regression tests.
- [Hugging Face tokenizers #2547](https://github.com/huggingface/tokenizers/pull/2547): Split deserialization honors the configured regex backend.
- [OpenTelemetry GenAI #634](https://github.com/open-telemetry/opentelemetry-python-genai/pull/634): local agent invocations record inference and tool-call counts.
- [fsspec #2268](https://github.com/fsspec/filesystem_spec/pull/2268): invalid in-memory copy destinations are rejected before they can corrupt the directory structure.
- [OpenTelemetry GenAI #670](https://github.com/open-telemetry/opentelemetry-python-genai/pull/670): retrieval spans record document relevance scores, valid zeros included.

### Also

First-year Computing and Information Technologies student at RIT Kosovo. Elsewhere: [X](https://x.com/KrasniqiErin) · [ORCID](https://orcid.org/0009-0008-0051-4163)
