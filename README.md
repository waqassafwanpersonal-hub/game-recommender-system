# 🎮 Game Recommender System (KNN-Based)

## 📌 Project Overview
This project implements an interactive **Game Recommender System** using the **K-Nearest Neighbors (KNN)** algorithm.  
The system recommends games based on a user’s preferred **genre** and an optional **text description** of gameplay preferences.  
It also includes full **model evaluation** and **visual results**, making it suitable for academic submission.

---

## 🚀 Features
- Genre-based and description-based recommendations  
- KNN model with cosine similarity  
- Interactive user interface (Jupyter / Google Colab)  
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

The dataset includes a variety of genres such as Action, Shooter, RPG, Strategy, Racing, Sports, Horror, Simulation, and Adventure.

---

## ⚙️ How the System Works
1. Game genres are encoded using **MultiLabelBinarizer**  
2. Game descriptions are converted into numerical features using **TF-IDF**  
3. Genre and text features are combined into a single feature vector  
4. A **KNN model** identifies the most similar games  
5. Results are displayed along with similarity scores and graphs  

---

## 📊 Model Evaluation
The system evaluates its performance using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

Evaluation is performed by comparing the predicted nearest game’s genre with the actual primary genre.

> Since this is a recommender system, these metrics are used to demonstrate performance rather than strict classification accuracy.

---

## 🖥️ User Interface
The project includes an interactive interface that allows users to:
- Select a preferred game genre  
- Optionally enter a gameplay description  
- Generate recommendations and evaluation results  

All outputs appear only after user interaction.

---

## ▶️ How to Run
### Google Colab (Recommended)
1. Open Google Colab  
2. Paste the provided code into a notebook cell  
3. Run the cell  
4. Interact with the UI to receive recommendations  

### Jupyter Notebook
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib ipywidgets
