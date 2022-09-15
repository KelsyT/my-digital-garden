---
title: else tests execute when all other tests are false
---

`else` tests are a catchall statement. It matches any condition that wasn't matched by a specific [[if tests execute when true|if]] or [[elif tests execute when true in sequence|elif]] test, and that can sometimes include invalid or even malicious data. If you have a specific final condition you are testing for, consider using a final `elif` block and omit the `else` block. As a result