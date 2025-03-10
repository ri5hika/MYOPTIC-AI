![image](https://github.com/user-attachments/assets/4fb4f70a-9340-4d2c-b45d-d7eece80b3de)![image](https://github.com/user-attachments/assets/d0bef046-21d8-4b42-a964-e6e1d36d3b95)# MyOptic AI
This is an Artificial Intelligence Driven Multi-Model Framework for Vision Care. It integrates deep learning, machine learning, and natural language processing to provide a comprehensive AI driven Vision Care system. The CNN based analysis enables accurate detection of retinal abnormalities through image processing, while the RFC prediction model offers data driven insights based on numerical parameters. Additionally, the LLM chatbot enhances user engagement by providing interactive consultations and personalized recommendations. By combining these three approaches, this tool aims to assist individuals in monitoring their eye health efficiently, promoting early detection, and encouraging preventive care.

# Overview
Myopia is a global pandemic. With increasing screen time, reduced outdoor activities, and genetic predisposition, the prevalence of myopia is rising at an alarming rate. If left unmanaged, progressive myopia can lead to severe complications such as retinal detachment, glaucoma, and even vision loss. This model analyzes user input and retinal images to predict and monitor severity of a case while controlling the progression with the help of a recommendation system. MyOptic AI is built using Python, FastAPI, HTML, CSS, JS.

# Install dependencies
pip install -r requirements.txt

# Methodology
This project uses multi-model approach and has 3 phases – 
1. Convolutional Neural Network (CNN) analyzes retinal scans and other  images, they are then compared with existing dataset to detect abnormalities indicative of myopia progression, glaucoma, and potential retinal detachment.
2. Random Forest Classifiers (RFC) processes the numerical parameters entered by the users to predict the probability of a  patient having Myopia.
3. An AI integrated LLM chat-bot recommendation system that suggests best preventive measures using supervised and unsupervised learning. To ensure seamless functionality, the backend of the system is built using FastAPI and Python, paired with an optimal web framework that supports real-time inference and efficient processing of AI models.
The approach will finally generate a detailed risk assessment report, highlighting potential concerns and suggesting preventive measures.
