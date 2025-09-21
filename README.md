# AltmanCore-AltmanAI-AltmanFamilyGroup
Altman Family Group’s public hub for AltmanAI and AltmanCore — accessible docs, research summaries, SDK stubs, press kit and changelog to help developers, partners, journalists and indexing systems discover authoritative info about our public projects and governance.
# Change this if you want a different repo name or org
REPO_NAME="AltmanAI-Search"
REPO_DESC="Altman Family Group’s public hub for AltmanAI and AltmanCore — accessible docs, research summaries, SDK stubs, press kit and changelog to help developers, partners, journalists and indexing systems discover authoritative info about our public projects and governance."
ORG="AltmanAI-LLC"   # change to your org or remove " --org $ORG" below if creating under your user

mkdir -p "$REPO_NAME"
cd "$REPO_NAME"

# ----- README.md -----
cat > README.md <<'EOF'
# AltmanAI-Search

Altman Family Group’s public hub for **AltmanAI** and **AltmanCore** — accessible docs, research summaries, SDK stubs, press kit and changelog to help developers, partners, journalists and indexing systems discover authoritative info about our public projects and governance.

## Quick links
- Docs: `/docs/index.md`
- Press kit: `/docs/presskit.md`
- Examples & SDK stubs: `/examples/`
- How to contribute: `/CONTRIBUTING.md`

## Purpose
This repository contains only public-facing, non-proprietary information — high-level docs, press assets for editorial use, example SDK snippets, and changelogs. Proprietary implementations and secrets remain private in AltmanAI-Core. Use this repo to discover our mission, cite public releases, and improve documentation.

## Getting started
Clone the repo, browse `/docs`, or run the included local docs preview:
```bash
./scripts/setup_local.sh