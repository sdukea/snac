<div align="left">

# Snac.

*A Streamlit-based food ordering application for institutional events.*

*Python · Streamlit · QRCode · Pillow*

</div>

---

## Overview

Snac. was developed as an institutional food ordering platform for school events such as **Fests**, **A-Days**, and **F-Days**.

The application demonstrates a complete ordering workflow—from event selection to QR-based order verification—using **Streamlit** as the primary application framework.

### Highlights

- 🍔 Event-specific food menus
- 📋 Interactive ordering workflow
- 🔢 Quantity selection
- 💳 Payment confirmation (planned)
- 📱 QR code generation for vendors
- ⚡ Built entirely with Python & Streamlit

---

## User Workflow

```text
Launch App
     │
     ▼
Select Event
     │
     ▼
Browse Menu
     │
     ▼
Choose Snacks
     │
     ▼
Select Quantity
     │
     ▼
Payment
     │
     ▼
Generate QR Code
     │
     ▼
Vendor Scans QR
     │
     ▼
Order Fulfilled
```

---

## Project Structure

```text
Snac/
│
├── Snac.py
│   └── Main application
│
└── pages/
    └── Instructions.py
        └── User instructions page
```

---

## Installation

### Clone the repository

```bash
git clone <repository-url>
cd Snac
```

Or manually arrange the project as:

```text
Snac/
│
├── Snac.py
└── pages/
    └── Instructions.py
```

---

### Install Dependencies

```bash
pip install streamlit
pip install --upgrade streamlit
pip install qrcode
```

---

### Run

```bash
streamlit run Snac.py
```

The application will automatically launch in your default browser.

---

## Features

| Feature | Status |
|:---------|:------:|
| Event Selection | ✅ |
| Dynamic Food Menu | ✅ |
| Quantity Selection | ✅ |
| QR Code Generation | ✅ |
| Payment Integration | 🚧 |
| Database | 🚧 |
| Cloud Deployment | 🚧 |

---

## Technology

| Category | Stack |
|-----------|-------|
| Language | Python |
| Framework | Streamlit |
| QR Generation | QRCode |
| Imaging | Pillow |

---

## Planned Improvements

- Payment gateway integration
- Persistent database
- User authentication
- Improved UI & animations
- Responsive styling
- Cloud deployment
- Custom domain
- Order management
- Inventory management

---

## Project Status

>
> Snac. was one of my earlier projects and is no longer maintained.
>
> It remains available as a demonstration of building an end-to-end institutional food ordering workflow with Streamlit, including QR-based order verification.

<div align="center">

</div>
