# 🚀 Security Analytics with AI: UNSW-NB15 Dataset Analysis

## 📊 Project Overview
Analyze the UNSW-NB15 dataset for network intrusion detection using machine learning, focusing on decision tree classifiers. The goal is to identify and classify malicious network activities.

## 🗂️ Dataset Details
- **Features:** 49 attributes describing network traffic
- **Classes:** 9 attack types + normal traffic
- **Task:** Binary classification — Normal (`1`) vs Attack (`0`)

## 📁 Project Structure
- Data preprocessing and exploration
- Feature engineering and selection
- Model training and evaluation
- Visualization of results

## 🛠️ Technologies Used
- Python (Pandas, Scikit-learn, Matplotlib)
- Jupyter Notebook

## 📚 References
- [UNSW-NB15 Dataset](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/CS502M-Security-Analytics.git
cd CS502M-Security-Analytics
```

### 2. Install Dependencies
```bash
bashpip install -r requirements.txt
```
### 3. Download Dataset
Download the UNSW-NB15 dataset files and place them in the data/ folder:

`UNSW_NB15_training-set.csv`
`UNSW_NB15_testing-set.csv`
`NUSW-NB15_features.csv`

### 4. Run Analysis
Open and run the Jupyter notebook:
```bash 
jupyter notebook notebooks/UNSW_NB15_Analysis.ipynb
```

*For questions or contributions, feel free to open an issue or submit a pull request!*
