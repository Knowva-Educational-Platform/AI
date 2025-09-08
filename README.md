# Knowva AI Module 🤖✨

This repository contains the **Artificial Intelligence components** of **Knowva**, an educational platform designed to support teachers, students, and parents by automating repetitive tasks and enhancing the learning process.

## 📌 Overview
The AI part of Knowva leverages **Natural Language Processing (NLP)** and machine learning models to:
- **Generate quizzes** automatically from uploaded educational materials.
- **Grade exams** (objective & short-answer) with instant results.
- **Provide personalized feedback** and analytics for both students and teachers.
- **Enable an AI-powered chatbot** for interactive revision and Q&A.

By integrating these features, the AI module reduces teacher workload, improves student learning outcomes, and keeps parents informed through automated reports.

---

## 🎯 Key Objectives
- Automate quiz and exam generation with NLP models.  
- Deliver **real-time insights** into student performance.  
- Provide **personalized feedback** tailored to individual learning gaps.  
- Support **teachers** with class-wide analytics and improvement strategies.  
- Enable **interactive student revision** through conversational AI.

---

## 🤖 Core AI Features
### 1. AI Quiz Generation
- Converts uploaded materials into **MCQs, True/False, and Short-Answer questions**.
- Uses **NLP models** to extract key concepts and generate diverse questions.
- Editable by teachers for fine-tuning.

### 2. AI Auto-Grading
- Automatically evaluates:
  - Multiple-choice & true/false questions.
  - Short-answer responses using semantic similarity.
- Provides **instant results** and grading consistency.

### 3. AI Feedback & Analytics
- **For Students**: 
  - Highlights weak topics.
  - Explains mistakes clearly.
  - Suggests **personalized study plans**.
- **For Teachers**: 
  - Tracks class-wide performance.
  - Identifies frequently missed questions.
  - Provides improvement strategies.

### 4. AI Revision Chatbot
- Conversational chatbot that:
  - Answers student queries on uploaded material.
  - Provides **topic-specific practice and explanations**.
  - Supports iterative revision before exams.

### 5. Future Enhancements
- **AI Homework Management** (auto-checking assignments).
- **Adaptive Learning Paths** (personalized quiz difficulty scaling).

---

## 🛠️ Tech Stack (AI Part)
- **Python** (core ML/NLP)
- **PyTorch / TensorFlow** (model development)
- **Transformers (HuggingFace)** for NLP
- **Scikit-learn** for classical ML models
- **FastAPI** / **Flask** for model serving
- **PostgreSQL** integration for storing quiz, grading, and feedback results
- **Docker** for deployment

---

## 📐 AI Workflow
1. **Input**: Teacher uploads learning material (text, PDF, notes).  
2. **Processing**: NLP pipeline extracts key topics and generates quiz questions.  
3. **Student Interaction**: 
   - Students attempt quizzes.  
   - AI grades answers instantly.  
   - Feedback & analytics provided.  
4. **Chatbot Support**: Students can revise interactively with the AI tutor.  
5. **Reporting**: Automated reports for teachers and parents.

---

## 👨‍💻 AI Team
- **Khaled Zakarya Zyada** – Team Lead (AI)  
- **Khaled Ahmed Helmy** – AI Developer  
- **Faris Nagy Abouagour** – AI Developer  

---

## 📌 Why Our AI is Different
✅ **End-to-End Automation**: From quiz creation to grading and feedback.  
✅ **Educator-Centric**: Designed to save teachers time, not add extra steps.  
✅ **Personalized Insights**: Both individual (students) and group-level (teachers).  
✅ **Scalable**: NLP-driven pipeline adapts to any subject domain.  

---

## 🚀 Getting Started (AI Module)
```bash
# clone the repo
git clone https://github.com/<your-username>/<repo-name>.git

# create virtual environment
python -m venv venv
source venv/bin/activate   # on mac/linux
venv\Scripts\activate      # on windows

# install dependencies
pip install -r requirements.txt

# run API server
uvicorn app.main:app --reload
