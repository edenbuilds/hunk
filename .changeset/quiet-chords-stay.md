---
"hunkdiff": patch
---

Reject key chords with an empty component, such as `s+` or `ctrl++s`, instead of binding them as `s` or `ctrl+s`. The literal `+` key and spaced chords like `ctrl + s` still work.
