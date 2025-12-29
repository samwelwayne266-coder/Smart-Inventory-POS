# 🌌 Wayne Core | Quantum Logistics & POS Ecosystem

![Status](https://img.shields.io/badge/STATUS-OPERATIONAL-emerald?style=for-the-badge&logo=statuspage)
![License](https://img.shields.io/badge/SECURITY-ENCRYPTED-indigo?style=for-the-badge&logo=auth0)
![Platform](https://img.shields.io/badge/PLATFORM-WEB_/_MOBILE-white?style=for-the-badge&logo=googlechrome)

**Operator ID:** samwelwayne266  
**System Version:** 13.0.2 (Enterprise Stable)  
**Security Tier:** Level 5 (Auth-Gated)

---

## 🛠 Project Overview
Wayne Core is a high-fidelity, cloud-integrated management suite designed for real-time inventory tracking and rapid-fire Point of Sale (POS) operations. Built with a focus on **mobile-first glassmorphism**, the system bridges the gap between physical asset management and digital cloud synchronization.

### 🧩 Core Modules
1.  **Inventory Hub (`index.html`)**: A centralized registry for asset nomenclature and UID (Unique Identifier) assignment. Features live stock distribution analytics.
2.  **Sales Engine (`pos.html`)**: A debounced transactional terminal with optical capture and hybrid selection capabilities.

---

## 🚀 Key Features

### 📡 Quantum Cloud Sync
Powered by **Firebase Realtime Database**, every stock adjustment in the Sales Engine is reflected across the entire network instantly. No manual refreshing required.

### 👁️ Intelligent Optical Capture
The system utilizes a custom-built **HTML5-QR Engine** with:
* **Debounce Logic:** Prevents duplicate scans by implementing a 2.5s optical lockout.
* **High-Fidelity Brackets:** 260x160 focus area optimized for mobile camera focal lengths.
* **Laser Sweep UI:** Visual scanning feedback for operators.

### 🔐 Security & Logic
* **Auth Gate:** Biometric-style access control requiring the `WAYNE` secret code.
* **Smart Nomenclature:** Optional naming logic—scan a code first, or name the item first; the system maps the relationship automatically.
* **Payment Gateway:** Integrated selection for Cash, Card, and Mobile Money (M-Pesa) protocols.

---

## 📱 Mobile Architecture
The UI is engineered for field use:
* **Compact Button Architecture:** Minimized hit-areas for professional density.
* **Touch-Optimized Scrolling:** Fixed `overflow` issues ensuring 100% scrollability on iOS/Android.
* **Glassmorphism UI:** High-contrast blur effects for readability in varying light conditions.

---

## 🛠 Technical Stack
* **Frontend:** Tailwind CSS (Styling), Chart.js (Analytics)
* **Backend:** Firebase Realtime DB
* **Scanning:** Html5-Qrcode Framework
* **Versioning:** Git-managed via `samwelwayne266`

---

## 💻 Installation & Deployment
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/samwelwayne266-coder/smart-inventory-pos.git](https://github.com/samwelwayne266-coder/smart-inventory-pos.git)
    ```
2.  **Configure Firebase:**
    Update the `firebaseConfig` object in both `index.html` and `pos.html` with your proprietary keys.
3.  **Deploy:**
    The system is pre-configured for **GitHub Pages**. Ensure "Workflow Permissions" are set to `Read/Write` in repository settings.

---

## ⚠️ Security Notice
Access to the Master Inventory Hub requires the encrypted secret key.  
**Default Access Key:** `WAYNE`

---
*Developed by **samwelwayne266** - 2025 Integrated Systems Division.*
