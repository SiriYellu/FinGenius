# 💸 **FinGenius – AI-Powered Personal Finance Advisor**

## 🚀 **Overview**

**FinGenius** is your intelligent personal finance companion — an AI-powered advisor that helps users understand, analyze, and improve their financial health.  
It processes real transaction data, generates interactive insights, and engages users through a conversational AI interface to make smarter financial decisions.

---

## ✨ **Key Features**

- 📁 **Upload Real Data** – Secure CSV upload with smart validation and preview  
- 🤖 **AI Financial Advisor** – Chat-based personal finance assistant powered by GPT / Gemini  
- 📊 **Advanced Analytics Dashboard** – Interactive charts for spending, income, and savings trends  
- 💡 **Personalized Insights** – AI-generated tips for budgeting, investment, and expense optimization  
- 🎯 **Financial Health Score** – Quantitative wellness metric combining multiple financial indicators  

---

## 🧠 **Technology Stack**

| Layer | Tools / Frameworks |
|-------|--------------------|
| **Frontend** | Streamlit (Python) |
| **AI Layer** | OpenAI GPT / Google Gemini |
| **Data Analytics** | Pandas, NumPy, Plotly |
| **Vector Database** | ChromaDB (for RAG-based contextual insights) |
| **Visualization** | Plotly + Streamlit interactive components |

---

## ⚙️ **Quick Start Guide**

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Configure API Keys
Create a `.env` file in the project root:
```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 3️⃣ Run the Application
```bash
streamlit run app.py
```

### 4️⃣ Run in Demo Mode (No API Key Required)
```bash
streamlit run demo_mode.py
```

---

## 🗂 **Project Structure**
```
├── app.py                # Main Streamlit interface
├── ai_engine.py          # Core AI logic and RAG-based responses
├── visualizations.py     # Functions for charts and dashboards
├── data_generator.py     # Synthetic transaction data creator
├── config.py             # Global configuration and constants
├── demo_mode.py          # Offline demo version
├── requirements.txt      # Dependencies list
├── sample_upload.csv     # Example CSV for testing
└── DEMO_GUIDE.md         # Step-by-step presentation guide
```

---

## 🧩 **Hackathon Demo**

Check out **`DEMO_GUIDE.md`** for:
- Suggested presentation flow  
- Demo script and speaking notes  
- Example conversations with FinGenius  
- Key analytics visuals and RAG examples  
