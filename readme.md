# Youssef Ahrour

Backend developer building reliable services. Software Engineering student at 1337 (42 Network), where I work on systems programming and backend development.

I care about the parts that are easy to get wrong: concurrency, correctness, and what happens when things fail.

---

## Currently building

A **PostgreSQL backup and restore service** that makes restores safe, which is where most backup setups fall over: each backup is test-restored before it's kept, and the restore only swaps a database into place once its replacement has restored successfully, so a failure never touches live data. Optional age encryption and AWS S3 replication, proven by an end-to-end test suite in CI.

---

## Skills & Tools

**Languages:** TypeScript · Go · SQL · C/C++ · Bash

**Frontend:** React · Next.js · Tailwind CSS · TanStack Query · Vite

**Backend:** Node.js · NestJS · Express · Gin · REST APIs · Authentication · Background Jobs

**Databases:** PostgreSQL · Prisma · SQLite · GORM

**Infrastructure:** Docker · Linux · AWS S3 · GitHub Actions

---

## Things I've built

**[Incident Lifecycle Manager](https://github.com/yahrour/incident-lifecycle-manager)** — a self-hosted on-call platform that turns raw alerts into tracked incidents: deduplication, on-call rotation, automatic escalation, and MTTA/MTTR metrics. Built by a team of four as a NestJS modular monolith with a feature-based React frontend, live updates over SSE. I was the technical lead and architect.

**[ReceiptFlow](https://github.com/yahrour/receipt-flow)** — an AI-powered receipt organizer that uses Google Gemini 2.5 Flash to extract merchant, date, and amount from photos, with cursor-based pagination and a ~98% tested service layer.

**[Uptime Monitor API](https://github.com/yahrour/uptime-monitor-api)** — a Go uptime monitoring API where each site runs in its own goroutine and reports to Healthchecks.io.

**[Digital Closet](https://github.com/yahrour/digital-closet)** — a digital wardrobe manager for organizing items and building outfits, with image storage and user-scoped data.

**[Tag-Based Email Manager](https://github.com/yahrour/tag-based-email-manager)** — a full-stack email tool with tag-based organization and search.

More on my [portfolio](https://yahrour.github.io/projects).

---

## Open Source

**Fixed an OAuth password-reset bug in a 100+ star project.** OAuth users were being routed into the wrong password-reset flow. Traced the split and patched it without breaking the existing paths. [Merged PR](https://github.com/nizzyabi/platform/pull/31)

---

## Find me here

[Portfolio](https://yahrour.github.io/) · [Email](mailto:youssefahrour.contact@gmail.com) · [GitHub](https://github.com/yahrour)

---

<p align="center">
  <a href="https://gitshine.com/stats/yahrour">
    <img src="https://gitshine.com/card/yahrour" alt="Youssef's GitHub stats" />
  </a>
</p>

<p align="center">
  <a href="https://github-stats-extended.vercel.app/api?username=yahrour&hide_title=true&show_icons=true&include_all_commits=true&theme=dark_github">
    <img src="https://github-stats-extended.vercel.app/api?username=yahrour&hide_title=true&show_icons=true&include_all_commits=true&theme=dark_github" alt="Youssef's GitHub stats" />
  </a>
</p>
