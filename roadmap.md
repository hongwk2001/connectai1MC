# 🗺️ ConnectAI 1MC (1-Man Company) Roadmap

Welcome to the roadmap for the **ConnectAI 1MC (1-Man Company)** automation system. This document outlines the step-by-step implementation phases for building the multi-agent enterprise automation system inside the Anti Gravity environment. We will return to this roadmap after completing each step to track our progress, check off completed milestones, and align on the next tasks.

---

## 🚀 Overview of the Vision
ConnectAI 1MC is an autonomous enterprise automation platform that coordinates **10 AI agents** to work 24/7 towards a defined business goal (e.g., "Generate $10k monthly revenue", "Reach 100k subscribers"). It runs fully on local models (Ollama/LM Studio) for zero cost, maintains a cumulative visual "Brain" network of knowledge, and allows seamless backup/sync via GitHub.

---

## 📍 Progress Tracker
- [ ] **Phase 1: Basic Structure, Shell, & Authentication** <!-- id: phase1 -->
- [ ] **Phase 2: Company Setup & Enterprise Dashboard UI** <!-- id: phase2 -->
- [ ] **Phase 3: Multi-Agent Hub & Visual Activity** <!-- id: phase3 -->
- [ ] **Phase 4: Local LLM Orchestration & CEO Dispatcher** <!-- id: phase4 -->
- [ ] **Phase 5: Agent Collaboration (Chat & Logs)** <!-- id: phase5 -->
- [ ] **Phase 6: The "Brain" (Knowledge Graph & Visualization)** <!-- id: phase6 -->
- [ ] **Phase 7: Skill System & "Brain Pack" Modularity** <!-- id: phase7 -->
- [ ] **Phase 8: Online Sync & GitHub Backup** <!-- id: phase8 -->

---

## 🛠️ Phase Breakdown

### **Phase 1: Basic Structure, Shell, & Authentication**
Build the foundation of the ConnectAI Lab extension.
- [ ] Set up the standard extension skeleton (HTML, CSS, JS).
- [ ] Implement the **Enterprise Mode Entry Lock** (Password validation UI, default passcode: `0101`).
- [ ] Create the layout navigation sidebar/header (Dashboard, Logs, Conversations, Brain, Settings).
- [ ] Design custom Google Fonts integration, premium glassmorphism, and a sleek dark theme.

### **Phase 2: Company Setup & Enterprise Dashboard UI**
Implement the onboarding flow and core management views.
- [ ] **Onboarding Form**: Inputs for Company Name, Company Description, Target Audience, and Core Goals.
- [ ] Persistent storage of the company configuration.
- [ ] Beautiful dashboard metrics panel (active agents count, current active day: e.g. Day 12, task progress).

### **Phase 3: Multi-Agent Hub & Visual Activity**
Build the visual board representing the 10 AI Agents.
- [ ] Design and render the 10 core agents with distinct avatars, roles, and missions:
  * **CEO**, **YouTube Manager**, **Instagram Manager**, **Designer**, **Developer**, **Business Agent**, **Secretary**, **Editor**, **Writer**, **Researcher**.
- [ ] Implement hover states showing agent stats, goals, and current active "Skills".
- [ ] Design visual "Working" animations (glowing nodes, activity logs) indicating when an agent is active (e.g., "Working: 4" indicator).

### **Phase 4: Local LLM Orchestration & CEO Dispatcher**
Implement connections to local model servers and setup agent communication routing.
- [ ] Build configuration interface for **Ollama** and **LM Studio** integration.
- [ ] Set up offline fallback mode checks.
- [ ] Implement the **CEO dispatch logic**: CEO receives user goals/commands, analyzes them, and divides tasks among appropriate agents.

### **Phase 5: Agent Collaboration (Chat & Logs)**
Make the agents interact with each other and output logs.
- [ ] **Conversations (Dialogue Record) View**: A scrollable thread showing multi-agent group chats (e.g., Writer asking Secretary for draft reviews).
- [ ] **System Logs**: Day-by-day logs (Day 1, Day 2, Day 3) recording behind-the-scenes execution details.
- [ ] Interactive terminal/chat box for user commands (e.g., *"Make a YouTube plan like MrBeast"*).

### **Phase 6: The "Brain" (Knowledge Graph & Visualization)**
Build the interactive visual knowledge network.
- [ ] Design an interactive 2D node-link graph (Brain view) using Canvas or SVG.
- [ ] Implement neural-like flashing node animations showing specific database lookups when commands run.
- [ ] Create separation between **Local Knowledge Space** (SQLite/JSON-based memory) and external feeds.

### **Phase 7: Skill System & "Brain Pack" Modularity**
Equip agents with specific tools.
- [ ] Map out base agent skills (e.g., YouTube comments fetcher, competitor analysis, Telegram notifications, writing draft generator).
- [ ] Implement a **Brain Pack installer**: Allow users to drag/drop or select pre-configured JSON/JS packs containing new skills and domain knowledge.

### **Phase 8: Online Sync & GitHub Backup**
Add backup capabilities.
- [ ] Add GitHub repository URL configuration.
- [ ] Implement Git integration (clone, add, commit, push) for automatic backing up and restoring of the local knowledge space.
- [ ] Visual progress bars for "Knowledge Syncing...".

---

## 🎨 Design System Guide
To ensure visual excellence:
- **Theme**: Premium Deep Space / Obsidian Dark mode.
- **Colors**: Glassmorphic borders, HSL-tailored accents (electric indigo, cyan glow, neon green, soft lavender).
- **Animations**: Soft hover scales, pulse effects on active agent avatars, subtle particle background in the Brain view.
