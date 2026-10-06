## Choosing the Right Model

- typically providers have 3-4 models for different use cases
  - cheap and fast → generate text, short task, dumb
  - cheap and slow → reason about text, docs. still pretty dumb
  - expensive → day to day prompting and coding
  - **very expensive** and slow → flagship, very long tasks, dumb less often

---

- claude
  - haiku
  - sonnet
  - opus
  - fable

> (10.2026): do not use haiku right now. last update ~8 months ago. unusable.

---

- gpt
  - luna
  - terra
  - sol
  - astra

> (10.2026) do not use astra for very long tasks right now: its dumb too often

---

general rule of thumb: stick to day to day tier models on medium or high effort.
bump up or down on demand.

## On Permissions

different harnesses approach permissions and sandboxing differently

- pi: none
- codex: sanbox
- claude: complex, regex rules and modes

---

while learning and exploring: pick auto

---

```claude
/permissions
```

---

> at some point, you and your company have to decide upon a sandboxing and permission model, that you are comfortable with.
> but that is a significant engineering effort!
> understand the tooling first, then restrict it
