# Venera — Dental Tourism Website

Website for **Venera Dental Clinic**, Yerevan, Armenia: veneers and implants, with the patient's trip arranged from A to Z.

- `index.html` — the whole site (one page with hash routes: `#home`, `#why-armenia`, `#about`, `#consultation`, `#bookings`)
- `logo.png`, `logo-white.png` — brand logo (copper and white)

## Features
- English / Russian / Armenian language switch
- Treatments (veneers, implants), A–Z travel package, doctors, results, FAQ
- "Why Armenia" and "About us / Why Venera" pages
- 4-step free video consultation booking: photo upload → details → doctor & time (Yerevan time + patient's local time) → confirmation with a video room link
- Staff bookings view with statuses and CSV copy

## Notes
Bookings and photo uploads currently use the claude.ai artifact runtime (`window.claude.use("db")`, `"assets"`, `"user"`).
To go live on your own domain, replace those calls with your backend / clinic system API.
Video rooms use Jitsi Meet links (`meet.jit.si`).

Contact: Argishti 4/1, Yerevan · +374 94 844811 · Instagram @veneradentalclinic
