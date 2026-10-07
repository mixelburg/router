---
'@tanstack/start-plugin-core': patch
---

Import protection: keep the parsed AST out of the cached analysis, so dev-server memory no longer scales with the size of every analysed module.
