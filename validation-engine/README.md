# 🚀 n8n Validation Engine (Reusable Sub-Workflow)

A rule-based validation engine for n8n workflows that ensures clean, structured data before processing.

---

## 🔥 Why this exists

Most workflows fail because of bad input data.

Instead of writing validation logic repeatedly, this sub-workflow provides:
- Centralized validation
- Reusable rules
- Clean error handling

---

## ⚙️ Features

- ✅ Required field validation  
- 📧 Email validation  
- 🔤 Length validation  
- 🔁 Bulk processing (array support)  
- 📊 Structured output (success, errors, count)

---

## 📥 Input Format

```json
{
  "data": [...],
  "rules": {...}
}

---

## 📤 Output Format

```json
{
  "success": true,
  "errors": [],
  "error_count": 0
}

---

🧩 How to Use

- Import the workflow JSON into n8n
- Call this sub-workflow from your main workflow
- Pass:
  - data (array of records)
  - rules (validation rules)

---

🧠 Example Use Cases

- Lead ingestion systems
- API validation layer
- Data pipelines

---

💡 Pro Tip

Use this as a first step in every workflow to ensure clean data.

---

📣 Connect

If you found this useful, connect with me on LinkedIn.