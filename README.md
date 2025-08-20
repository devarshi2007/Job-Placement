 Placement Prediction System Using Machine Learning

 Overview
A machine learning project that predicts whether a student will get placed based on academic and extracurricular details.  
It integrates data visualization, a Logistic Regression model, and an interactive Tkinter GUI for real-time predictions.



 Features
- Data Visualization: gender distribution, stream count, CGPA & SSC histograms, placement status, etc.  
- Machine Learning: Logistic Regression with balanced class weights and categorical encoding.  
- Interactive GUI: Tkinter app where users enter student details and get:  
- Placement status (Placed / Not Placed)  
- Probability of placement  



 Dataset
`placementdata1.csv` includes:  
- Inputs: Age, Gender, Stream, SSC Marks, CGPA, Masters, Internships, Projects, International Competitions, Extracurricular Activities, Placement Training  
- Target: PlacedOrNot (Placed / NotPlaced)  



 Tech Stack
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `joblib`, `tkinter`  



 How to Run
```bash
# Clone repo
git clone https://github.com/yourusername/job-placement-predictor.git
cd job-placement-predictor

# Install dependencies
pip install -r requirements.txt

# Run application
python placement_app.py
