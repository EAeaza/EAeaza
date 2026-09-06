# Azamat Egamberdiev

I build the internal systems that commerce businesses run on — settlement reconciliation,
tax and e-invoicing, demand forecasting, warehouse control. Tashkent, Uzbekistan.

Most of my work is operational software for a live business, so the repositories are private.
What follows is what they do and roughly how big they are.

---

### Marketplace control tower · Python · 655 commits

The system a distributor's operations actually run on. It reconciles settlement reports from
three marketplaces against the accounting ledger and fiscal receipt data, finds the gaps, and
explains them. On top of that sits demand forecasting and procurement cover, VAT position
calculation, and a Telegram bot that answers questions about stock and money in plain language.

About 1,200 Python modules. The hard part was never the code — it was that three marketplaces,
an accounting system and the tax authority all disagree about the same transaction, and
something has to decide which one is right.

### Advertising analytics · Python, TypeScript · 173 commits

OCR over advertising panels, brand detection, and clustering of what ran where. Built as a
sweep harness — parallel branches per experiment, so variants could be compared against the
same captured dataset rather than re-shot each time.

### Grant discovery · Python · 42 commits

Finds and tracks grant opportunities, keeps a captured snapshot of each source so a listing
that disappears is still auditable later.

### Product & warehouse tooling · JavaScript, Python · 184 commits

Stock transfer workflows, an automation MVP against the accounting system, and export
pipelines for product cards and error reports.

---

### How I work

Almost all of this was built with coding agents — **Claude Code and Codex, ~1,900 sessions
across three machines** over the past year. That is a working method, not a shortcut: the
agent writes most of the code, and my job is to specify the problem precisely, define the
invariants, and adversarially audit what comes back. A lot of these repos contain their own
audit harnesses for exactly that reason.

I also keep the machines themselves in sync through a small coordination hub, because work
spread across three computers otherwise drifts into fourteen copies of the same project.

**Working with:** Python · JavaScript / TypeScript · PowerShell · SQLite · marketplace and
tax-authority APIs · 1C · Telegram bots

Earlier public work: [ShakyGround](https://github.com/EAeaza/ShakyGround) — an earthquake app
in Kotlin, 2023.
