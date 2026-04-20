# Vibe Projects

My repository of small **vibe-coded** projects — from fun experiments to somewhat useful tools (and a few that are gloriously useless).

All projects are single-file HTML applications (vanilla HTML + CSS + JavaScript). Just open the `.html` file in your browser — no installation required.

## Projects

### atom-visualizer.html

**Description**  
An interactive visualizer for atomic structures and electron orbitals. It lets you explore different atoms, their electron configurations, and animated orbital models.

**Purpose**  
Educational / fun tool for visualizing chemistry and quantum concepts in a playful way.

**How to use**  
1. Open `atom-visualizer.html` in any modern browser.  
2. Select an element from the periodic table or input atomic number.  
3. Watch animated orbitals and explore different visualization modes.

**Key features**  
- Interactive periodic table  
- 3D-like orbital animations  
- Electron configuration display  
- Zoom / rotate controls

**File:** `atom-visualizer.html`

---

### cortex-xdr-xql-editor.html

**Description**  
A web-based editor and query helper for Cortex XDR XQL (XDR Query Language).

**Purpose**  
Helps security analysts write, test, and understand XQL queries more efficiently without needing to be logged into the Cortex console all the time.

**How to use**  
Open the file in your browser and start writing XQL queries. Syntax highlighting, auto-complete suggestions, and example queries are included.

**Key features**  
- XQL syntax highlighting  
- Built-in query examples  
- Quick reference for common commands  
- Export query options

**File:** `cortex-xdr-xql-editor.html`

---

### crypt-chat.html

**Description**  
A simple end-to-end encrypted chat interface (demonstration / prototype).

**Purpose**  
Showcase of basic web-based cryptography for private messaging using the browser's Web Crypto API.

**How to use**  
Open in browser. Generate or exchange public keys, then chat with simulated or real peer (WebRTC or local demo mode).

**Key features**  
- Client-side encryption/decryption  
- Simple key exchange demo  
- Clean chat UI

**File:** `crypt-chat.html`

---

### nexus_associations_search.html

**Description**  
Search and exploration tool for french non profit & NGOs

**Purpose**  
Discover french association / NGOs registry

**How to use**  
Load the page and enter search terms. Results show linked associations with optional graph visualization.

**Key features**  
- Fuzzy / semantic search  
- Relationship mapping  
- Clickable association nodes

**File:** `nexus_associations_search.html`

---

### nutrition-tracker.html

**Description**  
A simple daily nutrition tracking web app. Log meals, track calories, macros, and get basic insights.

**Purpose**  
Lightweight personal nutrition logger that runs entirely in the browser (data saved via localStorage).

**How to use**  
Open the HTML file, add foods/meals, view daily/weekly summaries.

**Key features**  
- Food database or manual entry  
- Macro & calorie calculator  
- Progress charts  
- Persistent local storage

**File:** `nutrition-tracker.html`

---

### webrtc-videochat.html

**Description**  
A minimal WebRTC-based video chat demo.

**Purpose**  
Quick prototype to test and demonstrate peer-to-peer video/audio calling directly in the browser.

**How to use**  
1. Open the file in two different browser tabs or devices.  
2. Share the generated room/link or use the signaling demo.  
3. Start video call.

**Key features**  
- Peer-to-peer video & audio  
- Basic signaling (demo mode)  
- Screen sharing option (if enabled)

**File:** `webrtc-videochat.html`

---

## How to run any project

All tools are **client-side only**.  
Just download or clone the repo and double-click any `.html` file — or host the whole folder locally with any static server.

Example with Python:
```bash
python -m http.server 8000
