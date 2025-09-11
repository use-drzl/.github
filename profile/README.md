<h1 align="center">DRZL</h1>
<p align="center">
  Schema-in → Typed-out tooling for type-safe apps.
</p>

<p align="center">
  <a href="https://use-drzl.github.io/drzl/">Docs</a> ·
  <a href="https://github.com/use-drzl">GitHub</a> ·
  <a href="https://www.npmjs.com/org/drzl">npm @drzl</a>
</p>

---

## About the org

**DRZL** is a family of open-source projects that turn your data models into **strongly-typed** building blocks.  
I design small, composable tools you can mix and match across stacks — from schema analyzers to code generators and ready-to-run templates.

**What I build (now and next):**
- **Analyzers** — parse DB/ORM schemas into a typed graph
- **Generators** — emit validators, routers, services, and contracts
- **CLIs** — watch, codegen, and pipeline orchestration
- **Templates** — opinionated starters you can ship with minimal glue

I care about **DX**, **type safety**, and **predictable outputs** (easy to review, diff, and refactor).

---

## Principles

- **Typed-first**: strict TS, zero `any`, fail fast.
- **Composable**: opt-in pipelines; bring only what you need.
- **Framework-agnostic**: works across ORMs & runtimes over time.
- **Deterministic outputs**: CI-friendly, consistent structure.
- **Extensible by design**: add generators/templates without rewrites.

---

## Ecosystem & compatibility

My projects aim to play well with popular tools (e.g., Drizzle ORM, Prisma, oRPC, Zod, Valibot, ArkType — with room for tRPC/Express and others).  
Support and version ranges vary by repo — check each project’s README.

---

## Getting started

Most repos follow the same ergonomics:

```bash
# with pnpm
pnpm install
pnpm build
pnpm test
