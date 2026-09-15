# Your first AI skill: fill-in-the-blanks template

A "skill" is a set of instructions you write once, in plain language, that
teaches an AI to do one of your recurring tasks *your way*. No code. If you
can write an email explaining a task to a new colleague, you can write a skill.

Copy the template, replace the brackets, delete what doesn't apply.

---

```
THE JOB
When I give you [raw notes / a draft / a request], produce
[the finished thing you want back], in one sentence.

ASK FIRST
Before starting, make sure you know: [audience, deadline, inputs
(whatever would change the result)]. Ask me if it's missing.

THE STEPS
- [How you actually do the task, in order]
- [Step two...]

WHAT GOOD LOOKS LIKE
[Tone, length, format. Who reads it and what they care about.
Paste an example if you have one.]

NEVER
[The no-go zones: never invent facts, never bury bad news...]
If something is missing or unclear, mark it "to confirm", do not guess.
```

---

## Where to put it

- **Claude (claude.ai or Claude Code):** save it as a skill / project instructions,
  it will be used automatically when the task comes up.
- **ChatGPT:** paste it into a Project's instructions or a custom GPT.
- **Copilot:** paste it at the start of a chat, or save as a prompt.

The concept is portable: you are not learning a tool, you are writing down
how you work. That document outlives any tool.

## The three rules that make skills good

1. **One task per skill.** "Handle my email" is a wish. "Turn meeting notes
   into minutes + action items + a follow-up draft" is a skill.
2. **Say what NOT to do.** The "never invent decisions" line does more work
   than any other line. Guardrails are what make the output trustworthy.
3. **Refine, don't restart.** First output mediocre? Don't write a new prompt,
   add one rule to the skill and run it again. You're editing a skill,
   and it gets better every week you use it.
