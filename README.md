# 🏏 IPL Stats Analyzer — Cricket + Code + Coffee ☕

Welcome to the **IPL Stats Analyzer** — a Python-powered data exploration tool that dives deep into IPL matches using **pandas**, a bit of logic, and a lot of cricket love ❤️

> ⚠️ Note: This is one of my **first Python + Pandas projects**, and I’m continuously learning and improving. Feedback is welcome!

---

## 🧠 Features

This isn’t just a notebook — it’s a full-on cricket brain. Here’s what it can do:

### 🔝 1. Top 10 Run Getters
Find out who’s been consistently hitting it out of the park season after season. (Yes, Kohli’s in there. Calm down.)

### 🏆 2. Teams With Most Wins
Want to settle the argument about which IPL team is truly the best? Here’s your proof.

### ⚔️ 3. Head-to-Head Between Two Teams
Input two team names and get their full battle history:
- Matches played
- Wins by each team
- No-results (if any)

### 👥 4. Batsman vs Bowler 1-on-1 Record
Enter any batsman and bowler — get:
- Total runs scored
- Balls faced
- Times dismissed
- Strike Rate
- Batting Average

Useful for spotting personal rivalries 🔥

### 🤖 5. Win Predictor (No ML, Just Smart Logic)
Enter two teams and (optionally) toss winner. The tool gives you a **predicted winner** based on:

- 40% Head-to-Head Record
- 30% Recent Form (last 5 matches)
- 30% Toss Advantage

**Formula used:**

```python
final_score = 0.4 * h2h_score + 0.3 * recent_form + 0.3 * toss_boost
```

### 🎯 6. Player vs Team Batting Record

Ever wanted to check how a specific player performs against a certain team? This feature makes that super easy.

You simply input:
- A **batsman's name**
- An **opponent team name**

And it returns:
- 🏏 The **last 5 innings** of the player against that team
  - Shows runs scored, balls faced, and whether the batter got out
- 📊 The **total career runs** vs that team
- 💥 The **strike rate** and **batting average**

---

### 📦 Python Libraries:
- `pandas` – for data wrangling magic 🐼
- `matplotlib` – for plotting things that look smart 📊

---

## 🚀 How to Run the Project

Follow these steps to run the notebook and start analyzing:

1. **Clone the repository**:
```bash
git clone https://github.com/shritij26/ipl-stats-analyzer.git
cd ipl-stats-analyzer
```
---
