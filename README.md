
# TeamNova-AI

> **DEXATHON 2026** | Track 04: AI & Machine Learning | PS Category: Software

A conversation-based AI coordination assistant that converts messy team chats into structured, accountable action cards using the Google Gemini API.

---

### Key Features
- **Instant Ingestion:** Paste raw transcripts from Slack, WhatsApp, or Discord.
- **Structured Extraction:** Enforces JSON schema outputs for tasks, owners, and deadlines.
- **Verbatim Quote Tracing:** Every generated card cites the exact chat message for accountability.
- **Risk Detection:** Automatically flags unassigned roles, missing deadlines, and ambiguous tasks.

---

### Architecture & Pipeline
1. **Input:** Raw conversational text ingested via web dashboard.
2. **Processing:** Gemini API parses intent via structured system instructions.
3. **Validation:** Heuristic check identifies missing assignees and tentative dates.
4. **Output:** Rendered as an interactive, exportable action board.

---

### Tech Stack
- **AI Core:** Google Gemini API (Structured Outputs)
- **Backend:** Python / FastAPI
- **Frontend:** Responsive Web Interface (HTML, CSS, JavaScript)

---

### Project Roadmap
- [x] Problem discovery & competitive analysis
- [x] System architecture & JSON schema design
- [ ] Core prototype implementation & API integration
- [ ] Live demo deployment
