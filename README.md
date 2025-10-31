## 🌾 SmartKheti – AI-Powered Farming Assistant

### 🚀 Project Overview

**SmartKheti** is an AI-driven smart farming platform built to empower Indian farmers with data-based insights, crop recommendations, pest control solutions, and image-based crop detection — all in an accessible bilingual interface.

It integrates three AI modules:

1. **AI Crop Prediction (Python Notebook)** – Suggests the most profitable crop using ML based on soil, rainfall, and temperature data.
2. **SmartKheti Chatbot (Ollama Integrated)** – A bilingual AI assistant offering instant, step-by-step organic farming advice.
3. **AI Crop & Food Detection (Web App)** – Detects crops and foods using TensorFlow.js, OpenCV, and YOLO deep learning models.

---

### 🧠 Key Features

* 🌱 **AI-Based Crop Suggestion** — Smart ML predictions for optimal crop selection.
* 🤖 **Bilingual Farming Chatbot** — Works in English & Hindi, even offline via Ollama.
* 📸 **Crop & Food Detection** — Identifies crops, fruits, and vegetables via image upload.
* 💡 **Offline + Online Compatibility** — Runs with local models and minimal internet use.
* 🧩 **Clean, Mobile-Responsive UI** — Designed for simplicity and rural accessibility.

---

### ⚙️ Tech Stack

| Component          | Technology                          |
| ------------------ | ----------------------------------- |
| Backend (AI Model) | Python, Scikit-learn, Pandas, NumPy |
| Frontend           | HTML, CSS, JavaScript               |
| Vision             | TensorFlow.js, OpenCV, YOLO         |
| Chatbot AI         | Ollama + Llama2                     |
| Notebook           | Jupyter (.ipynb)                    |

---

### 🧩 Project Structure

```
📦 SmartKheti
│
├── ai_crop_prediction.ipynb      # Crop prediction ML model
├── ollama_integrated.html        # AI Chatbot (SmartKheti Assistant)
├── crop_product.html             # Crop & food detection interface
├── README.md                     # Project documentation
└── assets/                       # (Optional) images/icons/resources
```

---

### 🧪 Setup Instructions

#### 1. Clone Repository

```bash
git clone https://github.com/your-username/smartkheti.git
cd smartkheti
```

#### 2. Run the Crop Prediction Model

```bash
jupyter notebook ai_crop_prediction.ipynb
```

#### 3. Launch Chatbot

1. Install [Ollama](https://ollama.ai/download)
2. Run the local Llama2 model:

   ```bash
   ollama run llama2
   ```
3. Open `ollama_integrated.html` in browser

#### 4. Use the Detection Tool

Open `crop_product.html` in browser for AI image detection.



### 💼 Business Model

**SmartKheti** follows a **freemium model** ensuring accessibility and scalability:

* 🆓 **Free Tier** – Available for small farmers, government bodies (e.g. ICAR), and agricultural institutes for education and awareness.
* 💰 **Paid Tier** – Subscription for:

  * Large-scale farmers and agritech enterprises for premium analytics & forecasting.
  * Agricultural cooperatives and NGOs for farmer network data insights.
  * Data companies & research institutions for anonymized agri-data access.



### 🌍 Social Impact

* 👨‍🌾 **Empowers Rural Farmers** with low-cost, localized AI solutions.
* 🌾 **Promotes Sustainable Farming** through organic, preventive, and climate-aware advice.
* 📶 **Bridges the Digital Gap** — Works offline and in Hindi for better rural usability.
* 📊 **Supports Agri-Policy & Research** by providing transparent, data-backed insights for governments and organizations.



### 👨‍💻 Team Members

 **Avantika Rana**  
 
 **Bhavya Joshi** 
 
 **Shaily Dhouliyan**   


