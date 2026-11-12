# Nawfal Imran

**Senior Full Stack Developer.** I build complex interactive editors (diagrams, canvases, form and layout builders) and multi-tenant SaaS on React, TypeScript, Ruby on Rails and GraphQL.

I've spent 4+ years making hard UI feel simple: diagram editors that stay smooth on large graphs, booking systems that never double-book, and many organisations sharing one platform without seeing each other's data. I've led a node-based workflow editor on a multi-tenant healthcare data platform, reviewing both frontend and backend work, and I build features end to end on a practice-management platform for clinics.

## What I've worked on

- **Large diagrams, fast:** took rendering on large ReactFlow diagrams from below 10 FPS to 40–56 FPS by removing the cause of the re-renders (per-node Zustand state, decoupled components, memoisation, debounced drag/pan, lazy loading).
- **Editor building blocks:** 10+ custom ReactFlow node types with attachable content, plus version history, canvas and export features.
- **GraphQL on the client:** tuned Apollo Client cache policies and reactive variables for optimistic UI without redundant requests, with typed operations through codegen.
- **Architecture:** led the move from a monolithic frontend to a modular, reusable component structure.
- **Tixters** ([tixters.com](https://tixters.com)), an event-ticketing platform: lead developer in a three-person team. I designed and built the venue seat-map editor, then rebuilt it from DOM elements onto a Konva canvas so it holds up for big venues (stress-tested at 5,760 seats), with sections, standing areas, objects and section groups. I wrote about two-thirds of the organiser dashboard and the check-in app.
- **Clinic SaaS:** built clash-free scheduling (availability checked in real time at booking time, so slots never double-book), a charting questionnaire builder, a consent-form builder, and data migrations.

## Featured work

A few demos I've built, each one a hard problem solved end to end:

| Project | What it shows |
|---|---|
| [realtime-reactflow-canvas](https://github.com/Nawfaldev19/realtime-reactflow-canvas) | Several people editing one diagram at once: live cursors, connector routing, version history. React Flow, TypeScript, Rails, Action Cable. **[Live demo](https://live-canvas-web.onrender.com)** |
| [rails-booking-kiosk](https://github.com/Nawfaldev19/rails-booking-kiosk) | Double booking refused by the database itself, plus a front-desk kiosk. Rails 8, GraphQL, PostgreSQL, React |
| [multitenant-graphql-bookings](https://github.com/Nawfaldev19/multitenant-graphql-bookings) | Several organisations on one system that can never see each other's data. Rails 8, GraphQL, React, TypeScript |
| [svg-floorplan-studio](https://github.com/Nawfaldev19/svg-floorplan-studio) | A floor-plan editor with an embeddable read-only viewer; every editing rule is a pure, unit-tested reducer. React 19, TypeScript, SVG |
| [autosave-submission-wizard](https://github.com/Nawfaldev19/autosave-submission-wizard) | A multi-step form that saves as you go; a stale tab can't overwrite a newer save |
| [react-inclusive-ui](https://github.com/Nawfaldev19/react-inclusive-ui) | Accessible components that work by keyboard and screen reader, with a live docs site |

Also: [rails-graphql-room-booking](https://github.com/Nawfaldev19/rails-graphql-room-booking) · [graphql-sse-live-feed](https://github.com/Nawfaldev19/graphql-sse-live-feed) · [hashchain-esign](https://github.com/Nawfaldev19/hashchain-esign) · [safe-record-merge](https://github.com/Nawfaldev19/safe-record-merge)

## How I work with AI

I use Claude Code and Cursor every day, and I build agentic workflows around them: subagents running in parallel, MCP servers and custom skills. The part I care about most is keeping the AI on the rails:

- **Project rules the agents must follow:** I write the coding guidelines (CLAUDE.md) for each app, covering conventions, architecture, testing and what never to touch, so the AI works the project's way, not its own.
- **Guardrails:** scoped permissions, one agent per file so nothing gets overwritten, and humans in charge of anything irreversible.
- **Verification:** write the spec, have the tests prove it, cross-check AI code reviews with a second agent, and review every diff before it merges.

AI makes me faster; it doesn't replace the judgement.

## Stack

- **Frontend:** React, TypeScript, ReactFlow, Konva, Zustand, Redux, Apollo Client, MUI, Tailwind
- **Backend:** Ruby on Rails, GraphQL, PostgreSQL, Action Cable
- **Testing:** React Testing Library, Vitest, Playwright, Minitest, RSpec

## Get in touch

[LinkedIn](https://www.linkedin.com/in/nawfal-imran-886b13218)
