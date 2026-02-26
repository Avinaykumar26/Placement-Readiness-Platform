# KodNest Premium Build System

Author/DEVELOPER : A VINAY KUMAR
MAIL : avinaykumar2004@gmail.com

> **Design Philosophy:** Calm. Intentional. Coherent. Confident.

A premium SaaS design system architected for serious B2C product companies. This system prioritizes clarity over noise, utilizing a strictly defined typographic scale, a muted and harmonious color palette, and purposeful whitespace to create a "confident" user experience.

---

## 🎨 Design Principles

*   **No Visual Drift:** Every element belongs to a unified visual language.
*   **Intentional Spacing:** A rigid 8px grid system (8, 16, 24, 40, 64px) defines all rhythm.
*   **Calm Aesthetics:** No gradients, no glassmorphism, no neon. Just solid, intentional design.
*   **Premium Typography:**
    *   **Headings:** *Playfair Display* (Serif) — Authoritative and elegant.
    *   **Body:** *Inter* (Sans-serif) — Clean and highly legible.

## 🛠 Technology Stack

*   **Core:** HTML5 (Semantic Structure)
*   **Styling:** Vanilla CSS3 (Custom Properties/Variables for theming)
*   **Logic:** Vanilla JavaScript (Lightweight interactions)
*   **Zero Dependencies:** No frameworks, no bloat.

## 📂 Project Structure

```text
/
├── css/
│   └── style.css       # The single source of truth for design tokens & styles
├── js/
│   └── app.js          # Interaction logic (copy-to-clipboard, focus states)
├── index.html          # Core layout template
└── README.md           # Documentation
```

## 🚀 Getting Started

### Prerequisites
You need a modern web browser. No build steps required.

### Running Locally
You can serve the project using Python's built-in server or any static file server.

```bash
# Python 3
python -m http.server 8000
```
Then visit: `http://localhost:8000`

## 🧩 Key Components

1.  **Global Layout:** Top Bar → Context Header → Workspace (70/30) → Proof Footer.
2.  **Context Header:** Sets the stage for the user's task.
3.  **Proof Footer:** A persistent validation checklist that enforces quality before progression.
4.  **Prompt Tools:** Specialized UI for copying prompts and managing workflow steps.

---

*"Everything must feel like one mind designed it."*


