# 🎓 SEFB Degree Planner

A degree-planning and CGPA-simulation dashboard for the **School of Economics, Finance & Banking (SEFB)** at **Universiti Utara Malaysia**.

🔗 **Live demo:** <https://mukhrizizraf.github.io/sefb_degree_planner/>

> Plan every semester · Track prerequisites · Predict your CGPA in real time · Graduate with confidence.

---

## ✨ Features

- 🗂️ **5 SEFB programs** with 264 courses, official credit allocations, and prerequisite chains
- 🎯 **Drag-and-drop semester planning** with the recommended UUM plan pre-loaded
- 🔒 **Smart prerequisite locking** — courses grey out if prereqs aren't met, prereq is failed, or the course is offered only in odd/even semesters
- 🇬🇧 **English Pathway selector** (LAMPIRAN A) — picks the right MPB courses by MUET / IELTS / CEFR band
- 🌏 **5 foreign-language options** — Mandarin, Arabic, Japanese, French, Korean (per UUM rule: Chinese students must pick non-Mandarin)
- ➕ **Add Semester** — extension semesters for students who need more time
- 📊 **Animated CGPA ring gauge** — colour-coded by classification tier, sweeps to your projected CGPA as you enter grades
- 📈 **Semester GPA bar chart** — per-semester bars colour-coded by tier (Fail / Lower 2nd / Upper 2nd / First Class) with Dean's List line
- 🧮 **Standalone GPA calculator** — quick per-semester math
- 🎯 **CGPA projection calculator** — project your new CGPA from current standing
- 🎓 **Graduation audit** — checks every credit-component requirement (A through H)
- 🎨 **8 colour themes** (VS Code-style picker) — Solarized Light/Dark, GitHub Light, Monokai, Sunny Yellow, Banana Buddy, Pop Art, High Contrast
- 📱 **Mobile responsive** — works on phones, tablets, laptops
- 💾 **Auto-save** to your browser (nothing leaves your device)
- 📄 **Export to .txt** for backup or sharing

---

## 📚 Programs Covered

| Code       | Program                                  | Credits | Semesters | Specialization Tracks    |
| ---------- | ---------------------------------------- | ------: | --------: | ------------------------ |
| **BFIN**   | Bachelor of Finance (Hons)               |     122 |         8 | Investment · Wealth Mgmt |
| **BBANK**  | Bachelor of Banking (Hons)               |     120 |         7 | KK · PR · MP · PM        |
| **BECONS** | BSc Economics (Hons)                     |     125 |         7 | —                        |
| **BRMI**   | Bachelor of Risk Mgmt & Insurance (Hons) |     120 |         7 | —                        |
| **BAGRO**  | BSc Agribusiness Management (Hons)       |     125 |         7 | —                        |

---

## 🚀 How to use

1. Open the **[live demo](https://mukhrizizraf.github.io/sefb_degree_planner/)** in any browser
2. Select your **program** (and **specialization track** if applicable)
3. Pick your **English Pathway** (based on your MUET band) and **Foreign Language**
4. Click **📋 Load Recommended Plan** to start from the official UUM sequence
5. **Drag courses** between semesters to customize your plan
6. Set **target grades** to see your projected CGPA on the gauge
7. Use the **📈 GPA Calculator tab** for per-semester GPA bars, the CGPA ring gauge, and standalone calculators
8. Use the **🎓 Audit tab** to check graduation eligibility
9. Click **🎨 Theme Selector** to pick your favourite colour theme

No login. No install. Just open the link.

---

## 🔒 Enforcement rules

The planner enforces UUM academic regulations automatically:

- **Pass prerequisites** — a course locks if its prerequisite was graded C-, D+, D, or F (rule c)
- **Odd / Even semester offerings** — courses like BEEDK2013 are only offered in odd semesters; the planner blocks misplacement
- **Minimum credits gate** — capstone, Research Methods, and Industrial Training unlock only after their credit thresholds (70 cr / 90 cr / total cr − 8)
- **English pathway** — only the MPB courses required for your chosen pathway are shown
- **Foreign language family** — picking Mandarin shows only Mandarin courses; switching to Arabic hides them and shows Arabic instead

---

## 📊 Grading Scale (UUM)

| Grade | Points | Status               |
| ----- | -----: | -------------------- |
| A+/A  |   4.00 | Pass                 |
| A−    |   3.67 | Pass                 |
| B+    |   3.33 | Pass                 |
| B     |   3.00 | Pass                 |
| B−    |   2.67 | Pass                 |
| C+    |   2.33 | Pass                 |
| C     |   2.00 | Pass                 |
| C−    |   1.67 | **Retake required**  |
| D+    |   1.33 | **Retake required**  |
| D     |   1.00 | **Retake required**  |
| F     |   0.00 | **Retake required**  |

⭐ **Dean's List** = semester GPA ≥ **3.67** (per UUM rule)

---

## 🔒 Privacy

Everything happens **inside your browser**. Your plan, grades, and personal data are saved to `localStorage` on your own device. **Nothing is sent to any server**, no account needed, no tracking. Two students opening the same link get private, separate sessions.

---

## 🛠 Tech

- Single self-contained HTML file (~3900 lines)
- Vanilla JavaScript — zero dependencies, zero install
- Canvas API for animated CGPA ring gauge and semester GPA bar chart
- CSS custom properties for theming (8 palettes)
- Hosted free on GitHub Pages
- Works offline once loaded

---

## 📖 Data Source

Curriculum data extracted from the official program books:

- **SEFB 251 — Panduan Akademik Sesi Kemasukan 2025/2026** · UUM College of Business (Bahasa Melayu)
- **A252 Academic Guides** — official English-language handbooks for BFIN, BBANK, BECONS, BRMI, BAGRO
- **LAMPIRAN A — Teras Bahasa Inggeris** — official UUM English-pathway requirements table
- Grading scale per UUM Academic Regulations

---

## 🙏 Acknowledgements

Built by:

- **Prof. Dr. Soon Jan Jan** · School of Economics, Finance & Banking · Universiti Utara Malaysia
- **Assoc. Prof. Dr. Mukhriz Izraf Azman Aziz** · School of Economics, Finance & Banking · Universiti Utara Malaysia

For feedback, bug reports, or feature requests, please open an issue on this repository.

---

Last updated: May 2026
