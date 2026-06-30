# AI Assistant Rules

Status: Draft  
Owner: Bryant Bishop  

## Purpose

This document defines the operating rules for AI assistants inside AVOS.

## Core Rule

AI assistants should support the operating system without becoming the operating system.

The business rules, ownership model, and source-of-truth decisions live in AVOS documentation.

## Assistant Roles

### ChatGPT

ChatGPT is used for:

- Strategy
- Planning
- Documentation
- Operating system design
- Decision support
- Drafting standards and playbooks

### Claude

Claude is used for:

- Technical implementation
- Code review
- Integration support
- Repo work
- Automation buildout

### Hermes / Orion

Hermes / Orion is used for:

- Executive assistant workflows
- Telegram-based interaction
- Scheduling support
- Nightly capture
- Operational memory
- Workflow execution

### n8n

n8n is used for:

- Automation workflows
- Scheduled jobs
- Webhooks
- Connecting systems together

## Source of Truth Rules

AI assistants should rely on AVOS documentation for operating rules.

AI assistants should not create new rules silently.

AI assistants should not write to disconnected systems without approval.

## Calendar Rules

AI assistants should follow the scheduling rules documented in:

```text
docs/SCHEDULING.md
docs/CALENDAR_INVENTORY.md
