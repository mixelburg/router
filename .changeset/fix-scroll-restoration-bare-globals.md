---
"@tanstack/router-core": patch
---

fix(scroll-restoration): qualify bare browser globals with `window.` to prevent crashes in Node+jsdom environments
