# 🚀 Resume Screening AI System

This project is an intelligent, AI-powered resume analysis system built using **Flask** and **Machine Learning**. It allows users to upload resumes in PDF or TXT formats and performs:

- 📂 **Resume Categorization** (using ML)
- 💼 **Job Recommendation** (based on predicted category)
- 📊 **Resume Parsing** (Name, Email, Phone, Skills, Education)

> ⚡ Smart, beautiful, and responsive web UI with animations and file preview.

---

## 🛠 Tech Stack

| Category | Technologies Used |
|----------|-------------------|
| Backend  | Python, Flask      |
| ML Model | TF-IDF + Random Forest |
| Frontend | HTML, CSS, JavaScript |
| Parsing  | `pdfminer.six`, Regex |
| Deployment Ready | ✅ Yes |

---

## ✨ Features

- Drag-and-click file upload with file name preview
- Support for `.pdf` and `.txt` resume formats
- Displays:
  - 📌 Predicted job category
  - 💡 Recommended job
  - 🧾 Extracted personal info (Name, Email, Phone)
  - 🛠 Skills and 🎓 Education
- Stylish gradient UI with fade and slide animations
- Responsive design (mobile-friendly)

---

## 🔧 How It Works

1. **User uploads a resume**
2. **Backend parses the content**
3. **ML model predicts category**
4. **Recommended job is suggested**
5. **Parser extracts key information (name, email, etc.)**
6. **Frontend displays everything cleanly**

---

## 🚀 Run Locally

### Clone the Repository
```bash
git clone https://github.com/your-username/resume-screening-ai.git
cd resume-screening-ai
Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

## Install Requirements
```bash
pip install -r requirements.txt
```
## Run the App
```
python app.py
```
### 📂 Folder Structure
```
resume-screening-ai/
│
├── templates/
│   └── index.html              # Web UI (HTML + Jinja2)
├── static/
│   └── style.css               # Stylesheet (optional if used)
├── models/
│   └── model.pkl               # Trained ML model
├── app.py                      # Main Flask App
├── utils.py                    # Resume parsing helpers
├── requirements.txt            # Dependencies
└── README.md
```
### 📸 UI Preview


![Image Alt Text](ss1.jpeg)
![Image Alt Text](ss2.jpeg)
![Image Alt Text](ss3.jpeg)
![Image Alt Text](ss4.jpeg)


### 🙌 Acknowledgments
Machine Learning with sklearn

PDF parsing using pdfminer.six

Inspired by the need to automate HR processes using AI

### 📬 Contact
For questions, reach out via snehanshusaha.6072@gmail.com or open an issue.

### ⭐ Star this repo if it helped you!

yaml
```
Let me know if you’d like help generating a screenshot banner for your README or deploying to Vercel/Render.
```
