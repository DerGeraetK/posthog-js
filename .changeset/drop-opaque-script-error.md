---
'posthog-js': patch
---

fix(error-tracking): do not autocapture the opaque cross-origin "Script error." from `window.onerror`, because it has no stack, source, or position to act on
