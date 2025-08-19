# 🌾 FarmOK
AI-powered Smart Farming Web Application that helps farmers make data-driven decisions to improve crop yield and health


🔥 Motivation
Agriculture is the backbone of many economies, especially in countries like India where a large portion of the population depends on farming. However, farmers often face challenges like:

Choosing the right crop for their soil and climate

Deciding the right fertilizer balance

Detecting and curing plant diseases on time

FarmOK is developed to bring the power of Machine Learning and Deep Learning into agriculture, making farming smarter and more productive.

With this project, farmers (or users) can:

📊 Get crop recommendations based on soil and weather data

🌱 Receive fertilizer suggestions tailored to their crop and soil condition

🍂 Detect plant diseases by simply uploading a leaf image

📂 Features
1. Crop Recommendation
Input soil parameters (N-P-K values, temperature, humidity, pH, rainfall) and get the best crop suggestion for maximum yield.

2. Fertilizer Suggestion
Enter soil details and the crop you plan to grow, and FarmOK will suggest which nutrients are lacking or in excess, along with fertilizer recommendations.

3. Plant Disease Detection
Upload a photo of a plant leaf and the model will identify whether it’s healthy or diseased. If diseased, it provides information about the disease and possible treatments.

📊 Datasets
Crop recommendation dataset (open-source)

Fertilizer dataset (customized for this project)

Plant disease dataset (publicly available)

⚙️ Tech Stack
Languages: Python, HTML, CSS, JavaScript

Frameworks: Flask, Bootstrap

Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, PyTorch

Deployment: Heroku / Cloud hosting

Version Control: Git & GitHub

🚀 Deployment
FarmOK can be deployed on Heroku or any cloud platform.

Note: If using Heroku free tier, the server might take some time to wake up if inactive.

---

## 🖥️ How to Run Locally  

1. **Install** Git, and Anaconda/Miniconda.  

2. **Clone the repository:**  
```bash
git clone https://github.com/kalesh-94/FarmOK 
```

3. **Create a virtual environment:**
```
conda create -n farmok python=3.6
conda activate farmok
```

4. **Install dependencies:**
```
pip install -r requirements.txt
```

5. **Run the application:**
```
python app.py

```

Open the link provided in the terminal (usually: http://127.0.0.1:5000/) in your browser.


🔮 Future Improvements
Improve UI with better frontend design

Add more crops and diseases to the database

Collect more real-world data to increase accuracy

Make the platform multilingual for better farmer accessibility

👨‍💻 Author
FarmOK is designed and developed by Kalesh Patil.
