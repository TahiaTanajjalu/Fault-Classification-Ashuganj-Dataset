# Fault Classification — Ashuganj Power Plant Dataset

This project applies machine learning to classify power plant operational events from the **Ashuganj Power Station** logbook dataset.  
The dataset was **collected and cleaned by me**, including fixing headers, cleaning dates, normalizing event types, and preparing NLP text features.

---

## Dataset

- Source: Ashuganj Power Station Company Ltd.
- Collected manually from plant logbook registers.
- Columns: Date, Time, Unit, Event, Cause, Maintenance.
- Cleaned and standardized for ML use.

---

## Methods

### Data Cleaning
- Fixed header row  
- Standardized multiple date formats  
- Parsed time  
- Normalized event names (Trip / Shutdown / Start / Other)  
- Filled missing causes  
- Added features (Month, Day, Weekday)

### Modeling
- TF-IDF text vectorization  
- Multinomial Naive Bayes classifier  
- Train-test split (80/20)

### Evaluation
