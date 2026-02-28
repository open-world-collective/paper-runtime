# License Choice: GPL vs AGPL

## Recommendation

Use **AGPL-3.0-only** for server-side/runtime code in this repo.

## Rationale

- GPL-3.0 triggers source-sharing on binary distribution.
- AGPL-3.0 additionally covers network use, which fits hosted server tooling and service-style modifications.
- Early AGPL adoption reduces future relicensing friction as hosted components grow.

## Practical implication

If operators modify AGPL-covered server software and provide it over a network, they must provide corresponding source to users.

## Caveat

This is an engineering recommendation, not legal advice.
