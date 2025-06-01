# Spotify Hybrid Recommender 🎵

A hybrid recommender system for Spotify tracks that combines content-based and collaborative filtering to personalize music recommendations based on user behavior and track features.

##  Project Objective

The goal is to build an intelligent recommendation engine that suggests songs a user might like, based on:
- Past user interaction (`playcount`)
- Track metadata
- Similar user preferences

This project is currently in progress 🚧 and will evolve over time.

## 🔍 Dataset

- **Source:** Provided dataset containing:
  - `user_id`
  - `track_id`
  - `playcount`

- Size: ~9.7 million entries

## 💡 Approach

1. **Exploratory Data Analysis (EDA)**:
   - Analyzing user behavior and playcount distributions
   - Identifying duplicate records
   - Cleaning and preprocessing

2. **Collaborative Filtering**:
   - User-based or item-based similarity using `Surprise` or `SciPy` sparse matrix

3. **Content-Based Filtering**:
   - If available, use track metadata (genre, artist, tempo) to find similar items

4. **Hybrid Model**:
   - Combine predictions from both approaches for better accuracy
  

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Surprise (for collaborative filtering)
- Jupyter Notebook

## ✅ To Do

- [x] Perform EDA on user-track-playcount dataset
- [ ] Build collaborative filtering model
- [ ] Add content-based recommendation logic
- [ ] Tune and evaluate hybrid model
- [ ] Deploy via Streamlit or Flask (optional)

## 🙋‍♀️ Author

**Aditi Bedi**  
MCA Student @ IGDTUW | Aspiring Data Analyst  
🔗 [LinkedIn](https://in.linkedin.com/in/aditi-bedi-b184291a0?trk=public_profile_browsemap_profile-result-card_result-card_full-click)  
📬 aaditi26002@gmail.com

---

> **Note:** This is a live project and under active development. Contributions, suggestions, and feedback are welcome!





