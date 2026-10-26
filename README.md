<div align="center">

```
███╗   ███╗██╗   ██╗███╗   ██╗███████╗███████╗██████╗ 
████╗ ████║██║   ██║████╗  ██║██╔════╝██╔════╝██╔══██╗
██╔████╔██║██║   ██║██╔██╗ ██║█████╗  █████╗  ██████╔╝
██║╚██╔╝██║██║   ██║██║╚██╗██║██╔══╝  ██╔══╝  ██╔══██╗
██║ ╚═╝ ██║╚██████╔╝██║ ╚████║███████╗███████╗██████╔╝
╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═══╝╚══════╝╚══════╝╚═════╝ 
```

**Data & AI Engineer** — AI security tooling, LLM evaluation harnesses, full-stack products
`Islamabad, Pakistan` · `@turing` · [`muneebs.space`](https://muneebs.space) · [`ORCID 0009-0001-2042-7656`](https://orcid.org/0009-0001-2042-7656)

</div>

```console
muneeb@horizon ~ $ whoami
Muneeb Anjum — Data & AI engineer, researcher, author.

muneeb@horizon ~ $ cat focus.txt
> LLM security        prompt injection, quantization-induced attack surface
> Evaluation           benchmarks that report what aggregate accuracy hides
> Quantization         what survives compression, and what silently flips
> Product engineering  Chrome extensions, MCP servers, self-hosted tools

muneeb@horizon ~ $ tree research --depth 1
research/
├── quantized-guardians          accuracy-neutral decision churn in compressed detectors
├── smart-contract-verdict-churn verdict churn in quantized smart-contract auditors
├── sentinel-llm                 five-layer defense framework for adversarial prompts
└── tokenization-attack-kit      11 Unicode-level attack families + detector
```

| Paper | What it measures | Status |
|---|---|---|
| **Quantized Guardians** — Accuracy-Neutral Decision Churn in Compressed Prompt-Injection Detectors | F1/AUROC hold steady while *which* inputs get blocked flips | [DOI](https://doi.org/10.5281/zenodo.23210534) |
| **Same Accuracy, Different Verdicts** — Quantization-Induced Verdict Churn in Small LLM Smart-Contract Auditors | 175 Solidity contracts, F16 → Q8_0 → Q4_K_M, up to 45.7% verdict flips | [DOI](https://doi.org/10.5281/zenodo.23241640) |
| **SENTINEL-LLM** — Practical Multi-Layer Defense for Adversarial Prompts | 7 PoC prompts, 32 real attacks (JailbreakBench / HarmBench / OWASP) | [preprint + code](https://github.com/horizonbymuneeb/sentinel-llm) |
| **TokenAttackKit** — Unicode-Level Tokenization Attack Detection | 11 attack families, 0.98 F1 heuristic detector, CPU-only | [code](https://github.com/horizonbymuneeb/tokenization-attack-kit) |

```console
muneeb@horizon ~ $ ./projects --sort recent --limit 6
```

| Project | Stack | Description |
|---|---|---|
| [`localbench`](https://github.com/horizonbymuneeb/localbench) | `Python` `FastAPI` | Benchmark console for local LLM servers — TTFT, prefill/decode tok/s across 1K–64K contexts, concurrency sweeps, GPU telemetry |
| [`pin-saver`](https://github.com/horizonbymuneeb/pin-saver) | `JavaScript` `MV3` | Download a whole Pinterest board as ZIP or PDF — zero dependencies, [live on the Chrome Web Store](https://chromewebstore.google.com/detail/pin-saver-pinterest-board/jdfjeiajmielkjbeoafnekpppdlpjkeg) |
| [`linkedin-mcp-pro`](https://github.com/horizonbymuneeb/linkedin-mcp-pro) | `Python` `MCP` `Playwright` | MCP server exposing 54 LinkedIn tools to any agent runtime |
| [`llm-quantization-benchmarks`](https://github.com/horizonbymuneeb/llm-quantization-benchmarks) | `Python` | Accuracy delta, per-input decision churn and per-layer sensitivity across FP32/BF16/INT8/INT4 |
| [`agentic-rag-pipeline`](https://github.com/horizonbymuneeb/agentic-rag-pipeline) | `Python` | Hybrid BM25 + dense retrieval, reciprocal rank fusion, query rewriting, grounding checks |
| [`tinyllm-eval-suite`](https://github.com/horizonbymuneeb/tinyllm-eval-suite) | `Python` | Reproducible eval harness for small models — task suites, scoring, regression tracking |

```console
muneeb@horizon ~ $ ls ~/engineering
speech-to-text-pipeline   time-series-anomaly      fraud-detection-system
neural-architecture-search mlops-experiment-tracking synthetic-data-generator
multimodal-vlm-training   medical-imaging-diagnosis autonomous-rl-agent
edge-vision-tensorrt
```

```console
muneeb@horizon ~ $ cat ~/books.txt
Practical AI Security Series — Muneeb Anjum
  [01] Quantum Computing with AI           Kindle · Paperback
  [02] LLM Security and Prompt Injection   Kindle · Paperback
  [03] AI and Blockchain                   Kindle · Paperback
  [04] AI and Cyber Security               Kindle · Paperback
```

```console
muneeb@horizon ~ $ cat stack.toml
[core]
python = "primary — PyTorch, FastAPI, numpy"
js     = "TypeScript, Chrome MV3, React"
infra  = "Linux, systemd, Nginx, Docker, Cloudflare"

[ai]
models = "transformers, llama.cpp, vLLM, quantization tooling"
agents = "MCP, tool-calling, RAG, evaluation harnesses"

muneeb@horizon ~ $ uptime
writing code · measuring what it actually does
```

<sub>`writing code · measuring what it actually does`</sub>

<div align="center">

[`muneebs.space`](https://muneebs.space) · [`GitHub`](https://github.com/horizonbymuneeb) · [`ORCID`](https://orcid.org/0009-0001-2042-7656) · [`LinkedIn`](https://www.linkedin.com/in/muneeb-anjum)

</div>
