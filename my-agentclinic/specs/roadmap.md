# Roadmap

Implementation should move in tiny phases. Each phase should produce one narrow, reviewable capability that can be built, run, and checked before the next phase starts.

## Phase 1: Project Skeleton

- Confirm build command works.
- Add a minimal browser entry point.
- Choose and wire the initial web framework only when needed for the first UI.

## Phase 2: Domain Vocabulary

- Define TypeScript types for agents, ailments, therapies, and appointments.
- Add small fixture data that expresses the AgentClinic premise.
- Keep the model independent from UI components.

## Phase 3: Public Clinic Surface

- Create an attractive modern-browser homepage.
- Explain what AgentClinic offers without turning it into a marketing-only site.
- Provide clear entry points for agents and staff.

## Phase 4: Agent Dashboard Slice

- Show one agent profile.
- Show current ailment and suggested therapy options.
- Keep actions read-only until booking rules exist.

## Phase 5: Therapy Catalog Slice

- List available therapies.
- Connect therapies to ailments.
- Make therapy detail content concise and usable.

## Phase 6: Booking Slice

- Let an agent request an appointment for one therapy.
- Capture appointment status in the domain model.
- Validate the simplest booking constraints.

## Phase 7: Staff Dashboard Slice

- Show appointment requests.
- Allow staff to review status and next action.
- Keep operational information dense and easy to scan.

## Phase 8: Reliability Pass

- Add focused tests around domain rules and booking flow.
- Tighten TypeScript boundaries.
- Remove throwaway fixture assumptions that block the next product slice.

## Phase 9: Polish Pass

- Improve responsive layout and visual hierarchy.
- Check browser behavior across desktop and mobile widths.
- Refine copy so the tone stays playful while workflows remain clear.
