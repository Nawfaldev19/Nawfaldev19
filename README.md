# Nawfal Imran

**Full-stack engineer · React and TypeScript · Ruby on Rails · GraphQL**

I build web applications that stay correct under real conditions: several people editing the same thing at once, many customers sharing one database, bookings that must never collide, and users who rely on a keyboard or a screen reader. I write down the trade-offs and prove the important behaviour with tests.

## Projects

Each project runs locally in a couple of commands, comes with demo data, and has its own tests, CI, architecture notes and a list of known limitations. All of them are original portfolio work with fictional data.

### Real-time and collaboration

| Project | What it shows | Stack |
|---|---|---|
| [**realtime-reactflow-canvas**](https://github.com/Nawfaldev19/realtime-reactflow-canvas) | A diagram editor several people can edit at once, with live cursors, connector routing, alignment guides and version history | React Flow, TypeScript, Rails, Action Cable |
| [**graphql-sse-live-feed**](https://github.com/Nawfaldev19/graphql-sse-live-feed) | A live activity feed where each member only ever sees events from their own space | GraphQL subscriptions, Server-Sent Events, Node.js, React |

### Data integrity and multi-tenancy

| Project | What it shows | Stack |
|---|---|---|
| [**rails-booking-kiosk**](https://github.com/Nawfaldev19/rails-booking-kiosk) | Machine booking where double booking is impossible at the database level, plus a staff kiosk | Rails 8, GraphQL, PostgreSQL, React |
| [**multitenant-graphql-bookings**](https://github.com/Nawfaldev19/multitenant-graphql-bookings) | Equipment booking for several organisations that can never see each other's data | Rails 8, GraphQL, React, TypeScript |
| [**rails-graphql-room-booking**](https://github.com/Nawfaldev19/rails-graphql-room-booking) | Room booking with clash-proof database rules, correct time zones and email notifications | Rails 8, GraphQL, React, SQLite |
| [**hashchain-esign**](https://github.com/Nawfaldev19/hashchain-esign) | Versioned agreements and sign-offs chained by hashes, so any later change is detectable | TypeScript, GraphQL, PostgreSQL row-level security |
| [**safe-record-merge**](https://github.com/Nawfaldev19/safe-record-merge) | Finds duplicate members and merges them in one transaction, with an exact undo | TypeScript, GraphQL, PostgreSQL |

### Interfaces and accessibility

| Project | What it shows | Stack |
|---|---|---|
| [**svg-floorplan-studio**](https://github.com/Nawfaldev19/svg-floorplan-studio) | A floor-plan editor with full undo and redo, touch support and a complete keyboard alternative | React 19, TypeScript, SVG |
| [**autosave-submission-wizard**](https://github.com/Nawfaldev19/autosave-submission-wizard) | A multi-step form that saves every step, plus an editorial review queue | TypeScript, GraphQL, PostgreSQL, React |
| [**react-inclusive-ui**](https://github.com/Nawfaldev19/react-inclusive-ui) | Accessible React components with design tokens whose colour contrast is checked by tests | React, TypeScript, Vite |

## How I work

- Put each rule where it cannot be skipped, in the database when it is about data.
- Keep important logic in plain functions with direct tests.
- Measure before optimising.
- Write down the trade-off, not only the choice, and say what is not done.

## Contact

[nawfal.imran.dev0@gmail.com](mailto:nawfal.imran.dev0@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nawfal-imran-886b13218)
