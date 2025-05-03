Our Website is made for detecting any malicious behaviour in a PE file. If the uploaded PE file is malicious then it generates a warning message along with the log as a report for the same else if the file is safe it generates the alert and the log

---

## ⚙️ Prerequisites

1. Make sure Python (version 3.12.2) is installed on your system  
2. Install Django (version 5.0.2):  
   `pip install django`  
3. Install joblib:  
   `pip install joblib`  
4. Install scikit-learn:  
   `pip install scikit-learn`  
5. Install PEFILE library:  
   `pip install pefile`  
6. Install NumPy:  
   `pip install numpy`  

---

## 🚀 Steps to Access the Project

1. Navigate to the `bytedefender` project folder:  
   `cd bytedefender`  
2. Run the Django server:  
   `python manage.py runserver`  
3. Click on the URL shown in the terminal to access the website in your browser.

---

## 🖥️ Website Description

1. **HOME PAGE:**  
   Landing page for navigation across the website.

2. **SCAN PAGE:**  
   Requires user login/signup. Users can upload PE files to scan. The backend processes the file and redirects to a log page with the prediction and a report.

3. **HELP PAGE:**  
   Contains usage guidelines and frequently asked questions.

4. **ABOUT PAGE:**  
   Explains the purpose and details of the website.

5. **CONTACT PAGE:**  
   Allows users to submit queries using a contact form.

6. **LOGIN PAGE / SIGNUP PAGE:**  
   New users must sign up and verify via email before scanning. Registered users can log in directly and access the scan functionality.

---

 
