# TraceZero v1.1.0 — Air-Gapped Loopback & Audit Log Specification

TraceZero is engineered for NDA-bound, Fintech, HealthTech, and air-gapped Windows environments where zero source code may leave the local workstation.

## 1. Hardcoded Loopback Inference (`127.0.0.1:11434`)
- All local LLM inference calls bind strictly to `http://127.0.0.1:11434` (local Ollama daemon).
- External cloud endpoints, third-party analytics SDKs, and background telemetry beacons are excluded from the runtime engine.
- Bring Your Own Model: Edit `tracezero.json` (`"model": "qwen2.5-coder:7b"`, `"deepseek-coder-v2"`, etc.) to route TraceZero's AST + 3-attempt Reflexion verifier to any locally installed Ollama model.

## 2. Verifiable Local Audit Log (`.tracezero/audit.log`)
Every debugging session appends an immutable timestamped record to `.tracezero/audit.log` in your workspace:
```text
[2026-11-27 23:38:00] HOST=127.0.0.1:11434 | EGRESS=0_BYTES | FILE=auth.py | ATTEMPTS=1/3 | STATUS=VERIFIED_CLEAN
```

## 3. Independent Verification Steps (Windows)
1. Enable **Windows Airplane Mode** (`Win + A`) or disconnect Ethernet/Wi-Fi.
2. Run a bug fix in TraceZero—the 3-Attempt Reflexion + AST/bytecode verifier completes locally with `EGRESS=0_BYTES` logged to `.tracezero/audit.log`.
