# Paper Runtime Issue Seed

Use format `- Title :: Description`.

- Bootstrap Paper runtime wrapper :: Add a pinned Paper runtime bootstrap script with checksum validation and version pinning.
- Define plugin boundary contract :: Document plugin API boundaries for world powers and lifecycle hooks.
- Add backup/restore smoke test :: Create a repeatable backup+restore workflow with integrity checks.
- Add healthcheck endpoints and probes :: Expose lightweight runtime health probes for automation and alerts.
- Baseline incident runbook :: Create first incident runbook for crash-loop, lag spike, and corruption cases.
- Introduce environment matrix docs :: Document local/dev/staging/prod environment differences and invariants.
- Build release artifact policy :: Define versioning, changelog, and release artifact retention expectations.
- Add structured runtime logging profile :: Standardize log fields and severity mapping for operations debugging.
- Permission model for ops scripts :: Add least-privilege guidance and script permission boundaries.
- Migration tracker: game-specific assumptions :: Track assumptions that must be abstracted for future engine-agnostic migration.
