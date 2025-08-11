Airbnb Price Prediction & Investment Analysis
This project predicts Airbnb listing prices and identifies top investment opportunities using multiple machine learning models. It processes and enriches listing data, compares model performances, and visualizes high-potential listings on interactive maps.

Features
Data Preprocessing & Feature Engineering:

Handles property attributes (beds, baths, room type, review scores, etc.)

Calculates advanced metrics such as price per accommodate, bed-bath ratio, and distance to downtown using the Haversine formula.

Machine Learning Models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Multi-Layer Perceptron (Neural Network)

Model Evaluation:

Compares models using MAE, RMSE, and R² Score.

Investment Scoring:

Custom scoring system factoring price thresholds, availability, and review ratings.

Visualization:

Interactive Folium maps highlighting top investment listings.

Tech Stack
Languages & Libraries: Python, Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Folium

Environment: Google Colab / Jupyter Notebook

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/airbnb-price-prediction.git
cd airbnb-price-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Upload the Airbnb dataset in the notebook when prompted.

Run the notebook cells to preprocess data, train models, and view results.

Explore investment opportunities via generated maps.

Applications
Real estate investment planning

Dynamic Airbnb pricing strategies

Tourism & location-based analytics

License
This project is licensed under the MIT License.

