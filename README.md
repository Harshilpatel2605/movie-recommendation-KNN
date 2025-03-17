🎬 KNN Movie Recommendation System

A collaborative filtering-based movie recommender using K-Nearest Neighbors (KNN). This system suggests similar movies based on user ratings.
📌 Features

✅ Movie Similarity: Finds similar movies based on user ratings.
✅ KNN with Cosine Similarity: Uses scikit-learn's NearestNeighbors to identify closest movies.
✅ Fuzzy Matching: Handles slight spelling mistakes in movie titles using fuzzywuzzy.
✅ Sparse Matrix Representation: Converts user-movie interactions into an optimized sparse matrix for faster computation.
🛠️ Technologies Used

    Python
    pandas (Data processing)
    scikit-learn (KNN model)
    scipy (Sparse matrix representation)
    fuzzywuzzy (Fuzzy string matching for movie titles)

📂 Dataset

This project uses MovieLens dataset:

    movies.csv → Contains movie IDs and titles.
    ratings.csv → Contains user ratings for movies.

🚀 Installation & Setup
1️⃣ Clone the Repository

git clone https://github.com/yourusername/knn-movie-recommender.git
cd knn-movie-recommender

2️⃣ Install Dependencies

pip install pandas scikit-learn scipy fuzzywuzzy python-Levenshtein

3️⃣ Run the Script

python recommender.py

🎯 How It Works

    Loads movie ratings from ratings.csv and movies.csv.
    Converts the data into a sparse matrix to optimize performance.
    Uses K-Nearest Neighbors (KNN) with cosine similarity to find similar movies.
    Accepts a movie name as input and suggests similar movies.

🔍 Example Usage

recommender('Interstellar', mat_movies_users, model_knn, 5)

Output:

Movie Selected: Interstellar  
Searching for recommendations...  
1. Inception  
2. Gravity  
3. The Martian  
4. 2001: A Space Odyssey  
5. Contact  

📜 To-Do / Future Enhancements

    ✅ Improve recommendation accuracy
    ⏳ Add a user-based recommendation model
    ⏳ Deploy as a web app using Flask/Streamlit

🏆 Contributing

Feel free to fork this project and submit pull requests! 🎉
