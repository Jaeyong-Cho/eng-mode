# Software Engineering Skill Set

This repository contains the [`eng-mode`](./SKILL.md) skill. It routes the current user request using the request, conversation context, and repository context, then follows a practical engineering chain:

```text
Situation → Principle → Action
```

- **Situation**: a recurring problem or challenging situation encountered in software engineering.
- **Principle**: a general approach or guiding rule for handling the situation effectively.
- **Action**: a concrete, observable practice that applies the principle.

## How to use it

1. The router extracts the goal, symptoms, context, constraints, and evidence.
2. It maps the request to the best matching situation.
3. It follows that situation's principle and concrete actions.
4. Add a situation when you encounter a recurring problem, then link its principle and actions.
5. After applying an action, record the result and refine the entry.

Keep each entry focused on one idea. Prefer observable language over abstract advice.

## Directory structure

- [`situation/`](./situation/) — recurring engineering problems
- [`principle/`](./principle/) — reusable decision rules
- [`action/`](./action/) — concrete practices and checklists

## Entry conventions

- Use lowercase kebab-case filenames.
- Give each entry a stable `ID` matching its filename.
- Link related entries with relative Markdown links.
- Add evidence, examples, or a short retrospective when possible.

## Routing rule

Route by the underlying recurring problem—not by the requested technology or artifact. If the evidence does not distinguish candidates, report low confidence and ask one focused question rather than inventing a match.
# eng-mode
