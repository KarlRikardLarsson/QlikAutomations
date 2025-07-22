# 📊 Qlik P&L App Generator – Swedish Report Structure

This repository provides an automated way to install a Qlik Sense app based on a **Swedish Profit & Loss (P&L)** structure. With just a Qlik Automation and minimal setup, you can deploy a standardized financial reporting app in seconds.

---

## 🚀 Features

- Automatically installs a Qlik Sense app with Swedish P&L structure
- Includes dashboard, detailed income statement, and key financial KPIs
- Designed for reuse across multiple environments
- Requires only one automation run – setup is handled for you!

---

## ✅ Prerequisites

To use this setup, your data must include the following fields:

| Field                | Description                              |
|---------------------|------------------------------------------|
| `Account`            | A field containing only account numbers or names |
| `Amount`             | The booked amount (Bokfört belopp)       |
| `Date`               | A valid date field (used for YTD/period filtering) |

> These field names can be customized in the automation if needed.

---

## ⚙️ How It Works

1. Import the included automation into **Qlik Application Automation**
2. Run the automation
3. The app will be created automatically in your Qlik Cloud environment

That’s it — your financial app is ready!
