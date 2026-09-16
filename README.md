# Arvind Sagar

Backend engineer. I build Rust services and the infrastructure they run on.

Four years across enterprise systems and small product teams, mostly in Rust and
PostgreSQL: HTTP APIs, job queues, storage pipelines, containerised deployments, and the
telemetry around them. I like owning the whole vertical — schema, service, deploy, and the
measurements that show whether any of it actually got better. I currently work on an
independent contract and I'm open to backend and SDE roles.

**Core** — Rust · PostgreSQL · Docker · AWS / GCP · OpenTelemetry
**Also** — Tokio · Axum · Redis · TypeScript · Python · Cloudflare R2 · CI/CD

---

## Projects

### [Gradient](https://projects.itscryo.com/ml) — an interactive machine learning course

Machine learning from the ground up, written for people who have never programmed. Sixteen
chapters and 254 code cells, and every code block on the page runs.

The design problem was where to execute Python. About 70% of the course needs nothing but the
site: Python runs in the browser through a vendored Pyodide build, so it works offline and
with no install. The PyTorch chapters are different — a shared kernel would execute arbitrary
Python on behalf of every visitor, so it can never be hosted centrally. Those cells connect to
a Jupyter kernel the reader runs on their own machine instead.

`Astro` `Python` `Pyodide` `PyTorch` `Docker` — [live site](https://projects.itscryo.com/ml) · [source](https://github.com/cryoelite/ml)

### [cgol-rs](https://github.com/cryoelite/cgol-rs) — Conway's Game of Life in Rust

A native desktop implementation using `egui`/`eframe`. A fixed 100×100 board that wraps at the
edges — the top row is treated as adjacent to the bottom, the left column to the right — seeded
with a compile-time pattern and stepping roughly three generations a second. 351 lines of Rust
with no `unwrap` in the codebase.

`Rust` `egui` `eframe` — [source](https://github.com/cryoelite/cgol-rs)

---

## Elsewhere

- Website — [itscryo.com](https://itscryo.com)
- LinkedIn — [in/itsarvindsagar](https://www.linkedin.com/in/itsarvindsagar/)
- Email — [itsArvindSagar@gmail.com](mailto:itsArvindSagar@gmail.com)
