# 🧠 AI-Driven Plagiarism Intelligence for Assignments

This project addresses the challenge of detecting nuanced and AI-generated plagiarism in academic assignments by building an **adaptive plagiarism detection system** using **IBM Watsonx.ai**, powered by **Granite Foundation Models** on IBM Cloud.

---

## 🚀 Problem Statement

Academic institutions are struggling to detect paraphrased or AI-generated plagiarism, especially when students alter content to bypass traditional checkers. Moreover, current systems lack the ability to adapt to instructor-specific styles and grading preferences.

**Goal:**  
Build an AI system that:
- Learns from historical submissions and instructor feedback.
- Detects AI-generated content and paraphrasing.
- Adapts to stylistic and structural expectations of each instructor.
- Generates plagiarism risk reports with contextual analysis.

---

## 🔧 Technology Stack

| Component                | Technology / Service             |
|--------------------------|----------------------------------|
| AI Model                 | IBM Granite (Foundation Model)   |
| Cloud Platform           | IBM Cloud Lite                   |
| Prompt Engineering       | Watsonx.ai Prompt Lab            |
| Document Input           | Instructor Styles & Assignments  |
| Output                   | Similarity, AI Probability, Risk |

---

## 🧪 How It Works

1. **User Inputs:**
   - Student Assignment
   - Instructor's Style Guidelines (comments, tone, rules)

2. **Prompt Lab Instructions:**
   A structured prompt is sent to the IBM Granite model which analyzes:
   - Text similarity with known content
   - Probability of AI-generation
   - Deviation from instructor style

3. **Output:**
   - Similarity Score (0–100%)
   - AI Probability (0–100%)
   - Style Deviation (Low / Moderate / High)
   - Final Plagiarism Risk (Low / Moderate / High)

📎 References
IBM Watsonx.ai Documentation
IBM Granite Models
Prompt Lab Overview
