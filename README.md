# 📚 Book Recommender System

A machine learning-based recommendation system that suggests books to users based on popularity metrics and collaborative filtering. This project helps users discover new books by leveraging historical user ratings and book data.

---

## 🔍 Features

- 📈 **Popularity-Based Filtering**: Recommends books that are highly rated and widely read.
- 👥 **Collaborative Filtering**: Suggests books by analyzing similar users' preferences using a user-item matrix and cosine similarity.
- 📊 **Evaluation Metrics**: Includes a confusion matrix, precision, recall, and accuracy calculations to assess recommendation quality.
- 🧹 **Data Preprocessing**: Cleans and filters data to handle noise, missing values, and inconsistencies.
- 🖼️ **Visualizations**: Displays top-rated books, distribution of ratings, and user activity.

---

## 🧰 Tech Stack

- **Language**: Python
- **Libraries**:
  - `Pandas`, `NumPy` – Data handling
  - `scikit-learn` – Model building, evaluation
  - `Matplotlib`, `Seaborn` – Visualization
  - `scipy` – Similarity calculations
- **Data Source**: `Books.csv`, `Ratings.csv`, `Users.csv` (Book-Crossing dataset)

---

## 🚀 How It Works

1. **Data Loading & Cleaning**
   - Loads user, book, and ratings datasets.
   - Handles missing values and drops low-activity users/books.

2. **Popularity-Based Model**
   - Computes average ratings and number of ratings.
   - Filters books with sufficient popularity.

3. **Collaborative Filtering**
   - Builds a user-item matrix.
   - Applies cosine similarity between users to suggest books based on similar profiles.

4. **Evaluation**
   - Simulates user feedback.
   - Uses a confusion matrix and metrics like precision, recall, and accuracy for assessment.

---
## 📌 Future Improvements

- Integrate **content-based filtering** using book genres/descriptions.
- Deploy as a **web app** using Streamlit or Flask.
- Add a **user authentication system** for personalized recommendations.
- Use **deep learning** for hybrid recommendation models.

