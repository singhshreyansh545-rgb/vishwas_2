# VISHWAS: Voice-Enabled Digital Ledger for SHGs

VISHWAS is a zero-dependency, enterprise-grade financial ledger and governance web application designed to digitize and secure operations for Self-Help Groups (SHGs). Built specifically for rapid deployment and accessibility, it features a robust multi-tier architecture capable of handling complex committee structures and multi-enrolled members.

## Core Features

*   **Dual-Key 2FA Governance:** Implements a Maker-Checker workflow where Field Officers initiate transactions and Managers authorize them via a secure PIN to prevent fraud.
*   **Bilingual Accessibility:** Full English and Hindi interface translation with a single toggle, ensuring inclusivity for grassroots users.
*   **Voice Synthesis Integration:** Leverages the Web Speech API to provide contextual audio announcements (in Hindi) upon successful transaction settlements.
*   **Member 360° Directory:** Comprehensive financial tracking across multiple committees, showing active loans, savings balances, and real-time ledger histories.
*   **Cryptographic Audit Trail:** Simulates SHA-256 block hash references for all approved transactions, ensuring an immutable record-keeping environment.

## Tech Stack

*   **Frontend Structure & Styling:** HTML5, Tailwind CSS (via CDN)
*   **Application Logic & Local State:** Vanilla JavaScript, LocalStorage API
*   **Data Visualization Analytics:** Chart.js
*   **Icons & Typography:** Lucide Icons, Google Fonts (Plus Jakarta Sans, JetBrains Mono)

## Deployment

VISHWAS uses a highly streamlined, single-file architecture (`index.html`). To deploy, simply commit the file to your repository and enable **GitHub Pages**. The application runs entirely in the client's browser without requiring a dedicated backend server or database setup.

---
*Developed by Bug Slayers.*
