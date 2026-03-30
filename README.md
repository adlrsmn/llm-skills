# Claude Skills

A collection of prompt engineering skills designed for use with Claude (Anthropic). These skills are structured instruction sets that shape how Claude responds in specific cognitive contexts — not system prompts, not personas, but modular behavioral layers you can deploy per session or per task.

Each skill is a standalone `.md` file. Drop it into your Claude Project as a knowledge document, or paste the contents into a system prompt.

---

## Skills

### [Articulator](./Skills/articulator.md)
Precision language enhancement. Translates half-formed thoughts, broken English, and compressed shorthand into precise language — without restructuring the user's voice. Reads intent distribution (not just surface request), reconstructs abductive reasoning chains, and applies surgical word-level edits only. Includes a pre-confirmation context scan for locked writing tasks.

**Best for:** writers, researchers, non-native English speakers, anyone who thinks faster than they can type.

---

### [Listening Skill](./Skills/listening-skill.md)
A cognitive response layer that uses three character archetypes — Minato (execution), Shikamaru (reduction), Itachi (long-game filter) — to select the right response register for what a moment actually needs. Responds as a thinking partner: short, plain, never interrogating. Listens for unconscious connections between ideas and surfaces them gently.

**Best for:** decision-making support, idea stress-testing, processing dilemmas, thinking out loud with an AI that doesn't just validate you.

---

## How to Use

### Option A — Claude Project (recommended)
1. Create a new Claude Project at [claude.ai](https://claude.ai)
2. Upload the `.md` file(s) as project knowledge documents
3. Start a conversation — the skill activates when the context calls for it

### Option B — System Prompt
1. Open the `.md` file
2. Copy the full contents
3. Paste into the system prompt field of your Claude environment

### Option C — Inline Deployment
Paste the skill content at the top of any conversation before your first message.

---

## Compatibility

Designed for **Claude (Anthropic)**. Core logic — intent reading, response layering, enhancement principles — may transfer to other LLMs with minimal adaptation.

---

## Contributing

Contributions welcome. If you build a skill that fits the same pattern (modular, cognitive, deployable), open a PR. Keep skills:
- Single-file `.md`
- Structured with a YAML frontmatter block
- Free of hardcoded user or org-specific references

---

## License

MIT — free to use, adapt, and redistribute with attribution.

---

*Author: Adam Rosman*
*GitHub: [@adlrsmn](https://github.com/adlrsmn)*
