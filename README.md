# 🩺 Health Economics Project: Cost-Effectiveness of Diabetes Screening in Nairobi

This project explores whether **preventive screening for Type 2 Diabetes** in Nairobi is a **cost-effective intervention** compared to treating diagnosed patients. It uses simulated data and simplified cost-effectiveness analysis (CEA) principles.

---

## 📌 Objectives

- Simulate a basic health economics scenario
- Calculate and compare **Cost-Effectiveness Ratios (CER)** and the **Incremental Cost-Effectiveness Ratio (ICER)**
- Visualize cost vs. health outcomes
- Practice sharing reproducible R-based analysis

---

## 📊 Methods

- Analysis done using **R** and **R Markdown**
- Simulated data on:
  - Cost per patient for Screening (B) vs No Screening (A)
  - Quality Adjusted Life Years (QALYs) gained
- ICER calculated as:
  
  \[
  ICER = \frac{\text{Cost}_{B} - \text{Cost}_{A}}{\text{QALY}_{B} - \text{QALY}_{A}}
  \]

---

## 📂 Files

| File                         | Description                                      |
|------------------------------|--------------------------------------------------|
| `health_econ_diabetes.Rmd`   | Main analysis and narrative                      |
| `health_econ_diabetes.html`  | Rendered report (optional, viewable in browser)  |
| `figures/`                   | Contains plots from the analysis (optional)      |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/health-econ-diabetes.git
