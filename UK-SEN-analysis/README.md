# SEN Pupils Analysis Dashboard (Power BI)

## Project Description

This project presents an in-depth **exploratory and analytical study of pupils with Special Educational Needs (SEN)** in England using an interactive **Power BI dashboard**.

The dashboard is designed to move beyond surface-level statistics and instead **reveal structural patterns, inequalities, and risk factors** affecting how pupils with SEN are supported across the education system.

Particular attention is given to:
- Differences between **mainstream, special schools, and pupil referral units (PRUs)**
- The role of **formal vs informal SEN support**
- The interaction between **SEN type and socio-economic disadvantage**
- Factors that increase the likelihood of **placement in PRUs**

This project combines **data modelling, visual analytics, and policy-relevant interpretation**, making it suitable for academic, professional, and public-sector use.

---

## Objectives

The objectives of this project are to:

1. Analyse how pupils with SEN are distributed across different **types of schools**
2. Identify the **most prevalent SEN primary needs** nationally and regionally
3. Compare **SEN Support vs Statement/EHC plans**
4. Examine **temporal trends** in SEN provision
5. Investigate links between **SEN and socio-economic disadvantage (FSM)**
6. Identify **key influencing factors** associated with placement in PRUs
7. Provide an **interactive, user-driven analytical tool** for stakeholders

---

## Scope of Analysis

- Geographic scope: **England**, with filtering down to **regional and local authority level**
- Time span: **Multiple academic years (2015–2022)**
- Population: **All pupils recorded within the SEN framework**
- Level of data: **Aggregated official statistics**

---

## Data Sources

The dashboard uses **official publicly available UK education datasets**, primarily derived from national school census data.

### Dataset Characteristics

- Aggregated pupil counts
- Annual reporting
- Standardised SEN classifications
- Regionally and institutionally consistent

### Key Variables

| Category | Description |
|------|------------|
| Academic Year | School year |
| Region | Government Office Region / Local Authority |
| Type of School | Primary, Secondary, Special School, PRU |
| SEN Status | No SEN, SEN Support, Statement/EHC |
| Primary Need | Main SEN category |
| FSM Eligibility | Eligible / Not Eligible |

---

## Data Preparation & Modelling

### Cleaning and Transformation
- Normalised naming conventions
- Harmonised SEN categories across years
- Removed inconsistencies in school-type classifications
- Ensured time-series comparability

### Data Model
- Star-schema style design
- Dimension tables for:
  - Region
  - Time
  - School Type
  - SEN Status
  - Primary Need
- Fact table containing pupil counts

This structure enables **efficient slicing, filtering, and cross-visual interaction**.

---

## Dashboard Structure & Visuals

### 1. Decomposition Tree
Used to analyse how total pupil counts break down hierarchically:
```
All Pupils → Type of School → SEN Status → Primary Need
```
This visual helps uncover **pathways through the SEN system**.

---

### 2. Key Influencers (PRU Focus)
Identifies **statistical drivers** that increase the likelihood of a pupil being placed in a **Pupil Referral Unit**.

Outputs are expressed as **relative likelihood (e.g. 2.1× more likely)** rather than absolute counts, allowing meaningful comparison.

---

### 3. Regional Distribution
Shows the proportion of SEN pupils by region, providing context around population density and geographic concentration.

---

### 4. SEN Status Breakdown
Illustrates the dominance of **SEN Support** relative to formal **Statement/EHC plans**.

---

### 5. Primary Need Distribution
Ranks SEN categories from most to least prevalent, highlighting where demand is concentrated.

---

### 6. Time-Series Analysis
Tracks changes in pupil numbers by school type across academic years to identify growth or stability trends.

---

### 7. FSM and SEN Interaction
Explores how **economic disadvantage intersects with SEN**, broken down by:
- Primary Need
- Type of School

---

## Key Findings

### 1. Mainstream Schools Carry the Majority of SEN Provision
Most pupils with SEN are educated within **state-funded primary and secondary schools**, not special schools.

---

### 2. SEN Support Dominates Over Formal Plans
The majority of SEN pupils receive **SEN Support**, with **Statement/EHC plans accounting for a small minority**.

This highlights reliance on informal support mechanisms.

---

### 3. Most Common SEN Needs
The highest-prevalence primary needs are:
- Speech, Language and Communication
- Moderate Learning Difficulty
- Social, Emotional and Mental Health
- Specific Learning Difficulty
- Autistic Spectrum Disorder

Physical and sensory impairments are comparatively rare.

---

### 4. Strong Risk Factors for PRU Placement
The likelihood of placement in PRUs increases significantly when:
- Primary need is **SEN support without specialist assessment**
- The need relates to **SEMH, speech & language, or learning difficulties**

This suggests **gaps in early assessment and intervention**.

---

### 5. Socio-Economic Disadvantage and SEN Are Closely Linked
FSM eligibility is disproportionately high among pupils with:
- ASD
- SEMH
- Moderate Learning Difficulties

FSM-eligible pupils are also over-represented in **special schools and PRUs**.

---

### 6. Trends Over Time
- Overall SEN pupil numbers remain stable
- Special school populations show gradual growth
- PRU populations remain small but persistent

---

## Interpretation & Implications

### Policy
- Early specialist assessment may reduce PRU placements
- Increased demand for specialist provision is likely to continue

### Schools
- SEMH and communication needs require early, targeted support
- FSM pupils represent a higher-risk group

### Research
- Demonstrates the value of **interactive analytics** for education policy analysis

---

## Limitations

- Aggregated data prevents individual-level causal inference
- Reporting practices may vary between regions
- FSM is an imperfect proxy for disadvantage
- SEN categories are administratively defined

---

## Future Enhancements

- Inclusion of exclusion and attendance data
- Local authority benchmarking
- Post-16 SEN transition analysis
- Outcome-based measures
- Predictive modelling

---

## How to Use the Dashboard

1. Select a **Region**
2. Select an **Academic Period**
3. Explore SEN pathways using interactive visuals
4. Drill down into PRU risk factors
5. Compare needs, school types, and FSM status

---

## Tools & Technologies

- Power BI
- DAX
- UK education open data
- Data modelling best practices

---

## Intended Audience

- Education policymakers
- Local authorities
- School leadership teams
- Researchers
- MSc / undergraduate students

---

## License & Usage

This project is shared for **educational and research purposes**.
You are free to reuse and adapt the work with attribution.

---

Built with ❤️ by
**Shreyas Gowda**  
*MSc Data Science*  
*University of Glasgow*  

Feel free to use, learn from, and build upon this work.

**Note:** OpenAI GPT-5.2 was used as a support tool to improve understanding, summarisation, and clarity of insights derived from the analysis.