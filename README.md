# Movie Recommendation System

This project is a **content-based Movie Recommendation System** built using **Python, Streamlit, and TMDB API**. The system suggests movies similar to the selected movie based on their feature similarity.

## Features
- Recommend similar movies based on content similarity.
- Fetches movie posters using the TMDB API.
- Interactive UI using **Streamlit**.
- Deployable on **Streamlit Community Cloud**.

## Technologies Used
- **Python**
- **Pandas**
- **Streamlit**
- **Scikit-learn** (for feature extraction and similarity computation)
- **Requests** (for fetching movie posters from TMDB API)
- **Pickle** (for saving precomputed models, though not included in GitHub due to file size constraints)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/MovieRecommenderSystem.git
cd MovieRecommenderSystem
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Generate `movie_dict.pkl` and `similarity.pkl`
Since `.pkl` files are not uploaded to GitHub, you need to generate them using `MovieRecommendersystem.ipynb`.
- Open the Jupyter Notebook `MovieRecommendersystem.ipynb`.
- Run all the cells to preprocess the data and generate `movie_dict.pkl` and `similarity.pkl`.
- Move the generated `.pkl` files to the `model/` directory.


## Folder Structure
```
MovieRecommenderSystem/
│── app.py                    # Streamlit Application
│── MovieRecommendersystem.ipynb # Jupyter Notebook for preprocessing
│── model/                     # Store generated `.pkl` files here
│── requirements.txt           # Dependencies
│── README.md                  # Project documentation
```

## Future Improvements
- Improve the recommendation model using **hybrid techniques** (content-based + collaborative filtering).
- Enhance UI/UX for a better user experience.
- Deploy as a web app with **Flask/Django** for a more scalable solution.

## Author
**Bhanuteja**

---
Enjoy recommending movies! 🎬🍿

