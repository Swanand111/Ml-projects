# 🎬 Movie Recommender System

This project is a **Content-Based Movie Recommender System** built using **Python, Streamlit**, and **scikit-learn**. It suggests movies similar to the one you select — using cosine similarity between movie features.

<br>

## 🚀 Live Demo

🔗 [Click here to try it live on Streamlit](https://swanand111-ml-projects.streamlit.app)

<br>

## 🧠 Features

- 🔍 Recommend 5 similar movies based on title
- 🖼️ Show movie posters via TMDB API
- 📦 Deployed on Streamlit Cloud
- 📁 Uses large ML model file via Git LFS

<br>

## 📂 Project Structure

├── app.py # Streamlit app
├── movie_dict.pkl # Movie data dictionary
├── similarity.pkl # Similarity matrix (tracked by Git LFS)
├── requirements.txt # Python dependencies
└── README.md # Project overview


<br>

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**: pandas, scikit-learn, requests
- **Deployment**: Streamlit Cloud
- **API**: [The Movie Database (TMDB)](https://www.themoviedb.org/)

<br>

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Swanand111/Ml-projects.git
cd Ml-projects


<br>

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**: pandas, scikit-learn, requests
- **Deployment**: Streamlit Cloud
- **API**: [The Movie Database (TMDB)](https://www.themoviedb.org/)

<br>

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Swanand111/Ml-projects.git
cd Ml-projects

pip install -r requirements.txt

streamlit run app.py

📌 Note on Large Files
This repo uses Git LFS to store similarity.pkl (over 100MB).
If you're cloning this repo, make sure to install LFS first:

bash
Copy
Edit
git lfs install
git lfs pull
<br>
🙋‍♂️ About Me
👨‍💻 Developed by Swanand Mahadik
📫 Reach me at: LinkedIn (replace with your link)

⭐ Star this repo if you found it helpful!
yaml
Copy
Edit

---

## 📌 To Add it to GitHub

1. Create a new file named `README.md` in your project folder.
2. Paste the content above.
3. Commit & push:

```bash
git add README.md
git commit -m "Add project README"
git push
