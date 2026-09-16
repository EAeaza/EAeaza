# Azamat Egamberdiev

I build the internal systems that commerce businesses run on — settlement reconciliation, tax and
e-invoicing, demand forecasting, warehouse control. Tashkent, Uzbekistan.

Most of it is operational software for live businesses, so the code is private. Each project has
a public page instead: the problem, how it works, how it is verified, and screenshots of the real
code running on synthetic data.

**Portfolio → [https://EAeaza.github.io/](https://EAeaza.github.io/)**

---

### [Marketplace Control Tower](https://github.com/EAeaza/marketplace-control-tower)
Pulls marketplace, tax, bank and 1C data into one database, reconciles the sources against each other, forecasts demand and answers questions over read-only SQL.
<br><sub>since Jun 2026, active · 709 commits · Python · SQLite</sub>

### [E-Invoice Stock Ledger](https://github.com/EAeaza/einvoice-stock-ledger)
Rebuilds a wholesaler's item-level stock from its e-invoices on top of a 1C opening balance, traces every amount to a source line, and routes judgment calls to people.
<br><sub>since Jul 2026, active · 245 commits · JavaScript (Node.js) · Python</sub>

### [Reklama Radar](https://github.com/EAeaza/reklama-radar)
Works out which advertisers ran on a roadside LED screen from a two-minute phone video — built on a parallel experiment harness where most results were honestly negative.
<br><sub>Aug 2026 · 173 commits · Python · TypeScript</sub>

### [GrantPulse](https://github.com/EAeaza/grantpulse-showcase)
Finds scholarships and grants, checks every fact against the official page, and publishes source-backed posts to a Telegram channel.
<br><sub>since Jun 2026, active · 45 commits · Python · SQLite</sub>

### [Agent Fleet Hub](https://github.com/EAeaza/agent-fleet-hub)
Keeps one developer's machines, coding-agent sessions and GitHub identity in sync — unattended, with its safety rules enforced in code.
<br><sub>since Sep 2026, active · 52 commits · Python · PowerShell · Bash</sub>

---

### How I work

Almost all of this was built with coding agents — **Claude Code and Codex, 2,212
sessions across 3 machines**. That is a working method, not a shortcut: the agent
writes most of the code; my job is to specify the problem precisely, define the invariants, and
adversarially audit what comes back. Several of these projects carry their own audit harnesses
for exactly that reason.

**Working with:** Python · JavaScript / TypeScript · PowerShell · SQLite · marketplace and
tax-authority APIs · 1C · Telegram bots

**Contact:** eazamat360@gmail.com, or open an issue on any project page to request a walkthrough
or read access.

Earlier public work: [ShakyGround](https://github.com/EAeaza/ShakyGround) — an earthquake app in
Kotlin, 2023.

<sub>Figures on this page are generated from the repositories and refresh automatically.</sub>
