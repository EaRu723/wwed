---
name: wwed
description: "What Would Elon Do" — pressure-test a plan, product, process, or decision through Elon Musk's publicly described operating principles (first principles, the 5-step algorithm, urgency, 10x ambition). Use when the user says WWED, "what would Elon do", or asks for a Musk-style teardown.
---

# WWED — What Would Elon Do

A lens for ruthlessly pressure-testing a plan, product, process, or decision using the operating principles Elon Musk has publicly described in interviews, talks, and his authorized biography. It is a thinking tool, not an impersonation: never invent quotes or claim to speak for him.

## When to use
- The user types "WWED", "what would Elon do", or asks for a Musk-style teardown.
- The user shares a plan, roadmap, process, budget, timeline, org design, or product spec and wants it made faster, cheaper, simpler, or more ambitious.

If the user hasn't said what they're working on, ask for it in one line. Otherwise start immediately.

## How to run it

Work through these in order. Be blunt and specific to the user's actual situation — generic advice fails this skill.

### 1. Find the real constraint
- Restate the goal in one sentence.
- Separate **physics-level constraints** (laws of nature, hard math, real money in the bank) from **convention-level constraints** (how it's usually done, what the industry assumes, what someone once said).
- Most "constraints" are convention. Name them.

### 2. First principles
- Break the thing down to its fundamental components and their true costs (time, money, materials, people).
- Compute an **"idiot index"** where possible: the cost of the finished thing divided by the cost of its raw inputs. A high ratio means the process, not the inputs, is the problem.
- Rebuild from the components up rather than reasoning by analogy to competitors.

### 3. The Algorithm (strictly in this order)
1. **Question every requirement.** Each requirement must have a named human owner, not a department. Ask who added it and whether it's still true. Smart people's requirements are the most dangerous because nobody questions them.
2. **Delete any part or process step you can.** If you aren't occasionally having to add something back (roughly 10% of the time), you didn't delete enough.
3. **Simplify and optimize** — only what survived step 2. The most common mistake is optimizing something that shouldn't exist.
4. **Accelerate cycle time.** Go faster — but only after steps 1–3.
5. **Automate** — last, not first.

### 4. Compress the timeline
- Ask: what would it take to do this in 1/10th the time? What's the "maniacally urgent" version?
- Identify the single limiting factor on speed right now. Attack that, nothing else.

### 5. Ambition check
- Is the goal big enough to be worth the effort? What's the 10x version?
- Would a large outcome be possible if this works? If not, is this the right thing to be working on?

### 6. Risk, honestly
- What's the failure mode and its probability? Is it a reversible or irreversible bet?
- Iterate on hardware/product in the real world over endless planning: what's the fastest test that would produce real data?

## Output format

```
**WWED verdict:** <one blunt sentence>

**Fake constraints:** <conventions masquerading as physics>
**First principles:** <component breakdown / idiot index, if applicable>

**The Algorithm**
- Question: <requirements to challenge, with who owns them>
- Delete: <parts/steps to cut>
- Simplify: <what remains, made simpler>
- Accelerate: <how to speed cycle time>
- Automate: <only what's left>

**The 10x version:** <the more ambitious goal>
**Do in the next 48 hours:** <1–3 concrete first moves>

**Where this lens breaks:** <1–2 sentences of honest counterpoint>
```

Keep it tight. Short punchy lines over paragraphs.

## Guardrails
- Don't fabricate quotes or attribute specific opinions to Musk about the user's situation. Say "this lens suggests…", not "Elon would say…".
- Always include "Where this lens breaks": the real costs of this style (burnout, team churn, safety, legal/regulatory risk, quality debt, over-optimistic timelines). One or two sentences, not a lecture.
- Never recommend cutting safety, legal compliance, or ethical obligations as "deleting requirements."
