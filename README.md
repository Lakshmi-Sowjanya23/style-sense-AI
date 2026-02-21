
# 👗 StyleSense – Generative AI Fashion Recommendation System

StyleSense is a Generative AI-powered fashion recommendation system that suggests outfits based on user preferences like gender, occasion, budget, and color.

---

## 🚀 Features

* Personalized outfit suggestions
* Occasion-based styling
* Budget-friendly recommendations
* Color preference filtering
* Secure API key handling using environment variables

---

## 🛠️ Tech Stack

* Python
* Groq API (LLM)
* Prompt Engineering
* Git & GitHub

---

## 📌 How It Works

1. User provides:

   * Gender
   * Occasion
   * Budget
   * Preferred Color

2. The system generates a structured prompt.

3. The prompt is sent to the LLM via Groq API.

4. AI returns customized outfit recommendations.

---

## 🔐 Security

API keys are stored securely using environment variables and a `.env` file.
The `.env` file is excluded using `.gitignore` to prevent exposure.

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/stylesense.git
cd stylesense
pip install -r requirements.txt
```

Create a `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

Run the project:

```bash
python app.py
```

---

## 🌟 Future Improvements

* Add image-based outfit generation
* Integrate e-commerce APIs
* Deploy as web application
* Add user profile system

---

