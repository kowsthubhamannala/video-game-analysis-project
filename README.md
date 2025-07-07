# 🎮 Video Game Sales and Engagement Analysis

This project analyzes trends in video game performance using user engagement metrics (ratings, wishlists) and global sales across platforms and genres.

## 📁 Project Contents

- `games.csv`, `vgsales.csv` — Raw datasets  
- `cleaned_games.csv`, `cleaned_vgsales.csv` — Cleaned data  
- `merged_games.csv` — Merged dataset from both sources  
- `top_10_sales.csv`, `avg_rating_per_genre.csv`, `sales_by_platform.csv`, `games_per_year.csv` — SQL analysis results  
- `video_games.db` — SQLite database with 3 tables: `games`, `sales`, `merged_games`  
- Python scripts for cleaning, merging, inserting, and analyzing data  
- Power BI dashboard: `Video Game Sales and Engagement Dashboard.pbix`  
- Final report: `video_game_project_report.docx` (optional)

## 🧪 Tools Used

- Python (Pandas, SQLite)  
- SQLite3  
- Power BI  
- Visual Studio Code  
- Git & GitHub

## 🔍 Key Insights

- 🏆 **Top Game by Sales:** Wii Sports  
- ⭐ **Highest Rated Genres:** Role-Playing, Puzzle  
- 🎮 **Top Platforms:** DS, PS2, Wii  
- 📅 **Peak Years:** 2008–2011

## 🚀 How to Run

```bash
python clean_data.py  
python merge_data.py  
python setup_database.py  
python insert_data.py  
python analyze_data.py
