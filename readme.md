# ProcessLens AI™ — Business Process Discovery & Automation Readiness

ProcessLens AI™ is an interactive, AI-powered platform that helps small and midsized businesses uncover operational inefficiencies, repetitive tasks, and bottlenecks — and then delivers a prioritized automation roadmap with recommended AI solutions from the NOFA AI Factory.

> **See how your business really works — and what to automate first.**

This repository contains a complete, working prototype designed to demonstrate the full user journey from business assessment to automation recommendations. It features a premium, light-themed SaaS interface, realistic simulated AI analysis, and a sample company mode for immediate exploration.

---

## ✨ Features

- **Multi‑step Assessment Onboarding** – Collect business profile, goals, departments, workflows, and repetitive tasks.
- **Workflow Builder** – Add detailed steps, roles, time estimates, and risk factors for each process.
- **AI‑Powered Analysis** – Simulated analysis engine that generates scores, identifies bottlenecks, and estimates savings.
- **Executive Dashboard** – View key metrics, department‑wise opportunity distribution, time consumption, risk matrix, and top findings.
- **Prioritized Opportunity Ranking** – Sortable table with priority, feasibility, impact, and recommended AI type.
- **Opportunity Detail View** – In‑depth breakdown with problem description, recommended AI solution, human oversight requirements, and NOFA product matches.
- **Automation Readiness Report** – Generate a comprehensive report with executive summary, findings, and a 30/60/90‑day roadmap.
- **Sample Company Mode** – Pre‑loaded “BrightPath Property Services” to instantly explore the platform.
- **Embedded AI Assistant** – Contextual “ProcessLens Advisor” for guidance and explanations.
- **Fully Responsive** – Works seamlessly on desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

This prototype is built with:

- **React** – UI components and state management
- **Tailwind CSS** – Utility‑first styling with a clean, light theme
- **Lucide Icons** – Clean, consistent icon set
- **Local State** – Uses React `useReducer` for app‑wide state, with localStorage persistence (optional)

> The code is delivered as a single HTML file with inline scripts for easy deployment. It can be integrated into a full Next.js/TypeScript project with minimal effort.

---

## 🚀 Getting Started

### Prerequisites

No build tools or package managers are required to run the prototype — it works directly in the browser.

### Running the Prototype

1. **Clone or download** this repository.
2. **Open the `index.html`** file in any modern web browser.
   - That’s it! The entire application loads from the single HTML file.
3. To get the full experience, click **“Start a Free Process Assessment”** or **“View Sample Report”** on the landing page.

### Deploying to Vercel

Since the prototype is a static HTML file, you can deploy it to Vercel with a simple `vercel` command:

```bash
# Install Vercel CLI (if not already)
npm i -g vercel

# Deploy
vercel
