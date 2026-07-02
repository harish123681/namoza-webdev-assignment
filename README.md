# Namoza Developer Assignment

Developer assignment submission for Namoza — client: OrthoNow, a chain of 9 orthopaedic clinics across Bengaluru, Hyderabad, and Chennai. Three deliverables: a GTM event schema, a consultation landing page, and a CRM integration design.

## Candidate
* **Name:** Harish khan

## Assignment Overview

| Task | Description | Status |
| :--- | :--- | :--- |
| **Task 1** | GTM event schema, booking funnel drop-off tracking, Google Ads conversion recommendation | Complete — see `task-1/` |
| **Task 2** | Single-file consultation landing page with `consultation_form_submitted` dataLayer push | Complete — see `task-2/index.html` |
| **Task 3** | HubSpot/WhatsApp/Google Ads integration design (written, 300–400 words) | Complete — see `task-3/integration_design.md` |

---

## Repository Structure

```text
namoza-developer-assignment/
├── README.md
├── .gitignore
├── LICENSE
├── task-1/             # GTM event schema
│   └── schema.md
├── task-2/             # Landing page build
│   ├── index.html
│   └── pagespeed/
└── task-3/             # Integration design
    └── integration_design.md
Tech Stack
​HTML5, CSS3, Vanilla JavaScript — no frameworks, no build tools
​Google Tag Manager, Google Analytics 4, Google Ads (design only — no live account exists for this exercise)
​How to Run
​Task 2 (The Landing Page)
​Open task-2/index.html directly in any standard web browser. No server or build steps required.
​To check the dataLayer push live:
​Open the browser console (F12 -> Console tab).
​Fill in the form fields and click submit.
​Run window.dataLayer in the console — the consultation_form_submitted event should be logged as the last entry.
​Task 1 & Task 3
​Both deliverables are written as clear Markdown files and can be read directly on GitHub under their respective folders.
​Remaining Before Final Submission
​[x] Confirm consultation_form_submitted fires in window.dataLayer on submit, not on load — verified in browser console
​[x] Local Lighthouse Mobile check — 90+ Mobile Core Web Vitals achieved
​[x] Hosted on GitHub Pages for live preview
​[ ] Record the Loom video (max 8 min): GTM schema decisions (2 min) → live dataLayer demo in console (3 min) → integration architecture answer (3 min)
​[ ] Commit and push this repository, share public/access with himanshu@namoza.com
​[ ] Email the repo link + Loom link to naman@namoza.com — subject: "Developer Assignment - Harish khan"
