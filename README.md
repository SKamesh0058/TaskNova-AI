# TaskNova-AI

> **DEXATHON 2026** | Track 04: AI & Machine Learning | Team ID: DEX262092

A dual-input reconciliation engine that converts chat logs into structured task boards using Google Gemini 2.5 Pro.

---

## Core Features

* **Dual-Mode Workspace:** Switch between Student Mode for peer accountability and Office Mode for manager-led assignment.
* **Verbatim Quote Auditing:** Binds every task card to its source chat message for complete accountability.
* **Local-First Persistence:** Uses browser local storage and portable session files with zero cloud database overhead.
* **Automated Risk Detection:** Flags unassigned roles and missing deadlines.
* **Export Options:** Download task boards and reconciliation reports instantly in PDF or image formats.

---

## Architecture and Tech Stack

1. **Ingestion:** Upload master scope checklists and raw chat transcripts.
2. **Backend:** Python 3.11 and FastAPI for preprocessing and filtering.
3. **AI Core:** Google Gemini 2.5 Pro via Python SDK with strict Pydantic schema validation.
4. **Frontend:** Vanilla JavaScript, Tailwind CSS, and export handlers.

---

## Contributors

* @SKamesh0058
* @mithuhere26-ops
* @harshu121526
* @abinav277
* @Inykaash
* @KarthikBalaje6212
