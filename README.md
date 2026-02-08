**💸 Expense Management System**

🚀 Streamlit Frontend • ⚡ FastAPI Backend • 🧪 Test-Ready Architecture

A clean, scalable full-stack expense management system built with FastAPI and Streamlit, showcasing real-world backend + frontend engineering best practices.



**🧠 System Architecture**

```
┌──────────────────┐
│     User (UI)    │
│   Web Browser    │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│  Streamlit App   │
│   (Frontend)     │
│  • Forms         │
│  • Dashboards    │
│  • Charts        │
└────────┬─────────┘
         │  REST API Calls
         ▼
┌──────────────────┐
│  FastAPI Backend │
│  (Server Layer)  │
│  • Business Logic│
│  • Validation    │
│  • API Endpoints │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│  Data Layer /    │
│  Storage         │
│ (Extensible)     │
└──────────────────┘

```




**📂 Project Structure**

```
expense-management-system/
│
├── frontend/            # Streamlit UI
│   └── app.py
│
├── backend/             # FastAPI backend
│   └── server/
│       └── server.py
│
├── tests/               # Unit & integration tests
│
├── requirements.txt     # Python dependencies
│
└── README.md            # Project documentation
```



**🚀 Features**

💰 Add and manage expenses

📊 Interactive dashboards and visualizations

⚡ High-performance FastAPI backend

🎨 Streamlit UI for rapid interaction

🧪 Test-friendly code structure

🔌 Easy to extend with DB, auth, analytics





**🧰 Tech Stack**

| Layer        | Technology |
| ------------ | ---------- |
| Frontend     | Streamlit  |
| Backend      | FastAPI    |
| API Server   | Uvicorn    |
| Language     | Python     |
| Testing      | Pytest     |
| Architecture | REST       |




**⚙️ Setup Instructions**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   📍 Backend URL
   👉 http://127.0.0.1:8000

   📘 Swagger API Docs
   👉 http://127.0.0.1:8000/docs
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   🌐 Streamlit app opens automatically in your browser.

   ```
**🧪 Run Tests**
   ```commandline
   python -m pytest -v
   ```




