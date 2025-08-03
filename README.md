# 📊 NxtWave Marketing Automations Specialist Assignment

This repository contains the completed work for the **NxtWave Marketing Automations Specialist Assignment**, which includes three tasks:

1. ✅ Omnichannel Lead Nurturing Workflow  
2. ✅ Lead Qualification Chatbot using SwiftSell  
3. ✅ Tool Integration using Make.com

---

## 📁 Table of Contents

- [Task 1: Lead Nurturing Workflow](#task-1-lead-nurturing-workflow)
- [Task 2: Chatbot Setup with SwiftSell](#task-2-chatbot-setup-with-swiftsell)
- [Task 3: Form + Make.com Integration](#task-3-form--makecom-integration)
- [Final Notes](#final-notes)

---

## ✅ Task 1: Lead Nurturing Workflow

> **Objective**: Design a lead nurturing journey using diagrams.net for users who haven’t completed their profile.

### 🔗 Flowchart Link  
[View Lead Nurturing Workflow Diagram](https://app.diagrams.net/#your-diagram-link-here)

### 📝 Summary  
- Day 0: Welcome messages sent via WhatsApp, SMS, and Email.  
- Day 1: Check profile status.  
  - If completed → Send congratulatory message and exit.  
  - If not → Enter 3-day reminder loop.  
- Day 1–3:  
  - WhatsApp Reminder → If delivered, wait 24 hrs → Recheck.  
  - If not delivered → Send SMS fallback.  
- After Day 3: Final reminder via Email → End workflow.

---

## ✅ Task 2: Chatbot Setup with SwiftSell

> **Objective**: Build a lead qualification chatbot for NxtWave’s Free Career Kickstarter Webinar.

### 🔗 Bot Preview Link  
[Open Chatbot in SwiftSell](https://app.swiftsell.biz/#your-bot-link-here)

### 📦 Features Implemented  
- Collects: Name, Phone, Email  
- Asks qualifying questions:
  - Student/Working
  - Tech/Non-Tech
  - Career Path
  - Readiness  
- Conditional responses based on user input  
- Graceful exit for uninterested users  
- Sends qualified leads in the following JSON format:

```json
{
  "name": "Example User",
  "email": "example@example.com",
  "phone": "9876543210",
  "status": "Hot Lead",
  "careerPath": "Data Science",
  "source": "Webinar Bot"
}

