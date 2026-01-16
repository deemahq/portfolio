# Chicago Chronic Disease Hospitalization Disparities

This project examines geographic disparities in chronic disease hospitalizations
across Chicago ZIP codes, focusing on asthma and diabetes. The analysis explores
variation in hospitalization rates by ZIP code and provides contextual discussion
using neighborhood-level socioeconomic hardship indicators.

The goal of this project is to identify patterns and associations in chronic
disease burden across the city, not to establish causal relationships.

---

## Research Questions
- How do asthma and diabetes hospitalization rates vary across Chicago ZIP codes?
- Which ZIP codes experience the highest burden of chronic disease hospitalizations?
- Are similar geographic patterns observed across different chronic conditions?
- How do high-burden ZIP codes relate, contextually, to areas with higher
  socioeconomic hardship?

---

## Data Sources
- **Asthma Hospitalizations by ZIP Code** (City of Chicago)
- **Diabetes Hospitalizations by ZIP Code** (City of Chicago)
- **Hardship Index by Community Area** (City of Chicago)

Health datasets are reported at the ZIP code level, while the hardship index is
reported at the community area level. Due to this difference in geographic units,
the hardship index is used for contextual interpretation rather than direct
statistical merging.

---

## Methods
1. Loaded and cleaned hospitalization datasets using Python.
2. Conducted exploratory data analysis to examine distributions and missing values.
3. Aggregated hospitalization rates by ZIP code and year.
4. Identified ZIP codes with consistently high hospitalization rates for asthma
   and diabetes.
5. Compared geographic patterns across both chronic conditions.
6. Interpreted findings in the context of neighborhood-level socioeconomic hardship.

All findings are interpreted as descriptive and associative.

---


## Tools Used
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Public health data from the City of Chicago

---

## Notes
This project is conducted in stages, beginning with health outcome analysis
and followed by contextual socioeconomic interpretation. Future work may include
additional geographic alignment or visualization tools as appropriate.

