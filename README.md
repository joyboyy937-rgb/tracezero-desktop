<div align="center">
  <h1>🛡️ TraceZero v1.1.0 — 100% Air-Gapped AI Code Debugger for Windows</h1>
  <p><strong>Surgical offline bug fixing powered by a local 1.5B–14B coding engine, <code>&lt;2ms</code> Python AST static pre-scanning, and 3-attempt execution-verified Reflexion — with <code>0 KB</code> external network egress.</strong></p>

  <p>
    <a href="(https://github.com/joyboyy937-rgb/tracezero-desktop)"><strong>⬇️ Download TraceZero v1.1.0 (Free Forever Lite + 7-Day Pro Trial)</strong></a>
    • <a href="https://virustotal.com"><strong>🛡️ VirusTotal Scan (0/67 Clean)</strong></a>
    • <a href="(https://buy.polar.sh/polar_cl_ki911IDNJsYba6voWEpE1PLZlxgEB8wVcRvun3M8vdS)"><strong>⚡ Buy Solo Pro Lifetime ($29 one-time)</strong></a>
  </p>

  <p><em>🎉 Launch Promo: Use code <code>PEER50</code> at checkout for <strong>50% off ($14.50 one-time)</strong> — limited to the first 30 Solo Pro subscribers!</em></p>

  <br/>

  <!-- Main Large Hero Screenshot -->
  <img width="1366" height="768" alt="tracezero main page pic" src="https://github.com/user-attachments/assets/80ce8618-de02-4de3-acb8-f5e3ba155edc" />
</div>

> **Note on Windows SmartScreen:** While our official Azure/EV Code Signing certificate is in verification, Windows SmartScreen may show an<img width="1366" height="705" alt="aeroplane mode proof" src="https://github.com/user-attachments/assets/0ffc75ac-1e58-427a-8539-39811874f866" />
 *"Unknown Publisher"* prompt on first run. Click **More info → Run anyway** (verified **0/67 clean** on [VirusTotal](https://virustotal.com)).

---

### 🔒 Why Developers & NDA Teams Choose TraceZero

* **100% Air-Gapped Runtime (`127.0.0.1:11434`):** Every inference call binds strictly to your local Ollama daemon (`0 KB` sent to external servers; works in Windows Airplane Mode and writes an auditable `.tracezero/audit.log` on every run).
* **Offline-Tolerant Cryptographic Licensing:** Once activated, license keys (`TZ-PRO-`, `TZ-TEAM-`, `TZ-PILOT-`) validate locally with a 30-day offline lease—zero continuous phone-home servers required during coding.
* **`<2ms` AST Pre-Scanner + 3-Attempt Reflexion Loop:** Catches mutable defaults, loop mutations, and race conditions deterministically, then compiles and tests candidate fixes in an isolated subprocess (`compile()` + runtime check) before displaying `✅ Verified Clean`.
* **Bring Your Own Local Ollama Model:** Tuned out of the box for `qwen2.5-coder:1.5b` (runs smoothly on 8 GB RAM laptops with no GPU), or switch `"model"` in `tracezero.json` to `qwen2.5-coder:7b` or `deepseek-coder-v2` in 2 seconds.
* **Free Forever Lite + Lifetime Solo Option:** Start with a **7-day unlimited Pro trial**, continue on **Free Forever Lite (`3` AI Reflexion fixes/day + unlimited `<2ms` AST scans forever)**, or unlock **Solo Pro Lifetime (`$29` one-time, all `v1.x` updates)** with zero recurring monthly fees.

---

### 📸 Visual Proof: Live Unified Diff & Airplane Mode Verification

| Live Red/Green Unified Diff & 1-Click Patch | Verified Offline in Windows Airplane Mode |
| :---: | :---: |
| <img width="100%" alt="live diff review" src="https://github.com/user-attachments/assets/4946ffe4-d3f3-4d55-a766-48332a7e83bb" /> | <img width="100%" alt="aeroplane mode proof" src="https://github.com/user-attachments/assets/6df80240-6b18-444f-8c0d-bbe41db35fea" /> |

---

### 🚀 Quick Start Guide (2 Minutes)

1. **Download & Install:** Grab **`TraceZero_Setup_v1.1.exe`** from [**GitHub Releases (v1.1.0)**](https://github.com/joyboyy937-rgb/tracezero-desktop) and run the 1-click installer.
2. **Automatic Local Engine Setup:** The installer initializes the local `qwen2.5-coder:1.5b` model on `127.0.0.1:11434` automatically (requires [Ollama](https://ollama.com) installed; one-time model pull during setup, `0 KB` network egress during runtime).
3. **Debug Offline:** Launch **TraceZero** from your Desktop shortcut, open a folder or paste code into the editor, and click **Find Bugs**—TraceZero creates `.tracezero/backups/` before patching and logs `EGRESS=0_BYTES` in `.tracezero/audit.log` (see [`AUDIT_SPEC.md`](./AUDIT_SPEC.md)).

> **💡 Pro Tip for Multi-Bug or Complex Files:** TraceZero's `1.5B` air-gapped engine is engineered for surgical precision on focused scopes (`±40` lines). If a file has several unrelated bugs, tackle or prompt **one bug or function at a time**—TraceZero's 3-attempt Reflexion verifier will lock onto the exact root cause and deliver clean, verified patches every single time.

---

### 💳 Licensing & Team Plans

| Plan | Price | Seats / Devices | Best For | Checkout |
| :--- | :--- | :--- | :--- | :--- |
| **Free Forever Lite** | **$0 Forever** (7-day full Pro trial, then **3 AI Reflexion fixes/day** + unlimited AST scans) | 1 Windows PC | Daily lightweight debugging & evaluation | [**⬇️ Download v1.1.0**](https://github.com/joyboyy937-rgb/tracezero-desktop) |
| **Solo Pro (Lifetime v1.x)** | **$29 one-time** *(`$14.50` with `PEER50` — first 30 spots)* | Up to **2 Windows PCs** (Unlimited fixes + all `v1.x` updates forever) | Independent developers & consultants | [**⚡ Buy Solo Lifetime ($29)**](https://buy.polar.sh/polar_cl_ki911IDNJsYba6voWEpE1PLZlxgEB8wVcRvun3M8vdS) |
| **Agency Team Pack** | **$79 / month** | **10 Windows Seats** (Monthly PDF Invoice + `.tracezero/audit.log`) | Freelance agencies & NDA teams | [**🏢 Buy Agency Pack ($79/mo)**](https://buy.polar.sh/polar_cl_ofFEoCtCwRX76fqqe85XDkup048aK12r1ZfcJ46K0UY) |
| **Founding Security Pilot** | **$399 / 3 months** | **10 Windows Seats + CTO Security Compliance Pack** | Fintech, HealthTech & enterprise pilots | [**🛡️ Start Security Pilot ($399)**](https://buy.polar.sh/polar_cl_9G2z1zWXqxSnGfOMVjcWcfXzyCSXxGOqJ4BOI18ln2H) |

---

### 📩 Support & Security Inquiries
* **Support Email:** `joyboyy437@gmail.com`
* **Architecture & Audit Log Spec:** [`AUDIT_SPEC.md`](./AUDIT_SPEC.md) • **Model Config:** [`tracezero.json`](./tracezero.json)
