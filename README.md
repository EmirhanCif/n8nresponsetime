# n8n Website Response Time Monitor 🚀

This project is a workflow example built with n8n that automatically tracks the response times (latency) of specific websites.

## 📝 About the Project
This automation sends HTTP requests to popular websites (Google, Facebook, LinkedIn) **every 5 minutes** and measures the response times in milliseconds. It is designed to detect latencies exceeding a defined threshold (5000ms).

## ⚙️ How to Install
1. Download the `Website Response Time Monitor.json` file from this repository.
2. Open your n8n interface.
3. Create a new workflow and select the **"Import from File"** option from the top-right menu to upload the JSON file.
4. Activate the `Schedule Trigger` node to start monitoring.

## 🛠 Nodes Used
- **Schedule Trigger:** Triggers the workflow every 5 minutes.
- **Date & Time:** Captures request start/end times and calculates the difference.
- **HTTP Request:** Sends requests to target websites.
- **Merge & Set:** Combines data and formats it into a meaningful output.

## ✨ Transparency & AI Assistance
In the spirit of transparency, please note that **n8n AI** and AI-assisted tools were utilized during the development, logic optimization, and documentation of this project. This collaboration helped ensure the workflow is efficient and well-documented.

## 🚀 Roadmap
- [ ] Add Slack or Email notifications for high latency alerts.
- [ ] Log data to a Google Sheet for historical analysis.

---
*This project was created for educational purposes.*
