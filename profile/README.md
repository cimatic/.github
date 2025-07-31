# Cimatic – CI/CD Pipeline Monitoring & CI Vitals for GitHub Actions

Cimatic turns your GitHub Actions logs into **actionable CI Vitals**—WET, NFR & POT—so you can ship faster, cut waste, and trust every build.

<p align="center">
  <a href="https://cimatic.io">
    <img src="https://raw.githubusercontent.com/cimatic/.github/main/profile/hero.svg" width="620" alt="Cimatic CI Vitals Dashboard"/>
  </a>
</p>

## Why Measure CI Vitals?

| Metric | What It Means | Why It Matters |
|--------|---------------|----------------|
| **WET**<br>(Workflow Execution Time) | Developer-visible runtime of a workflow (p75 & p90) | Long WET = slow feedback loops & context switching |
| **NFR**<br>(Noise-to-Fix Ratio) | % of failures caused by infra noise vs. real bugs | High NFR erodes trust—teams ignore red builds |
| **POT**<br>(Pipeline Overhead Time) | Pure waste: queue waits, retries, cache misses | High POT = hidden $$$ lost to idle engineers |

> "Three metrics. Infinite clarity. WET, NFR, POT—the only CI/CD numbers that actually matter." – Cimatic Manifesto

---

## What Makes Cimatic Different?

* **Instant CI Vitals Dashboard** – Connect your repo; see WET, NFR & POT for every workflow, no YAML edits required.
* **Historical Trends & Baselines** – Answer “Are our builds getting slower?” with month-over-month graphs.
* **Failure Classification Engine** – ML separates flaky infra noise from real test failures to improve NFR.
* **POT Breakdown** – Visualize queue time, retry time and cache misses—spot wasted minutes instantly.
* **Job & Step Drill-Downs** – Identify the exact job or step adding 4 minutes to WET.
* **Real-Time Alerts** – Slack & Teams notifications when WET spikes or NFR crosses a threshold.
* **Zero-Config Time-Travel** – We index your entire GitHub Actions history so you see trends from day one.

---

## Deep Dive: From Green Checkmarks to Real Insights

GitHub Actions tells you **pass/fail**. Cimatic tells you:

* How much **developer time** your pipeline wastes every day (POT)
* Which **jobs** cause 90% of slowdowns (WET p90 heat-map)
* Whether yesterday’s red build was a **real bug or infra noise** (NFR)
* How your **CI Vitals compare to the 10-minute-build ideal**

Stop guessing. Start measuring. Then optimize what matters.

---

## Learn More

* 📖 **CI Vitals Explained:** https://cimatic.io/docs/ci-vitals
* 📚 **CI/CD Pipeline Architecture Guide:** https://cimatic.io/blog/cicd-pipeline-architecture
* 📝 **Blog:** DevOps tips, DORA vs. CI Vitals, GitHub Actions optimization → https://cimatic.io/blog

---

## Stay in the Loop

| | |
|---|---|
| 🐦 X | [@cimatic_io](https://x.com/cimatic_io) |
| 💼 LinkedIn | [linkedin.com/company/cimatic-io](https://www.linkedin.com/company/cimatic-io/) |

---

### Ready to Slash Your Build Times?

👉  **[Join the Waitlist](https://cimatic.io#waitlist)** – be first to access CI Vitals for GitHub Actions.
