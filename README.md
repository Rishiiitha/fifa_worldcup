#FIFA 21 PLAYER STATS ANALYSIS
## 📌 Overview
This project analyzes the FIFA 21 player dataset (`df21`) to explore player performance, value, and distribution across clubs and nationalities.

## 📂 Dataset
- **Source**: FIFA 21 dataset
- **Rows**: N players
- **Columns**: Includes `overall`, `potential`, `club_name`, `nationality`, `value_eur`, `wage_eur`, `player_positions`, etc.

## 🔍 Key Questions & Answers

### 1️⃣ Which club has the highest average overall rating?
```python
df21.groupby('club_name')['overall'].mean().sort_values(ascending=False).head(1)

📊 Visualizations

Top 10 Nationalities by Average Wage

Boxplot of Overall Ratings by Primary Position

Distribution of Player Values

Correlation Heatmap between Player Attributes

🛠️ Tech Stack

Python: Data analysis & visualization

Pandas: Data manipulation

Matplotlib / Seaborn: Visualizations

NumPy: Numerical operations
