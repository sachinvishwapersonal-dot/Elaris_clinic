# Elaris Women & Vision Centre — Project Notes

## Project
- **Goal:** Build a full website + appointment booking system for the clinic.
- **Source material so far:** two photos of the business card — `assets/source-materials/Card01.jpeg` (services side) and `assets/source-materials/Card02.jpeg` (contact side) — plus `assets/source-materials/Doctor_image.jpeg` (Dr. Purval Vaidya portrait: white coat with name embroidered, stethoscope, glasses; already circle-cropped on a dark gradient, ~700px circle, plain off-white wall behind). Usable for prototype; for launch ask for the original uncropped, high-res photo.

## Prototype (v1, 2026-10-31)
- Files: `prototype/index.html` + `prototype/doctor.jpg` (cropped from Doctor_image.jpeg)
- Live private link: https://claude.ai/artifact/92Gn116kw1v7ajb88CuV1S
- Pages (hash routes): home, treatments, ivf-journey, womens-health, costs, about, faq, contact, book, clinic-desk (demo staff view)
- Footer credit: "Website by Cleveress Marketing"
- Design (v2): **light theme only, white + green** (user rejected dark-green bands/dark mode). Fresh green accent, mint sections, white cards with soft shadows, line icons, gold used sparingly, green gradient CTA banner.
- Hero (v3): **no doctor photo on the home page** and no filler badges/feature chips. Right side is an animated booking-flow mockup (Visit → Time → Details → Confirmed with WhatsApp bubble), looping. Doctor photo stays on About page only.
- Placeholders (gold dashed underline): fees, hours, ART/PC-PNDT/MMC reg nos., training/experience, clinic photos, EMI, cancellation window
- Booking is front-end only (localStorage in viewer's browser); no real messages sent

## Important: what "Vision" means
"Vision" in the name is **branding only** — this is an **IVF / fertility clinic**, NOT an eye-care centre (confirmed 2026-10-31). Position the site around fertility/IVF.

## Clinic details (from the card)
- **Doctor:** Dr. Purval Vaidya — MBBS, DGO, DNB (OBGY), Obstetrics & Gynaecology
- **Phone:** +91 84830 95406
- **Email:** drpurvalvaidya@gmail.com
- **Address:** 101, Yadnyabhaskar Apartment, Tata Square, Manewada-Besa Road, Nagpur, Maharashtra 440027
- **Services listed on card:** Antenatal Care & Pregnancy Checkup, Ultrasonography, Gynecological Consultation, Infertility Evaluation, Laparoscopy, Family Planning & Contraception
- Card has a QR code (destination unknown)

## Branding
- Colours: deep forest green, white, gold/bronze accent (curved diagonal split)
- Logo: line-art mother & baby profile with lotus + leaves; lotus has an eye at its centre; small lotus on the "A" in ELARIS
- Type: condensed bold sans for headings, geometric sans for body
- Need original vector logo from the client (card photos are not usable as artwork)

## Compliance (India)
- **ART (Regulation) Act 2021:** clinic must be registered with the National ART & Surrogacy Registry — display ART registration number; confirm Level 1 (IUI) vs Level 2 (IVF).
- **PC-PNDT Act:** ultrasound offered — show "sex determination not done" notice + PC-PNDT registration number.
- **NMC advertising rules:** no "best doctor" claims, no unverified success rates/guarantees; careful with testimonials; doctor approves all copy.
- **DPDP Act 2023:** health data — privacy policy, consent checkbox, secure storage.

## Booking system requirements (draft)
- Couple consultations: both partners' details, years trying, female age, previous treatments
- Optional secure upload of past reports (AMH, semen analysis, HSG)
- Optional video consultation for out-of-town patients
- **Discretion:** reminders must not mention IVF (e.g. "Your appointment at Elaris is confirmed"); reason-for-visit optional
- Two booking types: new consultation vs follow-up/monitoring
- Admin dashboard for doctor/receptionist (view, confirm, reschedule, block dates)

## Open questions for the client
1. ART registration number and level (1 or 2)
2. Full list of fertility services (IUI, IVF, ICSI, FET, egg/embryo freezing, semen analysis, donor programmes); in-house lab or partner? Embryologist?
3. Clinic timings, slot length, token vs fixed slots
4. Doctor photo, clinic photos, original logo file
5. Pricing approach (packages / "starting from" / contact) and EMI/financing
6. Domain name (owned or to buy)
7. Other doctors on staff
8. Payment online vs at clinic; confirmation channel (WhatsApp/SMS/email)
9. Cancellation policy; existing clinic software (Practo, Eka Care, etc.)
10. Languages (English / Marathi / Hindi); social links; Google Business Profile
11. Budget and deadline
