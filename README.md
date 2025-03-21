---
# **Terminated: A Global Perspective on Layoffs**
---
## **Table of Contents**
---

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---
### Project Overview
---




---
### Data Sources
---




---
### Tools
---

- ***Microsoft Excel*** – Data Cleaning
    - [Kaggle](https://www.kaggle.com/datasets/samayashar/startup-growth-and-funding-trends)
- ***Tableau*** – Creating Reports
- ***Microsoft Powerpoint*** – Creating Background Template

---
### Data Cleaning
---

In the initial data preparation phase, I performed the following tasks:
1. Data Loading and Inspection.
2. Handling Missing Values,
3. Data Cleaning and Formatting.

---
### Exploratory Data Analysis
---

EDA involving exploring the data to answer key questions, such as:

**Temporal Analysis**:

- How has startup activity evolved over time?
  - Do certain years or periods show spikes in startup founding or significant increases in funding rounds?
  - Could these temporal trends be linked to broader economic conditions, technological breakthroughs, or market shifts?

- Is there a relationship between the year a startup was founded and its subsequent performance metrics (such as funding amount or valuation)?
  - Are startups founded in more recent years securing higher funding or achieving faster valuations compared to older ones?
  - Does the data suggest evolving market dynamics that influence the success and growth of startups over time?

**Industry and Geographic Distribution**:

- What is the distribution of startups across various industries and regions?
  - Which industries have the highest concentration of startups or attract the most funding, and how does this vary regionally?
  - Are there identifiable geographic clusters indicating regional startup hotspots or emerging markets?

- How do key performance metrics differ by industry and region?
  - Do certain regions consistently produce startups with higher revenues, valuations, or profitability rates?
  - Are specific industries more dominant in particular regions, and how might this relate to local market conditions or cultural trends?

**Funding and Performance Dynamics**:

- How do funding rounds and amounts correlate with overall startup performance?
  - Are startups that secure more funding rounds also achieving higher valuations or revenue growth?
  - Can distinct funding patterns be observed among industries or during different time periods?

- What insights can be drawn from funding efficiency—such as the ratio of funding received to employee count?
  - Does a higher funding-to-employee ratio align with increased market share or profitability?
  - How do these metrics vary across industries and regions, and what might this indicate about operational scale and resource allocation?



---
### Data Analysis
---
- Created Bins:
  - Funding Amount (Millions Actual)
- Created Measures:
   - Funding Ranges:
     - ```
        IF [Funding Amount (Millions Actual)] < 20000000 THEN "<$20M"
        ELSEIF [Funding Amount (Millions Actual)] <= 40000000 THEN "$20M–$40M"
        ELSEIF [Funding Amount (Millions Actual)] <= 60000000 THEN "$40M–$60M"
        ELSEIF [Funding Amount (Millions Actual)] <= 80000000 THEN "$60M–$80M"
        ELSEIF [Funding Amount (Millions Actual)] <= 100000000 THEN "$80M–$100M"
        ELSEIF [Funding Amount (Millions Actual)] <= 120000000 THEN "$100M–$120M"
        ELSEIF [Funding Amount (Millions Actual)] <= 140000000 THEN "$120M–$140M"
        ELSEIF [Funding Amount (Millions Actual)] <= 160000000 THEN "$140M–$160M"
        ELSEIF [Funding Amount (Millions Actual)] <= 180000000 THEN "$160M–$180M"
        ELSEIF [Funding Amount (Millions Actual)] <= 200000000 THEN "$180M–$200M"
        ELSEIF [Funding Amount (Millions Actual)] <= 220000000 THEN "$200M–$220M"
        ELSEIF [Funding Amount (Millions Actual)] <= 240000000 THEN "$220M–$240M"
        ELSEIF [Funding Amount (Millions Actual)] <= 260000000 THEN "$240M–$260M"
        ELSEIF [Funding Amount (Millions Actual)] <= 280000000 THEN "$260M–$280M"
        ELSEIF [Funding Amount (Millions Actual)] <= 300000000 THEN "$280M–$300M"
        ELSE ">$300M"
        END```
   - Profitability & Exit Status:
     - ```
       IF [Profitable] = 1 THEN
         "Profitable - " + [Exit Status]
       ELSE
        "Not Profitable - " + [Exit Status]
       END
       ```


---
### Results
---

The analysis of startup trends across various industries revealed a clear divergence in momentum over recent years. Notably, startups operating in the **E-Commerce**, **Ed-Tech**, and **Gaming** sectors have demonstrated robust **upward trends**. These industries are not only attracting increasing levels of funding—evidenced by rising funding rounds and higher valuations—but they also show healthy market engagement and growth signals across key performance indicators. In contrast, startups in sectors such as **AI**, **Cybersecurity**, **Fin-Tech**, **Health-Tech**, and **IoT** have exhibited a **downward trend**. The data indicates that these technology-intensive sectors are experiencing a decline in funding activity and overall growth, suggesting potential market challenges, increased competition, or shifting investor sentiment within these domains.

A deeper dive into profitability metrics reveals that profitable **E-Commerce** startups are emerging as standout performers. These companies are achieving higher valuations and commanding higher median funding amounts, even while requiring fewer rounds of funding and operating with leaner employee structures. This efficiency not only marks them as attractive investment targets but also reflects their streamlined business models and rapid scalability. Additionally, the analysis shows that E-Commerce startups are more likely to be retained privately or acquired across sectors, indicating a diverse range of exit strategies that further contribute to their growth and profitability compared to their counterparts in other industries.

Geographical segmentation of the data further enhances our understanding of the startup landscape. The results highlight that regions such as **Australia**, **Asia**, and **Europe** are home to a higher proportion of profitable startups than other regions. The clustering of successful startups in these territories suggests that local market conditions, regulatory environments, and cultural factors may be particularly favorable for startup growth. This regional advantage is evident in both the financial performance and strategic outcomes—such as higher valuations and attractive exit opportunities—observed in these areas. Together, these findings underscore the heterogeneity of the global startup ecosystem, emphasizing that industry trends, profitability metrics, and regional dynamics all play pivotal roles in shaping the competitive landscape.

---
### Recommendations
---

Based on the analysis of startup funding trends and performance metrics, several actionable recommendations emerge to guide investors, startup founders, and industry stakeholders:

1. Focus on High-Growth Sectors: The upward trends observed in the E-Commerce, Ed-Tech, and Gaming sectors suggest that these industries are currently attracting strong investor confidence and market interest. It is recommended that investors consider increasing their exposure to these sectors. For startup founders, leveraging emerging trends and adopting scalable business models in these fields may yield robust growth opportunities.

2. Refine Strategies in Underperforming Sectors: The downward trends in AI, Cybersecurity, Fin-Tech, Health-Tech, and IoT sectors indicate that these industries might be facing increased market challenges, competition, or shifting investor sentiments. Stakeholders in these areas should reexamine their strategic approaches—whether through innovation, restructuring funding strategies, or exploring niche market opportunities—to reverse these declining trends.

3. Capitalize on E-Commerce Efficiency: Profitable E-Commerce startups have shown remarkable strength by achieving higher valuations and median funding amounts with fewer funding rounds and a leaner employee base. This indicates an efficient use of resources and strong market positioning. Investors and entrepreneurs in this space should focus on further optimizing operations, scaling digital capabilities, and exploring strategic exit opportunities such as private-retention or cross-sector acquisitions to maximize value.

4. Emphasize Regional Opportunities: The analysis highlights that regions such as Australia, Asia, and Europe are home to a larger proportion of profitable startups. This suggests that local markets in these regions offer favorable conditions for startup growth. It is advisable for investors to prioritize these geographies when seeking high-return opportunities and for startups to consider strategic positioning within these markets to benefit from regional advantages such as supportive regulatory frameworks, robust infrastructure, and active innovation ecosystems.

By tailoring strategies to these insights, stakeholders can more effectively navigate the complex startup landscape, channel resources toward high-growth opportunities, and drive sustainable, long-term value in an ever-evolving global market.


---
### Limitations
---

While this analysis offers valuable insights into startup growth and funding trends, several limitations should be acknowledged. First, the dataset—sourced from Kaggle—provides a comprehensive snapshot of startup metrics; however, it may not capture the full spectrum of the global startup ecosystem. Data quality and completeness can vary, and certain aspects—such as qualitative factors, macroeconomic influences, or emerging trends outside the recorded time frame—are not captured. Consequently, the insights derived are based solely on the available quantitative attributes (startup name, industry, funding rounds, funding amount, revenue, employees, market share, profitability, year founded, region, and exit status) and may not fully represent the underlying market realities.

Additionally, the analysis relies on aggregated measures and predefined classifications (e.g., grouping industries as upward or downward trending), which can potentially oversimplify the complex dynamics that drive startup performance. For example, the binary profitability indicator does not account for the nuances of financial health, such as margin fluctuations or cash flow variability. Similarly, while the segmentation of funding and performance metrics provides a structured overview, it might mask smaller, yet significant, variations within each category of startups. This level of aggregation may limit the ability to detect subtle trends that could be important for more granular decision-making.

Finally, the use of visualization tools like Tableau offers powerful interactive capabilities, but these visual representations also come with inherent limitations. The interactivity is confined by the structure of the dataset and the design choices made during analysis, potentially leading to oversights if users rely solely on visual summaries without further detailed investigation. Moreover, while global filters help standardize the view across multiple dashboards, they may inadvertently filter out important outlier data that could provide additional context. Despite these limitations, the project serves as an insightful starting point for understanding startup trends and provides a basis for further refined analyses.


---
### References
---

1. [Kaggle](https://www.kaggle.com/datasets/samayashar/startup-growth-and-funding-trends)
