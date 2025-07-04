<h1 align="center">
  ✨ n8n Appointment-Confirmation Agent ✨
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/built%20with-n8n-7f52ff?logo=n8n&logoColor=white&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/status-automated-success?style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/Yashhh47/n8n-Appointment-confirmation-workflow?style=for-the-badge"/>
</p>

> **The 60-second pitch**:  
> Book a slot ➜ workflow checks the date ➜ ✉️ sleek confirmation e-mail fires if the appointment is < **7 days** away.  
> No spam, no manual follow-ups, just instant service. Perfect for clinics, salons, coaches—anywhere appointments matter.

---

## 🚀 Quick Demo

| Booked Date | Workflow Action | Result |
|-------------|-----------------|--------|
| **Within 7 days** | <br/>🔹 Node 1 – *Date Check*<br/>🔹 Node 2 – *Send Gmail* | **Personalised confirmation e-mail** is sent ✅ |
| **≥ 7 days** | 🔹 Node 1 – *Date Check* | No mail (stay silent) 💤 |

<p align="center">
  <img src="https://github.com/Yashhh47/n8n-Appointment-confirmation-workflow/raw/main/.github/assets/flow-preview.png" width="650" alt="Workflow preview">
  <br/><sub><i>Drag-and-drop logic in n8n’s editor.</i></sub>
</p>

---

## ✨ Key Features

- **💡 Intelligent Date Logic** – confirms only when the slot is imminent.
- **📧 Gmail Integration** – polished template with dynamic placeholders (`Name`, `Date`).
- **🔒 Zero Hard-Coded Secrets** – credentials stay inside n8n; repo is safe to fork.
- **⚡ One-Click Import** – ship the JSON, tweak your credential, hit “Execute”.

---

## 🛠️ Tech Stack

| Layer | Tool | Why |
|-------|------|-----|
| Low-Code Engine | **n8n** | Visual, self-hostable, forever-free |
| E-mail Service | **Gmail API** | Reliable, trusted, easy OAuth setup |
| Versioning | **Git + GitHub** | Recruiter-friendly portfolio ✨ |

---

## 🏃‍♂️ Get Started in 3 Steps

1. **Clone** the repo  
   ```bash
   git clone https://github.com/Yashhh47/n8n-Appointment-confirmation-workflow.git
   cd n8n-Appointment-confirmation-workflow
