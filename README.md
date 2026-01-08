# 🧠 Winsanity

### 🌐 **Live App:** [https://winsanity.vercel.app](https://winsanity.vercel.app)

> **AI-Powered Stock Analysis & Market Intelligence System**

[![Live Demo](https://img.shields.io/badge/Demo-Visit%20Live%20Site-blue?style=for-the-badge&logo=vercel)](https://winsanity.vercel.app)

**Winsanity** is a financial intelligence platform powered by a **Multi-AI Agent System**. It automates due diligence by synthesizing complex market data into a single **"Win Score"** and structured narrative reports.

Unlike standard dashboards, Winsanity acts as an automated analyst—reading earnings calls, identifying catalysts, and ranking fundamentals against a peer group of 30+ top stocks.

---

## 📸 Dashboard Preview

![Winsanity Main Dashboard](https://via.placeholder.com/800x450?text=Paste+Dashboard+Link+Here)

---

## 🚀 Key Features

### **1. The "Win Score" Engine**
A proprietary composite score (0-100) that aggregates technicals, fundamentals, and sentiment into a single actionable metric.

### **2. ⚔️ Competitive Comparison**
* **Multi-Ticker Analysis:** Instantly compare stocks (e.g., NVDA vs. TSLA vs. AAPL) side-by-side.
* **Radar Visuals:** Uses **Recharts Radar Charts** to visually overlay distinct metrics.

![Comparison Radar Chart](https://via.placeholder.com/800x450?text=Paste+Comparison+Radar+Link+Here)

### **3. AI-Generated Investment Thesis**
* **🐂 The Bull Case:** Automatically extracts positive drivers and growth catalysts.
* **🐻 The Bear Case:** Identifies potential risk factors and headwinds.
* **Events by Impact:** Ranks news and catalysts by their potential market impact.

![Stock Detail Analysis](https://via.placeholder.com/800x450?text=Paste+Bull+Bear+Case+Link+Here)

---

## 🛠️ Technical Architecture

Winsanity is a **monorepo full-stack application** built entirely on Next.js, optimized for real-time data ingestion and server-side analysis.

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Full Stack** | **Next.js 14** | Unified frontend/backend; handles Server Actions for AI request orchestration. |
| **Database** | **PostgreSQL** | Relational storage for historical scores, cached reports, and user watchlists. |
| **Visualization** | **Recharts** | Renders interactive price charts and **Radar comparison plots**. |
| **AI Layer** | **Multi-Agent System** | Parallel agents dedicated to *Sentiment*, *Technicals*, and *Earnings* parsing. |
| **Styling** | **Tailwind CSS** | Responsive, dark-mode-first UI design. |

---

## 🧠 How It Works: The Agent Pipeline

When a user views a stock (e.g., NVDA), the system triggers a multi-step pipeline:

1.  **Data Ingestion:** Fetches real-time price, OHLCV, and raw financial statements.
2.  **Context Retrieval:** Pulls transcripts from the latest earnings calls and recent news headlines.
3.  **Agent Processing:**
    * *Catalyst Agent:* Classifies news into "Bullish" or "Bearish" buckets.
    * *Fundamental Agent:* Calculates percentile rankings against the tracked cohort.
4.  **Synthesis:** The "Supervisor" agent compiles these distinct streams into the final **Win Score** and renders the report via Server Components.

---

## ⚠️ Disclaimer

*This application is for informational purposes only. The AI system provides analysis based on available data and may occasionally generate incorrect or incomplete information. Always conduct your own due diligence before investing.*

---

## 📬 Contact

Feedback or Feature Requests?
Email: [vincentsham@hotmail.com](mailto:vincentsham@hotmail.com)

© 2026 Winsanity.
