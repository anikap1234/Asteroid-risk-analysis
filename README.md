# Asteroid-risk-analysis

# Overview
This project analyzes NASA's asteroid data to classify asteroids as **potentially hazardous** or **non-hazardous** based on their orbital and physical characteristics. The model is built using **machine learning** and **data visualization techniques** to understand asteroid risk factors.

# Dataset
The dataset is sourced from NASA's **Near-Earth Object (NEO) Database**:
- **Features Used**:
  - `h_mag` (Absolute magnitude - brightness)
  - `moid_au` (Minimum orbit intersection distance with Earth in AU)
  - `i_deg` (Orbital inclination in degrees)
  - `pha` (Potentially Hazardous Asteroid - Target variable: Yes/No)

# Workflow
1. **Data Preprocessing**
   - Selected relevant features
   - Converted categorical values (`pha`) to numeric (1 = Hazardous, 0 = Non-Hazardous)
   - Handled missing values
   
2. **Exploratory Data Analysis (EDA)**
   - Used **scatter plots** to visualize asteroid properties (size vs. distance)
   - Applied **Seaborn** for color-coded risk levels

3. **Machine Learning Model**
   - **Random Forest Classifier** trained on asteroid data
   - Train-Test Split: 80% training, 20% testing
   - Balanced class weights for fair predictions

4. **Model Evaluation**
   - **Classification Report**: Precision, Recall, F1-score
   - Accuracy assessment on test data
   - Sample predictions with real data


## Results & Insights
- Most hazardous asteroids have **low MOID (closer to Earth)** and **higher brightness (lower h_mag)**

## Future Enhancements
- Implement **3D asteroid motion visualization**
- Explore **deep learning models** for improved predictions
- Integrate **real-time asteroid tracking** using NASA APIs

## Credits
- **NASA JPL NEO Dataset**
- **Scikit-learn & Seaborn** for machine learning & visualization

---
🔭 **Explore Space, Stay Curious!** 🚀
