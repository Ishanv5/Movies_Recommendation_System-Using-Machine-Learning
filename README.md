🎬 Movies Recommendation System

A content-based movie recommendation system built with Streamlit, text vectorization, and cosine similarity.
It uses TMDb (The Movie Database) API and movie dataset to recommend similar movies based on content such as genres, keywords, cast, and crew

🚀 Features

Content-based recommendation using text vectorization and cosine similarity.

Integration with TMDb API to fetch posters and movie details.

Interactive Streamlit web app for a smooth user experience.

Clean UI where users can select a movie and get top recommended movies instantly.

🛠️ Tech Stack

Python

Streamlit (Frontend for app)

scikit-learn (Vectorization, cosine similarity)

pandas / numpy (Data handling)

requests (API calls to TMDb)

⚙️ How It Works

Data Preprocessing

Merged movie metadata (genres, keywords, cast, crew).

Converted text into feature vectors using CountVectorizer / TF-IDF Vectorizer.

Similarity Calculation

Used cosine similarity to compute similarity scores between movies.

Recommendation

When a user selects a movie, the system fetches the most similar movies based on cosine similarity scores.

Uses TMDb API to fetch posters and display them on the app.

🔑 TMDb API Setup

Create an account on TMDb
.

Get your API Key from your TMDb account.

Replace the placeholder key in your code with your actual API key:

api_key = "YOUR_TMDB_API_KEY"

📌 Example Recommendations

If you search for "The Dark Knight", you may get recommendations like:

Batman Begins

The Dark Knight Rises

Man of Steel

Inception

📖 Future Enhancements

Hybrid recommendations (content + collaborative filtering).

Add user-based rating system.

Deploy on Streamlit Cloud / Heroku / Render.

🤝 Contributing

Contributions are welcome! Feel free to fork this repo, raise issues, or submit pull requests.

📜 License

This project is licensed under the MIT License.

✨ Built with ❤️ using Streamlit, TMDb API, and Python.
