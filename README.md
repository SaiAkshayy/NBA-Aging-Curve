# NBA Aging Curve Analysis  

## Overview  

This project explores how NBA players perform across their careers, identifying peak performance ages and declines. Using metrics like BPM (Box Plus/Minus), OBPM (Offensive BPM), DBPM (Defensive BPM), and VORP (Value Over Replacement Player), we provide actionable insights for:  
- Contract timing and lengths.  
- Team roster optimization.  
- Tailored player development strategies.  

**Suggested Visual:** A summary infographic showing the lifecycle of a typical NBA player’s performance.  

## Data and Methodology  

### Data  
- **Source:** Basketball-Reference (2012-2023).  
- **Metrics Analyzed:** BPM, OBPM, DBPM, and VORP.  
- **Preprocessing:** Filtering players with consecutive seasons and 20+ games played.  

### Methodology  
We used the **Delta Method** to calculate performance trends:  
1. **Delta:** Year-over-year changes in performance.  
2. **Chained Drop-off:** Long-term performance trajectories.  
3. **Smoothed Trends:** Removing noise with the Savitzky-Golay filter.  

> **Suggested Visuals:**  
> - Line charts showing performance curves for key metrics like BPM and VORP.  
> - Tables comparing correlations of skills with performance by position (e.g., PG, C).  


## Key Insights  

### Performance Trajectories  
- **Peak Age:** Players typically peak between 25-27 years.  
- **Decline:** Performance begins declining consistently after age 28-29.  
- **Position-Specific Trends:**  
  - Centers improve significantly in early careers but decline in areas like assists and rebounds post-30.  
  - Defensive metrics (DBPM) show more stability compared to offensive ones.  

### Contract Recommendations  
- **Before Peak (22-25):** Sign players for longer contracts to benefit from their rise.  
- **At Peak (25-28):** Ideal for teams in 'win-now' mode.  
- **Post-Peak (29+):** Shorter contracts mitigate risks of performance decline and injuries.  

> **Suggested Visuals:**  
> - Smoothed aging curves for BPM, OBPM, and VORP.  
> - Age histogram highlighting peak performance periods.  

---

## Conclusion  

This analysis equips NBA teams, sponsors, and agents with tools to:  
1. Optimize roster decisions.  
2. Tailor training programs to prolong peak performance.  
3. Negotiate contracts that align with expected player trajectories.  

> **Suggested Final Visual:** A decision-making flowchart summarizing contract timing and player management strategies.  
