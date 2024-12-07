Women’s Health Assistant

Welcome to Women’s Health Assistant, a comprehensive AI-powered application designed to support and empower women’s health and well-being. This app combines the power of machine learning, deep learning, and intuitive UI design to provide a one-stop solution for various women’s health needs.

Features

🩺 PCOS Detection
	•	Predicts the likelihood of Polycystic Ovary Syndrome (PCOS) using machine learning models.
	•	Requires inputs like age, BMI, medical history, and lifestyle data.

📅 Period Tracker
	•	Tracks menstrual cycles and predicts the next period date based on user inputs.
	•	Simplifies cycle management with an intuitive interface.

🖼️ Image-Based PCOS Detection
	•	Upload ultrasound images for AI-powered analysis to detect PCOS.
	•	Powered by deep learning using a trained image classification model.

🥗 Personalized Diet Plan
	•	Generates tailored diet plans to help manage PCOS and improve overall health.
	•	Considers weight, activity level, and dietary preferences.

🏠 Home Section
	•	Provides an overview of the app’s features and user-friendly guidance for navigation.

How to Use
	1.	Clone the Repository

git clone https://github.com/karankadyan/Women-Healthcare-Assistant.git  


	2.	Install Dependencies
Make sure you have Python installed. Then, run:

pip install -r requirements.txt  


	3.	Run the Application

streamlit run app.py  


	4.	Explore the Tabs
	•	Home: Get an overview of the app’s features.
	•	PCOS Detection: Enter medical details for PCOS prediction.
	•	Period Tracker: Track and predict your menstrual cycle.
	•	Diet Plan: Get a personalized diet plan.
	•	Image-Based PCOS Detection: Upload ultrasound images for PCOS detection.

Requirements
	•	Python: 3.8+
	•	Libraries:
	•	streamlit
	•	numpy
	•	tensorflow
	•	joblib
	•	pandas
	•	datetime

Models
	1.	PCOS Prediction Model
	•	Built using scikit-learn and saved as a .pkl file.
	2.	Image-Based PCOS Detection Model
	•	Built using TensorFlow and saved as a .keras file.

Screenshots

Feature	Description
PCOS Prediction	Input medical details for prediction.
Period Tracker	Track menstrual cycles.
Diet Plan	Personalized PCOS-friendly diet plans.
Image-Based Detection	Upload and analyze ultrasound images.

Future Improvements
	•	Add real-time notifications for period tracking.
	•	Expand the diet plan feature with more detailed recipes.
	•	Integrate additional health metrics for improved predictions.
	•	Add multilingual support for accessibility.

Contribution

Contributions are welcome!
	1.	Fork the repository.
	2.	Create a new branch for your feature.
	3.	Submit a pull request with a detailed explanation of your changes.

Acknowledgments

Special thanks to the open-source community and AI tools that made this project possible!

Let’s work together to make healthcare smarter and more accessible!
