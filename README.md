# 🧠 Wage Prediction Model – Data Mining Project

This repository contains a wage prediction model developed as part of a data mining project at Bahçeşehir University. The goal was to analyze real-world salary data and build a robust regression model to predict wages based on various demographic and professional features.

## 🔧 Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and preprocessing
- **Scikit-learn**: Model building, evaluation, and hyperparameter tuning
- **Jupyter Notebook**: Interactive development environment
- **Anaconda**: Package and environment management

## 📈 Project Highlights
- Handled missing values using median, mode, and custom category imputation.
- Performed exploratory data analysis and distribution checks for both categorical and numerical variables.
- Built a linear regression model and validated assumptions using statistical tests (RAINBOW, Durbin-Watson, Breusch-Pagan, White, Shapiro-Wilk, Kolmogorov-Smirnov).
- Applied multicollinearity analysis (VIF, correlation matrix) to improve model reliability.
- Used IQR capping and Z-scale normalization for preprocessing.
- Converted categorical variables into dummy variables.
- Tuned model parameters using Grid Search and Cross-Validation.
- Achieved an R² score of **0.902**, indicating strong predictive performance.

## 📚 Key Takeaways
This project emphasized the importance of practical data handling and model validation techniques over purely theoretical approaches. It also reinforced the value of reproducible workflows and statistical rigor in machine learning.

---

Feel free to explore the notebook and experiment with the model. Contributions and feedback are welcome!
