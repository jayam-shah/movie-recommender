# 🎬 Movie Recommender System

A simple and elegant **Movie Recommender System** built using **Python** and **Streamlit**, allowing users to get personalized movie suggestions in a visually intuitive interface.

## 🔍 Overview

This application helps users find movies similar to a selected title using **cosine similarity** on a precomputed movie dataset. It displays the movie posters alongside their names for a visually engaging recommendation experience.

## 🚀 Features

- 🧠 Content-based movie recommendations
- 📽️ Displays movie posters using TMDb API
- ⚡ Built with Streamlit for fast and interactive UI
- 🧪 Easy to run locally with minimal setup
- 🛠️ Modular and readable code

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas, NumPy
- Requests (for API calls)
- TMDb API
- PyCharm (for development)

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system
````

### 2. Install Dependencies

Make sure you have Python 3.8+ installed.

```bash
pip install -r requirements.txt
```

### 3. TMDb API Key Setup

* Go to [The Movie Database (TMDb)](https://www.themoviedb.org/) and sign up.
* Generate a free API key.
* Replace the placeholder in your code with your TMDb API key:

```python
api_key = 'YOUR_API_KEY_HERE'
```

> 🛡️ Make sure not to expose your API key publicly. Store it in environment variables or a config file for production.

## ▶️ Running the App

```bash
streamlit run app.py
```

## 🖼️ Screenshots

> You can add screenshots or screen recordings of your app here.

Example placeholder:

```
<img width="1463" height="653" alt="Screenshot 2025-07-16 at 1 08 55 AM" src="https://github.com/user-attachments/assets/1feaebf9-bc22-4c0e-b9ea-1093dcb74523" />

```

## 📁 Project Structure

```
├── app.py                 # Main Streamlit app
├── movies.pkl             # Pickled movie data (metadata)
├── similarity.pkl         # Pickled similarity matrix
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

## 💡 How It Works

* Loads a list of movies and a precomputed similarity matrix using `pickle`.
* On selecting a movie, it retrieves the top 5 similar movies using cosine similarity.
* Fetches posters of recommended movies using TMDb API and displays them in a Streamlit layout.

## 🧑‍💻 Developed By

**JD Shah**
Master's in Data Analytics, San Jose State University
[LinkedIn]([https://www.linkedin.com/in/jayamshah2278/]) | [GitHub](https://github.com/jayam-shah)

---

**Note:** This project is for educational and demonstration purposes only.
---

📌 Just replace:
- `YOUR_API_KEY_HERE` with your actual TMDb API key.
- `yourusername` with your GitHub username.
- Screenshot placeholder if you'd like to include images or gifs.
