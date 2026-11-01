<div align="center">

# Magicube

**The AI agent & no-code platform that builds business apps from a conversation · .NET 10 + Vue 3 · Self-hosted**

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Release](https://img.shields.io/github/v/release/wolfweb/magicube-agent-zero-coding-platform?label=release&color=green)](https://github.com/wolfweb/magicube-agent-zero-coding-platform/releases/latest)
[![.NET](https://img.shields.io/badge/.NET-10-512BD4.svg)](https://dotnet.microsoft.com)

![Magicube no-code AI agent platform home screen](docs/screenshots/en-readme-hero.png)

**English** · [简体中文](README.zh-CN.md)

</div>

---

## Download

Grab the package for your OS, unzip and run: 👉 **[Latest Releases](https://github.com/wolfweb/magicube-agent-zero-coding-platform/releases/latest)**

| OS | Package | Run |
|----|---------|-----|
| Windows x64 | `basic-scd-win-x64.zip` | unzip, double-click `Host.exe` |
| Linux x64 | `basic-scd-linux-x64.tar.gz` | `tar -xzf basic-scd-linux-x64.tar.gz && cd basic-scd-linux-x64 && chmod +x Host && ./Host` (minimal distributions need libicu installed) |
| macOS · Apple silicon (M1 and later) | `basic-scd-osx-arm64.tar.gz` | `tar -xzf basic-scd-osx-arm64.tar.gz && cd basic-scd-osx-arm64 && chmod +x Host && ./Host` |
| macOS · Intel | `basic-scd-osx-x64.tar.gz` | `tar -xzf basic-scd-osx-x64.tar.gz && cd basic-scd-osx-x64 && chmod +x Host && ./Host` |

First visit `http://localhost:5000` → setup wizard (pick a database → create admin account) → you're running.

---

## What is Magicube

Magicube compresses "request → wait for dev schedule → ship" into a single conversation. Describe your business rules and the AI agent builds the forms, approvals, dashboards and workflows for you — then keeps participating at runtime: answers questions with charts, raises early warnings, and runs the follow-up flows automatically. Self-hosted; your data stays yours.

## Highlights

- **Conversation → App**: natural language to forms/approvals/dashboards/workflows, live the same day — business users can adjust them without code
- **AI agent in the loop**: Q&A over data and knowledge bases, early warning & auto-handling, and skills that evolve as the agent learns from your corrections
- **Prediction closed loop**: stockout / churn / anomaly detection → auto-started workflows → outcomes fed back to the model
- **Distributed clustering** (Enterprise): DB-centered node registry, automatic site config sync, gRPC instant wake-up — multiple nodes share one site configuration
- **Modular by design**: every business module is an independent DLL; editions differ only by which modules are installed; SDK/module/UI three-layer decoupling lets developers extend it in a low-code style

## Tech stack

.NET 10 · ASP.NET Core · EF Core · Elsa Workflow 3.x · Vue 3 · Element Plus · Vue Flow · ML.NET · ONNX Runtime · MagicOnion (gRPC) · SQLite / MySQL / PostgreSQL / SQL Server / MongoDB

![Magicube admin workbench](docs/screenshots/en-readme-admin.png)

---

## Contributing & Feedback

- Bug reports & questions: [Issues](https://github.com/wolfweb/magicube-agent-zero-coding-platform/issues)

## License

Apache License 2.0 — see [LICENSE](LICENSE).
