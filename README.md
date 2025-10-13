# Music-Recommendation-System
The Spotify Recommendation System suggests songs based on audio features like tempo, energy, and valence using KNN, CNN, and Logistic Regression. It integrates Spotify API for data retrieval and features an interactive Streamlit UI. Users input a song or preferences to receive real-time recommendations. Clone, install, and run to explore! 🎵🚀

Overview
The Music Recommendation System is a machine learning-based project designed to suggest songs based on user preferences. It leverages audio features such as tempo, energy, and valence to provide personalized music recommendations.

Features
✅ Content-Based Filtering – Recommends songs based on their audio characteristics.
✅ Spotify API Integration – Fetches song metadata and features.
✅ Machine Learning Models – Implements KNN
✅ User-Friendly Interface – Built using Streamlit for easy interaction.
✅ Real-Time Recommendations – Provides instant suggestions based on user input.

Technologies Used
🔹 Python – NumPy, Pandas, Scikit-learn, Matplotlib
🔹 Machine Learning – KNN
🔹 Streamlit – Creating an interactive UI

How It Works
1️⃣ Extract Audio Features – The system fetches song features from Spotify API.
2️⃣ Preprocess Data – Cleans and transforms data for analysis.
3️⃣ Train Models – Uses KNN to generate recommendations.
4️⃣ Generate Recommendations – Matches songs based on input features.
5️⃣ Display Results – Presents recommendations in a Streamlit UI.

Installation
sh
Copy
Edit
git clone 
cd 
pip install -r requirements.txt
streamlit run app.py
Usage
Enter a song name or select preferences.
The system fetches and processes song features.
Recommended songs are displayed instantly.
Contribution
💡 Contributions are welcome! Feel free to fork, star, and enhance the project.


