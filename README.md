# U.S. Divorce Statistics Dataset

**Open, structured data on divorce in the United States** — divorce rates, child custody outcomes, divorce costs, timelines, demographics, and remarriage trends, organized by state.

> **Full analysis and visualizations:** [unvow.com/divorce-statistics](https://unvow.com/divorce-statistics)

*Last updated: March 2026*

---

## What's Included

| File | Description | Records |
|------|-------------|---------|
| [`divorce_rates_by_state.csv`](data/divorce_rates_by_state.csv) | Divorce and marriage rates per 1,000 population for all 50 states + D.C. | 51 |
| [`divorce_rates_by_country.csv`](data/divorce_rates_by_country.csv) | International divorce rate comparison across 43 countries | 43 |
| [`divorce_rate_trends.csv`](data/divorce_rate_trends.csv) | National U.S. divorce rate trends, 2000–2023 | 24 |
| [`child_custody_outcomes.csv`](data/child_custody_outcomes.csv) | Custodial parent breakdown, child support compliance, and payment data | 6 |
| [`divorce_costs_average.csv`](data/divorce_costs_average.csv) | Filing fees, contested/uncontested costs, and attorney rates for all 50 states | 50 |
| [`divorce_timeline_average.csv`](data/divorce_timeline_average.csv) | Mandatory waiting periods and average duration for all 50 states + D.C. | 51 |
| [`divorce_demographics.csv`](data/divorce_demographics.csv) | First divorce rates by sex and race/ethnicity | 5 |
| [`remarriage_rates.csv`](data/remarriage_rates.csv) | Remarriage rates by sex, age group, and education level | 11 |

All data is in standard CSV format with headers. Each file includes a source column for citation.

**Note:** Five states (California, Hawaii, Indiana, Minnesota, and New Mexico) do not report divorce data to the CDC NVSS. Their divorce rate fields are blank in the state rates file.

---

## Sources

Data is compiled from official government and research sources:

- **CDC National Vital Statistics System (NVSS)** — divorce and marriage rates (provisional 2023 data, 45 reporting states + D.C.)
- **U.S. Census Bureau CPS Child Support Supplement** — custodial parent and child support data (P60-285, 2022 data, published August 2025)
- **U.S. Census Bureau SIPP** — child support payment data (2021 data, published 2023)
- **BGSU National Center for Family & Marriage Research** — first divorce rates and remarriage rates (FP-25-02, FP-25-03, 2023 ACS data)
- **State court administrative offices** — waiting periods and timelines (statute citations included)
- **Martindale-Nolo consumer surveys (2019)** and **Self.inc analysis (2025)** — cost estimates
- **State court fee schedules (2025)** and **Clio/LawPay (2023)** — filing fees and attorney rates

Detailed source documentation is in the [`sources/`](sources/) directory.

---

## How to Cite

If you use this data in an article, paper, or project, please cite:

> Unvow. "U.S. Divorce Statistics Dataset." GitHub, 2026. https://github.com/unvow/divorce-statistics-dataset

Or link to the full analysis at **[unvow.com/divorce-statistics](https://unvow.com/divorce-statistics)**.

---

## Related Resources

- [Divorce Statistics — Full Analysis & Charts](https://unvow.com/divorce-statistics)
- [Child Support Calculator](https://unvow.com/calculators/child-support)
- [Divorce Cost Estimator](https://unvow.com/calculators/divorce-cost)
- [Complete Guide to Divorce](https://unvow.com/divorce/complete-guide-to-divorce)
- [Child Custody Laws Explained](https://unvow.com/custody/child-custody-laws-explained)
- [How Alimony Works](https://unvow.com/support/how-alimony-works)
- [Divorce in California](https://unvow.com/divorce/california)
- [Divorce in Texas](https://unvow.com/divorce/texas)
- [Divorce in Florida](https://unvow.com/divorce/florida)
- [Divorce in New York](https://unvow.com/divorce/new-york)
- [Remarriage Statistics](https://unvow.com/divorce-statistics/remarriage)
- [Child Support Statistics](https://unvow.com/divorce-statistics/child-support)

---

## License

This dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE).

You are free to share and adapt this data for any purpose, including commercial use, as long as you provide attribution.

---

## Contributing

Found an error or have updated data? See [CONTRIBUTING.md](CONTRIBUTING.md) for how to submit corrections.
