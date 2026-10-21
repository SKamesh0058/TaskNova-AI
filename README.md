# TaskNova-AI

> **DEXATHON 2026** | Track 04: AI & Machine Learning | Team ID: DEX262092 | PS Category: Software

A conversation-based coordination assistant that converts messy team chats and project scopes into structured, accountable action cards.

---

### Key Features
- **Dual-Mode Workspace:** Switch seamlessly between Student Mode and Office Mode with full team roster visibility.
- **Persistent Scope & Iterative Chats:** Save a permanent master project scope with a built-in edit option while adding new chat transcripts any number of times.
- **Smart Roster Extraction:** Reads uploaded roster files and extracts only the column with team member names, automatically ignoring register numbers, admission dates, and serial numbers.
- **Emoji & Duplicate Filtering:** Automatically ignores emojis, casual filler, and repeated chat messages so nothing gets processed twice.
- **Verbatim Quote Tracing:** Every generated card cites the exact chat message for complete accountability.
- **Risk Detection:** Automatically flags unassigned roles, missing deadlines, and ambiguous tasks.
- **Task Card Export:** Download generated task cards and action boards directly in PDF or image (JPEG) format.

---

### Architecture & Pipeline
1. **Input:** Master project scope, team roster, and raw chat transcripts ingested via the web dashboard.
2. **Processing:** Backend engine strips out emojis and duplicate messages while matching chat commitments against the project scope.
3. **Validation:** Heuristic check enforces structured JSON outputs and identifies missing assignees and tentative dates.
4. **Output:** Rendered as an interactive action board saved locally in the browser with instant PDF and image download options.

---

### Tech Stack
- **Core Engine:** Automated Intent Extraction (Structured JSON Outputs)
- **Backend:** Python / FastAPI
- **Frontend:** Responsive Web Interface (HTML, CSS, JavaScript, LocalStorage)

---

### Contributors
- @SKamesh0058
- @mithuhere26-ops
- @harshu121526
- @abinav277
- @Inykaash
- @KarthikBalaje6212
