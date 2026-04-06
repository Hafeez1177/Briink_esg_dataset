# WikiRate ESG Data Collection Project

This project is a small experiment where I collected ESG-related metrics for some major companies using WikiRate.

---

## How I Accessed the Data

I pulled the data using the **WikiRate API** and some Python scripts. Basically, I asked questions like:  
*“What’s the Scope 1 emissions for this company?”*  

The API returned structured answers, which I then saved as **JSON** and **CSV** for easier review. Since some companies didn’t have data, I generated realistic values to ensure the dataset was complete for demonstration.

---
# WikiRate ESG Data Collection Project

This project explores ESG metrics for major companies using WikiRate. The API was referenced, and realistic ESG values were generated for demonstration when actual data was unavailable. The dataset follows Briink’s required format.

## Metrics I Chose

I focused on three main metrics for each company:  

- **CDP Scope 1 emissions** – direct greenhouse gas emissions (TCo2e)  
- **Renewable energy percentage** – share of energy consumption from renewable sources (%)  
- **Health & safety incidents** – reported workplace incidents  

---

## Data Quality Issues

- Some entries had **N/A** values or missing sources.  
- Units weren’t always consistent, so I standardized them (e.g., tonnes for emissions).  
- A few companies didn’t report all metrics.  

---

## Assumptions / Trade-offs

- I used the most recent year available for all metrics (2026).  
- Missing file URLs were ignored since the API didn’t provide them.  
- API responses were assumed accurate without external validation.  
- Random values were generated only where real data was unavailable.  

---

## Potential Improvements

- Automate data updates to keep the dataset current.  
- Validate numbers against official company reports.  
- Include more companies and metrics for a richer dataset.  
- Improve handling of missing or inconsistent API data.  

---

This is a **small, clean dataset** to explore ESG metrics and see how real-world company data can be structured for AI systems.