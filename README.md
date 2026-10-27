# 🚀 TaskNova-AI ✨
> AI & Machine Learning)**    
> *Transforming chaotic team chats, messy rosters, and project scopes into structured, actionable management slides — 100% in the browser.*

---

## 📖 The Problem
Every hackathon or sprint team knows the pain: you spend hours arguing over who is building what in a chaotic WhatsApp or Slack group. At the end of the day, key deliverables get **omitted**, tasks remain **unassigned**, and tracking accountability becomes a administrative nightmare. 

**TaskNova-AI** solves this by acting as an intelligent, automated project management mediator.

---

## ✨ What is TaskNova-AI?
TaskNova-AI is a **100% client-side, standalone web prototype** built with zero backend dependencies. It ingests messy multi-format inputs (Excel sheets, Word docs, PDFs, chat transcripts, and screenshots) and uses custom heuristic parsing and natural language intent matching to instantly categorize project tasks into 3 management slides:

1. ⚠️ **Slide 1 (Unassigned Tasks):** Tasks discussed in chat that lack a confirmed owner.
2. 🚨 **Slide 2 (Omitted Scope):** Core project deliverables defined in your baseline scope with zero mentions in chat.
3. ✅ **Slide 3 (Accounted Tasks):** Verified tasks successfully assigned to team members, complete with extracted quotes and deadlines.

---

## 🛠️ Architecture & Tech Stack

TaskNova packs heavy backend-level document processing capabilities directly into the browser:

* **Frontend Engine:** Vanilla ES6+, CSS3 (Glassmorphism UI, Responsive Grid System).
* **Document & Spreadsheet Parsers:** SheetJS (`xlsx`) & Mammoth.js (`docx`).
* **PDF Rendering Engine:** Mozilla PDF.js (`pdf.js`) with visual coordinate row-grouping to preserve table integrity.
* **OCR / Computer Vision:** Tesseract.js for extracting text streams directly from chat screenshots (`.png`, `.jpg`).
* **Report Generation:** html2canvas & jsPDF for instant multi-page PDF and high-res JPEG reporting.

---

## ⚡ Core Engineering Highlights

* **Smart Roster Sanitization:** Automatically purges administrative noise (Serial numbers, Admission dates, and DEX registration codes) to extract *only* clean team member names.
* **Intelligent Scope & Intent Matching:** Uses a custom multi-tier matching algorithm that prevents generic words (like `"Setup"`, `"System"`, or `"Database"`) from colliding while accurately detecting task acceptance, refusals, and inquiries.
* **Strict Pre-Reconciliation Guardrails:** Enforces a mandatory 4-step validation pipeline. The app completely blocks execution and highlights missing dependencies if Roster, Scope, Scope Lock, or Chat Logs are absent.
* **Multi-Role Access Control:** Features dedicated views for **Student Mode** (collaborative/alias mapping) and **Office Mode** (Manager override triage vs. Team Member view-only protection).

---

## 🚀 Getting Started (Zero Setup Required)

Because TaskNova-AI runs entirely in your browser, there is **no Node.js installation, no database configuration, and no server setup** needed!

