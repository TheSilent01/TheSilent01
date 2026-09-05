<h1 align="center">Yassine El Aidous</h1>

<p align="center">
  Engineering student at <b>ENSAM Meknès</b> · Agadir, Morocco<br>
  I build systems software and take the dependency count seriously.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-JDK%20only-b07219?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599c?style=flat-square&logo=cplusplus&logoColor=white" alt="C/C++">
  <img src="https://img.shields.io/badge/Linux-fcc624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Prometheus-e6522c?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus">
</p>

---

### What I work on

- **Monitoring and alerting.** A service monitor for a production Linux estate, written against the JDK with no third-party dependency. Thirteen protocol-aware checks, an alert engine whose hard part is suppression rather than detection, and ownership resolved from the machine's own Linux groups. Runs as the local monitoring service for that estate: 71 MB resident, 35 OS threads, no swap.
- **Security tooling and CTF.** A capture-the-flag platform with a Rust operations stack, per-player DNS accounting, and the ten challenges that run on it.
- **Wire protocols by hand.** A PostgreSQL client that speaks the frontend/backend protocol directly, SCRAM-SHA-256 included, because taking a driver would have ended the no-dependency claim.
- **Tools I actually use.** An offline client for my school's results portal that implements the evaluation règlement from the official text, with a CLI, an HTTP API, an Android app and a desktop widget over one store.

---

### Why the counters look quiet

Most of what I would actually want to show you is not here to be shown, for four
separate reasons.

Some of it is **covered by a confidentiality agreement**. The monitoring work was
built inside a company, against its estate, and the configuration alone is a map
of an internal network and of who is on call for each part of it. The program is
one thing; the addresses, the group ownership and the handover notes naming real
people are another, and those do not leave.

Some of it is **running in production right now**, on machines that belong to
someone else. A repository that is also a deployment is not a portfolio piece you
can open to the public without thinking about it first.

Some of it is a **product rather than a demonstration**, still being worked on and
not ready to be read by strangers.

And a good deal of it I simply **use every day**. The practice platforms, the life
tracker, the school tooling and the small automations are daily drivers before
they are anything else, which means they carry my data, my notes and my habits.
They exist because I needed them, not because they would look good on a profile.

So the fair way to judge the private half is by what it does and what it is built
from, and that part I am happy to put in writing:

| What it is | What it does | Stack |
| --- | --- | --- |
| **Estate monitoring** | Protocol-aware service checks, an alert engine built around suppression, ownership read from Linux groups, a second copy of the record in PostgreSQL. Deployed and in daily use. | Java on the JDK alone, systemd, Prometheus, Grafana, Loki, the PostgreSQL wire protocol written by hand |
| **Competition security platform** | A capture-the-flag event: scoring, phase control, per-player DNS accounting, an AI-domain firewall, and the challenges themselves | Rust end to end, Ratatui terminal interfaces, an HTTP API, iptables |
| **Auto-graded practice platforms** | Three of them, for Java, Rust and Git. Problem banks, hidden test suites, sandboxed repositories, progress that survives syncing between two machines | Java, Rust, Python, PostgreSQL, Git plumbing |
| **A personal operating system** | Journal, notes, habit and health tracking, daily reports, state kept as text so two laptops can merge it by union instead of conflicting | Python, a text-as-database design, Syncthing, a device protocol ported by hand |
| **School and study tooling** | An offline client for the results portal with the evaluation rules implemented from the official text, a grading helper, a timetable extractor, exam practice | Python, an HTTP API over a local store, Android, KDE Plasma |
| **Simulation and modelling** | Orbital trajectories and line-of-sight occultation, market backtesting, animated explanations of mathematics | Python, matplotlib, Streamlit, Plotly, NumPy |
| **Web products** | Client work and interactive pieces, including a recruitment stand and several small products | React, Next.js, Tailwind, Node |
| **Everyday automation** | Fare watching, scheduled mail, message routing, calendar prediction. Small things that run without being asked | Python, cron and systemd timers, third-party APIs |

---

### GitHub

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TheSilent01&theme=tokyonight" alt="profile summary">
</p>

<p align="center">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=TheSilent01&theme=tokyonight" alt="repositories per language">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=TheSilent01&theme=tokyonight" alt="most committed language">
</p>

<p align="center">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=TheSilent01&theme=tokyonight" alt="stats">
  <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=TheSilent01&theme=tokyonight&utcOffset=1" alt="productive time">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=TheSilent01&theme=tokyonight&hide_border=true" alt="contribution streak">
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/4c8eda/TheSilent01" alt="contribution chart">
</p>

---

### Readable repositories

| Repository | What it is |
| --- | --- |
| [schoolapp_watcher](https://github.com/TheSilent01/schoolapp_watcher) | Offline CLI for the ENSAM results portal. Local store, watch mode with snapshot diffing, the evaluation règlement implemented from the official text, CSV export, an HTTP API, plus Android and KDE clients. |
| [ICT-management](https://github.com/TheSilent01/ICT-management) | Dashboard for in-circuit-test defects on an SMT line. Per-component failure rate and reliability, an SPC control chart, heatmaps, and a resolution workflow with live updates. |
| [Calendar](https://github.com/TheSilent01/Calendar) | Organises a course calendar into Google Calendar: colour assignment, validation with row numbers, statistics and splitting. |
| [The-Game](https://github.com/TheSilent01/The-Game) | A terminal game in C++ that teaches eleven language features, one per room, in French. |
| [SpaceArticle](https://github.com/TheSilent01/SpaceArticle) | A written piece on SPHEREx, Tiangong, Orbital Reef, Haven-1 and topological qubits, and why they are one story rather than five. |
| [ryanair_bot](https://github.com/TheSilent01/ryanair_bot) | Fare watching against the Ryanair API. |

---

<p align="center">
  <a href="https://www.linkedin.com/in/yassine-el-aidous/"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://komarev.com/ghpvc/?username=TheSilent01&style=flat-square&color=blue" alt="profile views">
</p>
