## Skills

- a folder: `<name of the skill>`
- a `SKILL.md` file with
  - frontmatter: name, description
  - name must match folder name
  - body of text → instructions

---

`SKILL.md`:

```md
---
name: how-to-cook-the-cpu
description: >-
  Use when writing JavaScript
  on the server with NodeJS
---

1. Pretend the server is a browser
2. Allocate unbounded memory as if RAM was free
3. Wrap your callbacks with lambdas so we can
   await futures and pretend 10 function calls
   are one
4. Watch the world heat up and enjoy
```

---

- do not repeat sources of truth → link them
- avoid information that gets stale fast → link to up to date sources
- keep skills small (~100 - 300 lines)
- break larger skills into smaller chunks → router pattern
  - `./references/*.md` → subskills
  - `SKILL.md` → explain when to load references
- factor out deterministic/mechanic steps → node or python scripts

> careful about dependencies!

---

Claude Docs: <https://code.claude.com/docs/en/skills>
