The COVID-19 pandemic changed more than our health systems — it reshaped our mental landscape.
While society adapted to masks, online learning, and digital classrooms, students silently carried a different burden: rising anxiety, depression, sleep deprivation, and a loss of social connection.

This project investigates the psychological impact of COVID-19 on students, using real-world survey data to uncover patterns in mental health, lifestyle, and academic performance.

It’s not just an analysis — it’s a data-driven narrative of resilience, loss, and adaptation.

⸻

🎯 Project Objectives
Focus Area
Description
🧹 Data Preprocessing
Handle missing values, normalize scales, and prepare datasets for analysis.
📊 Exploratory Data Analysis (EDA)
Identify relationships between academic stress, sleep, and psychological states.
📈 Visual Insights
Build clear, emotional data stories using Seaborn, Matplotlib, and Plotly.
🤖 Machine Learning (Optional)
Apply clustering or classification (K-Means / Decision Trees) to detect mental health risk groups.
🧠 Actionable Outcomes
Translate findings into awareness strategies for educators and policy makers.

📂 Repository Structure

Mental-Health-Post-COVID/
│
├── data/
│   ├── mental_health_survey.csv
│
├── notebooks/
│   ├── 01_preprocessing.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_visualization.ipynb
│   ├── 04_predictive_analysis.ipynb
│
├── visuals/
│   ├── anxiety_correlation.png
│   ├── stress_heatmap.png
│   ├── sleep_quality_distribution.png
│
├── models/
│   ├── stress_predictor.pkl
│
├── requirements.txt
└── README.md
⚙️ Installation & Setup

To replicate this project on your local machine:
# Clone this repository
git clone https://github.com/afsar426/mental-health-post-covid.git
cd mental-health-post-covid

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
🧾 requirements.txt

pandas==2.2.1
numpy==1.26.4
matplotlib==3.9.0
seaborn==0.13.2
plotly==5.22.0
scikit-learn==1.5.0
notebook==7.1.2

🔍 Methodology
	1.	Data Collection
	•	Dataset sourced from post-COVID student surveys and psychological studies.
	•	Includes variables: gender, age, academic load, sleep hours, anxiety level, depression index, and coping score.
	2.	Preprocessing
	•	Missing value imputation (mean/mode).
	•	Label encoding for categorical variables.
	•	Outlier detection using IQR and Z-score.
	•	Normalization with MinMaxScaler.
	3.	Exploratory Data Analysis (EDA)
	•	Correlation heatmaps for psychological metrics.
	•	Distribution plots for stress and sleep quality.
	•	Pairplots for demographic-lifestyle relationships.
	4.	Predictive Insights (Advanced Option)
	•	Logistic Regression / Random Forest for mental health risk prediction.
	•	K-Means clustering for segmenting students by coping behavior.
	5.	Visualization & Reporting
	•	Data storytelling using annotated graphs.
	•	Interactive dashboards (optional in Plotly).

⸻

📊 Key Insights
	•	💬 Anxiety levels increased by ~40% post-COVID.
	•	😴 Sleep deprivation strongly correlated with higher stress indices.
	•	📚 Students balancing academic + emotional stress showed lowest mental well-being scores.
	•	🧩 Early intervention and peer-based support reduce risk factors significantly.

⸻

📈 Example Visualizations

Graph
Description
🧮 Heatmap of Correlations
Shows interplay between stress, sleep, and grades.
🌙 Sleep Quality Histogram
Reveals post-COVID decline in regular sleep cycles.
💬 Anxiety vs. Academic Pressure
Scatterplot connecting workload to emotional distress.
❤️ Cluster Analysis (ML)
Visualizes clusters of mental health risk groups.
💭 Conclusion

This project reveals that the mental health impact of COVID-19 on students is a long-term challenge, not a temporary phase.
By combining data science and empathy, we can uncover silent struggles and inform educational systems to provide proactive support.

Data can’t heal emotions — but it can help us understand them.

⸻

🚀 Future Scope
	•	🧩 Integrate NLP sentiment analysis on student essays or journals.
	•	💻 Develop a simple web dashboard for schools to monitor emotional well-being.
	•	📱 Predictive alert system for high-risk students using real-time data inputs.
	•	🧬 Collaborate with psychologists for deeper model validation.

⸻

🧑‍💻 Author

Afsar Azam
B.Tech in Artificial Intelligence, Sage University, Indore
Frontend Developer • Data Analyst • AI Research Enthusiast
