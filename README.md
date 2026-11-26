### Hey, I'm Arthur (LeTuR) 👋

🤖 Agentic / DevOps Engineer — I build tools that let coding agents work side by side, and the infrastructure under them. Most of it lives at [Thurbeen](https://github.com/Thurbeen).

---

#### 📦 thurbox — the centrepiece

- [thurbox](https://github.com/Thurbeen/thurbox) — Coding agents side by side in one terminal: a TUI you reshape in Lua, on Fleet, a declarative Task engine whose sessions outlive the interface, locally or over ssh (Rust)

```bash
# Linux / macOS
curl -fsSL https://raw.githubusercontent.com/Thurbeen/thurbox/main/scripts/install.sh | sh
```

```powershell
# Windows (PowerShell)
irm https://raw.githubusercontent.com/Thurbeen/thurbox/main/scripts/install.ps1 | iex
```

#### 🧩 thurbox plugins

- [thurbox-info-panel](https://github.com/Thurbeen/thurbox-info-panel) — Session, git, agent, account quota and system readouts beside the terminal (Lua)
- [thurbox-code-review](https://github.com/Thurbeen/thurbox-code-review) — A Review tab: the session's diff against its base branch, with notes sent to the agent (Lua)
- [thurbox-auto-continue](https://github.com/Thurbeen/thurbox-auto-continue) — Waits out a Claude Code usage limit, then types `continue`, once; no LLM involved (Rust)
- [thurbox-fleetlens](https://github.com/Thurbeen/thurbox-fleetlens) — Fleet Lens: browse Fleet v3 resources, Tasks first, in one keyboard-first float (Lua)
- [thurbox-doom](https://github.com/Thurbeen/thurbox-doom) — DOOM's engine and WADs behind a Doom tab in the agent pane, because it had to be done (C)

#### 🛰️ Fleet

- [Fleet](https://github.com/Thurbeen/thurbox/tree/main/docs/fleet) — The engine under thurbox, shipped with it: declare Tasks, controllers run one agent session per brief and record the result (Rust)
- [vega](https://github.com/Thurbeen/vega) — VEGA, a Mission Control for Fleet: it dispatches and follows, worker Tasks do the work
- [fleet-reviewer](https://github.com/Thurbeen/fleet-reviewer) — Fleet plugin that starts one review Task per open pull or merge request, kept current until it merges (TypeScript)
- [fleet-factory](https://github.com/Thurbeen/fleet-factory) — Software factory on Fleet: ticket board to production and back, as infrastructure as code (TypeScript)
- [agent-observability](https://github.com/Thurbeen/agent-observability) — Grafana dashboards, Prometheus alerts and an OpenTelemetry quick-start for Fleet and thurbox

#### 🧠 Agent skills

- [publish](https://github.com/Thurbeen/publish) — Gates committed work — adversarial review, tests, lint, docs — before it pushes and opens the change request
- [thurview](https://github.com/Thurbeen/thurview) — Your agent reviews an opened pull or merge request on the forge and keeps that review current until it merges (TypeScript)

#### 🧰 More at Thurbeen

- [gdcruiser](https://github.com/Thurbeen/gdcruiser) — Static dependency analyzer and architecture-rule checker for Godot projects (Python)

#### 💼 Personal projects

- 🔢 [terraform-provider-sequence](https://github.com/LeTuR/terraform-provider-sequence) — Terraform provider for zero-padded sequential numbers gated by a trigger (Go)
- 🌐 [portfolio](https://github.com/LeTuR/portfolio) — Personal portfolio site (static HTML/CSS, GitHub Pages)

---

<p align="center">
  🌐 <a href="https://arthur.thurbeen.eu">Portfolio</a> · 💼 <a href="https://www.linkedin.com/in/arthur-cesar%C3%A9-herriau-a4a017153/">LinkedIn</a>
</p>
