## Licia Zheng

Moving from economics into data analysis. I like questions where the answer depends on getting the data right first.

Most of what I publish here follows the same habit: audit the data before trusting it, do every correction in code so it stays visible and reproducible, and say plainly which conclusions did not survive.

### Projects

**[HIV treatment and prevention across Sub-Saharan Africa](https://github.com/liciazheng/cross-national-public-health-analysis)**
Panel analysis of 48 countries, 2005–2022, pulled from the World Bank API. Under year and country fixed effects, a percentage point of antiretroviral coverage tracks 2.5% fewer AIDS deaths and 1.4% fewer new infections. Restating the mechanism as the untreated reservoir — `prevalence × (1 − coverage)` — one variable explains 91% of the variation in incidence, at an elasticity indistinguishable from 1.0.

It started as a three-country study built by hand in Excel. Auditing that spreadsheet turned up 14 errors, including a headline indicator off by a factor of four and a column filled down from a different country. Both the original and the correction are in the repo, because how the analysis was wrong is the more useful half.

**[WTI crude oil prices against global events, 1970–2026](https://github.com/liciazheng/oil-price-analysis)**
Which oil shock was genuinely the most expensive? Once every price is converted into 2026 dollars, June 2008 — around $206, with the entire real-price top five falling in that one year. The 1970s shocks everyone remembers do not make the list; nominal prices had been flattering them for decades.

Built on 56 years of FRED data. Automatic event matching pairs each large monthly move with the nearest of 15 curated geopolitical events and catches 9 of the top 10, alongside a rolling correlation against the dollar index and an ARIMA(1,1,1) forecast with intervals.

**[Wine cellar management system](https://github.com/liciazheng/wine-cellar-management-system)**
A relational schema in SQLite, third normal form, with the modelling decisions written down: why the wine name, grape and appellation are three columns instead of one, why the drinking window is two integers instead of a string, and why a tasting note has to record who wrote it.

**[LeetCode solutions](https://github.com/liciazheng/Leetcode-Solutions1)**
Python 3, with notes on the dynamic programming problems.

### Tools

Python — pandas, statsmodels, matplotlib · SQL and SQLite · panel and fixed-effects models · pytest and GitHub Actions · data quality auditing

### Contact

[LinkedIn](https://www.linkedin.com/in/liciazheng) · zhenglicia1801@gmail.com
