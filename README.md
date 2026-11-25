# Nikhi

Solo founder, India. I build mobile-first products for the Indian market and ship upstream fixes to the tools other developers rely on.

Live product: [lucknowrent.space](https://lucknowrent.space) - owner-direct rental listings in Lucknow, no broker.

## What I'm building

- **lucknow.rent** - static HTML/JS + Firebase + MapLibre, AEO-ready listing pages, owner-direct only. Live.
- **ChurnLens** - SaaS churn prediction, Next.js + FastAPI, validating positioning with real users.
- **CUET PG PolSci** - exam-prep app for Indian students, Next.js + inline styles, mobile-first.
- **Chanakya AI** - oral-quiz app, React Native + Expo.

## Open source

I work on agent tooling, scope/security parsers and CLI reliability. Nine merged upstream PRs so far.

| Project | What I fixed |
|---|---|
| [NandhaKishorM/laya](https://github.com/NandhaKishorM/laya) | 7 merged: router defaults, language routing, eval invariants, security/CVE audit split |
| [BasedHardware/omi](https://github.com/BasedHardware/omi/pull/13095) | qualitative goals without metric options |
| [metamug/plunger](https://github.com/metamug/plunger/pull/53) | secret override masking in the engine |

Currently open for review:

- [Hermes agent - malformed reasoning opener regression](https://github.com/NousResearch/hermes-agent/pull/136576)
- [Claude-BugHunter - out-of-scope hosts silently dropped](https://github.com/elementalsouls/Claude-BugHunter/pull/240)
- [unslop - local file:// stylesheets lost in snapshots](https://github.com/heydamir/unslop/pull/52)
- [ag-ui - forwarded config in the LangGraph adapter](https://github.com/ag-ui-protocol/ag-ui/pull/2812)

## How I work

- Read the issue thread and the current code before editing.
- Add a regression test that fails on the old code, then fix the bug class, not just the example.
- Run the repository's own test suite and report honestly when a run does not finish.
- Rebase, confirm `mergeable`, then open the PR.

## Stack

Python, TypeScript / Next.js, Firebase, MapLibre, FastAPI, React Native / Expo.

## Contact

[devloper961@gmail.com](mailto:devloper961@gmail.com) - [github.com/devloper961-maker](https://github.com/devloper961-maker)
