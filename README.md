# Social-Media-Graph-Analyzer
# Social Graph Engine: People & Page Recommendation System

This project simulates a mini social network system with features like data cleaning, friend suggestions, page recommendations, and user summary generation.

## 📌 Features

- ✅ Clean and validate user and page data (remove duplicates, handle empty names)
- 🧑‍🤝‍🧑 Recommend people users may know (based on mutual friends)
- 📄 Recommend pages users may like (based on shared page interests)
- 👤 Generate user summaries (total friends, liked pages, etc.)

## 🛠️ Technologies Used

- Python 3
- JSON for data handling
- Sets and dictionaries for efficient lookups
- Functional modular approach

## 🗂️ File Structure

| File                    | Purpose                                           |
|-------------------------|---------------------------------------------------|
| `Dummy_Data.json`       | Original raw data                                |
| `clean_data.py`         | Cleans and deduplicates user & page info         |
| `recommend_pages.py`    | Suggests pages based on mutual likes             |
| `recommend_people.py`   | Suggests people based on mutual friends          |
| `user_summary.py`       | Displays summary of a user                       |
| `cleaned_social_network.json` | Output after cleaning the data             |

## 🚀 How to Run

1. Place all `.py` scripts and `Dummy_Data.json` in the same directory.
2. Run `clean_data.py` first to generate `cleaned_social_network.json`.
3. Run any of the other scripts (`recommend_pages.py`, `recommend_people.py`, `user_summary.py`) with your desired `user_id`.

## 📊 Example Output

👤 User Summary
🔹 Name : Ravi
🔹 Total Friends : 2
🔹 Liked Pages : 0

🧑‍🤝‍🧑 People you may know for User 10 : [9, 11]
📌 Pages recommended for User 9 : [103]
