# Pokémon Analytics Dashboard (Power BI)

## Project Description

This project presents an exploratory and analytical study of Pokémon data using an interactive **Power BI dashboard**.

The dashboard moves beyond simple Pokémon counts and focuses on analysing **stat distributions, type composition, legendary presence, and generational trends**. It combines descriptive analytics with visual storytelling to make Pokémon data easy to explore, compare, and interpret.

This project is designed both as a fun dataset exploration and as a **portfolio-ready demonstration of Power BI, data modelling, and analytical thinking**.

---

## Objectives

The objectives of this project are to:

1. Analyse the overall distribution of Pokémon across generations
2. Compare legendary and non-legendary Pokémon proportions
3. Examine combat-related stats such as Attack and Defense
4. Understand Pokémon type composition and dominance
5. Identify types with higher average total stats
6. Explore the prevalence of dual-type Pokémon
7. Provide an interactive dashboard for intuitive exploration

---

## Scope of Analysis

- Domain: Pokémon dataset
- Generations covered: Multiple Pokémon generations
- Analysis focus:
  - Base stats
  - Pokémon types
  - Legendary classification
  - Generational distribution
- Level of data: Pokémon-level records

---

## Data Sources

The dashboard is built using a structured Pokémon dataset commonly used for analytics and data science practice.

### Dataset Characteristics

- One record per Pokémon
- Includes base stats such as Attack, Defense, Speed, and Total
- Categorical attributes for Type 1, Type 2, Generation, and Legendary status

### Key Variables

| Category | Description |
|--------|-------------|
| Name | Pokémon name |
| Type 1 | Primary Pokémon type |
| Type 2 | Secondary Pokémon type (if any) |
| Generation | Pokémon generation |
| Legendary | Legendary status (True/False) |
| Attack | Base attack stat |
| Defense | Base defense stat |
| Total | Sum of all base stats |

---

## Data Preparation & Modelling

### Cleaning and Transformation

- Verified data consistency across generations
- Standardised Pokémon type naming
- Handled missing Type 2 values
- Validated base stat calculations
- Ensured correct legendary classification

### Data Model

A flat analytical model was used:

- Pokémon fact table containing stats and attributes
- Derived measures created using DAX for averages and proportions

This structure supports fast filtering and responsive visual interactions.

---

## Dashboard Structure & Visuals

### 1. KPI Overview

Top-level KPI cards provide a snapshot of the dataset:
- Total Pokémon
- Total Legendary Pokémon
- Number of Dual-Type Pokémon
- Average Total Base Stats

---

### 2. Attack vs Defense Analysis

A scatter plot visualises the relationship between **Attack and Defense**, helping to:
- Identify balanced vs specialised Pokémon
- Spot outliers with extreme stats
- Understand overall stat distribution

---

### 3. Legendary Distribution

A donut chart shows the proportion of:
- Legendary Pokémon
- Non-Legendary Pokémon

This highlights how rare legendary Pokémon are within the dataset.

---

### 4. Pokémon by Generation

A bar chart displays the total Pokémon count per generation, allowing:
- Comparison of generation sizes
- Identification of expansion trends over time

---

### 5. Pokémon by Primary Type

A ranked bar chart shows Pokémon counts by **Type 1**, helping identify:
- Most common Pokémon types
- Underrepresented types

---

### 6. Average Total Stats by Type

This visual compares the **average total base stats** across Pokémon types, highlighting:
- Types with generally stronger Pokémon
- Differences between offensive and defensive-focused types

---

## Key Findings

### 1. Legendary Pokémon Are Rare

Legendary Pokémon make up a small percentage of the total dataset, reinforcing their exclusive status.

---

### 2. Clear Type Imbalances Exist

Some Pokémon types are significantly more common than others, indicating design preferences across generations.

---

### 3. Certain Types Have Higher Average Stats

Flying, Steel, and Psychic types tend to show higher average total stats compared to other types.

---

### 4. Generational Growth Is Uneven

Some generations introduce significantly more Pokémon than others, reflecting shifts in franchise expansion.

---

## Interpretation & Use Cases

### Analytics & Learning
- Demonstrates data modelling and DAX fundamentals
- Shows effective use of Power BI visuals
- Highlights exploratory data analysis techniques

### Portfolio Value
- Strong example of combining fun datasets with serious analytics
- Easy for recruiters to understand and engage with
- Visually appealing and interactive

---

## Limitations

- No battle mechanics or move sets included
- Stats are static and do not reflect in-game balancing
- No time-based or usage analytics
- Pokémon variants and forms are not separately analysed

---

## Future Enhancements

- Inclusion of Speed and Special stats analysis
- Type effectiveness and matchup exploration
- Pokémon clustering based on stat profiles
- Generation-wise stat evolution analysis
- Integration with battle simulation data

---

## How to Use the Dashboard

1. Use slicers to filter by Generation and Legendary status
2. Hover over visuals to view detailed tooltips
3. Click on bars and charts to cross-filter insights
4. Compare Pokémon types interactively
5. Explore stat relationships through scatter plots

---

## Tools & Technologies

- Power BI
- DAX
- Data modelling
- Interactive visual analytics

---

## Intended Audience

- Data analysts
- Power BI learners
- Pokémon fans
- Students and portfolio reviewers

---

## License & Usage

This project is shared for educational and portfolio purposes.
You are free to reuse and adapt the work with attribution.

---

Built with ❤️ by 
**Shreyas Gowda**  
*MSc Data Science*  
*University of Glasgow*

Note: OpenAI GPT-5.2 was used as a support tool to improve clarity, structure, and analytical articulation.
