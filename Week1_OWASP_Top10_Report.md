# OWASP Top 10 Research — Vortex Tech Cyber Security Internship (Week 1)

## Project Overview
This repository contains my Week 1 submission for the Vortex Tech Cyber Security Internship Track. The task was to research five vulnerabilities from the OWASP Top 10 (2021) and document them in a way that explains what each one is, how it's exploited, a real-world case where it caused harm, and how developers can prevent it.

This is a research/documentation deliverable — no code or live testing was required this week. The goal was to build a solid theoretical foundation before moving into hands-on testing in later weeks.

## Objectives
- Understand five OWASP Top 10 (2021) vulnerability categories in depth, beyond memorized definitions.
- Practice explaining technical security concepts in plain, accessible language.
- Study real, well-documented breaches to connect theory with actual impact.
- Build the habit of publishing internship work to a public GitHub portfolio.

## Vulnerabilities Covered
| Vulnerability | OWASP 2021 Category | Real-World Case Studied |
|---|---|---|
| SQL Injection | A03:2021 – Injection | TalkTalk (2015) |
| Broken Access Control | A01:2021 – Broken Access Control | Optus (2022) |
| Cryptographic Failures | A02:2021 – Cryptographic Failures | Adobe (2013) |
| Security Misconfiguration | A05:2021 – Security Misconfiguration | Capital One (2019) |
| Identification and Authentication Failures | A07:2021 – Auth Failures | 23andMe (2023) |

Full write-ups, including attack scenarios, prevention strategies, and severity ratings, are in [`docs/OWASP-Top10-Research-Report.md`](docs/OWASP-Top10-Research-Report.md).

## Learning Outcomes
- Learned to distinguish between related-but-different concepts, like encryption vs. hashing, and authentication vs. authorization.
- Gained a clearer picture of how a single logic gap (e.g., a missing ownership check) can scale into a breach affecting millions of records.
- Practiced researching primary sources (regulator reports, official breach disclosures) rather than relying on secondhand summaries.
- Started thinking about security as an ongoing operational discipline (config audits, permission reviews) rather than a one-time code fix.

## Repository Structure
```
vortextech-cybersec-week1/
├── README.md                              # This file
├── docs/
│   └── OWASP-Top10-Research-Report.md     # Full research report (main deliverable)
└── screenshots/                           # (Reserved for future weeks' hands-on evidence)
```

## Technologies / Resources Used
- [OWASP Top 10:2021](https://owasp.org/www-project-top-ten/) — primary reference standard
- Public breach disclosures and regulator reports (ICO UK, OAIC Australia, DOJ US, company statements)
- Markdown for documentation formatting

## Disclaimer
This repository is submitted as part of the Vortex Tech Cyber Security Internship Program (2026) and is for educational and portfolio purposes only. All real-world case studies referenced are based on publicly available information; no proprietary, confidential, or unpublished data is included. This week's task involved research and documentation only — no systems were accessed or tested.

## Author
[Your Name]
Cyber Security Intern — Vortex Tech Internship Program, 2026
[Your LinkedIn / GitHub profile link]
