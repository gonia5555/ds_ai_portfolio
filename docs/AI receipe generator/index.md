# 🍽️ AI Recipe Generator

## Project Overview

**AI Recipe Generator** is a web application built with **Streamlit** that uses artificial intelligence to generate personalized recipes based on either a photo of ingredients or a manually entered list of products.

The application combines **computer vision**, **OpenAI language models**, and a **vector database (Qdrant)** to deliver practical, real-world AI functionality in an intuitive user interface.

## 🔑 OpenAI API Key Required

To use the application, an **OpenAI API Key is required**.

- The API key must be entered in the **sidebar input field** inside the application.
- The application **will not run** until a valid API key is provided.
- The API key is **not stored permanently** and is used only for the current session.

👉 **Live application:**  
[here](https://gonia5555recipegenerator.streamlit.app/).

---

## Key Features

- 📸 **Recipe generation from images**  
  Automatically detects ingredients from a photo and generates a matching recipe.

- 📝 **Recipe generation from text input**  
  Users can enter ingredients manually, separated by commas.

- 🌍 **Multilingual support**  
  The application supports three languages:
  - English  
  - Polish  
  - Spanish  

- 🍰 **Recipe type selection**  
  - Sweet  
  - Savory  

- 💾 **Recipe saving**  
  Users can save up to 10 recipes per session.

- 📄 **PDF export**  
  Each recipe can be downloaded as a PDF file with full Unicode support.

- 🧠 **AI-powered content generation**  
  Recipes are generated using OpenAI models and text embeddings.

---

## Technologies Used

- **Python**
- **Streamlit**
- **OpenAI API (GPT models & embeddings)**
- **Qdrant (vector database)**
- **Pillow (image processing)**
- **ReportLab (PDF generation)**
- **dotenv (environment variable management)**

---

## Project Purpose

The goal of this project was to build a **complete, production-ready AI application** that demonstrates:
- integration of large language models,
- image-based input processing,
- vector database usage,
- clean UI/UX design,
- real-world applicability.

This project serves as a **portfolio example** of an end-to-end AI solution, from user interface to backend AI services.

---
## Author

**Małgorzata Osmęda**  
Data Science & AI Enthusiast