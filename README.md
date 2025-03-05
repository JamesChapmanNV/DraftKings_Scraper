# DraftKings_Scraper <a target="_blank" href="https://colab.research.google.com/github/JamesChapmanNV/DraftKings_Scraper/blob/main/DraftKingsScraper.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- This repository contains a Jupyter Notebook that scrapes NFL contest data from DraftKings' website. It provides robust ‘Data Cleaning’ and ‘Multi-Core Processing’ for efficient resource usage. 
- `DraftKings removes data after ~4 days! I ran this notebook 2-3 times a week throughout the season.`
- The output is structured into Pandas DataFrames (CSV’s)  for subsequent analysis and model building. This is ready for data science and machine learning experiments. Uniquely, this includes the percent usage per player. 
- Hypothesis: If popular players (highly used, high %) are predicted to underperform, will unpopular players be better picks?
- Can easily be adapted to other sports and DraftKings contests.


# Creates 3 CSV's 
## Column Summary

---

## 1. Contest Details DataFrame (30 Columns) (`contests.csv`)

- **max_entries**  
- **name**  
- **entries**  
- **entry_fee**  
- **total_prizes**  
- **date_time**  
- **contest_id**  
- **draftGroupID**  
- **gameType**  
- **is_guaranteed**  
- **is_starred**  
- **is_winner_take_all**  
- **is_double_up**  
- **is_fifty_fifty**  
- **is_multiplier**  
- **IsCasual**  
- **IsBeginner**  
- **date**  
- **week**  
- **year**  
- **draftGroupStatus**  
- **contestStatus**  
- **pt**  
- **pd.LiveFinalSeat**  
- **attr.IsPrivate**  
- **tix**  
- **pd.Experience**  
- **is_tournament_of_champ**  
- **pd.Prize**  
- **crownsAwarded**

---

## 2. Contest Results DataFrame (6 Columns) (`contestResults.csv`)

- **contest_id**  
- **place**  
- **entry_id**  
- **points**  
- **lineup**  
- **payout**

---

## 3. Player Selections DataFrame (5 Columns) (`contestOwnership.csv`)

- **contest_id**  
- **player**  
- **pos**  
- **drafted**  
- **points**
