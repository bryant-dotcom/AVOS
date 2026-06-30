# Scheduling

Status: Draft  
Owner: Bryant Bishop  
Capability Type: Core Business Capability  

## Purpose

The Scheduling capability defines how AVOS manages time, availability, meetings, invitations, calendar ownership, and AI-assisted scheduling.

Google Calendar is the current system of record.

## Default Calendar Rules

- General work events → Bryant 40 North
- AVseven meetings → Bryant AVseven
- Personal events → Personal
- Church events → High Council
- Real estate timelines → TIMELINES

## Calendar Source of Truth

Google Calendar is the authoritative scheduling ecosystem.

Apple Calendar may be used as a viewer/client only.

## Hermes / Orion Rules

Hermes currently runs through Telegram.

Hermes code and infrastructure are managed through GitHub.

Hermes hosting and related services are run through Hostinger.

Hermes may eventually read availability across approved calendars and write only to approved calendars.

## Approved Write Calendars

Hermes may write to:

- Bryant 40 North
- Bryant AVseven

Hermes should not write to Personal, High Council, TIMELINES, or external/shared calendars unless explicitly approved.

## Principle

Every assistant, calendar app, and AI tool should see the same availability, and every meeting invitation should come from the correct business identity.
