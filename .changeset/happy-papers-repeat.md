---
'@hono/inertia': minor
---

Shared props are combined with page props, with page props taking precedence when keys overlap. They are processed in the same way as props passed to `c.render()` and included in `PageProps` type inference. Their top-level keys are exposed through `sharedProps` page metadata.
