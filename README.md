# Recruitment Dropoff Automation

## 📌 Project Overview
This project automates the recruitment follow-up process by identifying candidates who are at risk of dropping out. It assigns risk levels based on the number of days since last contact and sends automated notifications to both candidates and HR.

## 🎯 Objectives
- Identify candidate drop-off risk
- Automate follow-up emails
- Reduce manual HR effort
- Improve recruitment efficiency

## ⚙️ Tools Used
- n8n (Workflow Automation)
- Google Sheets (Data Storage)
- Gmail (Email Notifications)
- Power BI (Dashboard Visualization)

## 🔄 Workflow Process
1. New candidate data added in Google Sheets
2. System checks "Days Since Last Contact"
3. Risk level assigned:
   - High Risk (>4 days)
   - Medium Risk (>2 days)
   - Low Risk (≤2 days)
4. Data merged and stored in processed sheet
5. Automated email sent to candidate
6. Alert email sent to HR team
7. <img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/f4b60796-665d-439f-9096-d75ace11c066" />


## 📊 Dashboard Features
- Total Candidates
- High Risk Candidates
- Average Days Since Last Contact
- Risk Distribution
- Roles Applied Analysis
- Contact Delay by Risk Level
- <img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/38bb06f9-3554-4a76-af23-df9f4ee4b0a4" />


## 📧 Automation Output
- Candidate receives status email
- HR receives risk alert notification

## 🚀 Benefits
- Prevents candidate drop-offs
- Improves hiring speed
- Better HR decision making
- Automated communication

## 📁 Project Structure
- Google Form → Candidate Input
- Google Sheet → Data Storage
- n8n Workflow → Risk Automation
- Power BI → Dashboard Visualization

## 👩‍💼 Use Case
HR teams can monitor candidate engagement and prioritize follow-ups with high-risk candidates.

## ✅ Conclusion
This automation helps HR teams reduce recruitment delays and improve candidate engagement through smart risk-based follow-up.
