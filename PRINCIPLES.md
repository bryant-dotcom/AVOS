# AVOS Principles

Status: Draft  
Owner: Bryant Bishop  

## Purpose

This document defines the core principles behind AVOS.

These principles should guide decisions even when tools, vendors, or implementations change.

## Principles

### 1. Architecture Before Tools

Choose the operating model before choosing the software.

### 2. One Source of Truth

Every important business capability should have a clearly defined source of truth.

### 3. Identity Matters

Business identity, personal identity, church identity, and project identity should not be mixed accidentally.

### 4. Documentation Is Infrastructure

If a system matters, its rules should be documented.

### 5. AI Executes Rules

AI assistants should follow clearly defined operating rules instead of inventing new ones in real time.

### 6. Keep Implementations Separate From Frameworks

AVOS is the framework.  
Hermes / Orion is an implementation.

### 7. Simplicity First

A clean, understandable system is better than an impressive but confusing system.

### 8. Human Approval for Sensitive Actions

AI should ask for confirmation before sending, deleting, moving, scheduling, or changing important information.

### 9. Tool-Agnostic Design

Tools may change.  
The operating principles should survive tool changes.

### 10. Build for Reuse

The system should work first for Bryant, then become reusable for other business owners.

## Guiding Statement

Architecture outlives technology.
