# project-1
AI-driven supply chain analytics project using n8n, Supabase (PostgreSQL), and Quadratic — automates CSV ingestion from Gmail and analyzes KPIs like OTIF, Fill Rate, and Delivery Timeliness.

# 📦 AI-Powered Supply Chain KPI Monitoring System

This project is an end-to-end, AI-augmented supply chain analytics solution built to monitor and evaluate fulfillment performance metrics such as OTIF, Fill Rate, and Delivery Timeliness using modern automation and analysis tools.

---

## 🚀 Project Overview

In a real-world simulation for **Atliq Mart**, a growing organic food brand, I built a lightweight **AI Agentic Monitoring Tool** to:

- Automate the ingestion of sales data from Gmail attachments
- Store and structure that data in a relational database
- Analyze and visualize key performance indicators (KPIs) that drive operational efficiency

> ✅ This project blends automation, AI tools, and core supply chain analytics into a practical, modular pipeline.

---

## 🧠 Tools & Technologies Used

| Tool        | Purpose                                     |
|-------------|---------------------------------------------|
| [n8n](https://n8n.io/)         | AI-driven workflow automation (Gmail to DB)   |
| [Supabase](https://supabase.com/)   | PostgreSQL database hosting & management      |
| [Quadratic](https://www.quadratichq.com/) | AI-powered spreadsheet for prompt-based analysis |
| [Eraser](https://eraser.io/)        | Visual planning and workflow mapping          |
| OpenExchangeRates API | Real-time currency conversion integration     |

---

## 🔄 Workflow Architecture

```plaintext
1. Gmail receives order data as CSV attachments
2. n8n detects new emails and extracts data → converts to JSON
3. JSON data is cleaned and loaded into Supabase (PostgreSQL)
4. Quadratic connects to Supabase to analyze and visualize KPIs
5. Dynamic date tables & exchange rate enrichment via AI prompts


🙏 Acknowledgments
Special thanks to Codebasics (Dhaval Patel & Hemanand Vadivel) for the inspiring content and project simulation.
