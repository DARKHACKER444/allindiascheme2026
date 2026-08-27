# 🇮🇳 Eligible.ai — All-India Government Schemes & Direct In-Site Video Guides Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Status: Production Ready](https://img.shields.io/badge/Status-Production%20Ready-success.svg)]()
[![Platform: Web & Mobile](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blue.svg)]()
[![Schemes: 85+ Active](https://img.shields.io/badge/Schemes-85%2B%20Verified-orange.svg)]()
[![Languages: 9+ Indian Languages](https://img.shields.io/badge/Languages-9%20Indian%20Languages-green.svg)]()

> **Eligible.ai** is a comprehensive, citizen-first civic technology platform designed to bridge the awareness and eligibility gap for **85+ Central & State Government Welfare Schemes across India**. It features **Direct In-Site Multilingual Video Guides**, special provisions for **Twin & Multiple Births**, dynamic profile-based matching, and authentic, secure redirection to official `.gov.in` and `.nic.in` portals.

---

## 🌟 Key Features

1. **🏛️ 85+ Verified Indian Schemes Catalog:**
   - Covers Central Sector Schemes, State Scholarships, Agriculture (PM-KISAN), Health (Ayushman Bharat PM-JAY), Higher Education (INSPIRE, PM YASASVI), Solar Energy (PM Surya Ghar), Women Welfare, and MSME/Artisan support (PM Vishwakarma).

2. **👶 Twin & Multiple Births Statutory Rule Engine:**
   - Dedicated filter and calculation clauses for statutory exemptions:
     - **CBSE Single Girl Child (Twins Statutory Rule)**
     - **Sukanya Samriddhi Yojana (SSY Twin/Triplet Exemption)**
     - **AICTE Pragati Scholarship for Girls (Twin Siblings Rule)**
     - **Mukhyamantri Kanya Sumangala Yojana (Twins Benefit)**

3. **🎬 Direct In-Site Embedded Multilingual Video Guides:**
   - Embedded HD video player right inside every scheme details screen.
   - One-click multilingual language switching across **9 Indian Languages**:
     - 🇮🇳 **தமிழ் (Tamil)**
     - 🇮🇳 **हिन्दी (Hindi)**
     - 🇬🇧 **English**
     - 🇮🇳 **తెలుగు (Telugu)**
     - 🇮🇳 **മലയാളം (Malayalam)**
     - 🇮🇳 **ಕನ್ನಡ (Kannada)**
     - 🇮🇳 **मराठी (Marathi)**
     - 🇮🇳 **বাংলা (Bengali)**
     - 🇮🇳 **ગુજરાતી (Gujarati)**

4. **🔐 Interactive OTP Verification & Secure Login:**
   - Mobile number validation with dynamic 6-digit OTP generation and instant auto-fill capability.
   - Emergency backup recovery code generator for resilient session access.

5. **🎯 Smart Profile Eligibility Matcher:**
   - Match schemes based on Age, Jurisdiction (State/UT), Category/Sector, Annual Family Income, and Twin status.

6. **🚀 Authentic Government Portal Redirection:**
   - Direct handover to official `.gov.in` / `.nic.in` gateways with zero intermediate advertisement redirects.

---

## 📁 Repository Structure

```text
├── index.html                           # Single-page complete web application
├── README.md                            # Project documentation & setup guide
├── LICENSE                              # MIT Open Source License
├── .gitignore                           # Standard git ignore rules
├── data/
│   └── india_schemes_and_scholarships.md # 85+ Schemes master database
└── docs/
    ├── PROJECT_DOCUMENTATION.md          # Comprehensive architecture documentation
    ├── FRONTEND_CODE_EXPLAINED.md        # Line-by-line frontend engineering guide
    ├── BACKEND_CODE_EXPLAINED.md         # FastAPI & Node.js backend architecture
    ├── DATABASE_SCHEMA_EXPLAINED.md      # PostgreSQL & SQLite relational schema
    ├── HACKATHON_PITCH_AND_PROJECT_EXPLANATION.md # Pitch deck, defense scripts & Q&A
    └── ALL_INDIA_SCHEMES_AND_TWINS_DOCS.md        # Twin rules & Gazette references
```

---

## 🚀 How to Run Locally

### Option 1: Direct Browser Launch (Zero Dependencies)
Simply open `index.html` in any modern web browser:
- Double-click `index.html`, OR
- In browser address bar: `file:///path/to/index.html`

### Option 2: Live Server (VS Code / Node / Python)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js npx serve
npx serve .
```
Visit `http://localhost:8000` in your browser.

---

## 🌐 Deploying to GitHub Pages

1. Create a new repository on GitHub: `eligible-ai-india`.
2. Push all files from this repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Eligible.ai platform"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/eligible-ai-india.git
   git push -u origin main
   ```
3. In GitHub, go to **Settings** > **Pages** > Select `main` branch > Click **Save**.
4. Your site will be live at `https://YOUR_USERNAME.github.io/eligible-ai-india/`!

---

## 📄 License
This project is open-source and licensed under the **MIT License** — feel free to use and extend for civic welfare applications.