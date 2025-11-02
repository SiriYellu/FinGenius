# 💸 **FinGenius – AI-Powered Personal Finance Advisor**

> 🧠 *An AI-driven personal finance companion that helps users analyze spending, understand patterns, and make smarter financial decisions.*

---

## 🚀 **Overview**

**FinGenius** is your intelligent personal finance assistant — built to empower users with data-driven financial awareness.  
It leverages **Generative AI** and **interactive analytics** to analyze real or synthetic transaction data, generate meaningful insights, and guide users through personalized financial advice.

With FinGenius, users can:
- Upload their **bank transaction history** securely.
- Explore interactive **income–expense dashboards**.
- Chat with an **AI-powered financial advisor**.
- Receive **tailored tips** on budgeting, savings, and investment strategies.

This project was originally designed for **hackathon demos** and **AI-driven FinTech research**, making it both **scalable** and **educational** for real-world deployment.

---

## ✨ **Key Features**

| Category | Description |
|-----------|--------------|
| 📁 **Data Upload** | Upload financial CSVs with smart validation and data preview |
| 📊 **Interactive Analytics Dashboard** | Visualize spending, income, and category trends using Plotly |
| 🤖 **AI Financial Advisor** | Conversational agent powered by GPT/Gemini with contextual memory |
| 💡 **Personalized Insights** | AI-generated budgeting & investment suggestions |
| 💬 **Natural Chat Interface** | Ask questions like “How can I save more this month?” or “What is my largest expense?” |
| 🎯 **Financial Health Score** | Composite metric combining savings ratio, recurring expenses, and income diversity |
| 🧾 **Synthetic Data Generator** | Auto-create realistic demo data for hackathon and testing scenarios |
| 🧠 **RAG (Retrieval-Augmented Generation)** | Stores insights in ChromaDB to enhance contextual reasoning |
| 🔒 **Privacy & Security** | No data is stored permanently; all processing is local/session-based |

---

## 🧠 **Technology Stack**

| Layer | Tools / Frameworks |
|-------|--------------------|
| **Frontend / UI** | Streamlit |
| **AI Layer** | OpenAI GPT-4 / Google Gemini API |
| **Data Analytics** | Pandas, NumPy |
| **Visualization** | Plotly, Streamlit Charts |
| **Database (RAG Context)** | ChromaDB |
| **Environment Management** | Python-dotenv |
| **Optional Extensions** | LangChain / LangGraph for multi-agent orchestration |

---

## 🏗️ **System Architecture**

- **User Interface (Streamlit Web App)**
  - Upload CSV, visualize analytics, chat with AI
- **Data Processing Layer**
  - CSV validation and cleaning (Pandas)
  - Statistical metrics, trends, and scoring
- **AI Engine Layer**
  - GPT / Gemini API calls
  - RAG context memory (ChromaDB)
  - Prompt templates + financial logic
- **Visualization Layer**
  - Plotly charts · KPIs · category/time insights
  - Interactive dashboards and financial reports



## 🚀 **Quick Start**

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Set Up API Key
Create `.env` file:
```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 3. Run the App
```bash
streamlit run app.py
```

### 4. Demo Mode (No API Keys)
```bash
streamlit run demo_mode.py
```

## 📁 **Project Structure**
```
├── app.py                 # Main Streamlit application
├── ai_engine.py          # AI logic and RAG implementation
├── visualizations.py     # Chart and graph functions
├── data_generator.py     # Sample data generation
├── config.py            # Configuration settings
├── demo_mode.py         # Demo version (no API keys needed)
├── requirements.txt     # Python dependencies
├── sample_upload.csv    # Sample data for testing
└── DEMO_GUIDE.md       # Presentation guide
```

## 🎯 **For Hackathon Demo**
See `DEMO_GUIDE.md` for complete presentation instructions and demo script.

## 🏆 **Hackathon Ready!**
- ✅ Professional UI/UX
- ✅ Real data processing
- ✅ AI-powered insights
- ✅ Interactive visualizations
- ✅ Upload-first approach
- ✅ Production-ready architecture


## 🧩 **Project Demo**

> 🎥 *See FinGenius in action — upload your data, explore insights, and chat with your AI financial advisor.*

---

### 🖼️ **1️⃣ Dashboard Overview**
Interactive analytics dashboard showing income, expenses, and savings trends.  
![FinGenius Dashboard](<img width="2038" height="1131" alt="Screenshot 2025-11-02 105409" src="https://github.com/user-attachments/assets/90d722fd-162c-4815-8676-a97b6e990c7a" />
)

---

### 💬 **2️⃣ AI Chat Interface**
Conversational AI advisor providing personalized budgeting and savings suggestions.  
![FinGenius Chat Interface](<img width="2040" height="1160" alt="Screenshot 2025-11-02 105425" src="https://github.com/user-attachments/assets/4fe194e8-1706-48d3-a248-53e2f6498bad" />
)

---

### 📊 **3️⃣ Spending Breakdown Visualization**
Category-wise spending chart and monthly expense trends.  
![FinGenius Spending Analysis](<img width="2023" height="1113" alt="Screenshot 2025-11-02 105532" src="https://github.com/user-attachments/assets/8e6f12ea-0f47-4c0b-8695-472595dd9f93" />
)

