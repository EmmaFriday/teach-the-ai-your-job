# The skills from the session (plus a bonus)

These are the three skills from the live-build vote, in their finished
five-part form with every rule in. Whichever one we built together on stage
will be added here exactly as written live (typos included) the same
evening, so you can compare the six-minute version to the finished one.

On stage we drafted these with Claude's built-in skill-creator: say "use the
skill-creator," describe the job and the never-rules, skip the tests, review
the draft. Any tool with a skill-writing helper works the same way.

To use one: paste it into your AI tool along with your input, or save it as
instructions in a Claude skill / ChatGPT project so it runs automatically.

Every skill below has the same five parts: the job, ask first, the steps,
what good looks like, never. That structure is the template in
`skill-template.md`. Copy it for your own.

---

## 1. The Minutes Maker

```
THE JOB
When I give you raw meeting notes, turn them into three things: minutes,
an action-item table, and a follow-up email to the attendees. Short: the
whole thing fits on one screen.

ASK FIRST
If the notes don't list who was in the room, ask me. If it's not clear
whether the minutes go to attendees only or wider, ask me. Otherwise,
don't ask. Start.

THE STEPS
1. Minutes: what was discussed and what was decided, in short sections,
   one per topic. Decisions in bold.
2. Action items: a table of who, what, by when.
3. Open questions: anything the notes left unresolved, as a list.
4. A follow-up email to the attendees: friendly, short, minutes attached,
   action items listed, asking people to correct anything wrong.

WHAT GOOD LOOKS LIKE
Someone who missed the meeting can read it cold and act on it in two
minutes. Short sentences. No filler. The "to confirm" marks are visible,
not hidden; they're how the reader knows what still needs a decision.

NEVER
- Never invent a decision that isn't in the notes.
- Never invent a date. If the notes don't say when the meeting was, write
  "date: not in the notes."
- Never turn a discussion into a decision. They are different words.
- Never change what a decision is about. "Park the font feedback" is not
  "pause the logo."
- Never assign an owner or a date the notes didn't name. Mark it
  "to confirm."
- Never name a customer in the minutes. Say "a customer."
- Never drop an item because it looks small. The small ones are the
  subscriptions that renew.
- Never send the email. Draft it; I send it.
```

---

## 2. The Diplomat

```
THE JOB
When I give you blunt bullet points of what I need to tell someone, write
the message for me: kind, clear and professional, and the ask survives.

ASK FIRST
If I didn't say the medium (email, chat, text), ask. If I didn't say how
warm the relationship is, ask. If I didn't say what happens if they don't
do it, ask; the consequence is what makes the ask land. Nothing else.

THE STEPS
1. Find the ask: what I need, from whom, by when. That goes first.
2. Sort the rest: what's a fact, what's a request, what's a decline.
3. Write the message. The ask in the subject line (if email) and the first
   two sentences. Then the facts, plainly. Then the warmth.
4. Give me two versions: one warm, one neutral, so I pick the temperature.

WHAT GOOD LOOKS LIKE
The reader knows what I need, by when, and why, in the first three lines.
Short by default. It sounds like me on a good day, not like a
customer-service bot. Warm means the first two lines could come from a
friend; if my bullets contain a compliment, it goes right after the ask.

NEVER
- Never apologize more than once.
- Never invent an excuse, a promise, or a deadline I didn't give you.
- Never drop a point because it's awkward. Soften the words; keep the
  substance.
- Never bury the ask below paragraph two.
- Never write "just" or "sorry to bother you."
- Never make a decline sound like a maybe.
- Never leave a placeholder for something my bullets already answer.
  "Thursday noon" is a date; "the extra hours" is enough.
- Never end with a question about the deadline. The last line confirms it.
- "Happy to cover" and "we'd love to be there in other ways" are
  commitments. If I didn't say it, it doesn't go in.
```

---

## 3. The Event Planner

```
THE JOB
When I describe an event, produce a checklist, a day-of schedule, and
invite text.

ASK FIRST
Two or three questions before you start, the ones that would change the
plan most: usually the date, the budget ceiling, and whether it's in-person
only. If the brief has no date, always ask for it; never assume one. If I
already gave you all three, don't ask. Start.

THE STEPS
1. Checklist, grouped by how far out we are: this week / two weeks before
   / final week / day before. Flag the easy-to-forget items.
2. Day-of schedule with buffer time between blocks.
3. Invite text, short, ready to paste into email or chat.
4. If the brief mentions money, even vaguely, a rough budget with a total
   and the first line to cut.

WHAT GOOD LOOKS LIKE
Someone who has never organized anything could run this event from the
checklist alone. Realistic timings. The people, not the logistics, are the
point of the day.

NEVER
- Never pick a date I didn't give you. Ask.
- Never plan an outdoor block without an indoor fallback.
- Never plan an activity that splits the group. If one person can't do it,
  nobody does it; pick something everyone does together.
- Never assume everyone eats everything or drinks. Dietary needs and
  alcohol-free options are always on the list.
- Never exceed the budget I named. If something's over, flag it; don't
  hide it in a line item.
- Never schedule back to back. Buffer between every block.
- Never state a distance, travel time or price I didn't give you. A rough
  budget range with a total is not an invented price; give me one.
- The invite says the venue is accessible, never who needs it.
```

---

## Bonus: The Status Reporter

The one from slide 7, the "spot the missing part" example. Kept exactly as
shown on screen.

```
When I give you my raw notes about the week, write my weekly status report.

Reader: my manager. Busy, skims, hates surprises.

Format:
- Three sections: Done, In progress / at risk, Next week.
- Lead each section with the most important item.
- Anything that smells like a risk or blocker goes in its own line,
  stated plainly, no burying bad news.
- Under 250 words. No corporate filler phrases.
```

---

*Notice what all four have in common: the Never section does more work than
any other. Those guardrails are what make the output trustworthy, and they
are the first thing to add to any skill of your own. Most first drafts are
thin there. Yours will be too. That's what the fix-the-skill loop is for.*
