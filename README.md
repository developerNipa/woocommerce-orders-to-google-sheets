
# 🛒 WooCommerce Orders to Google Sheets Automation

<p align="center">
  <img src="https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white" alt="WooCommerce"/>
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white" alt="Google Sheets"/>
  <img src="https://img.shields.io/badge/n8n- EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="Automation"/>
</p>

## 📌 Project Overview

This workflow automates the export of existing WooCommerce orders and customer information to Google Sheets.

It helps organize order records in a centralized spreadsheet, reduce manual data entry, and simplify order management for eCommerce businesses.

## ⚙️ Workflow

1. **Manual Trigger** — Start the workflow when needed.
2. **WooCommerce** — Retrieve existing orders and relevant customer details.
3. **Google Sheets** — Append the retrieved order information to a spreadsheet.

## 📊 Data Exported

The workflow transfers the following information:

- Order ID and order date
- Customer name
- Customer email address and phone number
- Billing address
- Order total
- Payment method
- Order status

## 🎯 Project Goals

- Simplify WooCommerce order management
- Keep order and customer information organized
- Reduce repetitive manual data entry
- Maintain a centralized order record in Google Sheets
- Make order information easier to review and manage

## 🧰 Technologies Used

- WooCommerce
- n8n Workflow Automation
- Google Sheets
- WooCommerce integration/API
- Google Sheets integration

## 🔄 How It Works

```text
Manual Trigger
      ↓
WooCommerce: Retrieve Existing Orders
      ↓
Google Sheets: Append Order Data
      ↓
Centralized Order Spreadsheet
```

## ⚠️ Important Notes

- This workflow imports existing orders whenever it is executed.
- Duplicate checking should be implemented before repeated runs to prevent duplicate spreadsheet rows.
- WooCommerce and Google Sheets credentials must be configured before execution.
- Customer information should be handled securely and shared only with authorized users.

## 🚀 Future Improvements

- Add duplicate-order detection using the Order ID.
- Support scheduled workflow execution.
- Export only new or updated orders.
- Add error handling and execution logging.
- Send notifications when an export fails.

## 👩‍💻 Author

**Nipa Akter**

WordPress Developer | AI Automation Engineer

GitHub: [@developerNipa](https://github.com/developerNipa)

---

<p align="center">
  💜 Built to simplify eCommerce operations through workflow automation.
</p>
