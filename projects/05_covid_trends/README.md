# COVID-19 Trends Analysis

**Objective:** Analyze COVID-19 time-series data to study patterns and mobility impacts.

**Dataset:** [Johns Hopkins CSSE COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)

**Tools:** R (tidyverse, ggplot2, lubridate)

---

## Steps

1. **Data Cleaning:** Imported and structured global case data.
2. **Time-Series Analysis:** Calculated rolling averages.
3. **Visualization:** Built line charts and heatmaps.
4. **Mobility Trends:** Compared against Google mobility data.

---

## Insights

- Weekly cycles in reporting create noise → smoothed with rolling averages.
- Mobility restrictions correlate with sharp case drops.
- Vaccination rollout aligns with decreased death rates.

---

## Project Structure

- `notebooks/` → R scripts + analysis notebooks
- `sql/` → Queries if used
- `data/` → Small samples or link to source
- `assets/` → Graphs/plots

---

## Results

- 📊 Visualizations in `assets/`
- 📂 R scripts in `notebooks/`
