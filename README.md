REGRESSION PROJECT-
-OBJECTIVE:“To predict global stock market performance using Machine Learning and identify the best model for forecasting PortfolioOpen.”
🔹 Project Overview
Applied Machine Learning to predict global stock market performance

Target variable: PortfolioOpen
ARRIBUTES:
PortfolioOpen – Total value of portfolio at the start of trading day (Target)
PreviousIndiaTradingDate 
PreviousPortfolioClose 
PreviousNIFTY50Close 
PreviousUKTradingDate 
PreviousFTSE100Close 
PreviousUSTradingDate 
PreviousSNP500Close 
HongKongTradingDate 
HANGSENOpen 
BRENTClose 
GOLDClose 
BTCINR 
PreviousUS5yrBondYieldClose 
PreviousIndia5yrBondYieldClose 
USDINRLastClose 
GBPINRLastClose

Compared multiple regression models
Features: 17 | Target: PortfolioOpen
Sources: global stock exchanges, forex rates, bond yields, crypto prices.

*Preprocessing steps:
-Missing values handled (median imputation)
-Outliers treated (IQR method)
-Dropped irrelevant columns
-Converted categorical to numeric

*EDA Insights
-PortfolioOpen strongly correlates with PreviousPortfolioClose (~0.98).
-BTCINR moves opposite to bond yields.
-USDINR & GBPINR highly correlated (~0.79).
-Gold has little influence on portfolio changes.

*APPLIED DIFFERENT ML MODELS
-Best Model: Random Forest Regressor
-R² Score: 0.9541 (80:20 split)
-Ensemble methods (XGBoost, Gradient Boosting) also performed strongly.
-Simpler models (KNN, SVR) gave weaker results.

*DEEP ANALYSIS WAS CARRIED WITH THE HELP OF NEURAL NETWORK
*CONCLUSIONS WERE DRAWN-the best accuracy holds the value~0.9209 which occured in neural networks 
*THE BEST ACCURACY HOLDS FOR THE VALUE ~0.9209 WHICH OCCURED IN NEURAL NETWORKS

