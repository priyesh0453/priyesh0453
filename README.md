# Priyesh Mishra

I build software that has to keep working: real-time products, the systems beneath them, and the tooling engineers use to change them safely. Software engineer at Eltropy. BITS Pilani.

I have almost always been the most junior engineer in the room, or close to it. The work rarely was. What I get pulled in for is trust and connecting the dots: the problem that crosses systems and teams and needs one person to hold all of it.

Most of my best work starts without a ticket. I find what is wrong, trace it to the root cause, fix it properly, and write it down so everyone stays in the loop.

## At work

Since July 2024, on a communications platform used by credit unions:

- Front-end product surfaces built: a native email channel inside a text-first inbox, a third-party email campaigns integration, rich messaging with cards and carousels, campaign list and template management, the agent inbox, a phone dialer built from scratch, and member-data and consent controls.
- Reliability: the real-time video domain, with HD video on all 32 observed calls, an audio fallback when a camera hangs, and a class of call failures that had no recorded cause, now classified in logs; a real-time operations dashboard; 10 applications that no longer knock each other offline.
- Security: a legacy unsafe code path removed from 10 entry points, and one library upgrade covering 7 known vulnerabilities.
- Escalations: traced to root cause across service and team boundaries, closed in 1-2 days instead of 5.
- Quality and platform: unit testing taken from 2 applications to 8, the Node upgrade of 8 legacy applications and the React upgrade of 5 authored, the first now in production, and accessibility remediation.
- Beyond the browser: Windows desktop and kiosk clients in Rust, and a component design system with its Flutter port.
- Review and writing: 470 pull requests reviewed across 6 codebases, 427 of them other engineers'; when measured, 3 in 4 of my comments caught a real defect. 2,000+ tests, 139 design and root-cause documents, 12+ engineering interviews.

## Building

- [weekly-update](https://github.com/priyesh0453/weekly-update): keeps a Mac and the apps in its Dock current, once a week, without surprising you. One bash script, needing nothing beyond macOS and Homebrew. Every question defaults to No, and the unattended path is narrower than the interactive one. 1,804 checks pass.
- [stack-up](https://github.com/priyesh0453/stack-up): one command that brings a local dev stack up in the order you declare, proves each piece is really up, and names who should fix what failed. 1,506 checks pass.
- A fintech product, in progress.

Both tools are MIT-licensed reference designs, meant to be copied and changed. Both were AI-assisted throughout: I set the design and the safety rules, reviewed the code and ran the tests. Fast drafts, slow trust.

## How I work

- Root cause over symptom. Delete the vulnerability rather than patch around it.
- Tests, observability and written reasoning ship with the change, not after it.
- Surface mistakes early. In week one a wrong turn is a lesson; in month four it is an incident.
- Every review should teach, not just block.
- Languages are the easy part. Judgment in system design is what compounds.

## Where I am most useful

System design, software architecture, front-end architecture, reliability, application security, agentic AI, AI-native engineering, TypeScript, React, Rust, fintech.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/priyesh-mishra-bits/), for the full record. Outside work: algorithmic trading, low-latency systems and macroeconomics.
