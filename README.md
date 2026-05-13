# Founder OS Adoption Kit

A no-code starter kit for early-stage founders who want cleaner revenue follow-up, weekly reviews, onboarding visibility, hiring decisions, and investor updates without setting up code or automation first.

## The founder problem

Early-stage founders often know something is broken, but the next step is unclear. Deals are stuck, weekly reviews are messy, customers are slow to activate, hiring decisions sit in memory, and investor updates take too long to assemble.

The hard part is not adopting another tool. The hard part is turning one current operating problem into a simple input, a clear prompt, a founder-ready output, and one action to run this week.

## What this kit does

This kit gives non-technical founders a manual front door into the Founder OS ecosystem.

- Pick one current operating problem.
- Copy the matching CSV or Google Sheets-style template.
- Use sample data first.
- Replace sample data with company context in a private copy.
- Paste the table into the founder prompt.
- Generate a concise founder-ready output.
- Run the next action in your next review.

No code is required for the first version. Use Google Sheets, Google Docs, Notion, or CSV templates first. Automate later only after the manual workflow is useful.

## Start here

If you are new, start here:

1. Start with [Founder OS Lite](docs/founder-os-lite.md).
2. Pick one kit.
3. Use sample data first.
4. Replace the sample data with your company context in a private copy.
5. Do not adopt the full Founder OS on day one.

Open [START-HERE.md](START-HERE.md) if you want the shortest path.

## Pick your current problem

| Founder problem | Start with this kit | Time needed | Output |
| --- | --- | ---: | --- |
| Deals are stuck or follow-ups are slipping | [Revenue Rescue Kit](starter-kits/revenue-rescue-kit/README.md) | 10 min | Stuck deal action plan |
| Weekly review is messy | [Weekly Review Kit](starter-kits/weekly-review-kit/README.md) | 15 min | Founder weekly operating review |
| Investor update is due | [Investor Update Kit](starter-kits/investor-update-kit/README.md) | 20 min | Investor update draft |
| Customers are not activating | [Onboarding Risk Kit](starter-kits/onboarding-risk-kit/README.md) | 15 min | Customer risk memo |
| Hiring pipeline is stuck | [Hiring Bottleneck Kit](starter-kits/hiring-bottleneck-kit/README.md) | 15 min | Hiring bottleneck memo |

Use [founder-problem-picker.md](founder-problem-picker.md) if you are unsure which kit to open.

## Founder OS Lite

Founder OS Lite is the starter stack for founders who want value in one week:

1. [Revenue Rescue Kit](starter-kits/revenue-rescue-kit/README.md)
2. [Weekly Review Kit](starter-kits/weekly-review-kit/README.md)
3. [Investor Update Kit](starter-kits/investor-update-kit/README.md)

Read [docs/founder-os-lite.md](docs/founder-os-lite.md) for the weekly cadence.

## No-code path

The default path is manual and no-code:

1. Copy a template into Google Sheets, Notion, or a private CSV.
2. Fill 5 to 10 rows.
3. Paste the table into the kit prompt.
4. Use the sample output format.
5. Review the decision and assign the next action.

Read [no-code-adoption-path.md](no-code-adoption-path.md) for the three adoption levels.

## Advanced automation path

The n8n Founder Ops Command Router is the advanced automation layer. It is useful after a founder has validated the manual workflow.

Advanced teams can later connect business signals, GitHub module context, founder action generation, MySQL logging, and processed-signal updates. Do not make automation the first call to action.

Read [advanced-automation-path.md](advanced-automation-path.md) and [docs/how-this-connects-to-n8n.md](docs/how-this-connects-to-n8n.md).

## What you get in 10 minutes

- A current operating problem selected.
- A simple input template copied.
- A small sample table filled.
- A founder prompt ready to paste into ChatGPT, Gemini, Claude, or another assistant.
- A sample output format to follow.
- A next action that can be assigned in the next founder review.

## Starter kits

