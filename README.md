# 🤖 AI Customer Support Agent

This project implements a UiPath + AI Agent for **automated customer support**.  
The agent analyzes customer interactions, generates personalized responses, and decides when escalation to a human agent is required.

---

## ✨ Features

- 🔍 **Analyze customer messages** to understand intent and sentiment.  
- 💬 **Generate responses** tailored to the communication channel:  
  - **Chat** → friendly, concise, conversational  
  - **Email** → formal, structured, complete  
  - **Social Media** → short, warm, human-like tone  
- 🚨 **Automatic escalation** to a human agent when:  
  - customer is emotional/dissatisfied  
  - billing disputes or legal concerns are detected  
  - multiple failed clarification attempts occur  
- 📧 **Email generation** using a template located in `CustomerSuportEmail`, with dynamic fields automatically populated.  
- 📂 **Escalation workflow enhancement**: when escalation is required, the agent automatically sends an **email to the human support team**, attaching an **Excel file** with the customer’s registration data and details of the issue.  

---
