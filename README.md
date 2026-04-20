# 📄 InvoiceMaker – Aqua Tiles Edition
<p align="center">
  <img src="assets/icon.ico" alt="InvoiceMaker Icon" width="120">
</p>

**InvoiceMaker (Aqua Tiles Edition)** is a Windows desktop document generator designed specifically for trade and materials-based businesses.

It is built for fast invoice creation, structured product billing, and professional PDF document export.

---

## 🌐 Website
https://mustan.dev/

---

## 🧩 About This Version

This is a **custom-built edition for Aqua Tiles**, optimized for real-world trade workflows involving product-based billing.

It is designed for:

- Tile and materials invoicing  
- Customer quotations and estimates  
- Delivery documentation  
- Retail/trade invoice management  

The system is optimized for speed, accuracy, and professional document output.

---

## 🚀 Features

- 🧾 Invoice, Quote, Estimate, Delivery Note generation  
- 🔎 Product search from CSV database  
- ➕ Add/edit line items instantly  
- ⚡ Automatic subtotal, tax, and total calculations  
- 📄 Professional PDF export system  
- 🏢 Business branding support (logo, terms, bank details)  
- 🖼️ Optimized logo handling for clean PDF output  
- 💾 Flexible CSV data support (Aqua Tiles datasets)  

---

## 🧭 Workflow

1. Launch the application  
2. Select document type  
3. Enter company and customer details  
4. Search products from database  
5. Add items and adjust quantity/pricing  
6. Add notes, terms, and payment information  
7. Upload company logo  
8. Export professional PDF  

---

## 📊 Product Database

This version supports Aqua Tiles product structure:

- Primary dataset: `ALLPRODUCTS_Combined.csv`  
- Fallback dataset: `ALL_PRODUCTS.csv`  

The loader automatically normalizes CSV formats for compatibility.

---

## 📄 PDF Output

Generated documents include:

- Company header with logo  
- Document metadata (invoice number, date, type)  
- Customer billing details  
- Structured product table  
- Automatic totals (subtotal, tax, final amount)  
- Footer (terms, notes, signatures)  

---

## 🖥️ Interface Layout

### Left Panel
- Document configuration  
- Billing details (From / To)  
- Tax settings  
- Notes & terms  
- Bank & collection info  
- Logo upload  

### Right Panel
- Product search system  
- Item selection list  
- Editable invoice table  
- Real-time totals  
- Export controls  

---

## 🖼️ Logo Handling

- Upload and preview inside app  
- Automatic image optimization  
- Clean rendering in exported PDFs  
- Safe fallback handling if processing fails  

---

## ⚙️ Build System

- PyInstaller packaging system  
- Windows executable build supported  

### Output Files
- `dist/InvoiceMaker.exe`  
- `InvoiceMaker_windows_x64.zip`  

---

## 📦 Dependencies

- PyQt6 – Desktop UI framework  
- pandas – Data handling and CSV processing  
- reportlab – PDF generation  

---

## 📌 Current Status

- Application runs successfully  
- Product database loads correctly  
- PDF generation works as expected  
- Build system produces stable outputs  

---

## ⚠️ Notes

- This version is specifically designed for Aqua Tiles workflows  
- PyInstaller may show non-critical `jinja2` warnings during build  
- These warnings do not affect functionality  

---

## 👨‍💻 Developer

Built by **Mustan-Dev**

🌐 https://mustan.dev/

## 📜 License
This software is licensed under the Mustan‑Dev Proprietary License (2026).
Usage is permitted, but modification, redistribution, resale, or sharing is strictly prohibited.

See the full license text in the LICENSE file.