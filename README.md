# ByteDefender – Malware Detection System for Windows PE Files

ByteDefender is a machine learning-powered malware detection tool designed specifically for Portable Executable (PE) files on Windows. It analyzes static features and classifies files as malicious or benign using trained models.

## 🔍 Overview

- **Type**: Classification  
- **Approach**: Static analysis  
- **Tech Stack**: Python, Scikit-learn, Django, MySQL  
- **ML Models Used**: Random Forest, Support Vector Machine (SVM)  
- **Accuracy**: ~90%

## 🚀 Features

- Upload PE files via a web interface (Django)
- Extracts key features like section headers, entropy, size
- Classifies using ML model trained on labeled dataset
- Displays prediction results on the UI

## 🧠 Machine Learning

- **Feature Extraction**: Static analysis from PE header fields
- **Preprocessing**: Normalization and encoding of features
- **Model Training**: Used scikit-learn to train and evaluate models
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

## 🖥️ Tools & Libraries

- Python, Pandas, NumPy, Scikit-learn  
- Django (for web interface)  
- MySQL (for data storage)  

## 📁 Project Structure

```plaintext
ByteDefender/
├── frontend/           # Django templates and static files (HTML, CSS, JS)
├── backend/            # Django views, URLs, and logic
├── ml_model/           # Jupyter notebooks and model training scripts
├── trained_model.pkl   # Saved ML model file
├── media/              # Uploaded PE files (runtime)
├── db/                 # MySQL schema or SQLite DB file
├── manage.py           # Django entry point
└── README.md
```


## 📷 Demo

Add screenshots or a demo GIF here showing:
- File upload page
- Prediction result page

## ⚙️ How to Run Locally

1. Clone the repository  
2. Set up Python environment and install dependencies  
3. Run migrations and start Django server  
4. Navigate to `http://localhost:8000`  

## 📌 Future Improvements

- Integrate dynamic analysis techniques  
- Expand dataset to improve accuracy  
- Add file hash scanning with VirusTotal API

## 👩‍💻 Author

**Shivani Sharma**  
[LinkedIn](https://www.linkedin.com/in/shivanisharma2609) • [GitHub](https://github.com/shivani-00)


