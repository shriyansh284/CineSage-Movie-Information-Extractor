# CineSage-Movie-Information-Extractor
# 🎬 Movie Information Extractor

A simple Generative AI project that converts unstructured movie descriptions into **structured JSON data**.

This project was built to revisit and strengthen core **Generative AI (GenAI)** concepts by implementing a small but practical application.

---

## 🚀 Features

The application extracts key movie information from a paragraph:

* Title
* Genre
* Director
* Cast
* Rating
* Summary

Input: A free-form movie review or description.

Output: Clean structured JSON.

Example:

```json
{
  "title": "Dhurandhar",
  "release_year": null,
  "genre": ["drama", "thriller"],
  "director": "Aditya Dhar",
  "cast": [
    "Ranveer Singh",
    "Akshaye Khanna",
    "R. Madhavan",
    "Sanjay Dutt",
    "Arjun Rampal"
  ],
  "rating": 4.5,
  "summary": "Dhurandhar takes off brilliantly with gripping tension and strong performances."
}
```

---

## ⚙️ Tech Stack

* **Streamlit** – Interactive web interface
* **LangChain** – Prompt orchestration and LLM pipeline
* **Mistral AI** – Language model used for extraction
* **Pydantic** – Structured output parsing and schema validation

---

## 🧠 GenAI Concepts Practiced

This project demonstrates several important Generative AI concepts:

* Prompt Engineering
* Structured Output Parsing
* LLM Integration
* AI-powered Web Interfaces

---

## 📸 Application Preview

Add screenshots of:

1. Application UI
2. Raw model output
3. Structured JSON output

Example location:

```
assets/app_ui.png
assets/model_output.png
assets/structured_output.png
```

---

## ▶️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/movie-information-extractor.git
cd movie-information-extractor
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add environment variables

Create a `.env` file:

```
MISTRAL_API_KEY=your_api_key_here
```

### 5. Run the application

```bash
streamlit run streamlit_app.py
```

The app will run at:

```
http://localhost:8501
```

---

## 🌍 Deployment

You can easily deploy this application using:

* Streamlit Community Cloud
* Hugging Face Spaces
* Docker
* AWS / GCP / Azure

---

## 💡 Learning Goal

The goal of this project is to **practice building small but practical GenAI applications** while reinforcing core concepts like structured outputs, prompt design, and LLM pipelines.

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome.

If you'd like to enhance this project, feel free to fork the repo and submit a pull request.

---

## ⭐ Support

If you found this project useful, consider giving the repository a **star ⭐**.
