# GitHub Profile README — Style Guide

## Tone: Technical-Marketing

Write for developers who evaluate tools quickly. Every sentence should answer "what does this do and why should I care?" — not "how does it work internally."

### Rules

1. **Lead with capability, not implementation.** Say what the thing does, then how it does it — never the reverse. "Stream agent responses in real time via SSE" not "Uses SSE to send partial responses."

2. **Stack features with commas, not paragraphs.** When listing capabilities in a summary cell, chain them in a single sentence separated by commas. Each item is a noun-phrase or short clause. Example: "OIDC/RBAC security, row-level isolation, real-time streaming, plug-and-play backends."

3. **Use specifics over adjectives.** Name the protocols, formats, and tools — JWT, NDJSON, YAML, A2A, WebSocket. Don't say "secure" or "fast" without saying how.

4. **One paragraph per repo section intro.** The first paragraph under a `##` heading is a dense summary — what the project is, what it does, and one differentiator. No fluff sentence at the start.

5. **Bullet points are feature announcements.** Each `- ` line is one standalone capability. Start with the feature, then the detail. Keep each bullet to 1–2 sentences max.

6. **Parenthetical details for depth.** Use parentheses to add specifics without breaking sentence flow: "(SFT, RL, adapters)", "(JWT claims control CWD, tools, modes)".

7. **Dashes for inline separation.** Use ` - ` to separate a summary from its elaboration within a single bullet: "Data generation, fine-tuning, and evaluation - the full path from data to model to results."

8. **Tags after headings.** Repo headings use inline backtick tags to categorize: `` `Platform` `Tool` `Agent` ``. These signal scope at a glance.

9. **No filler.** No "This project is...", no "We built this because...", no "Getting started" sections. The README is a capabilities showcase, not a tutorial.

10. **Sentence structure pattern.** Prefer: `[What it does] — [how/why it matters]`. The em-dash or hyphen bridges the claim and the proof.

### Voice Checklist

- Confident, not hype-y — no "revolutionary", "blazing fast", "game-changing"
- Technical, not academic — write for practitioners, not paper reviewers
- Dense, not verbose — if a sentence doesn't add a new fact, cut it
- Specific, not vague — name the thing (protocol, format, tool, pattern)
