🔥 Fire Weather Index (FWI) Prediction
A machine learning-based approach to predict the Fire Weather Index (FWI), a crucial metric used to assess wildfire risk. Built as part of my academic and AI/ML club engagement, this project reflects my passion for combining chemical engineering knowledge with data science to solve real-world environmental challenges.

🧠 Motivation
As a Chemical Engineering undergraduate at NIT Agartala with active involvement in the technical Clubs, I aimed to apply data-driven techniques to a socially relevant problem — wildfire prediction. This project showcases how domain knowledge, when fused with machine learning, can yield impactful solutions.

📌 Project Highlights
Cleaned and preprocessed historical weather datasets.

Performed exploratory data analysis (EDA) to identify influential features.

Implemented various regression models including CatBoost, Random Forest, and Linear Regression.

Tuned hyperparameters to minimize RMSE and improve model robustness.

Analyzed feature importance and interpreted results to align with physical weather insights.

🧰 Tools & Technologies
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, CatBoost

Platform: Jupyter Notebook

Version Control: Git & GitHub

📊 Dataset Features
The dataset includes key meteorological parameters:

Temperature (°C)

Relative Humidity (%)

Wind Speed (km/h)

Rainfall (mm)

These features were used to predict FWI using regression-based approaches.

🚀 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/aniketanand118/FWI-prediction.git
cd FWI-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:
Open FWI_Prediction.ipynb in Jupyter or your preferred IDE.

📈 Results
Best Model: RidgeCV Regressor

MAE: e.g., Mean Absolute Error:  0.5158

R² Score: e.g., R2 score:  0.9879

Model performance indicates promising predictive capability for wildfire risk assessment.

💡 Future Scope
Deploy the model using Flask or FastAPI for real-time predictions.