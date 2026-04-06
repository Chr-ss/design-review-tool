## Backend
- Next.js app routing
- tRPC type-safe API routes
- Prisma db access with simple schema
- SQLite persistent local storage, Prisma handles connection

## Data
- model in `prisma/schema.prisma`
- seed data dev `prisma/seed.ts`
- import endpoint simple json `https://dummyjson.com`

## Infrastructure
- Docker + Docker Compose for local run/deployment parity
- T3-style setup for fast bootstrap and type safety
- Next.js + React + Tailwind for familiar, component-based UI development

## Quality & Tooling
- ESLint linting/style checks
- Storybook component development

## Frontend

### Pages
- Overview page
- Details page
- Comparison page (multi-option comparison)
- Add design flow (dialog from overview)

### Components

#### Atoms
- badge
- button
- image
- skeleton

#### Molecules
- data-block
- design-option-card
- tags

#### Organisms
- design-options-grid
- add-design-dialog
- import-design-dialog
- site-menu

### UX Notes
- loading skeletons for list/card states
- empty state when no options exist
- responsive layout
