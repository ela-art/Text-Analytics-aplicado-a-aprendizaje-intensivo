# Emotional Analytics of a Career Transition  
### Exploratory Text Analysis of a Bootcamp Experience

## Project Overview

This project is an experimental exploratory analysis based on a personal diary written during an intensive Data Analytics Bootcamp.

The objective was to transform unstructured narrative text into structured, analyzable data using Python and to identify emotional and behavioral patterns over time.

The project demonstrates how qualitative narrative can be converted into quantitative signals and analyzed using data workflows comparable to business environments.

---

## Objectives

- Convert unstructured text into structured tabular data
- Engineer measurable emotional and contextual variables
- Analyze emotional intensity over time
- Explore relationships between academic pressure and emotional variation
- Produce analytical and dashboard-ready visualizations (Python + Tableau)

---

## Dataset

- 19 dated diary entries
- One row per entry
- Text extracted and normalized programmatically
- Keyword-based emotional and contextual variables generated

Derived metrics:
- `emotional_negative_intensity`
- `emotional_positive_intensity`
- `emotional_balance`
- Word count per entry

---

## Methodology

### Data Processing (Python)
- PDF text extraction
- Date parsing and structuring
- Text normalization
- Feature engineering via keyword frequency detection

### Exploratory Data Analysis
- Temporal aggregation (daily and monthly)
- Correlation analysis (Pearson)
- Scatter analysis between workload proxies and emotional intensity
- Emotional balance trend modeling

### Visualization
- Python (pandas, matplotlib, seaborn)
- Tableau dashboard for executive-style visualization

---

## Key Insights

- Emotional intensity fluctuated episodically rather than decreasing linearly.
- Peaks in negative emotional intensity aligned with evaluation periods.
- Study-related mentions alone did not strongly predict emotional stress.
- Positive and negative emotions coexisted during high-pressure phases.
- Text length did not correlate with emotional intensity.

---

## Business Relevance

Although based on a personal dataset, the methodology is transferable to business contexts:

- Transforming unstructured text (employee feedback, customer reviews, support tickets) into measurable signals.
- Detecting emotional peaks linked to operational events (deadlines, launches, evaluations).
- Enabling lightweight People Analytics approaches without complex NLP models.
- Supporting early detection of stress patterns, disengagement, or churn signals.

The project illustrates how narrative data can inform decision-making when properly structured.

---

## Technical Stack

- Python  
  - pandas  
  - matplotlib  
  - seaborn  
- Tableau  
- Git & GitHub  

---

## Limitations

- Small dataset (19 entries)
- Keyword-based proxy approach (no advanced NLP model)
- Correlation analysis does not imply causation

This is an exploratory analytical exercise, not a statistically generalizable study.

---

## Future Improvements

- Expand dataset across longer time periods
- Implement NLP techniques (tokenization, lemmatization, sentiment models)
- Compare emotional patterns across different professional contexts
- Develop predictive modeling for emotional intensity trends

---

## Author

Ela Ruiz González  
Data Analyst | Performing Arts Background  
Exploring the intersection of narrative, behavior, and data.
