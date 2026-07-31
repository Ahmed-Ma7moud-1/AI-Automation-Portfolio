# 🚀 Smart AI Sales & Inventory Automation Agent

An end-to-end AI automation workflow built using **n8n**, **Telegram**, and **Google Sheets** to record sales, purchases, and debt tracking via natural speech/text.

---

## 🎯 Features

* 🗣️ **Natural Language Input:** Employees can send voice-to-text or normal messages in casual language.
* 🤖 **Smart Extraction:** Extracts Customer Name, Item Type, Quantity, Total Price, and Remaining (Deferred) Payment.
* 🛡️ **Validation (No Empty Rows):** Asks the user for missing fields before appending to Google Sheets.
* 💰 **Zero Model Subscriptions:** Self-hosted and setup to run without expensive monthly AI API subscriptions (Host cost only).
* 📈 **Scalable Architecture:** Easily expandable to handle inventory management, debt reminder alerts, and automated weekly/monthly financial reports.

---

## 🛠️ Tech Stack

* **Automation Engine:** [n8n](https://n8n.io/)
* **AI Engine:** OpenRouter / Open-Source Models
* **Database/Sheets:** Google Sheets API
* **Interface:** Telegram Bot API

---

## 📥 How to Import to n8n

1. Download the `workflow.json` file from this repository.
2. Open your n8n instance.
3. Click **Import from File** and upload the `.json` file.
4. Set up your credentials for Telegram Bot & Google Sheets.
