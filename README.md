# WhatsApp AI Agent Workflow

This workflow integrates WhatsApp messages with an AI Agent using OpenAI
Chat Models and Simple Memory. It processes incoming WhatsApp messages,
generates intelligent responses, and sends replies back through WhatsApp
Business Cloud.

![Workflow Diagram](workflow.png)

------------------------------------------------------------------------

## 🚀 Overview

This automation workflow is designed to: - **Receive messages** via
WhatsApp Trigger - **Process queries** using an AI Agent connected to
OpenAI Chat Model - **Store context** using Simple Memory for better
continuity - **Respond back** to users through WhatsApp Business Cloud
API

------------------------------------------------------------------------

## 🧩 Workflow Components

### 1. **WhatsApp Trigger**

Triggers automatically whenever a WhatsApp message is received.

### 2. **AI Agent**

Handles the decision-making and response creation using: - **OpenAI Chat
Model** for generating replies - **Simple Memory** to store and recall
conversation context

### 3. **WhatsApp Business Cloud (Send Message)**

Sends the AI-generated response back to the user on WhatsApp.

------------------------------------------------------------------------

## 📌 How It Works

1.  User sends a message on WhatsApp.
2.  WhatsApp Trigger captures the message.
3.  The message is passed to the **AI Agent**.
4.  AI Agent uses **OpenAI Chat Model** to understand and generate a
    reply.
5.  **Simple Memory** stores important conversation details.
6.  Response is forwarded to **WhatsApp Business Cloud**.
7.  User receives the reply instantly.

------------------------------------------------------------------------

## 📁 File Included

-   `workflow.png` --- Visual representation of the workflow (add this
    file in your repo or folder)

------------------------------------------------------------------------

## 🛠 Requirements

-   WhatsApp Business Cloud API setup
-   OpenAI API key
-   n8n or similar automation platform

------------------------------------------------------------------------

## 📞 Support

If you need help improving or customizing this workflow, feel free to
reach out!

**Built with ❤️ by Piyush Automations**
