### Krisztián Pettner

**Systems architect.** I design end-to-end systems under hard constraints — where raw data must be
processed only on hardware the owner controls, one client must never see another's data, and a
wrong number is worse than a missing one.

I work as the **architect of an AI development team**: I design the system, the agents write the
code to that design, and I hold the constraints and the gates, review every decision, and measure
whether it worked.

---

#### Featured work

**[Dat[AI]nsight — an invoice-processing platform, built and closed](https://github.com/krisztianpettner/datainsight-case-study)**
A no-cloud document-processing service for Portuguese small businesses and their accountants:
tiered PDF parsing anchored to the tax-authority QR code, a per-field identity gate with a human
review desk, a two-sided product, and a three-machine pipeline bridge with no inbound access to the
processing site. 1,564 commits over 6+ months. Header extraction worked, line items did not reach
the bar, and the business did not take off — the
[post-mortem](https://github.com/krisztianpettner/datainsight-case-study/blob/main/docs/en/09-post-mortem.md)
says why. English and Hungarian.

**[From spreadsheet chaos to a bank-grade dataset — a sales-data ETL case study](https://github.com/krisztianpettner/sales-data-etl-case-study)**
Years of hand-typed, unvalidated quote-tracking workbooks turned into a dataset a bank accepted:
a layout registry for spreadsheets that change every year, name matching in zones where a person
decides the uncertain cases, two databases that separate what is derived from what was decided,
and an operator loop that sends errors back to the people who type the data. In use since March
2026, refreshed quarterly. The client is anonymous and every record shown is synthetic — the
[data-protection chapter](https://github.com/krisztianpettner/sales-data-etl-case-study/blob/main/docs/en/10-data-protection.md)
documents how, including what the scans caught. English and Hungarian.

#### How I work

- **Constraints first.** Every design starts from what must never happen — and the architecture is the enforcement.
- **Decisions on record.** Why this, what was rejected, what it cost.
- **Measure, then trust.** A claim is only a claim until a measurement agrees — including my own.
- **Designed vs built, honestly.** A document that silently disagrees with the code is worse than none.

#### Elsewhere

[LinkedIn](https://www.linkedin.com/in/krisztian-pettner/) · krisztian [at] pettner.hu

<sub>🇭🇺 Magyarul is: a projektek dokumentációja kétnyelvű (angol · magyar).</sub>
