# ⚡ /elon

**First-principles AI mentor for Claude Code.** Type `/elon` and get challenged by a mentor who thinks like Elon Musk — from physics up, with zero tolerance for bullshit.

Built from *The Book of Elon* by Eric Jorgenson.

---

## Install

```bash
git clone https://github.com/zh131312/elon-skill.git ~/.claude/skills/elon
cd ~/.claude/skills/elon && ./setup
```

That's it. Open Claude Code and type `/elon`.

### Project-scoped install

```bash
git clone https://github.com/zh131312/elon-skill.git
cd elon-skill && ./setup --local
```

This installs to `.claude/skills/elon/` in your current project instead of globally.

---

## What it does

`/elon` transforms Claude into a direct, first-principles mentor that:

- **Runs The Algorithm** on every problem you bring — Question → Delete → Simplify → Accelerate → Automate
- **Challenges your assumptions** before letting you build anything
- **Pushes for action** — no analysis paralysis, no safe answers
- **Applies to code** — deletes before adding, attacks bottlenecks, parallelizes work

### Example

```
You:   /elon
Elon:  What are you building and why does it matter?

You:   I'm adding a caching layer to speed up our API
Elon:  Stop. Why is the API slow? Have you profiled it?
       You might be optimizing something that shouldn't exist.
       Show me the actual bottleneck.
```

---

## What's inside

```
elon/
├── SKILL.md    ← The skill (what Claude reads)
├── setup       ← One-command installer
├── LICENSE
└── README.md
```

No dependencies. No build step. No runtime. Just a single `SKILL.md` that Claude loads when you type `/elon`.

---

## The Algorithm

The core framework, applied to every problem in order:

| Step | Action | Principle |
|------|--------|-----------|
| 1 | **Question requirements** | Your requirements are definitely dumb |
| 2 | **Delete** | The best part is no part |
| 3 | **Simplify** | Don't optimize what shouldn't exist |
| 4 | **Accelerate** | Only after simplifying |
| 5 | **Automate** | Last, never first |

---

## Compatibility

| Platform | Status |
|----------|--------|
| Claude Code | ✅ Full support |
| OpenClaw | ✅ Compatible |
| Any tool reading `~/.claude/skills/` | ✅ Works |

---

## Customize

Edit `SKILL.md` to:
- Add your industry context
- Adjust intensity
- Add new frameworks
- Focus on specific domains

---

## Uninstall

```bash
rm -rf ~/.claude/skills/elon
```

---

## License

MIT

---

*Based on "The Book of Elon" by Eric Jorgenson. All principles from Elon Musk's own words.*
