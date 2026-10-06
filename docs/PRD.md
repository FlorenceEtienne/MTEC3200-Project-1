# Cat Box Product Requirements Document

## Project Overview

Cat Box is a responsive web app designed to fit short, guided play breaks into a cat owner's work or study routine. It helps a user redirect an energetic kitten away from distracting items such as chargers, keyboards, laptops, and screens by offering simple, owner-led activities that are safe, short, and easy to understand.

The project exists to test whether structured play prompts help owners naturally pause, engage with their cat, and return to work without requiring a complicated setup or a dedicated toy system. The app does not aim to entertain a cat unattended; instead, it supports supervised play that can be used as a quick break.

### Goals

- Support a cat owner who needs a quick, low-friction way to redirect a kitten away from work distractions.
- Provide short, guided activities that are easy to start and stop.
- Keep the experience owner-led and appropriate for a supervised home environment.
- Validate whether guided activity prompts meaningfully help owners maintain a work or study rhythm.

### Non-goals for the MVP

- Keeping a cat occupied without supervision.
- Encouraging a cat to focus on the laptop or other screen.
- Providing behavioral, medical, or veterinary advice.
- Creating user accounts, social features, or cloud-based pet profiles.
- Requiring hardware integrations or remote storage.
- Offering AI-generated recommendations or diagnosis features in the product experience.

## Target users

The initial target user is a cat owner or caretaker who works or studies at home while living with an energetic kitten. This user often needs to pause briefly to redirect the cat away from nearby objects and then return to a task. The MVP is designed around a single-user, college-life context before expanding to broader pet-owner needs.

The app should work in a typical home environment where the owner might use a phone or tablet while the cat is nearby. The product should be tested in a stable setup with a scratchable or touchable surface that does not require special equipment.

## Skills Required

- Next.js App Router (required by the project template)
- Vercel deployment (required by the project template)
- React and TypeScript
- Tailwind CSS
- Git and basic UX testing
- AI coding assistance may be used during implementation, but no AI product feature is required for the MVP

## Key Features

### Milestone 1

1. Start screen
   - Show a clear Cat Box welcome screen with a direct action to begin a play break.
   - Keep the flow simple enough to use in under 30 seconds.

2. Activity selection
   - Offer a small set of short, supervised activities.
   - Each activity should explain what the owner needs, how to play, and how to end the activity.
   - Use only toys or materials the owner already considers cat-safe.
   - Avoid suggesting chargers, cables, or anything that could be dangerous or distracting.

3. Session flow
   - Display the selected activity instructions and show a timer.
   - Support pausing, ending early, and marking a session complete.
   - Keep the activity owner-led and easy to re-enter after a short break.

4. Completion state
   - Confirm the session ends clearly and provide a direct return to the start screen.
   - Do not require sign-in or account creation.

5. Usability and accessibility
   - Support mobile and desktop layouts.
   - Ensure text is readable, controls are clear, and keyboard navigation works.
   - Use labels that make the interaction understandable without extra instructions.

### Milestone 2

- Add optional routine support after Milestone 1 is validated.
- Let the owner set preferred play-break times around their work or study schedule.
- Offer a lightweight, locally stored history of completed sessions so owners can see which activities they tried.
- Keep reminders opt-in and clearly explain any browser limitations before enabling them.
- Do not implement these features until testing confirms the guided activity experience is useful and wanted.

## Open questions

The following questions are now addressed by the current product direction and research response:

- Device and setup: The app should initially work best on a phone or tablet in a stable, scratchable environment, with attention to how the device fits in the room and how it can be protected from scratches or movement.
- Engagement: The goal is to keep a cat engaged for a short period, and possibly longer, but not to promise continuous attention. The product should validate engagement rather than assume it.
- Play modes: The app should offer both automatic movement and touch-responsive interaction to create variety and help owners test which activity modes are enjoyable.
- Session length: The MVP should support 30-minute and 60-minute activity windows, with a 15-minute pause or check-in built into the flow. These durations should be tested for usefulness and safety.
- Scratching and overstimulation: The owner should be able to pause or stop the activity at any time. Dispensing is treated as a possible future hardware concept, not a current MVP requirement. The app cannot detect scratching or overstimulation automatically.
- Broader testing: Additional owners and cats of different ages, breeds, temperaments, and living environments should be tested before expanding the product substantially.

## Research basis

- [Problem statement](research/problem_statement.md)
- [Routine audit](research/routine-audit.md)
- [What / How / Why observations](research/what_how_why.md)
- [Interview notes](research/interview.md)
- [Synthesis](research/synthesis.md)