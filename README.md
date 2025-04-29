#  A/B Testing in Mobile Game: Cookie Cats Game

This project investigates the effect of early game gate unlocking on user retention in the mobile game *Cookie Cats*. We use A/B testing methods to analyze and compare Day 1 and Day 7 retention rates between two user groups.

---

##  Objective

To determine whether unlocking a gate earlier in the game (treatment group) affects player retention compared to the default setting (control group).

---

##  Methods

- Exploratory Data Analysis (EDA)
- Group comparison: Control vs. Treatment
- Visualization of retention distributions
- Statistical testing:
  - Proportion Z-test
  - Confidence intervals
- Interpretation of statistical significance

---

##  Project Structure

```bash 
ab-testing-cookie-cats/
├── README.md
├── LICENSE
├── project_ab_cookiecats.Rmd
├── project_ab_cookiecats.html     
├── data/
     └── cookie_cats.csv
```
  
---

##  Technologies & Libraries

- **Language**: R
- **Libraries**: 
  - `tidyverse` 
  - `dplyr`
  - `ggplot2`
  - `knitr`

---

##  Results

- **Day 1 Retention**: Slightly improved with early unlocking.
- **Day 7 Retention**: Lower retention in the treatment group.
- **Conclusion**: Earlier gate unlocking may encourage short-term play but may reduce long-term retention.

---

##  Key Learnings

- Designed a real-world A/B testing experiment.
- Applied hypothesis testing and data visualization to drive product decisions.
- Developed a statistical thinking mindset and learned how to translate business questions into data analysis.

---

##  Requirements

- R (version ≥ 4.0)
- RStudio recommended for `.Rmd` rendering
- Install packages:
```r
install.packages(c("tidyverse", "dplyr", "ggplot2", "knitr"))
