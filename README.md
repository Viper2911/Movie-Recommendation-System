# 🎬 Movie Recommender System

A simple **Content-Based Movie Recommender System** built using Streamlit, Pandas, and Pickle. Given a movie selected by the user, the system recommends 5 similar movies based on content similarity.

---

## 🚀 Features

- 🎥 Select a movie from the dropdown  
- 🔍 Get 5 similar movie recommendations instantly  
- 💡 Content-based filtering approach  
- 🌐 Clean and responsive UI using Streamlit  

---

## 🧠 How It Works

The system uses **content-based filtering**, where movies are recommended based on similarity scores calculated from features like genres, keywords, cast, and crew.

- Movie data is processed and transformed into vectors  
- Similarity is computed using cosine similarity  
- Top 5 most similar movies are returned  

---

## 🧱 Tech Stack

- Python  
- Streamlit – UI framework  
- Pandas – Data handling  
- Pickle – Model/data serialization  
- Scikit-learn – Similarity computation  

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
```

### 2. Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

Activate it:

- **Windows**
```bash
venv\Scripts\activate
```

- **Linux / macOS**
```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open in browser:

```
http://localhost:8501
```

---

## 📂 Project Structure

```
movie-recommender-system/
│── app.py
│── movies.pkl
│── similarity.pkl
│── requirements.txt
│── README.md
```

---

## 🖥️ UI Preview

```
+-------------------------------------------------------------+
|                Movie Recommender System                     |
+-------------------------------------------------------------+
| Select a movie you like: [Inception ▼]                      |
|                                                           |
|                      [ Recommend ]                         |
|                                                           |
|  ┌──────────┬──────────┬──────────┬──────────┬──────────┐  |
|  │ Movie 1  │ Movie 2  │ Movie 3  │ Movie 4  │ Movie 5  │  |
|  └──────────┴──────────┴──────────┴──────────┴──────────┘  |
+-------------------------------------------------------------+
```

---

## ✨ Future Improvements

- 🎭 Add movie posters using TMDB API  
- ⭐ Include ratings and reviews  
- 🔍 Add search functionality  
- 🤖 Hybrid recommendation system (content + collaborative)  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.
