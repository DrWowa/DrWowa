### Vladimir Mosienko — Senior Python Engineer, legacy modernisation & migration

I take legacy codebases from broken to stable, and I do it the same way every time:

1. **Characterization tests** — so change becomes provable rather than hopeful
2. **Static-analysis gates and complexity ceilings** — so the ground gained cannot be lost again
3. **Complexity reduction**, measured under those gates
4. **A functional core** where the risk concentrates

No big-bang cutovers: both versions run side by side behind conditional routing, and rollback is a switch, not a procedure.

**Recent:** Python 2 → 3.12 migration of a decade-old 62k-line codebase · test and CI pipelines built from zero (0% → 38% coverage) · deployment orchestration cut 75% · multi-tenant re-architecture of a live banking platform, zero downtime.

**Stack:** Python · pytest · testcontainers · Ruff · PostgreSQL · MySQL · Docker Compose · OpenTofu · Nix · Bash

📫 [LinkedIn](https://www.linkedin.com/in/vladimir-mosienko/) · Yerevan, Armenia · remote
