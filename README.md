<div align="center">

# Nuvio

### Learn with intention. Grow with every session.

**A modern, cross-platform study companion for planning, tracking, and understanding your learning progress.**

[![Status](https://img.shields.io/badge/status-in%20development-7C6CFF?style=flat-square)](#project-status)
[![Platform](https://img.shields.io/badge/platform-web%20%7C%20iOS%20%7C%20Android-242938?style=flat-square)](#roadmap)
[![TypeScript](https://img.shields.io/badge/TypeScript-planned-3178C6?style=flat-square&logo=typescript&logoColor=white)](#planned-tech-stack)

*Plan smarter. Stay focused. See your progress. *

</div>

---

## ✨ About Nuvio

**Nuvio** is a study productivity application designed to help students turn learning goals into consistent progress. Instead of juggling separate tools for planning, timing study sessions, and reviewing statistics, Nuvio aims to bring everything together in one clean, distraction-free experience.

The project is being built as an **open-source collaborative portfolio project**, with an emphasis on thoughtful UI/UX, maintainable architecture, testing, and real-world software development practices.

> **Project status:** Early development / planning. The features and technologies below describe the intended direction, not an already released product.

## 🎯 Planned Features

| Feature | Description | Status |
| --- | --- | --- |
| Study dashboard | Overview of upcoming exams, goals, and activity | Planned |
| Subject management | Organize university modules and learning topics | Planned |
| Focus timer | Track focused learning sessions per subject | Planned |
| Study statistics | Visualize study time, consistency, and trends | Planned |
| Activity heatmap | See learning consistency at a glance | Planned |
| Exam planner | Plan preparation around exam dates and deadlines | Planned |
| User accounts | Secure personal accounts and synced data | Planned |
| Mobile experience | Native-feeling iOS and Android apps | Future |
| Smart scheduling | Adjust study plans as deadlines approach | Future |

## 🧭 Roadmap

- [ ] **Phase 1 — Foundation:** Repository setup, design system, code quality tooling, database schema
- [ ] **Phase 2 — MVP:** Authentication, subjects, exam dates, study-session tracking
- [ ] **Phase 3 — Insights:** Dashboard, charts, activity heatmap, responsive layouts
- [ ] **Phase 4 — Quality & Release:** Tests, accessibility, deployment, demo data, documentation
- [ ] **Phase 5 — Mobile:** Shared API and mobile applications for iOS and Android
- [ ] **Phase 6 — Exploration:** Collaborative study features and intelligent planning

## 🛠️ Planned Tech Stack

This stack is a proposal and may evolve as development progresses.

| Area | Technology |
| --- | --- |
| Web | Next.js, React, TypeScript |
| Mobile | React Native, Expo, TypeScript |
| API | Next.js API initially; separate API if needed |
| Database | PostgreSQL |
| ORM | Prisma |
| Styling | Tailwind CSS |
| UI components | shadcn/ui |
| Monorepo | pnpm workspaces + Turborepo (when mobile work begins) |
| Quality | ESLint, Prettier, automated tests |
| CI | GitHub Actions |

### Proposed Repository Structure

```text
nuvio/
├── apps/
│   ├── web/          # Next.js web application
│   └── mobile/       # Expo app (future)
├── packages/
│   ├── ui/           # Reusable design tokens / shared UI where appropriate
│   ├── config/       # Shared lint / TypeScript configuration
│   └── types/        # Shared types and validation schemas
├── docs/             # Architecture decisions and project documentation
└── README.md
```

*This is the target structure, not a claim about the current repository contents.*

## 👥 How We Work

Nuvio is a collaborative learning project. Our development workflow aims to reflect professional team practices:

1. Track features and bugs with GitHub Issues.
2. Develop in focused feature branches.
3. Open pull requests with a clear description and screenshots for UI changes.
4. Review code together before merging.
5. Use automated checks for formatting, linting, and tests.
6. Document meaningful technical decisions.

## 🚀 Getting Started

Local setup instructions will be added once the initial application scaffold is committed. Until then, this repository documents the project direction and roadmap.

## 📸 Preview

Design previews and screenshots will be added as development progresses.

## 🤝 Contributing

We welcome constructive feedback and suggestions through GitHub Issues. Contribution instructions will follow as the codebase takes shape.

## 📄 License

A license has not yet been selected. Until one is added, the repository is **not automatically licensed for reuse or redistribution**.

---

<div align="center">

**Nuvio — Make every study session count.**

Built by students, for students.

</div>
