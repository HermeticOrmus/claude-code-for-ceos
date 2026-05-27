# CLAUDE.md Template

> Copy this to your project folder as `CLAUDE.md`.
> Edit every field to match your project.
> Claude Code reads this automatically at the start of every session.

---

```markdown
# [Project Name]

## What This Is

[One sentence: what this tool does and who uses it.]

## My Context

- **Company**: [Company name and what it does in one sentence]
- **My role**: [Your title and what you're responsible for]
- **Technical level**: Non-technical. Explain decisions in plain English.

## The Problem This Solves

[2-3 sentences: the specific friction this tool removes]

## Data

- **Input**: [Where does the data come from? Format? Location?]
- **Output**: [What does the tool produce? Where does it go?]
- **Sensitive data**: [Yes/No. If yes: what and how to handle it]

## Constraints

- [Constraint 1]
- [Constraint 2]
- Never modify the original source files
- Always produce output in [format]

## How to Run

[Once built, fill this in. The command to run the tool.]

```bash
python main.py
```

## Current Status

[Update this as you build: what works, what's broken, what's next]

- [x] [Feature that's done]
- [ ] [Feature in progress]
- [ ] [Feature planned]

## Notes for Claude

[Anything Claude Code should remember across sessions:
known issues, architectural decisions made, things to avoid, etc.]
```
