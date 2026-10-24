# Paying for Power

**Industrial electricity prices in the United Kingdom, Germany and China, 2010–2025 — what Britain's are made of, and what would change them.**

📄 **Read the study:** https://gnievchenko.github.io/ReindustrialisingEurope/

> **Status: draft for review.** Figures may change; corrections are made as dated commits.

---

## What this is

A comparative study of what energy-intensive industry actually pays for electricity in three countries, built bottom-up from published tariffs, levies, network charging schedules and wholesale market data, and reconciled against national survey averages. It then tests the popular remedies — North Sea drilling, renewables, nuclear — against that diagnosis.

## The main findings

- **Policy relief means eligible firms pay no more than before.** A fully relieved site paid no more in 2019 than in 2010 in either country. The 85% of British industrial volume outside the relief scheme did pay for the levies: its levy line rose from $20 to $77/MWh between 2010 and 2020.
- **Since 2020 the problem is wholesale, which is gas plus carbon.** No exemption reaches that line.
- **China priced itself in.** Its industrial tariff fell from $145 to $87/MWh between 2012 and 2025, mostly through tariffs frozen in yuan; a weaker yuan explains about 30%.
- **Relief works, but it is a transfer** — every exempted pound is paid by other consumers or the taxpayer.
- **North Sea gas is a fiscal measure**, not an energy-price policy.
- **Renewables are the cheapest way to burn less gas**, even with storage; their limit is the grid.
- **Nuclear is a long-term bet**, not an answer for this decade.

## Contents

| Path | What it is |
|---|---|
| `paying_for_power_article.html` | The study. Single file, no dependencies, interactive figures drawn as inline SVG. Open it directly in a browser. |
| `paying_for_power_chart_data.xlsx` | The numbers behind every chart, one sheet per figure in article order, with units, notes, exchange rates and deflators. |
| `data/*.csv` | The same sheets as plain text, so changes show up in diffs. |

## How to check the numbers

Every chart has a **"View data"** control (or hover values) in the article, and every series is in the chart-data workbook with its source note. All prices are real 2025 US dollars: nominal local currency, converted at Federal Reserve annual-average exchange rates, deflated with US CPI-U; VAT excluded. Each figure note names its primary sources.

## Method, in brief

Prices are built as a stack — wholesale energy, network and system charges, levies and taxes including generation-capital recovery, and a supplier cost-and-margin block — for two archetypal sites in each country (500 GWh/yr baseload, transmission-connected; 20 GWh/yr two-shift, HV distribution), with and without the reliefs each qualifies for. The modelled stacks are labelled as modelled and compared against survey averages (DESNZ QEP for the UK, Eurostat for Germany; China has no survey).

## Corrections

Corrections are welcome and will be made as dated commits rather than silent edits. If a number looks wrong, name the figure and series it comes from and open an issue.

## Licence

Text, charts and analysis: [CC BY 4.0](LICENSE). Underlying data is drawn from public sources, each cited in the relevant figure note, and remains subject to its own terms.
