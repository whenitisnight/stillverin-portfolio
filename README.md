# Stillverin

Rejection memory and rule rehearsal for commercial-cleaning billing workflows.

I am exploring a narrow operational problem: customer-specific rejection rules are easy to lose between invoice batches. The prototype records historical examples, keeps sourced rules versioned, rehearses draft rules and checks the next CSV batch before a person decides what to do.

| Read | Purpose |
| --- | --- |
| [Product scope](docs/status.md) | Implemented behavior and pilot boundaries |
| [Architecture](docs/architecture.md) | Deterministic checks, versioned rules and persistence |
| [Rule-publication decision](case-studies/rules-before-automation.md) | Why rehearsal precedes activation |
| [Verification scope](verification/checkpoint.md) | Existing checks and limitations |

This is an AI-assisted software prototype with deterministic business rules. It does not claim market validation, measured customer savings or automatic financial compliance. Source and operating material remain private.

[William Haggard](https://github.com/whenitisnight)
