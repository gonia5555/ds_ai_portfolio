# 🏃 Half Marathon Time Predictor

## Project Overview

**Half Marathon Time Predictor** is an AI-powered web application that estimates a runner’s half marathon (21.097 km) finish time based on **natural language input**.

Instead of filling out structured forms, users simply describe themselves in plain English (or Polish), and the application automatically extracts key features using a Large Language Model (LLM). These features are then passed to a trained Machine Learning model to generate a realistic race-time prediction.

👉 **Live application:**  
[here](https://predyktorczasumaratonugonia5555.streamlit.app/).

---

## How It Works

1. The user describes themselves in natural language  
   (age, gender, and 5 km race time).
2. An **OpenAI LLM** extracts structured data from the text.
3. The extracted data is validated and preprocessed.
4. A **Machine Learning regression model** predicts the half marathon finish time.
5. Results are visualized and compared against other runners.

---

## Key Features

- 📝 **Natural language input**  
  No forms required — the app understands free-text descriptions.

- 🧠 **LLM-powered data extraction**  
  OpenAI models extract age, gender, and 5 km time directly from text.

- 🤖 **Machine Learning prediction**  
  A trained regression model estimates half marathon performance.

- 🌍 **Multilingual support**  
  - English  
  - Polish  

- 📊 **Data visualization**  
  - 5 km vs half marathon time comparison  
  - Histogram comparing the user’s result with other runners  

- 🏆 **Performance percentile**  
  Shows how the predicted time compares to thousands of other runners.

- 🔍 **Observability with Langfuse**  
  LLM calls are traced for monitoring, debugging, and experimentation.

---

## Data Used

The Machine Learning model was trained on **real race data** from:

- **Half Marathon Wrocław 2023**
- **Half Marathon Wrocław 2024**

This ensures that predictions are grounded in real-world performance distributions rather than synthetic data.

---

## Technologies Used

- **Python**
- **Streamlit**
- **Scikit-learn**
- **OpenAI API (GPT models)**
- **Langfuse (LLM observability)**
- **Pandas & NumPy**
- **Matplotlib**
- **Joblib**
- **DigitalOcean (deployment)**

---

## Project Goal

The goal of this project was to demonstrate:

- practical use of **LLMs for structured data extraction**,  
- integration of **Machine Learning models with LLM pipelines**,  
- explainable and user-friendly AI applications,  
- real-world performance prediction based on authentic datasets.

This application serves as a **portfolio-grade example** of combining NLP, Machine Learning, and modern AI tooling in a single production-ready system.

---
## Author

**Małgorzata Osmęda**  
Data Science & AI Enthusiast


