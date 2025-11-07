# 🎬 Movie Recommendation System

This project builds a **Movie Recommendation System** using Machine Learning techniques.  
It uses user ratings, genres, and movie metadata to recommend movies similar to a user’s preferences.

Two different implementations are provided:
- **Jupyter Notebook Version** – Local execution using scikit-learn.
- **Google Colab Version** – Cloud-based implementation with similar workflow.

---

## 📊 Dataset
The dataset (`movies_dataset.xlsx`) contains details such as:
- Movie titles  
- Genres  
- Ratings  
- User interactions  

---

## ⚙️ Features
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Similarity-based recommendation (cosine similarity)  
- Machine Learning-based recommendation (content-based filtering)  
- Performance evaluation  

---

## 💻 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/MovieRecommendation.git
   cd MovieRecommendation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run any notebook:
   - `notebooks/MovieRecommendation_Jupyter.ipynb`  
   - `notebooks/MovieRecommendation_Colab.ipynb`

---

## 🧩 Libraries Used
- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib / seaborn  

---

## 📈 Results
Both notebooks provide prediction outputs and movie recommendations based on the model.

---

## ✨ Future Work
- Add collaborative filtering  
- Integrate with a web interface using Flask or Streamlit  
- Include user authentication for personalized recommendations

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
