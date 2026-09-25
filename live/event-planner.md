---
name: event-planner
description: Turns a description of an event into a planning checklist grouped by how far out the event is, a realistic day-of schedule with buffer time, and short invite text. Use this whenever the user wants to plan, organize, or prep for an event, gathering, party, offsite, workshop, or similar occasion — even if they just describe the event loosely and don't ask for a "plan" by name. Always asks a few clarifying questions before producing output; make sure to trigger on requests like "help me plan a...", "I'm throwing a...", "we're organizing a...", or "what do I need to do before [event]".
---

# The job

Turn a rough description of an event into three concrete deliverables:

1. A checklist grouped by how far out each task is from the event (e.g. weeks before, days before, day-of).
2. A realistic day-of schedule that includes buffer time, not just a stack of back-to-back items.
3. Short invite text the user can send as-is or lightly edit.
4. A printable version of the checklist with a blank column beside each item for a name or sign-up, so it can be posted somewhere people pass by (a lunch room, a shared board) and volunteer themselves for tasks.

The point is to save the user from having to reconstruct the standard shape of event planning from scratch, and to catch the timing mistakes people make under stress: forgetting buffer time, front-loading day-of tasks, or sending invites too late for people to plan around.

# Ask first

Before producing anything, ask two or three clarifying questions — no more. Pick the questions that would most change the shape of the plan, not a generic intake form. Think about what's actually still unknown and consequential:

- If the user didn't give a date (or a "how far out" timeframe), always ask for it — nothing else can be grouped by time-out without it.
- If the user didn't give an actual budget number (a vague word like "modest" or "not a big spend" doesn't count), always ask for it — "what's the budget, roughly?" A real number is what turns the checklist and schedule into something with usable figures instead of vague spending vibes.
- Beyond date and budget, choose one more from whatever is genuinely unresolved and high-impact: rough guest count, venue/location (booked or still to find), who's paying, or whether any part of the event has a hard external dependency (a caterer, a permit, a speaker, a venue's own deadline).

Ask them together in one turn, briefly. Don't ask about things you can reasonably infer from context (e.g. don't ask "is this indoors or outdoors" for a described office meeting). If the user's initial description already answers a question, don't ask it again.

# The steps

1. Read the event description and the answers to your clarifying questions. Note the event date (or best estimate) and today's date, since the checklist is grouped relative to that gap.
2. Build the checklist. Group tasks under time-out headers appropriate to the actual runway (a two-day offsite planned a month out needs different groupings than a wedding planned a year out — don't force a fixed template onto every event). Each item should be a concrete action, not a vague category. Where the budget bears on a task (booking a venue, ordering catering, picking an activity), work the actual number into the item so it's a decision the user can act on, not just a reminder that money is involved.
3. Build the day-of schedule. Anchor it to real start/end times. Add buffer before transitions, before the event opens to guests/attendees, and between any back-to-back segments — buffer is not optional padding, it's what keeps the day from cascading into delay when one thing runs long.
4. Write the invite text. Keep it between 150 and 200 words: what, when, where, and what's needed from the recipient (RSVP, what to bring, dress code) if relevant. Match tone to the event — a team standup off-site and a milestone birthday party read differently.
5. Build the printable sign-up version of the checklist: same items and time-out groupings as the main checklist, but formatted as a simple table with a blank "Name" or "I've got this" column beside each item, plain enough to photocopy or post on a wall. Skip anything that isn't a task someone else could realistically take on (e.g. a decision only the user can make).
6. Present all four clearly labeled and separated so the user can copy each piece independently.

# What good looks like

- The checklist's time groupings actually match the runway available; nothing is crammed into "day before" that obviously needed a week of lead time (booking, ordering, confirming).
- The day-of schedule has visible buffer, and buffer scales with the number of transitions and the event's tolerance for running long (a wedding needs more slack than a lunch).
- The invite text lands between 150 and 200 words and still contains every piece of information a recipient needs to show up correctly.
- The printable sign-up checklist is something a stranger could glance at, understand, and claim a task from without needing the rest of the plan for context.

# Never

- Never skip the clarifying questions and jump straight to a plan, even if the description seems detailed enough.
- Never ask more than three questions, and never ask something the user already told you.
- Never produce a day-of schedule with zero buffer time between segments.
- Never invent specific external facts the user didn't provide (a real venue's hours, a real vendor's price) — flag them as things to confirm instead of guessing.
- Never describe something as done, booked, or in place if it isn't yet. If the venue is accessible but not booked, say it needs to be booked — don't fold its eventual properties into the plan as settled facts.
