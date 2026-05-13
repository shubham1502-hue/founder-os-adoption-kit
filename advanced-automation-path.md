# Advanced Automation Path

The advanced path is for teams that already know the manual workflow works.

Advanced users can later adopt:

- Founder Ops Command Router
- n8n
- MySQL
- GitHub README-backed module routing

Validated workflow shape:

```text
Business signal
-> classify signal
-> match to GitHub module
-> fetch README context
-> generate founder action
-> log action
-> mark signal processed
```

This is not the starting point for non-technical founders. Start manually, prove the output is useful, and then automate repeated work.

## Implementation notes

- Do not include private credentials.
- Do not include real passwords.
- Do not commit `.env` files.
- Any workflow export should use `.env.example` and sanitized JSON.
- Use synthetic signals in public repos.
- Keep customer, employee, investor, prospect, payment, and internal company data in private systems.

## When to automate

Automate only when:

- the same signal appears every week
- the founder trusts the output format
- owners act on the recommendations
- manual copy-paste is becoming the bottleneck
- the team knows what should be logged
