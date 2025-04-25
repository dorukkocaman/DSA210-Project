# 🔬 Playoff Data: Statistical Hypothesis Testing Results

## Hypothesis

- **Null Hypothesis (H₀):** Assist/Turnover (AST/TO) ratio has no relationship with Win Percentage and Points Per Game.
- **Alternative Hypothesis (H₁):** Assist/Turnover (AST/TO) ratio is related to at least one of Win Percentage or Points Per Game.

---

## Statistical Test

We performed a Pearson correlation test on the regular season and playoffs dataset to evaluate the relationship between AST/TO ratio and:
- **Points Per Game (PTS/Game)**
- **Win Percentage (Win%)**

### Results:

**AST/TO Ratio vs Points Per Game**
- Correlation coefficient (r) = **0.670**
- p-value = **1.06 × 10⁻⁵**

**AST/TO Ratio vs Win Percentage**
- Correlation coefficient (r) = **0.247**
- p-value = **0.1519**

---

## Interpretation

- For **Points Per Game**:
  - Since p < 0.05, we **reject the null hypothesis**.
  - There is a **statistically significant positive relationship** between AST/TO ratio and Points Per Game.

- For **Win Percentage**:
  - Since p > 0.05, we **fail to reject the null hypothesis**.
  - There is **no statistically significant relationship** between AST/TO ratio and Win Percentage.

---


## 📉 Observing Trends vs. Proving Correlation

> The playoff data analysis shows that a better Assist/Turnover ratio tends to correlate with higher scoring averages, but does not consistently predict higher win rates.

While analyzing the regular season and playoff data, visualizing Assist/Turnover Ratio, Points Per Game, and Win Percentage, I noticed that although there are **visible trends** in certain areas of the chart, we **cannot confidently claim a clear correlation** in win percentage metrics

For example, some teams with a relatively high AST/TO ratio also won more games, but this was not consistent across all teams. In several cases, teams with low assist efficiency still had high win percentages and vice versa.

This inconsistency suggests that other factors are likely influencing overall performance in the matches. Elements such as **defensive metrics, rebounding, steals, blocks, and defensive ratings** can significantly affect win outcomes— sometimes overshadowing assist-based efficiency.



---

