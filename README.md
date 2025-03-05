# DraftKings_Scraper


# CSV/DataFrame Column Summary

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
