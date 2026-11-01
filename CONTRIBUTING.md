# Contributing to WMOOP

This repository is part of [WMOOP](https://github.com/WMOOP), a multi-repository project. The
**canonical** contribution process, governance and ethics live in the documentation repository,
[`wmoop.doc`](https://github.com/WMOOP/wmoop.doc):

- [Contributing guide](https://github.com/WMOOP/wmoop.doc/blob/main/CONTRIBUTING.md)
- [AI contributor protocol](https://github.com/WMOOP/wmoop.doc/blob/main/AI_CONTRIBUTING.md)
- [Governance](https://github.com/WMOOP/wmoop.doc/blob/main/GOVERNANCE.md)
- [Ethics & quality](https://github.com/WMOOP/wmoop.doc/blob/main/ETHICS.md)

## Where your change belongs

| Change | Repository |
|--------|------------|
| A concept, property, domain, or a fix to the model | [`wmoop.doc`](https://github.com/WMOOP/wmoop.doc) (`model/**`) |
| The WML grammar (`wml.schema.json`, `wml.xsd`) | [`wmoop.json`](https://github.com/WMOOP/wmoop.json) |
| The loader, the generators, the conformance runner | [`wmoop.tools`](https://github.com/WMOOP/wmoop.tools) |
| Hand-written behaviour, demos and tests of one language | that language's binding (`wmoop.net`, `wmoop.py`, ...) |

In a binding repository, `generated/` is produced by `wmoop.tools` from the pinned model and is
never edited by hand: change the model or the generator instead, then regenerate.

By contributing, you agree that your contribution is released under the licence of the repository
you contribute to.
