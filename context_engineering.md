## Context Engineering

- the context windows and attention spans of llms are too small
- we cannot put all project knowledge in at once and expect the llm to work
- careful structuring of knowledge/context → context engineering

---

single most important new skill in agentic coding!

## Progressive Disclosure

the harness loads `CLAUDE.md`/`AGENTS.md` files and `SKILL.md` files from different locations at different times.

---

- global: your home directory
  - `.claude/CLAUDE.md` or `.claude/skills/`
- project local
  - `./CLAUDE.md` or `./.claude/skills/`
- project subdirs:
  - `./module_a/CLAUDE.md`
  - `./module_b/CLAUDE.md`
  - `./module_a/.claude/skills`

---

> there are more! consult your harness docs
> <https://code.claude.com/docs/en/skills>

---

the goal is to provide minimum necessary context to agent to be effective

---

share with your team

what works: teach
what does not work: repair
