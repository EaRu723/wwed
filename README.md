# WWED — What Would Elon Do

**A Claude skill that tears down your plan in Elon's voice, using his actual operating method.**

Type `WWED` plus whatever you're working on (a roadmap, a launch plan, a budget, a hiring plan, a product spec). Claude answers terse, blunt, in probabilities, with maniacal urgency, and runs your plan through the principles Musk has publicly described:

- **Fake vs. real constraints:** physics is the law, everything else is a recommendation
- **First principles + idiot index:** component costs vs. finished cost
- **The Algorithm, in strict order:** make requirements less dumb → delete → simplify → accelerate → automate
- **Limiting factor:** the one thing setting your speed
- **Build, fly, break, fix:** the smallest real test you can run this week
- **Vertical integration:** what to own vs. keep buying
- **Consolidate for scale:** what should merge
- **Long-horizon mission:** does this ladder up to something that matters? What's the 10x version?
- **Odds + 48-hour moves:** probabilities, not vibes

### Maximally truth-seeking, fair to the goat
- **Steelmans the method** with its real track record: reusable rockets, mass-market EVs, global satellite internet.
- **Names failure modes using Elon's own admissions first:** optimistic timelines, "production hell," over-automation.
- **Checks whether the analogy actually transfers** to your situation.
- **Judges the method, not the man.** No politics, no caricature, no worship, no dunking.
- **Quotes only verified public lines** and never invents new ones. It channels the voice without claiming to be him.

## Install

### Claude app (claude.ai / desktop / mobile)
1. Download [`wwed.zip`](../../releases) or zip the `wwed/` folder yourself
2. Go to **Settings → Capabilities → Skills** and upload the zip
3. In any chat: `WWED: <your plan>`

### Claude Code
```bash
git clone https://github.com/<you>/wwed.git
cp -r wwed/wwed ~/.claude/skills/
```

## Usage

```
WWED: we're planning a 6-month build for v2 of our app before launch
```

```
what would elon do about our hiring plan? [paste plan]
```

## Output shape

```
WWED verdict: <one blunt sentence>

Fake constraints: ...
First principles: ...

The Algorithm
- Make requirements less dumb: ...
- Delete: ...
- Simplify: ...
- Accelerate: ...
- Automate: ...

Limiting factor: ...
Timeline: ...
Ship & break: ...
Make vs. buy: ...
Consolidate: ...
Mission: ...
10x version: ...
Odds: ...

Next 48 hours: ...

Where this breaks: ...
```

## Guardrails
- No invented quotes, and it never claims to be Musk
- Safety, legal, and ethics are treated as physics, not "requirements to delete"
- Always names where the method breaks for your situation

## Contributing
PRs welcome: sharper prompts, better examples, other operator lenses.

## License
MIT. Not affiliated with or endorsed by Elon Musk, Tesla, SpaceX, or xAI.
