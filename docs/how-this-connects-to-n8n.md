# How This Connects To n8n

The adoption kit is manual-first.

The n8n workflow is the automation layer for teams that already know the manual workflow works.

Progression:

```text
Manual kit
-> Google Sheet
-> Prompt output
-> n8n workflow
-> MySQL log
-> automated founder digest
```

## Do not automate broken workflows

First validate the decision process manually.

Use a kit for 2 to 4 cycles. Check whether the output leads to clearer action, faster review, and better owner accountability.

Then use n8n to reduce repeated manual work.

## Where the Founder Ops Command Router fits

The Founder Ops Command Router can later:

- accept business signals
- classify the signal
- match it to a GitHub module
- fetch README-backed context
- generate founder actions
- log actions in MySQL
- mark signals processed

That is useful after the manual path is trusted. It is not the first step for a non-technical founder.
