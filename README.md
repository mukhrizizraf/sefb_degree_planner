# 🎓 SEFB Degree Planner

A degree-planning and CGPA-simulation dashboard for the **School of Economics, Finance & Banking (SEFB)** at **Universiti Utara Malaysia**.

🔗 **Live demo:** https://mukhrizizraf.github.io/sefb_degree_planner/

> Plan every semester · Track prerequisites · Predict your CGPA in real time · Graduate with confidence.

---

## ✨ Features

- 🗂️ **5 SEFB programs** with 264 courses, official credit allocations, and prerequisite chains
- 🎯 **Drag-and-drop semester planning** with the recommended UUM plan pre-loaded
- 🔒 **Prerequisite locking** — courses grey out if prereqs aren't met
- 📊 **Live CGPA gauge** that updates as you set target grades
- 🧮 **Standalone GPA calculator** — quick per-semester math
- 🎯 **CGPA projection calculator** — project your new CGPA from current standing
- 🔗 **Prerequisite dependency graph** — visualize course chains
- 🎓 **Graduation audit** — checks every credit-component requirement
- 🌙 **Dark mode** (default) + light mode
- 📱 **Mobile responsive** — works on phones, tablets, laptops
- 💾 **Auto-save** to your browser (nothing leaves your device)
- 📄 **Export to .txt** for backup or sharing

---

## 📚 Programs Covered

| Code | Program | Credits | Semesters | Specialization Tracks |
|------|---------|--------:|----------:|-----------------------|
| **BFIN** | Bachelor of Finance (Hons) | 122 | 8 | Investment Mgmt · Wealth Mgmt |
| **BBANK** | Bachelor of Banking (Hons) | 120 | 7 | KK · PR · MP · PM |
| **BECONS** | BSc Economics (Hons) | 125 | 7 | — |
| **BRMI** | Bachelor of Risk Mgmt & Insurance (Hons) | 120 | 7 | — |
| **BAGRO** | BSc Agribusiness Management (Hons) | 125 | 7 | — |

---

## 🚀 How to use

1. Open the **[live demo](https://mukhrizizraf.github.io/sefb_degree_planner/)** in any browser
2. Select your **program** (and **specialization track** if applicable)
3. Click **📋 Load Recommended Plan** to start from the official UUM sequence
4. **Drag courses** between semesters to customize your plan
5. Set **target grades** to see your projected CGPA on the gauge
6. Use the **📈 GPA tab** for the standalone GPA & CGPA calculators
7. Use the **🔗 Prereqs tab** to visualize course dependency chains
8. Use the **🎓 Audit tab** to check graduation eligibility

No login. No install. Just open the link.

---

## 📊 Grading Scale (UUM)

| Grade | Points | Status |
|-------|--------:|--------|
| A+ / A | 4.00 | Pass |
| A− | 3.67 | Pass |
| B+ | 3.33 | Pass |
| B | 3.00 | Pass |
| B− | 2.67 | Pass |
| C+ | 2.33 | Pass |
| C | 2.00 | Pass |
| C− | 1.67 | **Retake required** |
| D+ | 1.33 | **Retake required** |
| D | 1.00 | **Retake required** |
| F | 0.00 | **Retake required** |

⭐ **Dean's List** = semester GPA ≥ 3.50

---

## 🔒 Privacy

Everything happens **inside your browser**. Your plan, grades, and personal data are saved to `localStorage` on your own device. **Nothing is sent to any server**, no account needed, no tracking. Two students opening the same link get private, separate sessions.

---

## 🛠 Tech

- Single self-contained HTML file
- Vanilla JavaScript — zero dependencies, zero install
- CSS custom properties for theming
- Hosted free on GitHub Pages
- Works offline once loaded

---

## 📖 Data Source

Curriculum data extracted from the official program book:
**SEFB 251 — Panduan Akademik Sesi Kemasukan 2025/2026** · UUM College of Business.
Grading scale per UUM Academic Regulations.

---

## 🙏 Acknowledgements

Built by **Dr. Mukhriz Izraf** · School of Economics, Finance & Banking · Universiti Utara Malaysia.

For feedback, bug reports, or feature requests, please open an issue on this repository.

---

*Last updated: May 2026*
