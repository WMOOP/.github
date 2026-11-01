# WMOOP/.github

The default [community health files](https://docs.github.com/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
for every repository in the [WMOOP](https://github.com/WMOOP) organization. GitHub shows a file
from here in any WMOOP repository that has no file of its own, so each policy is written once
instead of being copied, or pointed to, from every repository.

| File | Shown in |
|------|----------|
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | every repository |
| [`SECURITY.md`](SECURITY.md) | every repository |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | repositories without their own (today `wmoop.json`, `wmoop.java`, `wmoop.cpp`, `wmoop.js`, `wmoop.db`) |

A repository's own file always wins. `wmoop.doc`, `wmoop.tools`, `wmoop.net` and `wmoop.py` keep
their own `CONTRIBUTING.md`, which holds guidance specific to that repository.

`LICENSE` is never inherited: every repository keeps its own. This repository holds documentation
only, so it is licensed CC-BY-4.0, like the WMOOP prose
(see [`LICENSE-DATA.md`](https://github.com/WMOOP/wmoop.doc/blob/main/LICENSE-DATA.md)).

To change a policy, open a pull request here; the change applies to every repository at once.
