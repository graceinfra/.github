# Grace

**Grace** is a modern infrastructure-as-code toolchain for the mainframe.

It provides a declarative developer experience for defining jobs, orchestrating pipelines, and generating system artifacts like JCL - all from a single command-line interface. Grace is designed to feel like Terraform or Docker, but purpose-built for legacy infrastructure.

Our goal is to make mainframe automation feel as natural as modern cloud workflows.


## Projects

- [`grace`](https://github.com/graceinfra/grace) — Define jobs in YAML, generate output, and prepare mainframe-ready pipelines.
- `hopper` (coming soon) — A daemon that collects job output and bridges it into modern environments (HTTP, S3, structured logs, etc.)
- `gracecloud` (future) — A hosted orchestrator for Grace-based workflows, with support for remote job submission, dashboards, and CI/CD.


## Why Grace?

Mainframes still power much of the world, but interacting with them is slow, manual, and disconnected from modern software practices.

Grace reimagines this ecosystem by offering:

- **Declarative IaC for mainframe jobs** (`grace.yml`)
- **CLI-driven orchestration** - generate, parameterize, and stage job flows
- **Clear, reproducible output** in `.grace/deck/` and beyond
- **Version-controlled automation** that integrates into dev pipelines
- A roadmap toward **TUI tools**, **remote agents**, and **enterprise workflows**


## Contact

If you work with COBOL, JCL, or mainframe DevOps - we’d love to hear from you.  
Reach out via Issues, @arnavsurve, or arnav (at) surve (dot) dev.
