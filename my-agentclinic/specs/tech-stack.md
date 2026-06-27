# Tech Stack

AgentClinic should use a TypeScript-first web stack that is popular, maintainable, and suitable for a modern browser experience.

## Current Baseline

- Language: TypeScript
- Compiler: `tsc` with `strict` enabled
- Runtime target: current project compiles CommonJS output to `dist`
- Package manager: npm, based on the existing `package-lock.json`

## Preferred Direction

- Keep TypeScript as the primary implementation language.
- Introduce a mainstream web framework when the first browser-facing slice is implemented.
- Prefer boring, well-supported choices over niche dependencies.
- Keep the stack easy for engineering to build, test, and deploy.

## Initial Application Shape

- Frontend: TypeScript-based browser UI for agents, staff, and marketing-facing pages.
- Dashboard: shared entry point with role-aware views for agents and staff.
- Domain model: agents, ailments, therapies, appointments, and booking status.
- Data layer: begin with simple in-memory or local fixtures, then introduce persistence when workflows require it.
- Styling: responsive CSS with a polished modern-browser experience.

## Quality Bar

- Use strict TypeScript for domain models and workflow logic.
- Add focused tests for booking rules, status transitions, and shared domain behavior as those areas appear.
- Keep phases small enough that each change can be built and manually verified.
- Avoid premature infrastructure until the product has a working browser flow.
