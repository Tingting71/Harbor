# Harbor: Context-Aware AI Workplace & Tab Manager

## Overview
**Harbor** is an AI-assisted workplace designed to solve tab overload and context switching during complex, multi-project work. 

Traditional bookmark folders and tab managers save URLs, but they strip away the **context**—why those tabs were opened, how they relate to one another, and what decisions or insights were already made. Harbor acts as a structured home port for your active tasks: it groups browser tabs into dedicated workspaces while preserving persistent task notes, page summaries, and AI context so you can switch projects or resume work without losing momentum.

---

## Core Features

### 1. Context-Aware Workspace Management
* **Task-Centric Workspaces:** Organize scattered tabs into dedicated workspaces tailored to specific projects, literature reviews, or daily workflows.
* **Persistent Mental Model:** Each workspace retains its associated notes, task objectives, and session state—not just a static list of links.

### 2. AI Context Synthesis & Assistance
* **Workspace-Scoped AI:** Interact with an AI assistant grounded in the active workspace's open tabs and notes, avoiding repetitive copy-pasting across windows.
* **Automated Summaries & Recall:** Quickly distill key takeaways from multiple open pages and surface relevant context when returning to an inactive workspace days later.

### 3. Streamlined Tab Control
* **One-Click Context Switching:** Dock an entire set of tabs when stepping away from a task and restore the full workspace cleanly when you are ready to resume.
* **Cross-Workspace Search:** Locate tabs, notes, and saved contexts across all workspaces without hunting through dozens of open windows.

---

## Typical Use Cases
* **Academic & Technical Research:** Keep literature searches, reference papers, code repositories, and reading notes bundled together by research topic.
* **Multi-Project Execution:** Separate coursework, engineering prototypes, and administrative workflows into isolated, clutter-free environments.
* **Deep Work & Reading:** Park tangential tabs into a saved workspace without derailing your current focus.

---

## Repository Structure
*(Update the folder names below to match your actual implementation, e.g., browser extension vs. web app)*

```text
Harbor/
├── src/                # Core application / extension source code
├── components/         # Workspace switcher, tab list, and AI context panel UI
├── services/           # Tab state persistence, context indexing, and AI API integration
├── assets/             # Screenshots and demo walkthroughs
└── README.md
