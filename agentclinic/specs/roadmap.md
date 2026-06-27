# AgentClinic Roadmap

The roadmap is MVP-first, but each phase should stay small enough to implement, review, and verify quickly.

## Phase 1: Constitution And Domain Shape

- Create the specs directory.
- Capture mission, stack, and roadmap.
- Define the first domain vocabulary: agent, ailment, therapy, appointment, staff dashboard.

Done when the project has written product direction and a shared vocabulary for implementation.

## Phase 2: Core Types

- Add TypeScript types for agents.
- Add TypeScript types for ailments.
- Add TypeScript types for therapies.
- Add TypeScript types for appointments.
- Add a small sample dataset.

Done when the code can represent the core clinic concepts without a UI.

## Phase 3: Clinic Queries

- List agents.
- View one agent with ailments.
- List therapies.
- List appointments.
- Keep query logic separate from presentation.

Done when the clinic data can be read through simple functions.

## Phase 4: Appointment MVP

- Create an appointment for an agent.
- Associate the appointment with a therapy.
- Store appointment status.
- Validate required appointment fields.

Done when the project can model the core booking workflow.

## Phase 5: Minimal Interface

- Add the smallest interface needed to exercise the MVP workflow.
- Prefer a simple HTTP or CLI surface before committing to a full frontend.
- Show agents, ailments, therapies, and appointments.
- Support creating an appointment.

Done when a user can try the MVP flow end to end.

## Phase 6: Dashboard Foundation

- Add a staff-oriented dashboard view.
- Highlight agents needing attention.
- Show upcoming appointments.
- Make the primary workflow easy to scan.

Done when staff can see the clinic state quickly.

## Phase 7: Browser Polish

- Improve layout for modern browsers.
- Add clear navigation.
- Add empty, loading, and error states.
- Refine the visual style so the site feels attractive and purposeful.

Done when the experience satisfies the marketing need without weakening the workflow.

## Phase 8: Reliability Pass

- Add focused tests around domain logic.
- Add build verification to the standard workflow.
- Document local development commands.
- Review dependency choices before expanding the stack.

Done when the MVP has a dependable development baseline.
