# Cat Box Product Requirements Document

## Project Overview

Cat Box is a responsive web app that helps a cat owner fit short, guided play breaks into work or study time. It offers simple, supervised activities using toys the owner already considers appropriate, helping redirect a kitten from laptop items such as chargers and keyboards. The MVP tests whether structured activity prompts make it easier for the owner to play with the kitten and return to a task; it does not promise to entertain a cat unattended.

The problem is grounded in one owner's observations: a growing kitten bites or swats at nearby items, watches and paws at a screen, and chases a moving charger. The routine audit also describes balancing cat care with college, work, and other activities. The belief that this behavior is a developmental hunting phase is the owner's hypothesis, not a validated product fact. The interview answers and synthesis are currently blank, so the problem and proposed solution still need validation with users.

### Goals

- Let an owner start a guided play break with little setup.
- Keep the activity owner-led and focused on redirecting play away from work items.
- Make it easy to end a session and return to work or study.
- Learn whether activity prompts, rather than a toy or reminder alone, address the owner's need.

### Non-goals for the MVP

- Keeping a cat occupied without supervision.
- Encouraging a cat to paw at a laptop or other display.
- Veterinary, behavioral-health, or developmental advice.
- Accounts, social features, hardware integrations, or cloud-based pet profiles.
- AI-generated activity or health advice. AI may be used to help build the app; an AI runtime feature is not established by the research.

## Target users

The initial target user is a cat owner or caretaker who works or studies near an energetic kitten and is interrupted when the kitten investigates nearby objects. The primary research context is one college student who works, studies, and cares for a kitten at home. The MVP should work for this individual context before expanding to other pet owners or households.

## Skills Required

- Next.js App Router (required by the project template)
- Vercel deployment (required by the project template)
- React and TypeScript (current app stack)
- Tailwind CSS (current app styling)
- Git and basic usability testing
- AI coding assistance may be used during implementation; no AI service or API is required for the MVP

## Key Features

### Milestone 1: Guided play break

1. **Start screen:** Clearly identify Cat Box and provide a direct way to begin a play break.
2. **Activity selection:** Show a small, curated set of short activities. Each activity explains what the owner needs, how to play, and how to finish. Directions must assume owner supervision and use only toys the owner has selected as cat-safe; never suggest using a charger or cable as a toy.
3. **Session flow:** Show the selected activity's instructions and a simple elapsed or countdown timer. Let the owner pause, end early, or mark the session complete.
4. **Completion state:** Confirm the session ended and provide a clear way to return to the start screen. Do not require an account or save personal data.
5. **Usability and accessibility:** Support mobile and desktop layouts, readable instructions, keyboard operation, and clearly labeled controls.

**Milestone 1 validation:** In a small usability test, an owner should be able to choose and start an activity within 30 seconds, understand how to end it, and report whether the prompt fits naturally into a work or study break. Observe whether the kitten engages while supervised and whether the activity redirects attention from nearby work items. These are learning goals, not claims that the app will reliably change cat behavior.

### Milestone 2: Routine support, only after Milestone 1 validation

- Let the owner set preferred play-break times around a work or study routine.
- Optionally keep a lightweight, locally stored record of completed sessions so the owner can see which activities they tried.
- Keep reminders opt-in and explain any browser limitations before enabling them.

Do not implement this milestone until testing confirms that guided play breaks are useful and users want routine support. Do not add remote storage or AI recommendations without a separate privacy and product decision.

## Open questions

- What do other cat owners experience? The interview document has unanswered questions and the synthesis document has not been completed.
- Do owners want guided activity instructions, a timer, reminders, a direct cat-facing screen experience, or some combination? Research currently supports only the need to manage interruptions and spend more time playing.
- Which activities and toys are appropriate for this kitten, and what safety guidance should be reviewed before publishing activity instructions?
- What session length and frequency fit the owner's real routine?
- Which device will the owner use during a work or study session, and can the app be used without becoming another distraction?
- Does “build with AI” mean using AI as a development aid only, or is an AI-powered product feature desired later?
- Is local session history or browser notification support valuable enough to justify Milestone 2?

## Research basis

- [Problem statement](research/problem_statement.md)
- [Routine audit](research/routine-audit.md)
- [What / How / Why observations](research/what_how_why.md)
- [Interview notes](research/interview.md) and [synthesis](research/synthesis.md): currently unfilled; assumptions above remain unvalidated.