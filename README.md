# 🧠 Winsanity

### 🌐 **Live App:** [https://winsanity.vercel.app](https://winsanity.vercel.app)

> **AI-Powered Stock Analysis & Market Intelligence System**

[![Live Demo](https://img.shields.io/badge/Demo-Visit%20Live%20Site-blue?style=for-the-badge&logo=vercel)](https://winsanity.vercel.app)

**Winsanity** is a financial intelligence platform that combines quantitative precision with qualitative AI insights. It automates due diligence by ranking stocks against a high-cap cohort and using AI agents to generate structured narrative reports.

---

## 📸 Dashboard Preview

![Winsanity Main Dashboard](https://via.placeholder.com/800x450?text=Paste+Dashboard+Link+Here)

---

## 🚀 Key Features

### **1. The "Win Score" Engine (Algorithmic)**
A deterministic scoring system (0-100) that calculates a stock's strength based on **percentile rankings**.
* **Methodology:** Every stock is ranked against a cohort of 30+ top market cap stocks.
* **Metrics:** Aggregates real-time performance in Valuation, Momentum, and Fundamentals into a single objective score.

### **2. AI-Powered Narrative Analysis**
* **Catalyst Agents:** Scrape and analyze news to separate "Noise" from "Signal," generating the **Bull Case** and **Bear Case**.
* **Earnings Agents:** Parse thousands of lines of earnings call transcripts to extract management sentiment and key takeaways.

### **3. ⚔️ Competitive Comparison**
* **Multi-Ticker Analysis:** Instantly compare stocks (e.g., NVDA vs. TSLA vs. AAPL) side-by-side.
* **Radar Visuals:** Uses **Recharts Radar Charts** to visually overlay the percentile strengths of multiple assets.

![Comparison Radar Chart](https://via.placeholder.com/800x450?text=Paste+Comparison+Radar+Link+Here)

![Stock Detail Analysis](https://via.placeholder.com/800x450?text=Paste+Bull+Bear+Case+Link+Here)

---

## 🛠️ Technical Architecture

Winsanity is a **monorepo full-stack application** built entirely on Next.js, optimized for real-time data ingestion and server-side analysis.

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Full Stack** | **Next.js 14** | Unified frontend/backend; handles Server Actions for orchestration. |
| **Database** | **PostgreSQL** | Relational storage for historical data and user watchlists. |
| **Visualization** | **Recharts** | Renders interactive price charts and **Radar comparison plots**. |
| **AI Layer** | **Multi-Agent System** | Dedicated agents for *News Classification* and *Transcript Parsing*. |
| **Styling** | **Tailwind CSS** | Responsive, dark-mode-first UI design. |

---

## 🧠 How It Works: The Hybrid Pipeline

When a user views a stock (e.g., NVDA), the system runs a parallel pipeline combining math and AI:

1.  **Quantitative Layer (The Win Score):**
    * The system fetches raw financial data (P/E, RSI, Revenue Growth).
    * It calculates the **Percentile Rank** of these metrics against the tracked peer group (Top 30+ stocks).
    * These percentiles are weighted to generate the final **Win Score**.

2.  **Qualitative Layer (The AI Agents):**
    * **Catalyst Agent:** Fetches recent news, filters out duplicates, and summarizes the distinct Bull/Bear arguments.
    * **Transcript Agent:** Retrieves the latest earnings call text and summarizes the "Key Takeaways" section.

3.  **Delivery:**
    * The frontend receives the calculated Score (Math) and the generated Reports (AI) simultaneously via Next.js Server Components.

---

## ⚠️ Disclaimer

*This application is for informational purposes only. The AI system provides analysis based on available data and may occasionally generate incorrect or incomplete information. Always conduct your own due diligence before investing.*

---

## 📬 Contact

Feedback or Feature Requests?
Email: [vincentsham@hotmail.com](mailto:vincentsham@hotmail.com)

© 2026 Winsanity.
