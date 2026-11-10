# Brand Building to Performance Ratio Calculator

**Where should your media investment go: Brand Building or Performance?**

A free, browser-based calculator that turns household panel data into a Brand Building vs. Performance budget split, grounded in two of the most cited principles in marketing effectiveness.

👉 **Try it live:** https://aravamudhananand.github.io/brandbuilding-to-performance-budget-calculator/

---

## Built on two principles

| Principle | What it says | How the tool uses it |
|---|---|---|
| **95:5** (John Dawes, Ehrenberg-Bass Institute) | At any moment, only a small share of category buyers are in the market to buy. Most are out-of-market. | Calculates your category's out-of-market vs. in-market buyer split. |
| **60:40** (Les Binet & Peter Field, IPA) | The most effective campaigns put about 60% into brand building and 40% into sales activation, with optimums that vary by sector. | Sets the starting budget split, anchored to your sector. |

## How it works

**1. Enter your household panel data** (NielsenIQ Homescan, Circana or Numerator, rolling 52 weeks)
- Category household penetration (HHP) and purchase frequency
- Brand HHP and purchase frequency (optional)
- Decision period: how long shoppers spend choosing

**2. See who's Out-of-Market vs. In-Market**
- Interpurchase time = 365 days ÷ category purchase frequency
- In-market % = decision period ÷ interpurchase time
- Brand share of in-market shoppers = (brand HHP × brand frequency) ÷ (category HHP × category frequency)

**3. Get your budget split**
- Starts at your sector's Binet & Field optimum (60:40 if no sector is chosen)
- Leans further into Brand Building as the out-of-market share rises above 90%, or toward Performance below it
- Compares the result with your current mix (slider or line-item spend) and recommends your next move

## Example

Pain care category: 71% HHP, bought 3.3 times a year, 1-day decision period, FMCG sector.

- Buyers purchase every **111 days**
- **0.9%** are in-market at any moment; **99.1%** are out-of-market
- Ideal split: **60:40 to 65:35** Brand Building : Performance

## Notes

- Runs entirely in your browser. No data is stored or sent anywhere.
- A single self-contained HTML file (`index.html`). No build step or dependencies.
- A planning starting point, not a replacement for MMM or incrementality testing. Validate before locking budgets.
- The sliding adjustment around the sector anchor is the author's rule of thumb, not part of Dawes' or Binet & Field's research.

## Sources

- John Dawes, *The 95:5 Rule* and *How B2B Brands Grow* (Ehrenberg-Bass Institute / The B2B Institute, 2021)
- Les Binet & Peter Field, *The Long and the Short of It* (IPA, 2013)
- Les Binet & Peter Field, *Effectiveness in Context* (IPA, 2018), Table S3: Brand:Activation Balance Guidelines
- Les Binet & Peter Field, *The 5 Principles of Growth in B2B Marketing* (The B2B Institute, 2019), for the B2B benchmark

## Author

Built by **Anand Aravamudhan**, a media and marketing strategy leader in full-funnel planning across CPG and retail media.

[Connect on LinkedIn](https://www.linkedin.com/in/aravamudhananand/)
