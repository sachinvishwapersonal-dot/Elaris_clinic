# Elaris Women & Vision Centre

> Website and interactive appointment booking system for **Elaris Women & Vision Centre** — a specialised fertility, IVF, and women's health clinic in Nagpur, Maharashtra, led by **Dr. Purval Vaidya** (MBBS, DGO, DNB (OBGY)).

🔗 **Live Prototype on GitHub Pages:**  
👉 **[https://sachinvishwapersonal-dot.github.io/Elaris_clinic/](https://sachinvishwapersonal-dot.github.io/Elaris_clinic/)**

---

## 📌 Project Overview

* **Clinic:** Elaris Women & Vision Centre
* **Lead Specialist:** Dr. Purval Vaidya (Obstetrics, Gynaecology & Fertility)
* **Location:** 101, Yadnyabhaskar Apartment, Tata Square, Manewada-Besa Road, Nagpur, Maharashtra 440027
* **Brand Note:** *"Vision"* in the clinic name is brand symbolism ("every family starts as a vision") — the clinic is exclusively focused on **fertility, IVF, and gynaecological care** (not eye care).
* **Agency:** Cleveress Marketing

---

## ✨ Features & Architecture

The website is a lightweight, zero-dependency single-page application (SPA) with responsive design and hash-based navigation:

* **Hash-Routed Views:**
  * `#home` — Hero with an animated 4-step booking preview, treatment tiles, specialist guidance, and care overview.
  * `#treatments` — Complete overview of fertility evaluation, ovulation induction, IUI, IVF, ICSI, frozen embryo transfer (FET), and fertility preservation.
  * `#ivf-journey` — Visual 7-step timeline covering stimulation through to pregnancy testing.
  * `#womens-health` — Antenatal check-ups, in-clinic ultrasonography, laparoscopy, and PCOS management.
  * `#costs` — Transparent starting costs breakdown and financing/EMI options.
  * `#about` — Dr. Purval Vaidya profile, qualifications, clinic philosophy, and facility photo placeholders.
  * `#faq` — Answers to common patient questions around evaluations, IVF, privacy, and video consults.
  * `#contact` — Google Maps navigation, clinic hours, click-to-copy phone (`+91 84830 95406`), and email.
  * `#book` — Multi-step appointment scheduler supporting both in-clinic and video consultations, couple history capture, past report uploads, and discreet channel selection (WhatsApp / SMS).
  * `#clinic-desk` — Simulated staff/receptionist management dashboard to confirm appointments, mark patient arrival, cancel bookings, and block doctor dates (persisted in browser `localStorage`).

* **Design System:**
  * Light theme: Clean white background (`#FFFFFF`), fresh forest green accents (`#1C6A46`, `#2F9466`), mint backgrounds (`#E6F4EC`), and warm gold details (`#A57C3C`).
  * Typography: Google Fonts `Marcellus` (display serif) + `Outfit` (clean geometric sans).

---

## 🌐 GitHub Pages Deployment

The repository is structured so GitHub Pages deploys seamlessly from the root directory:

1. In your GitHub repository, navigate to **Settings** → **Pages**.
2. Under **Build and deployment**:
   * **Source:** `Deploy from a branch`
   * **Branch:** `main` / `/(root)`
3. Click **Save**. Your site will be live at:
   `https://sachinvishwapersonal-dot.github.io/Elaris_clinic/`

---

## ⚖️ Indian Medical & Regulatory Compliance

* **PC-PNDT Act, 1994:** Statutory notice displayed across the site and ultrasonography sections confirming sex determination is prohibited and not performed.
* **ART (Regulation) Act, 2021:** Structure in place for National ART & Surrogacy Registry registration number and clinic level categorization.
* **NMC (National Medical Commission) Advertising Guidelines:** Non-promotional, purely factual clinical information without superlative claims or unverified guarantees.
* **DPDP Act, 2023 & Patient Privacy:** Reminders and messages maintain medical discretion by never disclosing the sensitive reason for consultation.

---

## 📂 Repository Structure

```
.
├── index.html                      # Main entry point served directly by GitHub Pages
├── doctor.jpg                      # Doctor portrait asset used by index.html
├── .nojekyll                       # Disables Jekyll processing for static files
├── .gitignore                      # Standard git ignore rules
├── README.md                       # Repository documentation & live links
├── Agent.md                        # Project brief, client notes, compliance rules
├── prototype/                      # Prototype archive / alternate path (/prototype/)
│   ├── index.html
│   └── doctor.jpg
└── assets/
    └── source-materials/           # Original business card photos and high-res doctor portrait
        ├── Card01.jpeg
        ├── Card02.jpeg
        └── Doctor_image.jpeg
```

---

## 🚀 Local Development

To view and test the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/sachinvishwapersonal-dot/Elaris_clinic.git
   cd Elaris_clinic
   ```

2. Open `index.html` in your browser:
   * **Windows:** Double-click `index.html` or run:
     ```powershell
     Start-Process "index.html"
     ```

---

## 📄 License & Attribution

Designed and developed for Elaris Women & Vision Centre by **Cleveress Marketing**. All rights reserved.
