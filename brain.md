# AGENT BRAIN & MEMORY INDEX

> **Last Updated:** 2026-09-11
> Purpose: Persistent context for any AI agent working on this repo. Read this file FIRST before making any changes.

---

## 1. Project Context & Constraints

- **Role:** Full-Stack AI Web Developer & Portfolio Maintainer.
- **Project Goal:** Personal Portfolio Website.
- **Design System / UI:** Pre-designed in Stitch (UI/UX finalized) — implement to spec, do not redesign.
- **Core Tech Stack:** `[TODO: confirm — e.g., Next.js 14, Tailwind CSS, TypeScript, Framer Motion]`
- **Deployment Platform:** `[TODO: confirm — e.g., Vercel, Netlify]`

### Hard Constraints
- Stitch design is the single source of truth for visuals; any deviation must be explicitly requested by the user.
- Confirm tech stack + deployment platform before scaffolding the base project.

---

## 2. Global Architectural Rules

- Prioritize clean, reusable component architecture.
- Keep CSS modular and strictly follow the design tokens defined in the Stitch specs.
- Do **NOT** rewrite existing working components unless explicitly asked; modify incrementally.
- Maintain responsive design (Mobile-first breakpoint standard: `<640px`, `<1024px`, `>=1280px`).
- All new files/components follow the paths defined in the map in §3 — no ad-hoc file locations.

---

## 3. Stitch UI/UX Integration Map

| Section / Component | Design File / Spec | Implementation Status | Path / File Location |
| :--- | :--- | :--- | :--- |
| **Hero Section** | Stitch Frame 1 | ⏳ Pending | `components/sections/Hero.tsx` |
| **About / Profile** | Stitch Frame 2 | ⏳ Pending | `components/sections/About.tsx` |
| **Projects Showcase** | Stitch Frame 3 | ⏳ Pending | `components/sections/Projects.tsx` |
| **Experience / Timeline** | Stitch Frame 4 | ⏳ Pending | `components/sections/Experience.tsx` |
| **Contact Form** | Stitch Frame 5 | ⏳ Pending | `components/sections/Contact.tsx` |

Status legend: ⏳ Pending → 🔨 In Progress → ✅ Done → ♻️ Needs Rework (append a dated note in §4 when status changes).

---

## 4. Key Decisions & State Log

*(Append short notes here when architectural decisions change to avoid repeating instructions)*

- `[2026-09-11]` Project initialized using Stitch UI design exports.
- `[2026-09-11]` Agent brain file (`brain.md`) created as the canonical memory index.
- `[YYYY-MM-DD]` `[Example: Selected Tailwind CSS for global styling]`

---

## 5. Active Task Checklist

- [ ] Export UI assets and design tokens from Stitch.
- [ ] Confirm final tech stack + deployment platform.
- [ ] Setup base project architecture and design tokens.
- [ ] Build reusable layout wrappers (Header, Footer, Navigation).
- [ ] Implement section components per Stitch specifications (Hero, About, Projects, Experience, Contact).
- [ ] Verify responsive behavior at `<640px`, `<1024px`, `>=1280px`.
- [ ] Configure deployment (build + deploy pipeline).

---

## 6. Working Agreement (for agents)

- Always read this file before starting a task; keep it updated after completing one.
- Use absolute paths when referencing files.
- Validate any code you add (build/typecheck/tests) before marking checklist items done.
