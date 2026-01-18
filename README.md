# n8n-Weather Daily Automation

Automate daily weather updates with n8n:  
✔ Fetch real-time weather data  
✔ Generate visual posts via Placid templates  
✔ Publish automatically to Facebook  
✔ Log errors to Google Sheets & send email alerts

This workflow saves time, eliminates manual posting, and ensures consistent weather updates every day. :contentReference[oaicite:1]{index=1}

---

## 📦 Features

- **Data collection** from OpenWeather API
- **Design & rendering** using Placid
- **Automatic posting** to Facebook
- **Error handling**
  - Global error route
  - Log to Google Sheets
  - Email notification on failure

---

## 🚀 Get Started

### 1) Clone the Repo

```bash
git clone https://github.com/<yourusername>/n8n-weather-daily-automation.git
cd n8n-weather-daily-automation

2) Import Workflow in n8n
- Open your n8n dashboard
- Go to Workflows → Import
- Select workflow/n8n-weather-daily.json

3) Configure Credentials
You’ll need:
- OpenWeather API Key
- Placid API Key & Template ID
- Facebook Page Access Token
- Google API (Sheets)
- Email SMTP credentials

Add them in Credentials inside n8n.
