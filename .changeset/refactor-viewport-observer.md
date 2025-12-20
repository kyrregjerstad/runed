---
"runed": patch
---

Refactor `IsInViewport` to expose the underlying observer directly via an `observer` property
Added a `once` option to `useIntersectionObserver` to automatically stop observing after the first intersection.
