# 🌾 Krishi-Buddy — AI-Powered Crop Disease Detector

> Helping farmers identify crop diseases instantly through simple image uploads — powered by Google Gemini AI.

---

## 📌 Overview

Krishi-Buddy is a lightweight web application that detects crop diseases from leaf images using AI. A farmer or agronomist can upload a photo of a diseased plant, and the app instantly diagnoses the disease along with actionable recommendations — no expertise required.

This project was built to reduce dependency on manual inspection and help small-scale farmers take early action before crop losses escalate.

---

## 🚀 Demo

> Upload a leaf image → Get instant disease diagnosis + treatment advice

*(Add a screenshot or screen recording GIF here)*

---

## ✨ Features

- 📷 **Image-based diagnosis** — Upload any crop leaf photo for instant analysis
- 🤖 **Gemini 2.5 Flash powered** — Uses Google's multimodal AI for accurate plant pathology detection
- 💊 **Treatment recommendations** — Provides actionable remedies alongside each diagnosis
- ⚡ **Fast & lightweight** — Built with Streamlit for a clean, no-friction UI
- 🌐 **No ML training required** — Leverages Gemini API's vision capabilities directly

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Streamlit |
| AI / Vision | Google Gemini 2.5 Flash API |
| Image Processing | Python (PIL / OpenCV) |
| Language | Python 3.x |
| Backend Logic | REST API calls to Gemini |

---

## 📁 Project Structure

```
Krishi-buddy/
│
├── Plant_Pathology_Project_Using_Gemini_2.5_Flash   # Main Streamlit app
├── backend/                                          # Backend API logic
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites
- Python 3.8+
- A Google Gemini API key ([Get one here](https://aistudio.google.com/app/apikey))

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/pawankushwahh/Krishi-buddy.git
cd Krishi-buddy

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set your Gemini API key
export GEMINI_API_KEY="your_api_key_here"
# On Windows:
# set GEMINI_API_KEY=your_api_key_here

# 4. Run the app
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 🌿 Supported Crops

The app can analyze diseases across a wide range of crops including:
- Tomato, Potato, Corn (Maize)
- Rice, Wheat, Cotton
- Apple, Grape, and more

*(Powered by Gemini's general vision — not limited to a fixed set of classes)*

---

## 💡 How It Works

1. User uploads an image of a crop leaf via the Streamlit UI
2. The image is encoded and sent to the **Gemini 2.5 Flash** vision API
3. Gemini analyzes visual symptoms and returns a structured diagnosis
4. The app displays the **disease name**, **confidence**, and **recommended treatment**

---

## 🔮 Future Improvements

- [ ] Add support for multilingual output (Hindi, regional languages)
- [ ] Integrate weather-based disease risk alerts
- [ ] Add history/log of past diagnoses
- [ ] Mobile-friendly PWA version

---

## 👨‍💻 Author

**Pawan Kushwah**
B.Tech CSE, Sitare University, Lucknow

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/pawan-kushwah-a45944248/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/pawankushwahh)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
