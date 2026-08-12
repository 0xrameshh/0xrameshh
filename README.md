# Hi, I'm Ramesh

Applied AI engineer based in Hyderabad. I build agents, RAG systems, and MCP tooling — and I verify what I build: byte-identical tests, eval harnesses, golden files.

**Portfolio:** [0xrameshh.github.io](https://0xrameshh.github.io)

## Featured projects

- [lix](https://github.com/0xrameshh/lix) — Rust CLI that extracts and converts AI agent traces (Claude Code, Codex, Cursor, Pi, Hermes, Droid) into training JSONL. Byte-identical output vs the Python reference, streaming memory (~9 MB RSS vs ~163 MB), single binary, no Python required. Ships with a `verify` command for regression testing against golden files.
- [agentflow](https://github.com/0xrameshh/agentflow) — LangGraph agent runtime with an eval harness, Chroma RAG, and MCP tools. YAML-defined evals, SSE streaming, CI.
- [velum](https://github.com/0xrameshh/velum) — Event-sourced workflow engine in Go: gRPC workers, durable timers, saga compensation.

## How I work

I use coding agents and MCPs in my day-to-day work, and I treat verification as part of the build — not an afterthought. Every project here has tests, and lix ships a `verify` command that regression-tests the release binary against golden files.
