# 🎯 Phishing Website Detector

This is a Machine Learning project to detect phishing websites using the **Random Forest Classifier**.

## 📁 Files in this Project

- `Phishing_website.ipynb` → Main Python code (Colab Notebook)
- `phishing_final_clean.csv` → Dataset used for training/testing

## 📊 Dataset Information

The dataset includes features like:

- UsingIP, LongURL, ShortURL, PrefixSuffix, SubDomains, HTTPS, DomainRegLen, PageRank, WebsiteTraffic, and more.
- `class` column is the target → `1` means phishing, `0` means safe website.

## 🤖 ML Algorithm Used

- **Random Forest Classifier**  
It is used because it gives good accuracy and works well for classification problems.

## ✅ Model Accuracy

- **Accuracy** = `96.78%`  
- **Classification Report**:

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0 (Safe) | 0.97 | 0.95 | 0.96 |
| 1 (Phishing) | 0.96 | 0.98 | 0.97 |

## 🔍 Confusion Matrix

![image](https://github.com/user-attachments/assets/dffade66-fb05-4eda-820b-dc7fb339e85c)

## 🧠 Tools and Libraries Used

- Python (Google Colab)
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib

## 💡 Feature Highlights

- ✅ `UsingIP` → Website has IP address instead of domain.
- ✅ `LongURL` → Is the URL suspiciously long?
- ✅ `PrefixSuffix-` → Uses hyphen in domain name?
- ✅ `HTTPS` → Has valid HTTPS or not?
- ✅ `PageRank`, `GoogleIndex` → Reputation factors

## 🚀 Future Scope

- Use Deep Learning models (like CNN) for better prediction.
- Deploy as a web application.
- Integrate real-time phishing detection in browsers.


## 🙋‍♀️ Made By

**Risha Gupta**  
MCA Student 



