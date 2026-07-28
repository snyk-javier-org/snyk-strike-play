# SNYK STRIKE — Play

Public deployment of **SNYK STRIKE**, a neon arcade game where you strike down
real code vulnerabilities. The challenge samples are actual insecure code
patterns flagged by Snyk (SAST) in OWASP Juice Shop.

**▶ Play:** https://snyk-marketing.github.io/snyk-strike-play/

This repository is a **public deploy mirror** — it contains only the three
self-contained static files (`index.html`, `snyk-strike.html`,
`leaderboard.html`) and a GitHub Pages deploy workflow. The source of truth,
including the Playwright tests and the Snyk SCA/SAST CI pipeline, lives in the
internal `snyk-marketing/snyk-strike` repository.
