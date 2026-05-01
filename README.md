# CAESAR
### Psychonomics No. 001 — Julius Caesar

**Published at [artometrics.com](https://artometrics.com)**

---

## What This Is

A data report applying the Leadership Trait Analysis (LTA) framework
to Julius Caesar — scored from primary sources, compared against Mao,
Xi Jinping, Thatcher, and the average world leader baseline. Three
charts. One argument: the man who built the Roman Empire never lived
in it, and the psychological profile that made him extraordinary is
the same one that killed him.

---

## Charts

| File | Description |
|---|---|
| `charts/chart1_lta_radar.png` | LTA radar — Caesar's psychological profile vs. comparable world leaders |
| `charts/chart2_rome_gdp.png` | Roman GDP per capita, 200 BCE – 400 CE |
| `charts/chart3_patronage_network.png` | Caesar's patronage network — trust weights and edge types |

---

## Data Sources

- **LTA scores** — Hermann (1999) framework; coded by author from Plutarch,
  Suetonius, and *Commentarii de Bello Gallico*. Comparative scores from
  Wang & Guo (2019).
- **Roman GDP** — Maddison (2007); Scheidel & Friesen (2009), *J. Roman Studies 99*;
  Lo Cascio & Malanima (2011). Values in 1990 Geary-Khamis dollars.
- **Patronage network** — Plutarch, Suetonius, Strauss (2015).
  Qualitative network, not computationally derived.

---

## Packages

```r
install.packages(c("tidyverse", "scales", "ggtext",
                   "fmsb", "igraph", "ggraph", "tidygraph"))
```

---

## Files

```
caesar.qmd                  # Master Quarto report
charts/
  chart1_lta_radar.png
  chart2_rome_gdp.png
  chart3_patronage_network.png
artometrics.css             # Artometrics stylesheet
art-head.html               # Quarto header injection
art-body.html               # Quarto body injection
```

---

## Series

This is the first report in the **Psychonomics** series by Artometrics —
profiles of historical and contemporary figures through the lens of
behavioral economics and leadership psychology.

**Artometrics** — The Economist for Artists.
[artometrics.com](https://artometrics.com)
