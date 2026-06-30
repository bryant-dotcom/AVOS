# Architecture Decision Records

Status: Active  
Owner: Bryant Bishop  

## Purpose

Architecture Decision Records document important AVOS decisions so the reasoning does not get lost over time.

Each decision should explain:

- What was decided
- Why it was decided
- What alternatives were considered
- What the decision affects

---

# ADR-001: Google Calendar as Scheduling System of Record

## Status

Accepted

## Decision

Google Calendar is the current scheduling system of record for the AVOS reference implementation.

## Reason

Google Calendar supports multiple calendars, shared access, identity-based invitations, AI integrations, and broad compatibility with scheduling tools.

## Consequences

- Google Calendar becomes the authoritative source for availability.
- Apple Calendar may be used only as a viewer/client.
- AI agents should connect to Google Calendar, not Apple Calendar.
- Duplicate or obsolete calendars should be removed.

---

# ADR-002: Separate AVOS From Hermes / Orion

## Status

Accepted

## Decision

AVOS will live in its own GitHub repository separate from the Hermes / Orion agent repository.

## Reason

Hermes / Orion is an implementation. AVOS is the operating framework.

Keeping them separate allows AVOS to remain documentation-first, reusable, and tool-agnostic while Hermes can evolve as software.

## Consequences

- AVOS documents the framework, standards, and implementation decisions.
- Hermes / Orion contains the agent code, Telegram logic, integrations, and deployment files.
- Hermes can reference AVOS as its operating standard.

---

# ADR-003: Bryant AVseven as the AVseven Calendar

## Status

Accepted

## Decision

Bryant AVseven is the active AVseven-owned calendar.

## Reason

The old 40 North-owned AVseven calendar created confusion and duplicated the real AVseven calendar.

## Consequences

- AVseven meetings should be scheduled on Bryant AVseven.
- General work should remain on Bryant 40 North.
- Hermes should write AVseven-branded meetings to Bryant AVseven.
- Hermes should write general events to Bryant 40 North.
