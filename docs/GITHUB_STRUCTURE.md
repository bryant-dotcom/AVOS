# GitHub Structure

Status: Active  
Owner: Bryant Bishop  

## Purpose

This document explains how the AVOS GitHub repository is organized.

It exists so humans and AI assistants know where files belong.

## Root Files

Root files define the overall AVOS framework.

Current root files include:

- `README.md`
- `VISION.md`
- `PRINCIPLES.md`
- `ROADMAP.md`

## Folders

### `docs/`

General AVOS documentation.

Used for:

- Scheduling
- Calendar inventory
- Operating procedures
- System documentation

### `adr/`

Architecture Decision Records.

Used for documenting important decisions and the reasons behind them.

### `standards/`

Reusable AVOS standards.

Used for rules that should apply across tools, agents, and implementations.

### `implementations/`

Real-world AVOS implementations.

Used for specific agents, systems, and workflows that apply the AVOS framework.

### `implementations/hermes/`

Hermes / Orion-specific implementation documentation.

## File Creation Rule

Always create new files from the main repo root unless intentionally adding a file inside a specific folder.

Use full paths when creating files.

Example:

```text
docs/SCHEDULING.md
standards/AI_ASSISTANT_RULES.md
implementations/hermes/README.md
