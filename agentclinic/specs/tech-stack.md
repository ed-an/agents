# AgentClinic Tech Stack

AgentClinic starts as a minimal Node and TypeScript project.

This keeps the codebase small while preserving the engineering stakeholder's requirement that the project use a popular TypeScript foundation. The stack should grow only when a product phase needs it.

## Current Baseline

- Runtime: Node.js
- Language: TypeScript
- Package manager: npm
- Build command: `npm run build`
- Compiler: `tsc`
- Source entry point: `src/index.ts`

## Near-Term Direction

The project should remain framework-light until the MVP workflow is clearer. The next technical decisions should be made in this order:

1. Define core domain types for agents, ailments, therapies, and appointments.
2. Add a small data access boundary using in-memory or file-backed data.
3. Add an HTTP interface only when the dashboard or browser experience needs it.
4. Add a browser UI framework after the core workflows are proven.

## Selection Criteria

Any new dependency should be:

- Common in the TypeScript ecosystem.
- Easy to build and test locally.
- Suitable for modern browser support when frontend work begins.
- Small enough to justify its maintenance cost.
- Compatible with a reliable dashboard experience for agents and staff.

## Deferred Decisions

These choices are intentionally not locked yet:

- Web framework.
- Frontend framework.
- Database.
- Authentication.
- Deployment platform.
- Styling system.

They should be chosen when the roadmap reaches the phase where each decision becomes necessary.
