## Prompt guide

- state your reasons
- say **no**!

## Reasons

prompt:

```txt
Refactor all usages of `Optional<TYPE>` arguments
in parameter lists to `@Nullable TYPE`
```

---

better:

```txt
Refactor all usages of `Optional<TYPE>` arguments
in parameter lists to `@Nullable TYPE`,
such that devs get warned by nullness checks
and the code is more performant.
```

- higher probability that agent checks:
  - is nullness checking even configured correctly
  - is the perf gain even real
  - is documentation about this existent and up to date

## No Man

- you must push back
- llms are trained to be sicophantic and nice
- when presented with multiple options
  → **negate** what you do not want
