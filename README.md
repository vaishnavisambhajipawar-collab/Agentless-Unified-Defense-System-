# 🛡️ Agentless Unified Defense System

Agentless Unified Defense System is a browser-based cybersecurity application designed to detect potentially phishing websites by analyzing URLs entered by the user.

## 🚀 Features

### 🔍 Phishing URL Detection

Analyze a website URL and identify potentially phishing websites.

### 🤖 Machine Learning Based

Uses a trained machine learning model for URL classification.

### 🌐 Web-Based Interface

Provides a simple interface for entering and checking URLs.

## 🛠️ Tech Stack

### Frontend

- HTML
- Tailwind CSS

### Backend

- Python
- Flask

### Machine Learning

- Scikit-learn
- Pandas
- NumPy
- Matplotlib

### 1. Clone the Repository

```bash
git clone https://github.com/vaishnavisambhajipawar-collab/Agentless-Unified-Defense-System-.git
cd Agentless-Unified-Defense-System-


````

OR

Download the ZIP file from GitHub and extract it.

### 2. Create a Virtual Environment

Creating a virtual environment is optional but recommended.

```bash
python -m venv venv
```

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

Install the required Python libraries:

```bash
pip install flask pandas numpy scikit-learn matplotlib
```

### 4. Run the Application

```bash
python app.py
```

The application will start on the local Flask server.

Open the following address in your browser:

```text
http://127.0.0.1:5000/
```

---

## 🔎 Usage

1. Open the application in your web browser.
2. Enter the website URL in the URL input box.
3. Click the Submit button.
4. The URL is processed by the application.
5. The trained machine learning model analyzes the URL.
6. The prediction result is displayed on the screen.

---

## 📊 Machine Learning

The project uses machine learning for phishing URL classification.

### Model Files

* `phishing.pkl` – trained phishing detection model
* `vectorizer.pkl` – saved feature vectorizer

### Dataset

* `phishing_site_urls.csv`

### Jupyter Notebook

* `Phishing Website Detection system.ipynb`

The notebook contains the data processing, analysis, machine learning experimentation, and model development.

---

## 🎯 Project Objective

The main objective of this project is to develop a browser-based cybersecurity system that can help identify potentially phishing websites using machine learning and URL analysis.

The system provides users with a simple way to check suspicious URLs before accessing them.

---





