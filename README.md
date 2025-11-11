# 🛒 OpenCart Manual Testing

![Status](https://img.shields.io/badge/status-in--progress-yellow)
![Tests](https://img.shields.io/badge/tests-142%20executed-green)
![Bugs](https://img.shields.io/badge/bugs-21%20found-red)

This repository documents a manual testing project for the [OpenCart Demo Application](https://demo.opencart.com), based on the SDET-QA course by Pavan Kumar.  
All core artifacts (FRS, Test Plan, Test Scenarios, Test Cases, Bug Reports) originate from the course and were used for learning and practice purposes.

The project has been partially executed and extended by **Piotr Staszewski**, with original test case execution, bug validations, and documentation improvements.

---

## 📌 Project Overview

- **Product Name:** OpenCart (Frontend)
- **Prepared By:** Piotr Staszewski
- **Based On:** SDET-QA course materials by Pavan Kumar
- **Version:** 1.0

This portfolio demonstrates practical manual testing skills, including requirement analysis, test case design, execution, bug reporting, and traceability documentation.

---

## 📂 Repository Structure

OpenCart-Manual-Testing/
```
├── README.md
├── 01.FRS.pdf
├── 02.Test_Plan.pdf
├── 03.Test_Scenarios.ods
├── 04.Test_Cases.ods
├── 05.Bug_Report.ods
├── 06.RTM.ods
└── Screenshots/
    ├── OC-BUG-3.png
    ├── OC-BUG-8.png
    └── ...
```

---

## ✅ Scope of Testing

Functional areas covered:

- Register / Login / Logout / Forgot Password
- Search / Product Compare
- UI, Accessibility, Security, Performance
- Multi-browser and mobile compatibility

---

## 🔍 Scope of Execution

Out of 31 defined test scenarios, the following have been executed independently:

| Test Scenario ID | Description        | Test Cases | Status    |
|------------------|--------------------|------------|-----------|
| TS_001           | Register Account   | 34         | Executed  |
| TS_002           | Login              | 33         | Executed  |
| TS_003           | Logout             | 14         | Executed  |
| TS_004           | Forgot Password    | 30         | Executed  |
| TS_005           | Search             | 31         | Executed  |

Remaining 26 scenarios are **defined only** and will be executed incrementally.

---

## 📊 Summary

| Artifact              | Count / Status                            |
|-----------------------|-------------------------------------------|
| Test Scenarios        | 31 total (5 executed, 26 defined only)    |
| Test Cases            | 142 executed by author                    |
| Bugs Reported         | 21 total (some verified independently)    |
| Blocked Test Cases    | 10+ (due to email system issues)          |
| RTM                   | Included (Excel + Markdown)               |
| Notes                 | Manual Testing Theory (SDET-QA)           |

---

## 🔗 Requirement Traceability Matrix (RTM)

| Requirement ID | Test Scenario ID | Test Case Range       | Status    | Bug IDs Found             |
|----------------|------------------|-----------------------|-----------|---------------------------|
| 1.1            | TS_001           | TC_RF_001 – TC_RF_034 | Executed  | OC-BUG-1 to OC-BUG-9      |
| 1.2            | TS_002           | TC_LF_001 – TC_LF_033 | Executed  | OC-BUG-10 to OC-BUG-15    |
| 1.3            | TS_003           | TC_LG_001 – TC_LG_014 | Executed  | OC-BUG-16                 |
| 1.4            | TS_004           | TC_FP_001 – TC_FP_030 | Executed  | OC-BUG-17 to OC-BUG-20    |
| 1.5            | TS_005           | TC_SF_001 – TC_SF_031 | Executed  | OC-BUG-21                 |
| 1.6–4.1        | TS_006–TS_031    | Various ranges        | Defined only | —                       |

---

## 🧠 My Contribution

- Executed **142 test cases** across 5 key scenarios  
- Reported and documented bugs with reproduction steps and screenshots (stored in `/screenshots/`)  
- Created RTM to map requirements → test cases → bugs  
- Organized and structured all documentation for GitHub presentation  

---

## 🚧 Project Status


This manual testing portfolio is a **work in progress**.  
Currently, 5 out of 31 defined test scenarios have been fully executed.  
Remaining scenarios are defined and will be executed incrementally.  
Additional test cases may be added in the future as the project evolves.

---

## 📎 How to Use

1. Review `FRS.pdf` and `Test_Plan.pdf` to understand the scope.
2. Review `Test_Scenarios.ods` for the full list of 31 defined scenarios (5 executed, 26 defined only).
3. Explore `Test_Cases.ods` for detailed execution steps.  
4. Check `Bug_Report.ods` for identified issues (screenshots in `/screenshots/`).  
5. Use `RTM.ods` to trace coverage.  


---

