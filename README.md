# Done

Done is a personal system for turning routines, college responsibilities, work tasks, and notes into clear daily actions.

The project is also a deliberate learning environment for improving frontend and backend engineering skills through a real product used every day.

## Product areas

- **Today** — daily priorities, routines, deadlines, and quick capture
- **Tasks** — college, work, personal, and project tasks
- **Study** — subjects, assessments, sessions, confidence, and review
- **Notes** — structured notes connected to subjects and tasks
- **Review** — weekly progress and planning
- **AI assistance** — summaries, task extraction, questions, and study planning

## Planned architecture

| Area | Direction |
| --- | --- |
| Android | Expo and React Native |
| macOS | Electron, React, and Vite |
| API | NestJS and TypeScript |
| Database | PostgreSQL and Drizzle |
| Shared UI | Tamagui foundations and design tokens |
| Repository | pnpm workspace with Turborepo |

The clients will share domain logic, validation, API contracts, tokens, and foundational components while keeping platform-specific navigation and advanced interactions.

## Status

Done is currently in **Phase 0: Definition**. Product scope and technical decisions are being documented before application scaffolding begins.

- [Product and development map in FigJam](https://www.figma.com/board/iKoAq2RusB3MZmEQm90H2k)
- [Development roadmap](docs/roadmap.md)
- [Security policy](SECURITY.md)

## Principles

1. Build for daily personal use.
2. Prefer small, complete vertical slices.
3. Connect every feature to an explicit learning goal.
4. Keep credentials, production data, and personal notes out of the repository.
5. Add design-system components only when a real screen needs them.
6. Treat mobile and desktop as related but distinct experiences.

## License

No license has been selected yet. The source is publicly visible, but reuse rights have not been granted.
