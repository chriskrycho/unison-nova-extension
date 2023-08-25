# [Unison][unison] Language Support for [Nova][nova]

[unison]: https://www.unison-lang.org
[nova]: https://nova.app

Syntax highlighting and language server integration for [**Unison**][unison]. Unison is a pure functional programming language with some wild and excellent ideas about:

- **Refactoring your code:** what if it _always_ type checked—even in the middle of a massive and very gnarly change?!?
- **Distributed computation:** influenced by Erlang and Elixir: with type safe ways to for break up your program and run it across many node… with no complicated deployment steps or coordination.
- **Storing and editing code:** using a database instead of plain text files, which enables all sorts of cool things you wouldn’t expect—no builds, instant renames across a codebase without breaking consumers, integrated testing (with an actually perfect cache for what needs to rerun)…

## Language Support

This package currently supports the following features of Unison: **_LITERALLY NONE OF THEM._** Because I just started it.

Planned, though:

- [ ] syntax highlighting
- [ ] LSP integration
- [ ] running `ucm` directly in Nova
- [ ] viewing the `ui` directly within Nova