| Kit | Use when | First file to open |
| --- | --- | --- |
| [Revenue Rescue Kit](starter-kits/revenue-rescue-kit/README.md) | Deals are stuck or follow-ups are slipping | [ten-minute-setup.md](starter-kits/revenue-rescue-kit/ten-minute-setup.md) |
| [Weekly Review Kit](starter-kits/weekly-review-kit/README.md) | Weekly leadership review is messy | [ten-minute-setup.md](starter-kits/weekly-review-kit/ten-minute-setup.md) |
| [Investor Update Kit](starter-kits/investor-update-kit/README.md) | Investor update is due soon | [ten-minute-setup.md](starter-kits/investor-update-kit/ten-minute-setup.md) |
| [Onboarding Risk Kit](starter-kits/onboarding-risk-kit/README.md) | Customers are not activating | [ten-minute-setup.md](starter-kits/onboarding-risk-kit/ten-minute-setup.md) |
| [Hiring Bottleneck Kit](starter-kits/hiring-bottleneck-kit/README.md) | Hiring pipeline is slow or unclear | [ten-minute-setup.md](starter-kits/hiring-bottleneck-kit/ten-minute-setup.md) |

## How this connects to the rest of Founder OS

This repo is the non-technical adoption layer. The deeper repos are optional modules for founders and operators who want more structure later.

- [founder-os](https://github.com/shubham1502-hue/founder-os): umbrella operating system map
- [founder-os-revenue-engine](https://github.com/shubham1502-hue/founder-os-revenue-engine): deeper revenue leakage module
- [founder-weekly-operating-review-agent](https://github.com/shubham1502-hue/founder-weekly-operating-review-agent): deeper weekly review module
- [board-pack-investor-update-agent](https://github.com/shubham1502-hue/board-pack-investor-update-agent): deeper board and investor update module
- [founder-customer-onboarding-os](https://github.com/shubham1502-hue/founder-customer-onboarding-os): deeper onboarding and activation module
- [founder-hiring-talent-pipeline-os](https://github.com/shubham1502-hue/founder-hiring-talent-pipeline-os): deeper hiring and talent pipeline module
- [founder-ai-workflow-roi-os](https://github.com/shubham1502-hue/founder-ai-workflow-roi-os): AI workflow ROI and hire-vs-automate decisions
- [revops-infrastructure-playbook](https://github.com/shubham1502-hue/revops-infrastructure-playbook): CRM and RevOps operating design
- [startup-metrics-playbook](https://github.com/shubham1502-hue/startup-metrics-playbook): metrics definitions and operating interpretation

Read [docs/how-this-connects-to-the-founder-os-repos.md](docs/how-this-connects-to-the-founder-os-repos.md) for the full map.

## How this connects to n8n

Manual first. Automate later.

The n8n Founder Ops Command Router is the advanced automation layer for teams that already know which business signals matter, what output format they trust, and what action log they want.

Progression:

Manual kit -> Google Sheet -> Prompt output -> n8n workflow -> MySQL log -> automated founder digest

## Data privacy

Use synthetic examples in public repos. Do not put customer, prospect, employee, investor, borrower, merchant, payment, or internal company data into public forks.

Use private copies for real company work. Remove emails, phone numbers, CRM IDs, customer names, financial details, and private deal notes unless they are fully anonymized.

Read [data-privacy-note.md](data-privacy-note.md) before using real data.

## Who this is for

- Non-technical early-stage founders
- Founder office operators
- BizOps operators
- RevOps operators
- Startup generalists
- Hiring managers reviewing this portfolio

## Who this is not for

- Teams looking for a production data pipeline on day one
- Teams that want to connect live private company systems before validating the decision workflow
- Anyone planning to store private company data in a public repo
- Founders who want the full Founder OS before proving one manual workflow is useful

## Built by

Built by [Shubham Singh](https://github.com/shubham1502-hue), a Founder Office, RevOps, and startup operator focused on founder-facing operating systems for early-stage startups.
