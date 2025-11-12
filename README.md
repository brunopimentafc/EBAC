📊 Telemarketing Analysis App

An interactive Streamlit dashboard for exploring and analyzing telemarketing campaign data from a Portuguese bank. This project allows users to apply dynamic filters, visualize acceptance rates, and download filtered datasets for deeper insights.

🚀 How to Run Locally

Install dependencies:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run telemarketing_clean.py

Access the app:
Once launched, Streamlit will display a local URL such as:
http://localhost:8501

Open it in your browser to explore the dashboard.

✨ Features

🧭 Dynamic filters for multiple columns (age, profession, contact method, loan, month, etc.)

📈 Comparison between raw and filtered acceptance rates

📥 Downloadable filtered dataset (Excel format)

📊 Dual visualization: choose between bar or pie charts

🧩 Interactive sidebar for exploring subsets of the data

🎨 Clean UI using Seaborn and Matplotlib visualizations

📁 Project Structure

meu_projeto_streamlit/
├── telemarketing_clean.py
├── requirements.txt
├── README.md
├── data/
│ └── input/
│ └── bank-additional-full.csv
├── img/
│ └── Bank-Branding.jpg
├── py/
└── venv/

🧠 Notes

Ensure your dataset is located at:
data/input/bank-additional-full.csv

If running locally with a virtual environment, activate it first:
venv\Scripts\activate

The application was built for educational purposes and is part of the EBAC Data Science course.

💡 About the Project

This app was developed to analyze the effectiveness of telemarketing campaigns, focusing on client acceptance (“yes”) versus rejection (“no”) rates. It allows users to understand how demographic and campaign factors influence outcomes, offering a visual and data-driven exploration experience.

Developed by Bruno Pimenta
🎓 EBAC Data Science Course Project