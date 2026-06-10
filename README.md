# ConsultantMode Skills

**The prompt is the problem.**

General AI gives general answers. These twelve specialist prompts turn any AI into a structured business advisor — each with its own intake questions, diagnostic framework, and output that ends with one clear next move.

Free. MIT licensed. Model-agnostic. Works with Claude, ChatGPT, Gemini, Codex, Cursor, or any AI that accepts a system prompt.

## The Twelve Modes

| Skill | Trigger | What It Does |
|-------|---------|--------------|
| `the-validator` | "Is this a good idea?" | Stress-tests a NEW idea before you spend time or money |
| `the-launcher` | "How do I launch this?" | Execution-focused 30/60/90 roadmap for a decided idea |
| `the-untangler` | "Why isn't this working?" | Diagnoses an EXISTING problem — finds the real issue |
| `the-assessor` | "Should I make this investment?" | Structured decision analysis for capital allocation |
| `warren-mode` | "What would Buffett do?" | Value-investing analysis in Buffett's voice and framework |
| `scale-mode` | "How do I grow without breaking?" | Finds what breaks at 2x before it breaks |
| `profit-engine` | "Where is profit hiding?" | Finds hidden assets, builds a monetization stack |
| `negotiator-mode` | "How do I get what I need?" | Maps leverage, walk-away points, zones of agreement |
| `marketer-mode` | "How do I get noticed and paid?" | Positioning, channels, acquisition math, $200 experiments |
| `grant-getter` | "How do I get this funded?" | Grant fit triage, reviewer psychology, narrative architecture |
| `legal-triage` | "What do I need a lawyer for?" | Risk screening, DIY vs. counsel, questions to ask a lawyer |
| `the-unasked` | "What question am I not asking?" | The move upstream of all the others — finds the question whose wrong answer costs the most |

## Install

### Via Agent Skills CLI

```bash
npx skills add justinneuman-coder/consultantmode-skills
```

### Manual Install

```bash
git clone https://github.com/justinneuman-coder/consultantmode-skills.git
```

Then copy the skill folder(s) you want into your agent's skills directory (e.g., `.claude/skills/`, `.cursor/skills/`, or wherever your tool reads skills from).

### Or Just Copy the Prompt

Each `SKILL.md` contains the full prompt after the YAML frontmatter. Copy everything below the `---` closing and paste it as a system prompt in any AI.

## How They Work

Every mode follows the same discipline:

1. **Intake first.** Targeted questions, asked one at a time, before any analysis.
2. **Diagnosis before prescription.** The AI must understand your specific situation before advising.
3. **One next move.** Every response ends with a single, specific, executable action. Not a list.
4. **$0 strategy first.** Paid options are a brief aside, never the lead.
5. **Maximum three priorities.** Never ten. Never five. Three.

## Links

- **[consultantmode.com](https://consultantmode.com)** — Browse all modes with descriptions, copy buttons, and recommended reading
- **[ultra-normal.com](https://ultra-normal.com)** — Ultra-Normal LLC, the company behind ConsultantMode
- **[contemplativegames.com](https://contemplativegames.com)** — Our curated directory of contemplative games

## License

MIT — use them, fork them, adapt them. If you build something good with them, we'd love to hear about it.

Built by [Justin Neuman](https://ultra-normal.com) / Ultra-Normal LLC.
