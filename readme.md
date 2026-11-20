# LabFlow — Diagnostic Lab Home Sample Collection & Report System

A minimal, responsive web prototype for booking diagnostic lab tests, scheduling home sample collections, tracking real-time sample progress via unique IDs, and managing family medical report histories.

---

## Overview

**LabFlow** streamlines communication and workflow across all key stakeholders in a diagnostic healthcare ecosystem using a clean, distraction-free interface with minimal iconography and a clinical color palette.

### Stakeholders & Core Features

1. **Patients & Guests**
   - Browse diagnostic tests and full-body health packages across multiple labs.
   - Compare test prices, turnaround times, and fasting/preparation instructions.
   - Book home sample collection visits with family member selection, address, date, time slot, optional prescription upload, and online dummy payment.
   - Track real-time sample status (`Assigned` → `Sample Collected` → `Received at Lab` → `Processing` → `Report Ready`) using a **Unique Sample ID**.
   - Filter and download verified PDF test reports and payment invoices by family member.
   - Real-time support and lab chat drawer.

2. **Sample Collectors**
   - View assigned home collection visits with patient details and fasting notes.
   - Verify patient identity at the doorstep via 4-digit OTP and mark samples as collected.
   - Report failed visits (e.g., patient unavailable or not fasting).

3. **Diagnostic Labs**
   - Manage incoming test bookings and assigned sample collectors.
   - Update sample processing stages in real time.
   - Upload verified PDF test reports and generate invoices.

4. **System Admin**
   - Monitor monthly booking statistics, average report turnaround times, and home collection fee rules.
   - Approve newly registered diagnostic labs and sample collectors.
   - Export monthly booking summary reports (PDF).

---

## Design System & Color Palette

Built with **Tailwind CSS** and **Inter** typography for responsiveness across desktop and mobile viewports:

| Role | Color | Hex |
| :--- | :--- | :--- |
| **Canvas Background** | Soft Slate | `#F8FAFC` |
| **Card / Surface** | Pure White | `#FFFFFF` |
| **Primary Accent** | Clinical Teal | `#0F766E` |
| **Primary Text** | Deep Slate | `#0F172A` |
| **Secondary Text** | Muted Gray | `#64748B` |
| **Dividers & Borders** | Light Slate | `#E2E8F0` |

---

## Project Structure

```text
├── index.html      # Complete single-file responsive UI prototype & interactive role views
└── README.md       # Project documentation and setup guide
```

---

## Getting Started

### Run Locally
1. Clone or download the repository.
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Use the **View Switcher** dropdown in the top-right navigation bar to test the **Patient / Guest**, **Sample Collector**, **Diagnostic Lab**, and **Admin** interfaces.

### Import into Figma (Optional)
1. Open `index.html` in Google Chrome (or deploy via GitHub Pages).
2. In **Figma**, open a new Design File and launch the **`html.to.design`** plugin.
3. Import the rendered page to generate editable Auto-Layout frames for Desktop (`1280px`) and Mobile (`375px`).

---

## Author

**Md. Yeasin Hasan Sunny**  
Department of Computer Science & Engineering, United International University (UIU)  
GitHub: [@im-ajax](https://github.com/im-ajax)