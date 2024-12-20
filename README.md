Graha.AI - 2D AI Home Plan Predictor



Graha.AI is an innovative web-based application that leverages Artificial Intelligence (AI) to generate custom floor plans for homes based on user inputs. This tool allows users to input the number of rooms, bathrooms, living areas, and other essential spaces, and the AI system will predict the most suitable floor plan based on these details.

Features:
AI-driven floor plan predictions: Using a pre-trained K-Nearest Neighbors (KNN) model, the system predicts the best floor plan based on user inputs.
Customizable inputs: Users can specify the number of bedrooms, bathrooms, garage, and other important spaces.
User-friendly interface: The frontend is built using Flask, making it intuitive and easy to interact with.
Image processing and visualization: Floor plans are visualized in a user-friendly format for a more interactive experience.
Scalable design: The backend is built to scale, capable of handling various user inputs and generating floor plans accordingly.


Tech Stack:

Frontend: HTML, CSS, JavaScript (Flask for integration)

Backend: Python, Flask


Machine Learning Model: K-Nearest Neighbors (KNN) algorithm

Dataset: Custom dataset containing floor plans and labels (rooms, garage, etc.)



Setup Instructions:

Prerequisites:

Python 3.x installed

Flask installed (pip install flask)

Required libraries: scikit-learn, numpy, pandas, etc.


Installation:

Clone the repository:
git clone https://github.com/SRAJANSHETTY8/GRAHA.AI.git

Navigate to the project directory:


cd GRAHA.AI

Install the required dependencies:


pip install -r requirements.txt

Run the Flask app:


python app.py


Visit http://127.0.0.1:5000/ in your web browser to interact with the application.

Create a virtual environment:

For Windows:

python -m venv venv

For MacOS/Linux:

python3 -m venv venv

Activate the virtual environment:

For Windows:


.\venv\Scripts\activate

For MacOS/Linux:

source venv/bin/activate

How it Works:

Users provide inputs such as the number of bedrooms, bathrooms, garage, etc.
The KNN model processes these inputs and predicts the most appropriate floor plan.
The predicted floor plan is displayed on the interface.

Please feel free to make any required changes based on your specific needs or preferences,For better accuracy in predictions, consider adding more images to the dataset.
You can modify the model parameters, update the UI, or adapt the dataset as needed to enhance the application further.

Developers:


Developed by Sraaz Developers.

![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/f984d51144bfeded10e32d3453078a8944492537/readme%20img/ai01.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/d563f49361c65aa1cdb42daef5ea1fe502878851/readme%20img/ai02.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/d7adeaf41aea321f299e4296c2598cc48fb37b48/readme%20img/ai03.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/bc774ec3e2cb8c979e3f4ce26c888921c0f83628/readme%20img/ai04.png)
![image alt](https://github.com/SRAJANSHETTY8/GRAHA-AI/blob/23b6046a8cdb0e3c141bc53ad41d99f36584a782/readme%20img/ai05.png)

