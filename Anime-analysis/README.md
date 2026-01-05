# Anime Ratings & Trends Dashboard (Power BI)

## Project Description

This project presents an **exploratory and analytical study of anime ratings, popularity, and genre-level trends** using an interactive **Power BI dashboard**.

The dashboard is designed to move beyond simple average scores and instead **uncover patterns in audience behaviour**, including how ratings vary by **genre, anime type, and popularity level**.

Particular attention is given to:
- Differences in **genre popularity and audience reception**
- The relationship between **number of ratings and average score**
- How **anime format (TV, Movie, OVA, ONA, Special)** influences ratings
- Distribution patterns across the **full rating scale**

This project combines **data modelling, visual analytics, and fandom-relevant insights**, making it suitable for portfolio use, exploratory analysis, and entertainment analytics research.

---

## Objectives

The objectives of this project are to:

1. Analyse overall **anime popularity** using total rating counts
2. Compare **average ratings across genres**
3. Identify **top-performing anime titles** by total ratings
4. Examine how **anime type impacts audience scores**
5. Explore the **distribution and spread of ratings**
6. Understand the relationship between **popularity and perceived quality**
7. Provide an **interactive, user-driven dashboard** for exploration

---

## Scope of Analysis

- Dataset scope: **Global anime ratings dataset**
- Time span: **Multiple release years (aggregated view)**
- Population: **Anime titles with user-submitted ratings**
- Level of data: **Aggregated anime-level statistics**

---

## Data Sources

The dashboard is built using a **publicly available anime ratings dataset**, compiled from large-scale user review platforms.

### Dataset Characteristics

- Anime-level aggregation
- User-generated ratings
- Genre and format classification
- Popularity measured via total rating count

### Key Variables

| Category | Description |
|------|------------|
| Anime Title | Name of the anime |
| Genre | Primary genre classification |
| Type | TV, Movie, OVA, ONA, Special |
| Average Rating | Mean user score |
| Total Ratings | Number of user ratings |
| User Count | Unique users contributing ratings |

---

## Data Preparation & Modelling

### Cleaning and Transformation
- Removed duplicate titles
- Standardised genre labels
- Normalised rating scales
- Handled missing values in type and genre fields

### Data Model
- Star-schema style design
- Dimension tables for:
  - Genre
  - Anime Type
- Fact table containing:
  - Ratings
  - User counts
  - Popularity metrics

This structure enables **fast filtering, cross-highlighting, and interactive exploration**.

---

## Dashboard Structure & Visuals

### 1. KPI Summary Cards
High-level overview showing:
- Total ratings
- Total users
- Total anime titles

---

### 2. Average Rating Distribution by Genre
Treemap visual highlighting how **average scores vary across genres**, helping identify consistently well-rated categories.

---

### 3. Top Anime by Total Ratings
Bar chart ranking the **most popular anime titles**, based on audience engagement rather than score alone.

---

### 4. Genre Popularity by Ratings Share
Donut chart showing how total ratings are distributed across genres, revealing **fanbase concentration**.

---

### 5. Rating Distribution Histogram
Displays how user ratings are spread across the scale, identifying clustering and bias toward higher scores.

---

### 6. Average Ratings by Genre and Type
Matrix visual comparing how genres perform across different anime formats (TV, Movie, OVA, etc.).

---

### 7. Popularity vs Rating Scatter Plot
Explores whether **popular anime are also highly rated**, highlighting diminishing returns at scale.

---

## Key Findings

### 1. Popularity Does Not Guarantee Higher Ratings
Highly rated anime are not always the most popular, suggesting **niche genres maintain strong quality perception**.

---

### 2. Genre-Based Rating Differences Are Significant
Genres such as **Drama, Fantasy, and Adventure** tend to show consistently higher average ratings than others.

---

### 3. Movies Often Score Higher Than TV Series
Anime movies show **slightly higher average ratings**, likely due to tighter storytelling and production focus.

---

### 4. Rating Distribution Is Positively Skewed
Most ratings cluster between **7 and 9**, indicating a generally positive user-review culture.

---

## Interpretation & Implications

### For Fans
- High popularity does not always mean higher quality
- Exploring lesser-known genres can yield strong experiences

### For Analysts
- Demonstrates how engagement and satisfaction metrics differ
- Highlights importance of separating **popularity from quality**

### For Portfolio Use
- Shows end-to-end analytical workflow
- Combines entertainment data with business-style insights

---

## Limitations

- User ratings are subjective and biased
- Dataset may overrepresent popular titles
- Genre classification is simplified
- No demographic segmentation available

---

## Future Enhancements

- Time-based trend analysis
- Studio-level comparisons
- Sentiment analysis from reviews
- Recommendation system integration
- Popularity normalisation by release year

---

## How to Use the Dashboard

1. Filter by **Genre**
2. Adjust **Rating range**
3. Explore top anime and genre patterns
4. Compare popularity vs rating behaviour
5. Drill into format-level differences

---

## Tools & Technologies

- Power BI
- DAX
- Public anime ratings datasets
- Data modelling best practices

---

## Intended Audience

- Anime fans and communities
- Data analytics learners
- Portfolio reviewers
- Entertainment and media analysts

---

## License & Usage

This project is shared for **educational and portfolio purposes**.
You are free to reuse and adapt the work with attribution.

---

Built with ❤️ by 
**Shreyas Gowda**  
*MSc Data Science*  
*University of Glasgow*  

**Note:** OpenAI GPT-5.2 was used as a support tool to improve understanding, structuring, and clarity of insights derived from the analysis.
