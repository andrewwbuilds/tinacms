---
"@tinacms/graphql": patch
---

`IsomorphicBridge.delete()` no longer throws `ERR_INVALID_ARG_TYPE` when it removes a file at the repository root or the last file under a top-level folder.
