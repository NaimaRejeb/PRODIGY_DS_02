# Aviation Crash Data Analysis - Exploratory Data Analysis (EDA)

## 📌 Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on aviation crash data, examining trends in flight accidents, fatalities, aircraft types, operators, and damage classification. The dataset contains records of aviation incidents with details on dates, locations, and severity.

## 📊 Dataset Features
- `acc.date`: Date of accident
- `type`: Aircraft model
- `reg`: Registration number
- `operator`: Operating company
- `fat`: Number of fatalities
- `location`: Accident site
- `dmg`: Damage classification (e.g., "w/o" = write-off, "sub" = substantial)

## 🔍 Key Analyses Performed
1. **Temporal Trends**: Accident frequency by year/month
2. **Aircraft Analysis**: Most accident-prone models
3. **Operator Risk**: Companies with highest incident rates
4. **Fatality Analysis**: Distribution and worst accidents
5. **Geographic Patterns**: Dangerous locations
6. **Damage Classification**: Severity distribution

## 🛠️ Technologies Used
- Python 3
- Pandas (Data manipulation)
- Matplotlib/Seaborn (Visualization)
- Jupyter Notebook (Analysis environment)


## 🚀 How to Run
**Option 1: Local Setup**
1. Clone repository
2. Install requirements: `pip install pandas matplotlib seaborn jupyter`
3. Launch Jupyter: `jupyter notebook`
4. Open and run `Aviation_EDA.ipynb`

**Option 2: On Kaggle**  
[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/naiimarejeb/task02)  
You can run the analysis directly on Kaggle without any installation.

## 📈 Sample Findings
- Beechcraft models appear frequently in accident data
- Many accidents with 0 fatalities (training incidents?)
- "w/o" (write-off) is most common damage classification

## 🤝 Contributing
Pull requests welcome!

