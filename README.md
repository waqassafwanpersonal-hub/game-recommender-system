# 🎮 Game Recommender System (KNN-Based)

## 📌 Project Overview
This project implements an interactive **Game Recommender System** using the **K-Nearest Neighbors (KNN)** algorithm.  
The system recommends games based on a user’s preferred **genre** and an optional **text description** of gameplay preferences.  
It includes **model evaluation metrics** and **visual outputs**, making it suitable for academic and portfolio use.

---

## 🚀 Features
- Genre-based and description-based game recommendations  
- KNN model with cosine similarity  
- Interactive user interface (Google Colab / Jupyter Notebook)  
- Bar chart visualization of recommendation scores  
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix  

---

## 🧠 Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- ipywidgets  

---

## 📂 Dataset Description
Each game entry contains:
- Game name  
- One or more genres  
- A text description  
- A primary genre (used for evaluation)

The dataset covers a wide range of genres, including Action, Shooter, RPG, Strategy, Racing, Sports, Horror, Simulation, and Adventure.

---

## ⚙️ How the System Works
1. Game genres are encoded using **MultiLabelBinarizer**  
2. Game descriptions are converted into numerical vectors using **TF-IDF**  
3. Genre and description features are combined into a single feature vector  
4. A **KNN model** finds the most similar games  
5. Results are displayed with similarity scores and visual charts  

---

## 📊 Model Evaluation
The system evaluates its performance using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

Evaluation compares the predicted nearest game’s genre with the actual primary genre.

> Note: Since this is a recommender system, evaluation metrics are used for performance demonstration rather than strict classification.

---

## 🖥️ User Interface
The interactive interface allows users to:
- Select a preferred game genre  
- Optionally enter a gameplay description  
- Generate recommendations and evaluation results  

All results appear only after user interaction.

---

## ▶️ How to Run
### Google Colab (Recommended)
1. Open Google Colab  
2. Paste the project code into a notebook cell  
3. Run the cell  
4. Use the UI to interact with the recommender system  

### Jupyter Notebook
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib ipywidgets
