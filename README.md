#  Spotify Listening History – EDA Project

Welcome to my exploratory data analysis project on **Spotify listening history**! This notebook walks through cleaning personal streaming data, feature engineering, and building insightful visualizations to understand listening behavior over time.

---

## 📁 Files in This Repository

| File Name                                 | Description                                      |
|-------------------------------------------|--------------------------------------------------|
| `eda.ipynb`                               | Main Jupyter Notebook for data cleaning + EDA    |
| `spotify_history.csv`                     | Raw Spotify listening history (Kaggle or export) |
| `spotify_history_cleaned.csv`             | Cleaned dataset used for analysis                |
| `spotify_data_dictionary Description.csv` | Column definitions/reference (optional)          |
| `README.md`                               | This documentation file                          |

---

## 🧼 What This Project Covers

- Cleaning and preprocessing raw Spotify history
- Extracting date & time features (hour, day, month)
- Removing short/invalid plays (< 5 sec, > 1 hr)
- Analyzing skip and shuffle behavior
- Finding top tracks, artists, albums
- Visualizing platform usage and session timing

---

## 📊 Visualizations Include

- 🔥 Top 10 Songs by Total Listening Time  
- 🎤 Top 5 Artists (Pie Chart)  
- 🗓 Listening Trend by Day of Week  
- ⏰ Hourly Listening Pattern  
- 📈 Monthly Streaming Trends  
- 🎛 Platform Usage Distribution  
- 🚫 Skip Rate by Hour  
- 🔁 Shuffle vs Non-Shuffle Comparison  
- 🧠 Reason for Starting a Track (click, autoplay, etc.)

---

## 🚀 How to Run This Notebook

1. Clone the repository  
2. Create a virtual environment (optional but recommended)  
3. Install dependencies  
4. Launch Jupyter Notebook

```bash
# Clone repo
git clone https://github.com/yourusername/spotify-eda.git
cd spotify-eda

# Create and activate virtual environment
python3 -m venv spotifyenv
source spotifyenv/bin/activate   # Windows: spotifyenv\\Scripts\\activate

# Install required packages
pip install pandas matplotlib seaborn jupyter

# Run the notebook
jupyter notebook eda.ipynb
