# AI Agent Orchestration Framework

This repository contains a collection of specialized AI Agent definitions designed to work together as a virtual software development team. Each agent has a specific role, set of responsibilities, and a defined workflow to ensure high-quality software development from requirements to deployment.

## 🚀 The Team

### 📋 Requirements Engineer
Translates vague ideas into structured feature specifications.
- **Output:** `/features/PROJ-X-feature-name.md`
- **Focus:** User Stories, Acceptance Criteria, and Edge Cases.

### 🏗️ Solution Architect
Plans the high-level architecture for non-technical stakeholders.
- **Output:** Architecture sections in feature specs.
- **Focus:** Component trees, data models, and technology choices (no code).

### 🎨 Frontend Developer
Builds the user interface and interactions.
- **Stack:** React, Next.js (App Router), Tailwind CSS, shadcn/ui.
- **Focus:** UI/UX, responsiveness, and accessibility.

### ⚙️ Backend Developer
Handles the server-side logic and data persistence.
- **Stack:** Supabase (PostgreSQL), Next.js Route Handlers, Zod.
- **Focus:** API design, Database migrations, and Row Level Security (RLS).

### 🛡️ QA Engineer
Ensures quality and security through rigorous testing.
- **Focus:** Manual testing against Acceptance Criteria, Edge Case verification, and security "Red-Team" analysis.

### 🚢 DevOps Engineer
Manages the infrastructure and deployment pipeline.
- **Stack:** Vercel, GitHub Actions.
- **Focus:** CI/CD, environment variables, and production monitoring.

## 🔄 Workflow

1.  **Requirement Phase:** The *Requirements Engineer* creates a feature spec.
2.  **Design Phase:** The *Solution Architect* defines the structure.
3.  **Implementation:** *Frontend* and *Backend Developers* build the feature in parallel.
4.  **Verification:** The *QA Engineer* tests the implementation.
5.  **Deployment:** The *DevOps Engineer* pushes the feature to production.

## 🛠️ Tech Stack Convention

- **Framework:** Next.js (App Router)
- **Styling:** Tailwind CSS
- **Components:** shadcn/ui
- **Database/Auth:** Supabase
- **Deployment:** Vercel

## 📖 How to use
To activate an agent, provide the respective `.md` file as context to your AI assistant (e.g., "Read `frontend-developer.md` and implement the feature described in `features/PROJ-1.md`").
