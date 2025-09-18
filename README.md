# 🎬 Movie Recommender System

A simple **Movie Recommendation System** built with **Python** and **Streamlit**.  
It recommends movies similar to the one you choose using pre-computed similarity scores and data from **TMDB API**.

---

## 🚀 Features
- Recommend top 5 similar movies to the selected movie.
- Fetch movie posters dynamically using **TMDB API**.
- Built with **Streamlit** for an interactive web interface.
- Uses pre-trained `.pkl` files (`movie_dict.pkl`, `similarity.pkl`, `movies.pkl`) for fast recommendations.

---

## 📂 Project Structure
movie-recommender/
│── app.py # Main Streamlit app
│── movie_dict.pkl # Dictionary of movies
│── movies.pkl # Movies dataset
│── similarity.pkl # Pre-computed similarity matrix
│── requirements.txt # Python dependencies
│── setup.sh # Setup script (for deployment)
│── Procfile # For deployment on Heroku
│── README.md # Project documentation

yaml
Copy code

---

## 🛠️ Installation & Usage

### 1️⃣ Clone the repository
git clone https://github.com/YOUR_USERNAME/movie-recommender.git
cd movie-recommender

2️⃣ Create a virtual environment (recommended)
bash
Copy code
python -m venv venv
source venv/bin/activate    # On Linux/Mac
venv\Scripts\activate       # On Windows

3️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt

4️⃣ Set up TMDB API key
Create a .env file in the root folder and add your TMDB API key:

ini
Copy code
TMDB_API_KEY=your_api_key_here
Or set it in your terminal:

bash
Copy code
# Windows
set TMDB_API_KEY=your_api_key_here

# Linux/Mac
export TMDB_API_KEY=your_api_key_here

5️⃣ Run the app
bash
Copy code
streamlit run app.py
Then open http://localhost:8501 in your browser.


2. (Optional) Add a screenshot of your app.  

Would you like me to also **generate a LICENSE file** (MIT) so your repo looks fully professional?
