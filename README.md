# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using Python, Pandas, Scikit-learn, and Streamlit. The application recommends movies similar to a selected movie by analyzing metadata such as genres, cast, keywords, overview, and other textual features. The recommendation engine uses Count Vectorization and Cosine Similarity to identify and rank similar movies efficiently.

## 🚀 Features

* Search and select movies from the dataset
* Get top recommended similar movies instantly
* Content-based filtering approach
* Interactive and user-friendly Streamlit interface
* Fast recommendation generation using precomputed similarity scores

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* CountVectorizer
* Cosine Similarity

## 📊 How It Works

1. Movie metadata is collected and preprocessed.
2. Important features such as genres, keywords, cast, crew, and overview are combined into a single text field.
3. CountVectorizer converts textual data into numerical vectors.
4. Cosine Similarity calculates similarity scores between movies.
5. The system recommends the most similar movies based on these scores.

## 📂 Project Structure

Movie-Recommendation-System/
│
├── app.py
├── movie_list.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
└── assets/

## ⚡ Installation

Clone the repository:

git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system

Install dependencies:

## Download
[Download Model from Hugging Face](https://huggingface.co/datasets/your-username/your-repo)

pip install -r requirements.txt

Run the application:

streamlit run app.py

## 🎯 Example

Input:
Avatar

Output:
Guardians of the Galaxy
John Carter
Star Trek
The Fifth Element
Aliens


## 🔮 Future Improvements

* Hybrid recommendation system
* User authentication
* Personalized recommendations
* Genre-based filtering
* Rating prediction
* Deep learning-based recommendations

## 👨‍💻 Author

Akshat Mehrotra

B.Tech CSE Student | AI/ML Enthusiast 

If you found this project useful, consider giving it a ⭐ on GitHub.
