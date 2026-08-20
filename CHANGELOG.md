# RedSync Public Changelog

This changelog records public-facing capability updates only. Private source, deployment details, credentials, binaries, and operational configuration are intentionally excluded.

## 2026-08-20 — Mission-sync and safe-join foundation

### Mission-state foundation

- Documented the Phantom Liberty `q301`–`q307` mission arc, including the Cynosure bunker and Songbird/President finale.
- Documented supported base-game main/side-quest whitelist coverage.
- Added the public description of host-authoritative quest facts, follower suppression, and late-join fact snapshots.
- Clarified that journal replication, full mission-NPC AI/workspot state, and door/device/dialogue interaction relay remain planned follow-up layers.

### Join and world safety

- Added explicit New Game detection separate from Continue, including same-username saved-data cases.
- Added fresh-character resume isolation and validated reconnect-position handling.
- Added replication guards for invalid transforms, ambient NPCs, untyped ownerless entities, and unsupported persistent props.
- Hardened shared vehicles, passengers, elevators, and remote-body join behavior.

### Public release policy

- Updated the public README without changing its existing Blackwall/Cyberpunk theme.
- BETA remains the test channel; `main` is the integrated source branch.
- This public repository contains documentation only and does not publish private source, credentials, VPS details, or deployment artifacts.
