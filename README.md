## Lionel Acosta

Senior Software Engineer, 9+ years building and modernizing web products — most recently enterprise eCommerce with Angular, TypeScript and SAP Commerce Cloud.

Most of that work has been on systems that were already in production and already earning: continuous platform upgrades, a B2B checkout rebuilt while it kept selling, payment and authentication flows. The constraint there is changing things without interrupting them.

I work daily with AI coding agents on production code, and I build my own products in TypeScript and Rust — web, desktop, mobile and terminal.

### What I'm building

**[ravix](https://github.com/lionelx87/ravix)** — an animated git client for the terminal, in Rust. A deliberately hybrid backend: `git2` for reads, the `git` CLI for every mutation, so your hooks and config keep working. Predicts merge results with `git merge-tree` before offering a strategy, and undoes destructive operations from silent snapshots written into the object database. 20k lines, 358 tests.

**[onix](https://github.com/lionelx87/onix)** — a learning capture CLI for Obsidian vaults, in TypeScript. LLM integration where the model proposes and deterministic code applies: the proposal engine returns a patch plan that is validated against Zod schemas before anything touches the vault, so a malformed response fails safely instead of corrupting notes. Provider-agnostic over the OpenAI and Gemini SDKs.

**Runergy** — a running training application in Expo and React Native, with GPS capture in a native Android module measured in the field at 1 Hz for 83 minutes, screen off, 100% continuity. Built from the domain upward: 54 architecture decision records, and discarded prototypes documented with the question each one answered. Not public yet.

### Stack

- **Languages** — TypeScript, JavaScript, Rust, SQL
- **Frontend** — Angular, React, Vue, Next.js, Nuxt, Astro, RxJS, Electron
- **Commerce** — SAP Commerce Cloud, SAP Composable Storefront (Spartacus), OCC REST APIs
- **Backend & data** — Node.js, PHP, Laravel, PostgreSQL, MySQL, SQL Server, SQLite
- **AI engineering** — LLM APIs (OpenAI, Google Gemini), structured outputs, schema validation of model output, context engineering, Model Context Protocol

### Elsewhere

[lionelacosta.vercel.app](https://lionelacosta.vercel.app) · [LinkedIn](https://linkedin.com/in/lionel-acosta) · lionelx87@gmail.com
