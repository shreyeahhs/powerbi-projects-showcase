# Hospital Patient Experience Survey Analytics (Power BI)

## Project Description

This project presents a detailed **exploratory and comparative analysis of hospital patient experience survey data** using an interactive **Power BI dashboard**.

The dashboard is designed to assess how patients perceive core dimensions of healthcare quality across multiple hospitals, with a specific focus on **attention to physical and environmental needs** and **effectiveness of treatment**. Rather than relying on single headline metrics, the analysis explores **distributional patterns, temporal stability, inter-hospital variation, and relationships between survey domains**.

The project demonstrates how survey-based data can be transformed into an **interactive decision-support tool** for healthcare managers, analysts, and researchers interested in service quality monitoring and benchmarking.

---

## Objectives

The objectives of this project are to:

1. Compare patient experience scores across **multiple hospitals**
2. Evaluate performance differences between **survey domains**
3. Analyse **average scores, variability, and response volume** per hospital
4. Examine **changes in patient experience over time**
5. Identify **consistency and volatility** in survey responses
6. Explore **correlations between survey items and domains**
7. Provide an **interactive dashboard** for exploratory and comparative analysis

---

## Scope of Analysis

- Geographic scope: **England (sample hospital dataset)**
- Time span: **2020–2021**
- Population: **Patients responding to hospital experience surveys**
- Level of data: **Aggregated survey responses**
- Unit of analysis: **Hospital-level and time-based summaries**

---

## Data Sources

The dashboard is built using a **sample hospital patient experience survey dataset** designed to replicate the structure and behaviour of real-world NHS-style survey data.

### Dataset Characteristics

- Survey responses collected over time
- Multiple hospitals included
- Ordinal survey scales (e.g. 1–5)
- Repeated measurements per hospital
- Domain-level survey questions

---

## Key Variables

| Category | Description |
|--------|-------------|
| hospital_id | Unique hospital identifier |
| hospital_name | Hospital name |
| Year | Survey year |
| Quarter | Calendar quarter |
| Month | Month of response |
| Day | Day of response |
| Postcode | Hospital postcode |
| apen | Attention to Physical & Environmental Needs score |
| efftreat | Effectiveness of Treatment score |

---

## Data Preparation & Modelling

### Cleaning and Transformation

- Standardised hospital identifiers and naming
- Verified survey scale consistency
- Removed incomplete or invalid records
- Created time-based fields for trend analysis
- Ensured comparability of scores across hospitals

### Data Model

- Single fact table containing survey responses
- Time attributes embedded for flexibility
- Measures created using DAX for:
  - Average scores
  - Total response counts
  - Domain-level comparisons
  - Trend analysis

This structure supports **dynamic filtering, slicing, and drill-down exploration**.

---

## Dashboard Structure & Visuals

### 1. Interactive Filters and Slicers

Users can filter the dashboard by:
- Hospital
- Attention to Physical & Environmental Needs score
- Effectiveness of Treatment score

This enables focused analysis of specific hospitals or score ranges.

---

### 2. Domain Distribution per Hospital

Pie charts display how survey responses are distributed across hospitals for:
- Attention to Physical & Environmental Needs
- Effectiveness of Treatment

These visuals highlight **relative contribution and variation** between hospitals rather than absolute performance alone.

---

### 3. Hospital-Level Summary Tables

Tabular visuals provide:
- Total response counts
- Average domain scores
- Hospital-by-hospital comparison

These tables allow quick benchmarking and validation of patterns seen in charts.

---

### 4. Time-Series Analysis

Line charts track survey scores over time for each hospital, allowing users to:
- Identify stability or volatility in patient experience
- Detect short-term dips or improvements
- Compare temporal patterns across hospitals

Separate visuals are used for each survey domain.

---

### 5. Bar Charts with Variability Indicators

Bar charts summarise average scores per hospital with error bars, illustrating:
- Central tendency
- Score dispersion
- Consistency of patient experience

This helps distinguish between consistently average performance and unstable results.

---

### 6. Correlation Heatmap

A correlation heatmap explores relationships between:
- Hospitals
- Individual survey items
- Survey domains

The heatmap reveals:
- Moderate positive relationships within domains
- Weak or negative correlations across some items
- Limited redundancy between survey questions

This supports interpretation of survey design and construct validity.

---

## Key Findings

### 1. Variation Exists Across Hospitals

Average patient experience scores differ across hospitals in both domains, indicating **uneven service quality perceptions**.

---

### 2. Domain Performance Is Not Uniform

Hospitals performing well in physical and environmental needs do not always score equally well in treatment effectiveness, suggesting **domain-specific strengths and weaknesses**.

---

### 3. Temporal Stability with Occasional Volatility

Most hospitals show stable trends over time, with occasional fluctuations likely driven by:
- Operational pressures
- Seasonal effects
- Isolated service disruptions

---

### 4. Moderate Within-Domain Correlations

Survey items within the same domain tend to correlate moderately, supporting the internal coherence of the survey structure.

---

### 5. Limited Cross-Domain Correlation

Physical environment scores and treatment effectiveness are not strongly correlated, reinforcing the need to evaluate patient experience as a **multi-dimensional construct**.

---

## Interpretation & Implications

### Healthcare Management

- Identifies hospitals requiring targeted improvement
- Highlights domains needing focused intervention
- Supports benchmarking and performance monitoring

### Quality Improvement Teams

- Enables early detection of declining patient experience
- Encourages data-driven service redesign
- Supports prioritisation of improvement initiatives

### Research and Analytics

- Demonstrates use of Power BI for survey analytics
- Shows value of visual analytics in healthcare quality assessment
- Provides a foundation for more advanced modelling

---

## Limitations

- Sample dataset limits real-world generalisation
- Aggregated data prevents individual-level inference
- Survey responses may be subject to response bias
- Correlation does not imply causation

---

## Future Enhancements

- Inclusion of demographic variables
- Integration with clinical outcome data
- Hospital peer-group benchmarking
- Statistical testing of score differences
- Predictive modelling of patient satisfaction
- Automated anomaly detection

---

## How to Use the Dashboard

1. Select a hospital or score range using slicers
2. Compare average scores across hospitals
3. Explore trends over time
4. Review correlation patterns
5. Use tables to validate visual insights

---

## Tools & Technologies

- Power BI
- DAX
- Survey analytics techniques
- Data modelling best practices

---

## Intended Audience

- Healthcare managers
- Quality improvement teams
- Data analysts
- Students and researchers
- Public-sector professionals

---

## License & Usage

This project is shared for **educational and demonstration purposes**.

You are free to reuse and adapt the work with attribution.

---

Built with ❤️ by  
**Shreyas Gowda**  
*MSc Data Science*  
*University of Glasgow*  

**Note:** OpenAI GPT-5.2 was used as a support tool for structuring analysis, summarisation, and clarity of insights.
