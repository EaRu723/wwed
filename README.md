# WWED — What Would Elon Do

**A Claude skill that tears down your plan the way a first-principles operator would.**

Type `WWED` plus whatever you're working on (a roadmap, a launch plan, a budget, a hiring plan, a product spec) and Claude runs it through the operating principles Elon Musk has publicly described:

- **Fake vs. real constraints:** separates physics from convention
- **First principles:** breaks it down to component costs, including the "idiot index" (finished cost ÷ raw input cost)
- **The Algorithm, in strict order:** question every requirement → delete → simplify → accelerate → automate
- **Timeline compression:** what does the 10x-faster version look like?
- **Ambition check:** what's the 10x-bigger version?
- **48-hour moves:** 1–3 concrete things to do now
- **Where this lens breaks:** an honest counterpoint, so it's a tool and not a cult

It's a thinking lens, not an impersonation: it never fabricates quotes or claims to speak for Musk.

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
- Question: ...
- Delete: ...
- Simplify: ...
- Accelerate: ...
- Automate: ...

The 10x version: ...
Do in the next 48 hours: ...

Where this lens breaks: ...
```

## Guardrails
- No invented quotes or attributed opinions
- Never treats safety, legal, or ethical obligations as "requirements to delete"
- Always names the real costs of this operating style

## Contributing
PRs welcome: sharper prompts, better examples, other operator lenses.

## License
MIT. Not affiliated with or endorsed by Elon Musk, Tesla, SpaceX, or xAI.
