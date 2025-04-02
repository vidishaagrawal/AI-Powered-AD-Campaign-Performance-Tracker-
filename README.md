# 🎯 AI-Powered AD Campaign Performance Tracker

## 📖 Project Description
Advertising campaigns generate massive amounts of data, but understanding **what works** and **what doesn't** can be challenging. This project provides an **AI-powered analytics solution** to help marketers **optimize ad performance** by analyzing key metrics such as **Click-Through Rate (CTR), Cost Per Click (CPC), and Cost Per Acquisition (CPA).**

### 🌟 **Why This Project?**
✅ **Optimizing Ad Spend**: Helps businesses reduce costs while improving engagement.  
✅ **Data-Driven Decision Making**: Uses AI and Machine Learning to uncover insights.  
✅ **Performance Tracking**: Measures key performance indicators (KPIs) to improve marketing strategy.  

---

## 🔍 **How It Works**
The project follows these steps:

1️⃣ **Data Collection & Preprocessing**  
   - Loads the advertising dataset (`data.csv`).  
   - Cleans missing values and standardizes data.  

2️⃣ **Feature Engineering**  
   - Computes **CTR** = `clicks / impressions`  
   - Computes **CPC** = `spent / clicks`  
   - Computes **CPA** = `spent / total_conversion`  

3️⃣ **Exploratory Data Analysis (EDA)**  
   - Heatmaps, bar charts, and scatter plots to understand correlations.  

4️⃣ **Machine Learning Model**  
   - Uses a **Random Forest Regressor** to predict **CTR** based on ad spend, impressions, and other features.  
   - Evaluates model performance using **MAE, MSE, and RMSE.**  

5️⃣ **Results & Insights**  
   - Identifies the most **influential factors** affecting ad performance.  
   - Suggests strategies for improving CTR and reducing CPC.  

---

## 📊 **Dataset Information**
- **File Name**: `data.csv`  
- **Columns Included**:  
  - `ad_id`: Unique identifier for each ad.  
  - `impressions`: Number of times the ad was shown.  
  - `clicks`: Number of times users clicked the ad.  
  - `spent`: Total money spent on the ad.  
  - `total_conversion`: Number of leads generated.  
  - `approved_conversion`: Number of verified conversions.  

---

## 🛠️ **Installation**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/vidishaagrawal/AI-Powered-AD-Campaign-Performance-Tracker.git
cd AI-Powered-AD-Campaign-Performance-Tracker
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Notebook**
Open Jupyter Notebook or Google Colab and run `AI_Powered_AD_Campaign_Performance_Tracker.ipynb`.

---

## 🚀 **Technologies Used**
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn  
- **Machine Learning Model**: Random Forest Regressor  

---

## 📈 **Sample Visualization**
Here’s a correlation heatmap from the dataset:  

![Heatmap](https://your-image-link.com)

---

## 🔮 **Future Enhancements**
- 🛠 **Hyperparameter Tuning**: Use **GridSearchCV** for optimizing the Random Forest model.  
- 📊 **Dashboard Implementation**: Build a **Streamlit** or **Plotly Dash** web app to display real-time ad insights.  
- 🤖 **Deep Learning Integration**: Try **Neural Networks (TensorFlow/Keras)** for better prediction accuracy.  
- 📡 **Automated Data Collection**: Use APIs to pull live ad data from Google/Facebook Ads.  

---

## 🤝 **Contributing**
Contributions are always welcome! Feel free to fork the repo, raise issues, and submit pull requests.  

---

## 📜 **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
