# TaskNova-AI

> **DEXATHON 2026** | Track 04: AI & Machine Learning | Team ID: `DEX262092` | PS Category: Software

A dual-input chat-to-action reconciliation engine built with FastAPI, Vanilla JavaScript, and Google Gemini 2.5 Pro that cross-references master project scope checklists against raw chat transcripts to generate interactive gap reports, task cards, mode-specific alerts, and slide exports.

---

## Executive Summary
In fast-paced project environments—such as hackathons, university group projects, and agile development squads—critical action items and task ownership frequently get lost in long, unstructured chat streams. **TaskNova-AI** eliminates manual project management overhead by automatically ingesting raw chat logs, parsing commitments via advanced AI, and diffing them against a master project scope checklist to generate verified, immutable task boards.

---

## Core Features and Capabilities

* **Dual-Mode Workspace Engine:**
  * **Student Mode:** Designed for flat peer-to-peer accountability, featuring transparent task distribution and public gap warnings.
  * **Office Mode:** Designed for structured hierarchical oversight, featuring top-down manager assignment queues and private triage.
* **Smart Emoji Intent Parsing:** Automatically interprets conversational reactions (e.g., mapping confirmation symbols to accepted tasks and ambiguous symbols to unassigned work).
* **Verbatim Quote Auditing:** Every generated task card is explicitly bound to its source chat sentence and timestamp, removing finger-pointing and establishing undeniable accountability.
* **Local-First Persistence and Portability:** Operates with zero mandatory cloud database overhead by leveraging browser local storage alongside portable session files for real-time state recovery.
* **Automated Risk Detection and Gap Reporting:** Actively flags unassigned roles, missing project milestones, and ambiguous conversational commitments days before deadlines.
* **One-Click Export:** Instantly compile your reconciliation results and workspace boards into clean PDF or JPEG slide exports.

---

## System Architecture and Workflow Pipeline

1. **Multi-Source Ingestion:** The user uploads the master project scope checklist alongside raw team communication transcripts.
2. **Preprocessing and Noise Filtering:** The FastAPI backend strips conversational noise, media placeholders, and duplicate entries while preserving essential sender metadata and timestamps.
3. **Gemini AI Reconciliation Core:** The cleaned payload is routed to **Google Gemini 2.5 Pro** via the software development kit, utilizing strict schema validation to guarantee deterministic, validated output structures.
4. **Structured Action Board Generation:** The system renders interactive task cards paired with verification tags, gap warnings, and audit logs.

---

## Technology Stack

* **Frontend Client:** Vanilla JavaScript, HTML5 Local Storage, Tailwind CSS
* **Backend API Server:** Python 3.11, FastAPI, Uvicorn asynchronous server
* **AI Reasoning Engine:** Google Gemini 2.5 Pro via Python software development kit with strict schema validation

---

## Project Contributors

* `@SKamesh0058`
* `@mithuhere26-ops`
* `@harshu121526`
* `@abinav277`
* `@Inykaash`
* `@KarthikBalaje6212`

---
