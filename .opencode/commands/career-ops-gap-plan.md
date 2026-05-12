---
description: Compare evaluation reports to dream roles and cv.md; propose a gap-closing plan
---

Run career-ops **gap-plan** mode. User request and optional report paths or scope (e.g. "last 5 reports", specific file): $ARGUMENTS

Load the career-ops skill and pass **gap-plan** as the mode (same skill as other commands):

```
skill({ name: "career-ops" })
```

The agent must read `modes/gap-plan.md` and follow its output structure, using `config/profile.yml`, `cv.md`, and the requested `reports/*.md` files.
