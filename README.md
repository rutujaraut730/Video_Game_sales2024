Video Game Sales Analysis
---------------------------
Tool: Python, Pandas, Jupyter Notebook

Dataset:
Video Game Sales 2024 (Kaggle) — 64,000+ games

Objective: 
Analyzing global video game sales to find the most popular games, platforms, and genres across different time periods.

-------------------------
Questions I'm Exploring:-
1.Which game has the highest global sales of all time?
2.Which platform has the most games released?
3.Which genre is most popular and which games in it are newest?

--------------------------------
Dataset Info

Source: Kaggle (asaniczka/video-game-sales-2024)

Rows: 64,000+

Key columns: title, platform, genre, critic_score, total_sales, release_year

--------------------------------------------
Data Cleaning

Dropped columns: img, critic_score, jp_sales — too many nulls
Dropped rows where total_sales was null
Final dataset: 18,922 rows, 11 columns

Key Findings

GTA V is the highest selling game of all time (20.32M copies on PS3)
PC has the most games released (12,617 games)
Misc is the largest genre but Action is the most recognizable dominant genre

Status
🔄 In Progress — Visualizations coming next
