# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## ⚡️ Initialization (The Standard Protocol)

**Before starting work:**

1. **Activate Venv:** `source /home/griermarkov/Drives/.virtual-environments/EajR-innovativEngineering_env/bin/activate`
2. **Initialize:** Run `/init` to sync and update dependencies.

### /init Command

```bash
# Pull latest changes and install dependencies
git pull origin $(git branch --show-current) && \
  pip install -r requirements.txt 2>/dev/null || \
  pip install -e . 2>/dev/null || \
  echo "No installable dependencies found"
```

### /save-point Command

Smart commit workflow that respects .gitignore and pushes to remote:

```bash
# Phase XV: Federation Save Point
git status
git add .
git commit -m "Phase XV: Federation Infrastructure Update"
git push origin HEAD
```

**Usage:** Run `/save-point` to checkpoint your work.


---

## Project: EajR-innovativEngineering
> **Profile:** etherware
> **Identity:** etherware / id_ed25519_etherware
> **Stack:** Markdown (Documentation Hub)

## Description
Partnership portfolio and organization hub showcasing micro-vlog, support mechanisms, and links to all EajR projects and innovations.

## R&D Team Assignments
* **Architect:** `system-architect` (Use for organizational structure)
* **Builder:** `polyglot-dev` (N/A - documentation repo)
* **Researcher:** `quantum-ag-researcher` (N/A - documentation repo)
* **Ops:** `infrastructure-ops` (N/A - documentation repo)
* **Guardian:** `security-qa` (N/A - documentation repo)

## Commands
* **Build:** N/A (documentation only)
* **Test:** N/A
* **Lint:** N/A

## Federation Context
* **Root:** `~/Drives/data/SynologyDrive/grimmerie/repositoriies-by-profile`
* **Sibling Projects:** You are authorized to traverse `../` to reference other repos in the etherware profile.
* **Related Repos:** All etherware.* repos (this is the organizational hub)
