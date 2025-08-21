# 🛠 Payout Internal Tool (Beta v0.1 → Web Version)

A **Python automation tool** (now migrated to Web) designed to streamline **payout sandbox integration testing**.
It automates transaction status updates and webhook notifications — reducing the process from **\~2 hours to just 2 minutes**.

---

## 📖 Background

Previously, sandbox testing for payouts was highly manual:

* 🔧 Manual **SQL updates** for transaction status.
* 📊 Manual **Excel editing** (10+ steps).
* 📧 Manual **email sending** to share reports.

This was time-consuming (**\~2 hours**) and required development team involvement.

👉 To solve this, I took the initiative to build this tool.
Now users just **fill in the required info once**, and the script automates the rest — **status update, webhook send, report generation, and email dispatch**.

---

## 🚀 Key Feature: Sandbox Update

### ⏳ Before

* 10+ manual steps across Excel, SQL, and email.
* Required Dev + Support resources.
* Time: **\~2 hours**.

### ⚡ Now (Automated)

* User performs **1 simple step** (enter info).
* Script automatically:

  1. Updates transaction status.
  2. Sends webhook notifications.
  3. Generates payout report.
  4. Encrypts files (if needed).
  5. Sends report via email.
* Time: **\~2 minutes**.

✅ Benefits:

* **Internal** → Saves Engineering, Support, and Compliance hours.
* **External** → Faster partner integration and testing.

---

## 🌐 Migration to Web Version

While the initial **Python script (Beta v0.1)** proved the concept, it required users to:

* Install Python.
* Set up virtual environments.
* Manually manage dependencies.

This setup was inconvenient and slowed adoption.

👉 To solve this, I migrated the tool into a **Web version** with:

* 🌍 **Browser Access** → No setup needed, just open in browser.
* 🎨 **Better UI/UX** → Clean interface with step-by-step guidance.
* ⚡ **Faster Execution** → Optimized backend for improved speed.
* 🧹 **Full Refactor** → Cleaner codebase with modular design.
* 📑 **Improved Guidelines** → Built-in instructions to help non-technical users.

🔗 **Try the Web Version here:** [payout-internal-tool](https://github.com/nelsonwong5079/payout-internal-tool)

---

## 🧑‍💻 Tech Stack

* **Language**: Python (backend) → Migrated to Web framework
* **Libraries**: `requests`, `csv`, `hmac`, `tkinter`, `pyzipper`, `smtplib` (script)
* **APIs**: Payout API (JWT/HMAC secured)
* **Automation**: Webhook, Report Generation, Email
* **Web Version**: Refactored into a browser-based interface

---

## 📸 Screenshots

<img width="572" height="301" alt="image" src="https://github.com/user-attachments/assets/9c778f41-f105-4dbc-9d32-ac42562529a8" />

---

## ⚡ Setup & Usage

### For Python Script (Beta v0.1)

```bash
# Clone repo
git clone https://github.com/yourusername/internal-tool.git
cd internal-tool

# Install dependencies
pip install -r requirements.txt

# Run the tool
python BETA_v0.1_Internal\ Tool.py
```

### For Web Version

* Simply open the hosted URL in your browser (or run locally if needed).
* No Python setup required.
* Follow the built-in step-by-step guidance.
* Source code available here → [payout-internal-tool](https://github.com/nelsonwong5079/payout-internal-tool)

---
