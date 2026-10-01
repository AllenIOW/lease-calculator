# Lease Calculator — IFRS 16 and FRS 102 Section 20

Live at **<https://alleniow.github.io/lease-calculator/>**

Lessee lease accounting for UK companies. One lease at a time, under IFRS 16 or
FRS 102 Section 20 as amended by the 2024 periodic review — effective for
periods beginning on or after **1 January 2026**, so a December year-end company
is in its first year now.

It measures a lease from commencement, or brings an existing one on balance
sheet at a transition date, and returns the liability schedule, the right-of-use
asset schedule, the journals and the disclosure figures. Every figure carries
its basis. No judgement input is ever defaulted.

## What it is not

- **Not audited software**, and it produces no filing. Every figure is a draft
  to be reviewed.
- **First recognition only.** It does not handle a lease that changes part-way
  through — a rent review, an index-linked uplift, a changed term. Those need
  the liability remeasured, which is not built.
- **One lease at a time**, not a portfolio. No lessor accounting, no sale and
  leaseback, no sub-leases.
- **Dates are modelled in whole months**, so a quarter-day rent is an
  approximation. The tool says so where it matters.

## Your figures stay with you

Everything is calculated in your browser. There is no account and no server:
this repository holds one self-contained HTML file.

The calculation engine is a separate, tested TypeScript library; this is the
built interface only.
