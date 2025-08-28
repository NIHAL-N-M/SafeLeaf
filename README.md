
## System Demo

![Leaf Disease Detection Demo](https://github.com/shukur-alom/leaf-diseases-detect/blob/main/Media/video.gif)



---

# 🌿 Leaf Disease Detection System

AI-powered system to detect plant leaf diseases using **FastAPI** (backend) and **Streamlit** (frontend).
It uses Meta’s **Llama Vision models via Groq API** to identify diseases, check severity, and suggest treatments.

---

## 🚀 Features

* 🔍 Detects 500+ plant diseases (fungal, bacterial, viral, pests, nutrient issues).
* 📊 Gives severity levels (mild, moderate, severe).
* ✅ Provides confidence scores for predictions.
* 💡 Suggests treatments and care steps.
* ⚡ Fast analysis (2–5 seconds per image).

---

## 🏗️ Project Structure

* `main.py` → Streamlit Web App (user interface).
* `app.py` → FastAPI Backend (API service).
* `Leaf Disease/main.py` → Core AI detection engine.
* `utils.py` → Helper functions for image processing.
* `requirements.txt` → Project dependencies.

---

## ⚡ Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/NIHAL-N-M/SafeLeaf.git
cd SafeLeaf
```

### 2. Setup environment

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your Groq API key

Create a `.env` file:

```
GROQ_API_KEY=your_key_here
```

### 5. Run the app

**Option A: Streamlit (UI)**

```bash
streamlit run main.py
```

→ Open [http://localhost:8501](http://localhost:8501)

**Option B: FastAPI (API)**

```bash
uvicorn app:app --reload
```

→ Open API docs at [http://localhost:8000/docs](http://localhost:8000/docs)

---

## 📡 How It Works

1. Upload a leaf image (JPG/PNG).
2. The AI analyzes it and detects any disease.
3. You get results: disease name, severity, confidence, and treatment tips.

---

## 🧪 Testing

Run tests with:

```bash
python test_api.py
```

---

## 🌍 Deployment

* Supports **Vercel**, **Streamlit Cloud**, **Railway**, **Docker**, and **Heroku**.
* Just set your **GROQ\_API\_KEY** as an environment variable before deploying.

---

## 📜 License

MIT License – free to use and modify.

---

<div align="center">

**🌱 Bringing AI into Agriculture for healthier crops. 🌱**

⭐ Star this repo if you find it useful!

</div>

