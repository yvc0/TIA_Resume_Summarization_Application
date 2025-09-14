# 📄 AI Resume Summarizer

This is a **Streamlit-based AI application** that allows you to upload resumes in **PDF or DOCX format** and automatically generates a **smart summary with key insights** using a pre-trained NLP model.

---

## 🚀 Features
- Upload resumes in **PDF** or **DOCX** format.
- Extracts raw text from resumes.
- Generates a **concise summary** using Hugging Face's `distilbart-cnn-12-6` model.
- Displays **key highlights** such as:
  - AI/ML experience
  - Project management background
  - Education level (Bachelor/Master)
- User-friendly **Streamlit web interface**.

---

## 📂 Project Structure
```
resume-summarizer-app/
├── resume_summarizer_app.py   # Main Streamlit application
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation
```

---

## 📦 Installation

1. **Clone this repository** (or copy project files):
   ```bash
   git clone https://github.com/your-username/resume-summarizer-app.git
   cd resume-summarizer-app
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Run the Application
Run the Streamlit app with:
```bash
streamlit run resume_summarizer_app.py
```

The app will open in your browser at:
```
http://localhost:8501
```

---

## 📊 Example Workflow
1. Upload a **resume.pdf** or **resume.docx**.
2. App extracts text and displays first 1500 characters.
3. Click **Summarize Resume** to generate a summary.
4. View:
   - **✨ AI Summary**
   - **🎯 Key Insights**

---

## 🛠 Requirements
Contents of `requirements.txt`:
```
streamlit
python-docx
PyMuPDF
transformers
torch
```

---

## 💡 Future Improvements
- Support for **multiple resumes** at once.
- Export summary and insights to **PDF/Word**.
- Add **NER (Named Entity Recognition)** for extracting skills and experience.
- Deploy app on **Streamlit Cloud or Hugging Face Spaces**.

---

## 📌 Disclaimer
⚠️ This project is for **educational/demo purposes** only.  
Summaries may not capture all details of a candidate's experience.  
Always review resumes manually for recruitment decisions.
