# 🤖 vendBot-invoicy

This UiPath automation processes WI3 work items from the ACME System 1 portal. It filters Open items with type "WI3", extracts vendor invoice details from attached PDFs, validates required fields, and updates the work item status to "Completed".

---

## 🛠 Key Features

- Filters WI3 work items with **Open** status.
- Extracts **Invoice No.**, **Date**, and **Vendor** from PDF attachments.
- Uses **Regex** and **string manipulation** for data extraction.
- Linear workflow built **without REFramework**.
- Built using **classic UiPath activities**.

---

## 🚀 How to Run

1. Open **ACME System 1** and log in.
2. Open the project in UiPath Studio.
3. Run `Main.xaml`.
4. The bot will process all available WI3 items and update them accordingly.

---

## 🧪 Test Data

Test using the provided sample PDFs from the ACME portal using test credentials.

---
*This project is for learning and demo purposes only. Built without REFramework.*
