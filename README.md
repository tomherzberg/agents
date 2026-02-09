# KI-Agenten Orchestrierung Framework

Dieses Repository enthält eine Sammlung spezialisierter KI-Agenten-Definitionen, die als virtuelles Software-Entwicklungsteam zusammenarbeiten. Jeder Agent hat eine spezifische Rolle, klare Verantwortlichkeiten und einen definierten Workflow, um hochwertige Software von der Anforderungsanalyse bis zum Deployment zu gewährleisten.

## 🚀 Das Team

### 📋 Requirements Engineer
Übersetzt vage Ideen in strukturierte Feature-Spezifikationen.
- **Output:** `/features/PROJ-X-feature-name.md`
- **Fokus:** User Stories, Akzeptanzkriterien und Edge Cases.

### 🏗️ Solution Architect
Plant die High-Level-Architektur für nicht-technische Stakeholder.
- **Output:** Architektur-Abschnitte in den Feature-Spezifikationen.
- **Fokus:** Komponentenhierarchien, Datenmodelle und Technologieentscheidungen (kein Code).

### 🎨 Frontend Developer
Implementiert die Benutzeroberfläche und Interaktionen.
- **Stack:** React, Next.js (App Router), Tailwind CSS, shadcn/ui.
- **Fokus:** UI/UX, Responsivität und Barrierefreiheit.

### ⚙️ Backend Developer
Verantwortlich für die serverseitige Logik und Datenpersistenz.
- **Stack:** Supabase (PostgreSQL), Next.js Route Handlers, Zod.
- **Fokus:** API-Design, Datenbank-Migrationen und Row Level Security (RLS).

### 🛡️ QA Engineer
Sichert Qualität und Sicherheit durch rigorose Tests.
- **Fokus:** Manuelle Tests gegen Akzeptanzkriterien, Überprüfung von Edge Cases und Security "Red-Team" Analysen.

### 🚢 DevOps Engineer
Verwaltet die Infrastruktur und die Deployment-Pipeline.
- **Stack:** Vercel, GitHub Actions.
- **Fokus:** CI/CD, Umgebungsvariablen und Produktions-Monitoring.

## 🔄 Workflow

1.  **Anforderungsphase:** Der *Requirements Engineer* erstellt eine Feature-Spezifikation.
2.  **Designphase:** Der *Solution Architect* definiert die Struktur.
3.  **Implementierung:** *Frontend-* und *Backend-Developer* bauen das Feature parallel.
4.  **Verifizierung:** Der *QA Engineer* testet die Implementierung.
5.  **Deployment:** Der *DevOps Engineer* pusht das Feature in die Produktion.

## 🛠️ Tech Stack Konventionen

- **Framework:** Next.js (App Router)
- **Styling:** Tailwind CSS
- **Komponenten:** shadcn/ui
- **Datenbank/Auth:** Supabase
- **Deployment:** Vercel

## 📖 Nutzung
Um einen Agenten zu aktivieren, übergib die entsprechende `.md`-Datei als Kontext an deinen KI-Assistenten (z. B.: „Lies `frontend-developer.md` und implementiere das Feature aus `features/PROJ-1.md`“).
