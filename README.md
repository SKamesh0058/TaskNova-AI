# TaskNova-AI


A conversation-based coordination assistant that converts messy team chats and project scopes into structured, accountable action cards.

---

### Key Features
- **Zero-Login Standalone App:** 100% client-side web application deployed on GitHub Pages, running instantly on any laptop or mobile browser with zero login walls or server setups.
- **Dual-Mode Workspace:** Switch seamlessly between Student Mode and Office Mode (featuring manager password protection and team member view-only mode) with full roster visibility.
- **Persistent Scope & Iterative Chats:** Save a permanent master project scope with a built-in edit option while adding new chat transcripts any number of times.
- **Smart Roster & Document Parsing:** Automatically extracts clean team member names from Excel, Word, PDF, or CSV files while ignoring register numbers, admission dates, and serial numbers.
- **Browser OCR & Chat Memory:** Upload `.txt`, `.docx`, or chat screenshots for instant browser-based OCR, manual chat typing with `[Add to chats]`, persistent scrollable history, and a dedicated `🗑️ Clear History` button.
- **Emoji & Duplicate Filtering:** Automatically ignores emojis, casual filler, and repeated chat messages so nothing gets processed twice.
- **Verbatim Quote Tracing:** Every generated card cites the exact chat message for complete accountability.
- **Risk Detection:** Automatically flags unassigned roles, missing deadlines, and ambiguous tasks.
- **Multi-Slide Action Board & Export:** Interactive 3-slide dashboard (Unassigned Tasks, Omitted Scope, and Accounted Tasks) with multi-page PDF and selectable JPEG exports.

---

### Architecture & Pipeline
1. **Input:** Master project scope, team roster, and raw chat transcripts/screenshots ingested via the browser dashboard.
2. **Processing:** Browser engine strips out emojis and duplicate messages while parsing document uploads and matching chat commitments against the project scope.
3. **Validation:** Heuristic check enforces structured outputs and identifies missing assignees and tentative dates.
4. **Output:** Rendered as an interactive 3-slide action board saved locally in the browser with instant multi-page PDF and JPEG download options.

---

### Tech Stack
- **Core Engine:** Automated Intent Extraction & Browser OCR (Tesseract.js, PDF.js, Mammoth, XLSX)
- **Deployment:** GitHub Pages (Zero-Server Standalone Architecture)
- **Frontend:** Responsive Web Interface (HTML5, CSS3, JavaScript, LocalStorage, jsPDF, html2canvas)

---

### Contributors
- @SKamesh0058
- @mithuhere26-ops
- @harshu121526
- @abinav277
- @Inykaash
- @KarthikBalaje6212
