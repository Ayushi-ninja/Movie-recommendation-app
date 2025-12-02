🎬 Movie Recommendation App

A project built as part of my Microsoft Azure AI-102 Add-on Course

This project is a simple Python-based Content-Based Movie Recommendation System that recommends similar movies based on user input. It demonstrates fundamental concepts of data preprocessing, similarity scoring, and recommendation logic — skills relevant to AI engineering and Azure-based intelligent applications.

🚀 Features

📌 Recommends movies based on similarity

🧠 Uses content-based filtering

📂 Lightweight & beginner friendly

🐍 Implemented entirely in Python

🔧 Easy to expand into a full ML/Azure project

📁 Project Structure
Movie-recommendation-app/
│
├── rec.py                # Main movie recommendation script
├── myenv/                # Virtual environment (ignored in Git)
└── README.md             # Project documentation

🛠 Technologies Used

Python 3.x

Pandas – Data handling

NumPy – Numerical operations

Scikit-Learn (optional) – Vectorization / similarity

▶️ How to Run the Project
1️⃣ Clone this repository
git clone https://github.com/Ayushi-ninja/Movie-recommendation-app.git
cd Movie-recommendation-app

2️⃣ (Optional but recommended) Create a virtual environment
python -m venv myenv

3️⃣ Activate the virtual environment

Windows:

myenv\Scripts\activate

4️⃣ Install dependencies

If a requirements.txt exists:

pip install -r requirements.txt


Or install manually:

pip install pandas numpy scikit-learn

5️⃣ Run the script
python rec.py

🧠 How It Works

Loads movie dataset

Extracts features such as genre, keywords, or descriptions

Converts text data into numerical vectors

Calculates similarity scores between movies

Returns the top recommended movies

🎯 Purpose of This Project

This project was created as part of my Microsoft Azure AI-102 Add-on Course, focusing on:

Understanding fundamental AI workflows

Preparing for building intelligent solutions

Strengthening skills in Python & machine learning

Practicing recommendation system concepts before deploying on Azure

📌 Future Improvements

Add a Streamlit or Flask web UI

Deploy the model to Azure App Service

Add Azure Cognitive Search

Add Collaborative filtering for better recommendations

Build an end-to-end Azure pipeline

🤝 Contributing

Contributions, issues, and suggestions are welcome!

👤 Author

Ayushi Rajput
