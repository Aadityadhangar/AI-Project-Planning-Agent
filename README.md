# 🤖 AI-Powered Project Planning & Task Reminder System

![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-FF6D5A?logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?logo=openai)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-Automation-EA4335?logo=gmail&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

> An AI-powered workflow automation system that transforms project requirements into structured project plans, assigns tasks to team members, tracks deadlines, and sends automated reminder emails.

---

# 📌 Overview

This project was developed as part of the **Lenovo LEAP NextGen Scholar Internship 2026**.

The system leverages **OpenAI**, **n8n**, **Google Sheets**, and **Gmail** to automate project planning and task management.

It consists of two intelligent AI agents:

- 🧠 Planner AI Agent
- 📧 Task Reminder AI Agent

The Planner Agent converts project requirements into structured milestones and tasks, while the Reminder Agent automatically tracks deadlines and sends email reminders to assigned team members.

---

# 📑 Table of Contents

- 📌 Overview
- 🚀 Features
- ⚙️ Workflow
- 🛠️ Tech Stack
- 📂 Project Structure
- 📸 Screenshots
- ⚡ Installation
- 📋 How It Works
- 💡 Use Cases
- 🔒 Security
- 📈 Future Improvements
- 👨‍💻 Author
- ⭐ Acknowledgement
- 📜 License

---

# 🚀 Features

| 🧠 Planner AI Agent | 📧 Reminder AI Agent |
|--------------------|----------------------|
| Generates project milestones | Detects upcoming deadlines |
| Creates detailed tasks | Identifies overdue tasks |
| Assigns team members | Sends reminder emails |
| Estimates project timelines | Logs notifications |
| Stores data in Google Sheets | Runs automatically on schedule |

---

# ⚙️ Workflow

```text
                  User Requirement
                       │
                       ▼
                 Planner AI Agent
                       │
               Generate Milestones
                       │
                 Generate Tasks
                       │
               Assign Team Members
                       │
             Store in Google Sheets
                       │
                 Scheduled Trigger
                       │
                       ▼
                Reminder AI Agent
                       │
                 Check Deadlines
                       │
             Send Reminder Emails
```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| **n8n** | Workflow Automation |
| **OpenAI API** | AI-powered Task & Milestone Generation |
| **Google Sheets** | Project Database |
| **Gmail API** | Automated Email Notifications |
| **Prompt Engineering** | Structured AI Outputs |
| **AI Agents** | Intelligent Project Planning & Reminder Automation |

---

# 📂 Project Structure

```text
AI-Project-Planning-Agent/
│
├── AI_Project_Planning_Agent.json
├── AI_Task_Reminder_Agent.json
├── README.md
│
└── Screenshots/
    ├── workflow.png
    ├── reminder_workflow.png
    └── google_sheet_data.png
```

---

# 📸 Screenshots

## 🏗️ AI Project Planning Workflow

This workflow automatically generates project milestones, creates tasks, assigns team members, and stores the output in Google Sheets.

![Workflow](Screenshots/workflow.png)

---

## 🔔 AI Task Reminder Workflow

The Reminder Agent periodically checks project deadlines and automatically sends personalized reminder emails using Gmail.

![Reminder Workflow](Screenshots/reminder_workflow.png)

---

## 📊 Google Sheets Dataset

Google Sheets acts as the project database, storing milestones, assigned team members, deadlines, and task status.

![Google Sheet](Screenshots/google_sheet_data.png)

---

# ⚡ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Aadityadhangar/AI-Project-Planning-Agent.git
```

### 2. Open n8n

Import the following workflow files:

- AI_Project_Planning_Agent.json
- AI_Task_Reminder_Agent.json

### 3. Configure Credentials

Set up the following credentials in n8n:

- OpenAI API
- Gmail OAuth
- Google Sheets OAuth

### 4. Execute

Run the Planner AI Agent.

Enable the Reminder AI Agent schedule.

---

# 📋 How It Works

### Step 1

The user enters a project requirement.

Example:

```text
I want to build an E-commerce Website.
```

---

### Step 2

The Planner AI Agent:

- Understands the project requirement
- Generates milestones
- Creates project tasks
- Assigns team members
- Estimates timelines

---

### Step 3

All generated project information is automatically stored inside Google Sheets.

---

### Step 4

The Reminder AI Agent:

- Reads project data
- Checks upcoming deadlines
- Detects overdue tasks
- Sends reminder emails through Gmail

---

# 📊 Project Highlights

- 🤖 Two AI Agents
- ⚡ Built using n8n
- 🧠 OpenAI Powered
- 📧 Gmail Integration
- 📄 Google Sheets Integration
- 🔄 End-to-End Workflow Automation
- ⏰ Automated Task Monitoring

---

# 💡 Use Cases

- Software Project Management
- Agile Sprint Planning
- Startup Project Planning
- Internship Team Management
- Academic Team Projects
- Automated Task Assignment
- Workflow Automation

---

# 🔒 Security

This repository **does not contain**:

- OpenAI API Keys
- Google API Credentials
- Gmail OAuth Tokens
- Personal Data

All sensitive credentials have been removed before publishing.

---

# 📈 Future Improvements

- Slack Integration
- Microsoft Teams Notifications
- WhatsApp Notifications
- Calendar Integration
- AI Risk Prediction
- Dashboard Analytics
- Task Completion Prediction
- Multi-Project Support

---

# 👨‍💻 Author

**Aaditya Rajendra Dhangar**

🎓 B.Tech – Artificial Intelligence & Data Science

🚀 Lenovo LEAP NextGen Scholar 2026

---

# ⭐ Acknowledgement

This project was developed during the **Lenovo LEAP NextGen Scholar Internship 2026**, a CSR initiative by **Lenovo**, implemented by **BharatCares** in collaboration with **AICTE**.

Special thanks to the mentors and trainers for their guidance and support throughout the internship.

---

# 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project for educational and learning purposes.

---

# ⭐ Support

If you found this project useful, please consider **starring ⭐ this repository**.

Your support motivates me to build more AI-powered automation projects and share them with the community. intended for educational and portfolio purposes.
