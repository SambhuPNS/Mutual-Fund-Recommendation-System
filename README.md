
# Mutual Fund Recommendation System  
### *A Personalized Investment Advisor Powered by Machine Learning*  

## Overview  
The Mutual Fund Recommendation System is a machine learning-based project designed to recommend mutual funds tailored to individual users based on their demographics and investment goals. The system analyzes user data, evaluates mutual fund performance, and provides personalized recommendations with a focus on maximizing future returns.  

---

## Features  
- **User Profiling**:  
  Captures user demographics such as age, income, and investment goals to tailor mutual fund recommendations.  

- **Data Integration**:  
  - Processes mutual fund data extracted from Kaggle datasets.  
  - Fetches real-time NAV (Net Asset Value) data using the **MFAPI**.  

- **Similarity Matching**:  
  Maps user profiles and mutual fund attributes to a common vector space to identify the top 10 similar funds.  

- **Future Performance Prediction**:  
  - Benchmarked multiple forecasting models (**ARIMA, SARIMA, LSTM, Prophet**).  
  - Selected **Prophet** for its superior accuracy in predicting future CAGR (Compound Annual Growth Rate).  

- **Recommendation Engine**:  
  Recommends mutual funds with the highest predicted returns, ensuring user-centric investment advice.  

---

## Tech Stack  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Prophet, Matplotlib, Seaborn  
- **APIs**: [MFAPI](https://www.mfapi.in/) for real-time NAV data  
- **Data Source**: [Kaggle Mutual Fund Dataset](https://www.kaggle.com/)  

---

