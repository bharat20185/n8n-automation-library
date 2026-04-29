# 📧 Gmail Automation System (n8n)

Automate email notifications using Gmail and n8n.

---

## 🚀 Overview

This workflow automatically sends emails when an event occurs (e.g., new lead, form submission, or database entry).

---

## ⚙️ How It Works

1. Trigger (Webhook / Form / DB)
2. Process incoming data
3. Send email via Gmail

---

## 🔁 Workflow

Trigger → Process Data → Send Email

---

## 📥 Input

```json
{
  "name": "string",
  "email": "string",
  "message": "string"
}