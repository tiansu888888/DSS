# 📊 DBSS2643: Decision Support Systems & Business Intelligence Hub

An interactive, bilingual (English/Chinese) learning platform designed for the **DBSS2643: Overview of Business Intelligence and Decision Support** course. Built with a premium Macaron Glassmorphism style, animated gradients, offline vector infographics, and interactive quiz/matching widgets.

---

## 🎨 System Preview & Interface

![DSS Hub Preview](assets/macaron_dss.png)

> [!NOTE]
> The hub features a curated **Macaron Aesthetic** designed for maximum engagement and visual relief during study sessions:
> - **Dreamy Pastel Gradients:** Shifting backgrounds of Rose Pink, Lavender, Soft Blue, and Mint Green.
> - **Glassmorphic Cards:** Frosted glass blocks (`backdrop-filter: blur(40px)`) with crisp borders and deep charcoal typography (`#111111`) for perfect contrast and readability.

---

## 🚀 Key Features

### 1. 📅 14-Week Curriculum & Detailed Syllabus
Step-by-step guides covering the entire course syllabus, completely translated in both English and Chinese:
- **Week 1-2:** BI & DSS Overview (Changing business environment, decision levels, BI architecture, DSS concept).
- **Week 3-4:** Decision Making Foundations (Simon's phases of decision-making, DSS types/DBMS/MBMS components).
- **Week 5-6:** Knowledge Management & Data Warehousing (Tacit vs explicit knowledge, ETL pipelines, OLAP cube operations).
- **Week 7-8:** Model Components (Linear programming modeling, Excel Solver, What-If scenario managers, Goal Seek).
- **Week 9:** User Interface (Dialog styles, Figma prototyping, usability guidelines).
- **Week 10-11:** Designing DSS (Planning considerations, feasibility studies, 3-tier logical architecture).
- **Week 12-13:** Object-Oriented UML Modeling (Use Case diagrams, Sequence diagrams, Class structures).
- **Week 14:** Implementation & Evaluation (Direct cutover vs parallel runs, UAT evaluation frameworks).

### 2. 🎮 Interactive Self-Assessments
Every module features a fully functional client-side practice suite:
- **Knowledge Check (Quiz):** 5 multiple-choice questions per week with instant correctness feedback.
- **Fill in the Blanks:** Inline term completions that validate input dynamically for both English and Chinese translations.
- **Practical Exercises:** 3 tasks per week (focusing on Excel formulas, SQL queries, and UML diagram mappings) with show/hide answer keys.
- **Matching Game:** Interactive terms and definitions card-matching game, randomized using a seeded deterministic shuffle.

### 3. 🌐 Dual-Language Translation Toggle
A unified, zero-dependency **CSS Class-Driven Translation Engine** allows students to instantly switch the entire interface between **English** and **Chinese** (`🌐 EN / 中文`) with a single click.

### 4. 📊 100% Offline Vector Infographics
Each week features a custom-designed, high-contrast SVG infographic explaining the core concept:
- **Week 1:** Managerial Decision Levels (Strategic, Tactical, Operational).
- **Week 3:** Herbert Simon's Decision Making Process Loop.
- **Week 6:** The ETL Data Pipeline Process Flow (Extract -> Transform -> Load).
- **Week 8:** What-If Scenario Analysis vs. Goal Seek Optimization.
- **Week 13:** UML Class Generalization Inheritance Relationships.

---

## 📂 Project Structure

```bash
DBSS2643/
└── website/
    ├── index.html         # Main Portal Dashboard (Week 1-14 navigator)
    ├── DSS-Note.html      # Comprehensive Single-Page Application Note Hub
    ├── week1.html ... week14.html
    ├── README.md          # Repository Readme (This File)
    ├── DESIGN.md          # Design Style Tokens
    └── assets/
        └── macaron_dss.png # Premium 3D theme graphic (Showcased above)
```

---

## 📚 Curriculum & Chapter Outline

| Week | Chapter | Key Concepts & Takeaways | Exam Topic Hint |
|------|---------|--------------------------|-----------------|
| **WK1** | BI & DSS Overview (1) | IPO cycle, structured vs unstructured decisions, managerial levels. | *Identify decision levels (Strategic vs Operational).* |
| **WK2** | BI & DSS Overview (2) | BI framework components: Data Warehouse, Analytics, BPM, UI Dashboard. | *Contrast DSS vs BI characteristics.* |
| **WK3** | Decision Foundations (1) | Herbert Simon's 4 Decision Phases (Intel, Design, Choice, Impl). | *Map specific activities to Simon's phases.* |
| **WK4** | Decision Foundations (2) | DSS Dominant Drivers (Model, Data, Document, Comm, Knowledge-driven). | *Identify DSS drivers from business scenarios.* |
| **WK5** | Knowledge Management | Tacit vs Explicit knowledge transfer, IT aids in corporate KM. | *Define difference between tacit and explicit.* |
| **WK6** | Data Warehousing | ETL pipelines, OLAP Cube operations (Roll-up, Drill-down, Slice, Dice). | *Explain roll-up vs drill-down details.* |
| **WK7** | Model Components (1) | Optimization models, LP formula (Variables, Objective, Constraints). | *Formulate Objective and Constraint equations.* |
| **WK8** | Model Components (2) | What-If Analysis, Scenario Manager, Goal Seek optimization. | *Solve single-variable target outputs using Goal Seek.* |
| **WK9** | User Interface | Dialog styles (CLI, Menu-driven, GUI), Figma prototyping, usability. | *List major UI design goals (modularity, low load).* |
| **WK10**| Designing DSS (1) | Project planning, requirement gathering, Feasibility (economic/technical).| *Define economic vs organizational feasibility.* |
| **WK11**| Designing DSS (2) | Architectural principles, 3-tier logical architecture layers. | *Draw/Describe 3-tier Logical Layers.* |
| **WK12**| UML Modelling (1) | OO-DSS mapping, UML Use Case actors, Sequence Diagram lifelines. | *UML sequence timeline message direction.* |
| **WK13**| UML Modelling (2) | UML Class attributes (public `+`/ private `-`), Generalization syntax. | *Draw class boxes with correct attribute signs.* |
| **WK14**| Implementation & Eval | Direct cutover, Parallel running, Phased rollout, Pilot study, UAT. | *Compare Direct Cutover risk vs Parallel cost.* |

---

## 🛠️ How to Run Locally

Since the platform is built purely with **Vanilla HTML5, CSS3, and JavaScript**, no installation or server configuration is required:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/dbss2643-dss-hub.git
   cd dbss2643-dss-hub/website
   ```
2. **Open in Browser:**
   Simply double-click `index.html` to launch the study hub dashboard in any modern web browser.
3. **Optional (Local Dev Server):**
   If you want to run a local HTTP server:
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your web browser.
