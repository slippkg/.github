# slippkg
![status: WIP](https://img.shields.io/badge/status-WIP-yellow)
> Slip is under active development. Expect breaking changes, incomplete features, and occasional design decisions made at 2am.

This is the meta-repo for the [`slippkg`](https://github.com/slippkg) organization — home of [`slip`](https://slip.run), the declarative, Lua-powered, reproducible system configuration tool for people who don’t want a package manager that also wants to be their therapist.

This repo exists to define shared GitHub community files:
- Default issue & PR templates
- Code of conduct
- Contribution guidelines
- Project-wide metadata

If you're looking for the actual code, it's in the usual places:

## 🔗 Links

- 🌐 [slip.run](https://slip.run) - Landing Page.
  It's a landing page, there's not much to it. Everything important is here on GitHub.

- 📦 [`slippkg/cli`](https://github.com/slippkg/cli) — The CLI tool.  
  Runs `slip sync`, `slip in`, `slip commit`. Declarative infra management with Lua, not regret.

- 📚 [`slippkg/docs`](https://github.com/slippkg/docs) — Project documentation.  
  Markdown-based. Works offline. No JavaScript frameworks were harmed.

- 🧰 [`slippkg/pkgs`](https://github.com/slippkg/pkgs) — Slipfile registry.  
  Community-driven install definitions. MIT licensed. No registry server needed.

---

## What Is Slip?

Slip is a system-level package/config manager designed to:
- Be fully declarative (but still human-readable)
- Use plain Lua, not cursed DSLs
- Let you define multiple system profiles in one structure or multiple modular
- Run without lockfiles, daemons, or central registries
- Give you control without requiring a sacrifice to Nix

---

## Licensing

| Project       | License   | TL;DR                                |
|---------------|-----------|--------------------------------------|
| CLI (`cli/`)  | AGPL-3.0  | Free to use, but don’t monetize it unless you open it up |
| Slipfiles     | MIT       | Use, remix, share freely             |
| Docs          | CC-BY 4.0 | Copy/paste with attribution          |


---

## Get Involved

Slip is a work in progress and welcomes thoughtful contributions.

You can help by:
- Submitting new `slipfiles` for useful packages
- Improving documentation or proposing structure
- Reporting bugs, edge cases, or unexpected install behavior
- Contributing to the CLI implementation or design logic

The project values clarity, reproducibility, and systems that behave as described.

If you're interested in helping out, check the issues tab or open a discussion.

All contributions are reviewed, tested, and handled with care. No bureaucracy, just quality.

If you’d like to talk about integrating Slip into a larger project or want to explore use in a commercial context, feel free to reach out via  `dev [at] slip [dot] run`.

---

Questions? Ideas?
Open a discussion or email  `dev [at] slip [dot] run`.

---

*Slip. Because config should be reproducible, not regretful.*
