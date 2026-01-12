## Hospital Lab Turnaround Time Analysis

This project explores patterns in turnaround times for hospital lab tests  using a synthetic intermediate dataset. The goal is to identify differences in turnaround time by test type, department, priority, and result flag.

---

## Objectives
- Calculate average and median turnaround times by test type.
- Visualize daily TAT trends and highlight outliers.
- Suggest operational improvements based on findings.

---

## Dataset
- **Source:** Simulated hospital lab data (1,000 samples)
- **Columns:** `test_type`, `received_time`, `completed_time`, `technician_id`, `result_flag`, `department`, and `priority`


---

## Methods
1. Parsed timestamps and calculated duration (`completed - received`).
2. Grouped by test type, department, priority, and result flag and visualized turnaround times.
---

## Results

### Turnaround Time by Test Type
Average turnaround times varied slightly by test type. Microbiology (1.95 hrs)
and immunology (1.97 hrs) tests showed marginally shorter average turnaround
times than hematology (2.03 hrs) and chemistry (2.04 hrs).

![Turnaround Time by Test Type](visuals/TAT_by_Type.png)

---

### Turnaround Time by Department
Outpatient tests had the highest average turnaround time (2.07 hrs), while ER
and ICU tests were processed slightly more quickly.

![Turnaround Time by Department](visuals/TAT_by_Dept.png)

---

### Turnaround Time by Priority
STAT tests had a slightly shorter average turnaround time (1.98 hrs) compared
to routine tests (2.00 hrs).

![Turnaround Time by Priority](visuals/TAT_by_Priority.png)

---

### Turnaround Time by Result Flag
Tests with abnormal results had a slightly shorter average turnaround time
(1.97 hrs) than tests with normal results (2.00 hrs).

![Turnaround Time by Result Flag](visuals/TAT_by_Result.png)


---
### Overall Turnaround Time Distribution
Most lab tests were completed within approximately 2 hours, with a right-skewed
distribution indicating occasional delays.

![Overall Turnaround Time](visuals/All_TAT.png)

---

## Tools Used
- Python (pandas, matplotlib)
- Jupyter Notebook
- Excel (data validation)
