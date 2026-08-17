# Done roadmap

The roadmap is organized around usable product increments. Dates will be assigned after the weekly schedule and available development time are defined.

## Phase 0 — Definition

- Define the minimum daily workflow
- Confirm MVP boundaries
- Record technical decisions
- Define initial domain model
- Create the project backlog
- Choose the first weekly development cycle

**Learning:** product scoping, architecture decisions, and breaking work into testable outcomes.

## Phase 1 — Identity and design system

- Create logo and application icon
- Select the light and dark palettes
- Define typography, spacing, radius, and motion tokens
- Configure Tamagui
- Build the first shared primitives
- Create reference versions of the Today screen for Android and macOS

**Learning:** design tokens, accessibility, component APIs, variants, and responsive composition.

## Phase 2 — Backend foundation

- Scaffold the NestJS API
- Configure PostgreSQL and Drizzle
- Add migrations and seed data
- Define error and validation formats
- Generate a typed API client
- Add unit and integration testing
- Add authentication

**Learning:** HTTP, REST, dependency injection, relational modeling, migrations, validation, authentication, and testing.

## Phase 3 — Today, routines, and tasks

- Create and edit recurring routines
- Generate daily routine occurrences
- Create tasks, priorities, and deadlines
- Build the Today experience
- Add daily completion
- Add basic Android notifications

**Usable outcome:** Done can guide and record an ordinary day.

## Phase 4 — College workspace

- Manage subjects
- Record class schedules and assessments
- Track topics and confidence
- Record study sessions
- Build a review queue
- Connect tasks and notes to subjects

**Usable outcome:** Done can organize current college work and suggest the next study action.

## Phase 5 — Notes

- Add a full desktop editor
- Add mobile quick capture and reading
- Implement autosave
- Add organization and search
- Link notes, tasks, subjects, and study sessions

**Usable outcome:** class notes become organized, searchable, and actionable.

## Phase 6 — AI assistance

- Clean up rough notes
- Summarize notes
- Extract tasks and dates
- Generate recall questions
- Explain selected text
- Suggest weekly study plans
- Add streaming and usage controls

**Learning:** structured outputs, streaming, prompt evaluation, server-side secrets, and background processing.

## Phase 7 — Offline support

- Persist drafts locally
- Cache the Today experience
- Queue offline completions
- Introduce SQLite
- Add background synchronization
- Resolve editing conflicts

**Learning:** local-first architecture, synchronization, idempotency, and conflict resolution.

## Working rules

- Keep no more than two items in progress.
- A large issue must be divided before implementation.
- Each implementation issue identifies a product outcome and a learning goal.
- Build one complete vertical slice before expanding horizontally.
- Review the backlog and technical debt weekly.
