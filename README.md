# Placement-Predictor-Model

## Project Overview
The Placement Predictor Model is a machine learning–based application designed to predict student placement outcomes using academic performance and skill-based attributes. This project helps analyze placement readiness and provides insights for improvement.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Dataset Description
The dataset consists of the following features:

- **CGPA** – Academic performance score  
- **Internships** – Number of internships completed  
- **Projects** – Number of academic/technical projects  
- **Skills** – Skill rating (out of 10)  
- **Aptitude** – Aptitude test score  
- **Placement** – Target variable (1 = Placed, 0 = Not Placed)

---

## Machine Learning Model
- **Algorithm Used:** Logistic Regression  
- **Problem Type:** Binary Classification  
- **Evaluation Metrics:** Accuracy Score, Confusion Matrix  

---

## Results
- The model achieved high accuracy on the test dataset  
- Successfully predicted placement outcomes for new student data  
- Visualized performance using a confusion matrix

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/snekavenu-cmyk/Placement-Predictor-Model.git

   ## Streamlit Web App
This project includes a Streamlit-based web application that allows users to input student details and predict placement outcomes in real time.

### Run the App
```bash
streamlit run app.py


