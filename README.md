# Graha.AI – 2D AI Home Plan Predictor
AI-powered 2D home plan generator: Python ML backend + Flask web interface.
---

## Overview
- **Backend:** Python Flask server using a K-Nearest Neighbors (KNN) model to predict house floor plans.  
- **Frontend:** HTML, CSS & JavaScript integrated via Flask templates.  
- **Purpose:** Predict a suitable 2D home plan based on user inputs (bedrooms, bathrooms, garage, etc.).

---

## Tech Stack

### Frontend
- HTML  
- CSS  
- JavaScript  
- Flask Templates  

### Backend
- Python  
- Flask  
- scikit-learn (KNN model)  
- numpy, pandas  

### Machine Learning
- **Model:** K-Nearest Neighbors (KNN)  
- **Dataset:** Custom floor plan dataset (rooms, garage, labels, etc.)
---

Project structure (important files)

app.py — main Flask application

model/knn_model.pkl — trained KNN model

static/ — CSS, JS, images

templates/ — HTML UI

dataset/ — floor plan dataset used for model training

requirements.txt — project dependencies
## Quick start (development)

### Clone the repository:
```powershell
git clone https://github.com/SRAJANSHETTY8/GRAHA.AI.git
cd GRAHA.AI
```
Install required dependencies:
```powershell
pip install -r requirements.txt
python app.py
```
Windows:
```powershell
python -m venv venv
```
MacOS/Linux:
```powershell
python3 -m venv venv
```
Activate venv
Windows:
```powershell
.\venv\Scripts\activate
```
MacOS/Linux:
```powershell
source venv/bin/activate
```
How it works

User enters details (bedrooms, bathrooms, garage, etc.).

Input is passed to the trained KNN model.

The algorithm finds the closest matching floor plan from the dataset.

Predicted 2D home layout is displayed on the UI.

Note:


Adding more labeled images improves prediction accuracy.

Model parameters can be tweaked for better performance.

Developers:

© All rights reserved by Srajan Shetty


![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/f984d51144bfeded10e32d3453078a8944492537/readme%20img/ai01.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/d563f49361c65aa1cdb42daef5ea1fe502878851/readme%20img/ai02.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/d7adeaf41aea321f299e4296c2598cc48fb37b48/readme%20img/ai03.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/bc774ec3e2cb8c979e3f4ce26c888921c0f83628/readme%20img/ai04.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/23b6046a8cdb0e3c141bc53ad41d99f36584a782/readme%20img/ai05.png)

