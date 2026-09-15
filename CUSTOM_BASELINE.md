# OpenHands Custom Baseline

This repository is the AI App Builder–managed fork/lineage of the OpenHands Agent Engine.

## Upstream

- Repository: https://github.com/OpenHands/software-agent-sdk
- Package focus: Agent Server / Software Agent SDK (not the OpenHands web UI)

## Production baseline (AI App Builder)

- Production MicroVM image: `openhands-agent:1.0`
- Reported Agent Server / SDK version: `1.46.0`
- Production build commit: `3fc7b221516485e07604e8068de2fdc2d0ef3f09`
- Production image created (JST): `2026-09-10`
- Closest upstream release tag: `v1.46.0` (this baseline is 3 commits ahead of that tag)
- Local baseline branch: `baseline/prod-1.46.0`
- Local baseline tag: `prod-baseline-2026-09-10`

## Branch intent

- `upstream/main` (remote): official latest
- `baseline/prod-1.46.0`: frozen commit matching current AWS production Agent Server
- `main` on this GitHub repo: default branch inherited from upstream; do not treat as the production baseline

Do not merge upstream `main` into the baseline branch casually. Future custom work should branch from this baseline (or a later deliberately chosen baseline).
