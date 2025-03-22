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

During the turbulent period from March 2020 to March 2023, the global economic landscape experienced significant shifts, leading to widespread workforce reductions across numerous industries. In this project, I harnessed the power of SQL to meticulously clean a comprehensive dataset that included key variables such as company, industry, total laid off, percentage laid off, date, stage, country, and funds raised (in millions). The data was carefully refined by removing duplicate entries, normalizing disparate data formats, addressing both null and blank values, and eliminating unnecessary columns. This thorough cleaning process ensured that the dataset was both reliable and optimized for a detailed analysis.

Once the dataset was streamlined, I conducted an exploratory analysis using SQL to uncover global layoff trends and gain deeper insights into the factors influencing these workforce shifts. The analysis revealed patterns that varied by industry, geographical region, and even the stage of the layoff process, while also highlighting how financial resilience—inferred from funds raised—correlated with the ability to navigate these challenges. Such insights not only paint a vivid picture of the immediate impacts of these layoffs but also contribute to a broader understanding of the evolving labor market dynamics during a period marked by uncertainty and rapid change.


---
### Data Sources
---

The dataset used in this project was sourced from a public [GitHub repository](https://github.com/AlexTheAnalyst/MySQL-YouTube-Series). This repository provided a comprehensive collection of layoff data spanning from March 2020 to March 2023 and included critical details such as company, industry, total laid off, percentage laid off, date, stage, country, and funds raised (in millions). The accompanying metadata and documentation ensured that the dataset's accuracy and context were well understood, providing a solid foundation for subsequent analysis.
Leveraging GitHub as the data source not only facilitated access to reliable, community-curated data but also underscored the transparency and collaborative spirit inherent in open-source projects. By utilizing this platform, I was able to effectively clean, normalize, and analyze the data, ultimately uncovering insightful global layoff trends during a tumultuous economic period. This approach reinforces the value of open-access data repositories in driving meaningful research and analysis.


---
### Tools
---

- ***SQL*** – Data Cleaning
    - [Github](https://github.com/AlexTheAnalyst/MySQL-YouTube-Series)
- ***Tableau*** – Creating Reports
- ***Microsoft Powerpoint*** – Creating Background Template

---
### Data Cleaning
---

In the initial data preparation phase, I performed the following tasks:
1. Data Loading and Inspection - SQL.
2. Remove Duplicates.
3. Handling Missing & NULL Values.
4. Data Cleaning and Formatting.
5. Remove Unnecessary Columns.

---
### Exploratory Data Analysis
---

The analysis of the dataset, which captures layoff events from March 2020 through March 2023, reveals noteworthy patterns in how various companies and industries have been impacted during and after the peak of the COVID-19 pandemic.

**Company Size and Layoff Impact**:

While many small and medium-sized enterprises experienced significant workforce reductions, several industry giants were not immune to the overall downturn. Notably, large companies such as Amazon, Google, Meta, Salesforce, Microsoft, and Phillips each cut over 10,000 jobs. This dual trend suggests that although smaller companies might be more vulnerable to sudden economic shocks, even the largest corporations had to implement major layoffs as the crisis unfolded.

**Industry Impact**:
The data indicates that the most affected sectors include:
- ***Consumer***
- ***Retail***
- ***Transportation***
- ***Finance***
- ***Healthcare***
- ***Food***
- ***Real Estate***
- ***Travel***

These sectors, intertwined with daily social and economic activity, experienced the greatest disruptions likely due to decreased consumer demand, supply chain interruptions, and widespread changes in business operations during the pandemic.
In contrast, industries such as manufacturing, fintech, aerospace, energy, legal, product, recruiting, HR, and support observed comparatively lower layoff figures. This divergence highlights how certain sectors, possibly due to their different operational dynamics or resilience factors, managed to weather the pandemic's economic impact more effectively.

**Geographical Insights**:
Geographically, the United States experienced the highest number of layoffs, with a staggering 256,559 jobs lost—an impact that was unparalleled by any other nation in the dataset. Following the U.S., India recorded 35,993 layoffs, indicating a significant though considerably less severe contraction in employment. The stark contrast between regions underscores varied economic vulnerabilities and recovery trajectories across countries.

**Year-Over-Year Trends**:
A temporal analysis shows that layoffs have increased dramatically year over year within the examined period. In total, the dataset accounts for 383,159 employees laid off, emphasizing that the repercussions of the pandemic have not only been immediate but also compounded over time. This finding suggests that as the economic fallout evolved, organizations across multiple industries and regions continued to adjust by trimming their workforce.

**Summary of Observations**:
- The dataset spans from March 2020 to March 2023, encapsulating the onset and evolution of pandemic-related economic challenges.
- Both small/medium enterprises and large corporations underwent significant layoffs, reflecting the broad-ranging impacts of the crisis.
- Industry-specific vulnerabilities are evident, with sectors such as consumer, retail, and transportation being highly affected, while others like manufacturing and fintech proved relatively resilient.
- The United States bore the brunt of the layoffs, followed by India, pointing to varying degrees of economic fallout on a global scale.
- The upward trend in layoffs highlights the prolonged and deepening impact of the pandemic over time.

This analysis not only elucidates the key trends across different dimensions—company size, industry, and geography—but also sets the stage for further investigation into the underlying causes and long-term implications of these layoff trends in a post-pandemic economy.


---
### Data Analysis
---
![Code 1](https://github.com/user-attachments/assets/176ba5ae-cc81-442a-b33c-618b05f194e3)

![Code 2](https://github.com/user-attachments/assets/33a0863d-6a59-444d-a38f-9e1bc3fc30ef)


---
### Results
---

The analysis of layoff data from March 2020 to March 2023 reveals significant findings about the multifaceted impact of the pandemic on the global workforce. The data show that layoffs affected both small and medium-sized companies as well as large multinational corporations. Notably, even industry giants like Amazon, Google, Meta, Salesforce, Microsoft, and Phillips each cut over 10,000 jobs, illustrating that no company was entirely immune to the unprecedented economic pressures triggered by the crisis.
Layoffs commenced in March 2020 and increased dramatically over the three-year period, with a cumulative total of 383,159 employees laid off globally. This steady upward trend not only reflects an immediate reaction to the pandemic’s onset but also indicates a sustained period of workforce reduction as companies continuously adapted to evolving economic conditions. The temporal pattern emphasizes that the repercussions of the pandemic extended far beyond the initial shock, becoming an enduring challenge for businesses worldwide.

Analyzing the impact by industry reveals that sectors deeply intertwined with consumer behavior and mobility suffered the most. Industries such as consumer, retail, transportation, finance, healthcare, food, real estate, and travel experienced severe disruptions, likely due to dwindling consumer demand, operational constraints, and supply chain interruptions. In contrast, sectors like manufacturing, fintech, aerospace, energy, legal, product development, recruiting, HR, and support registered comparatively lower layoff figures. This suggests that these industries may have benefited either from a lesser direct impact of the pandemic or from more effective mechanisms for adapting to the rapidly changing environment.

Geographical disparities also emerged clearly from the data. The United States, with 256,559 job losses, bore the brunt of the layoffs, reflecting the massive scale of its economic adjustments during the crisis. In comparison, India accounted for 35,993 layoffs, highlighting that while the global nature of the pandemic was undeniable, its severity and consequences varied considerably from one region to another.

Overall, these results underscore a dual narrative of widespread economic strain across businesses of all sizes and specific challenges in industries and regions particularly vulnerable to pandemic-related disruptions. The findings not only quantify the scale of layoffs but also set the stage for further analysis into the underlying causes and long-term implications. Understanding these factors is critical as policymakers and business leaders strive to design recovery strategies and foster resilience in a post-pandemic economy.

---
### Recommendations
---

Based on the comprehensive analysis of layoff trends from March 2020 to March 2023, several strategic recommendations emerge for both industry leaders and policymakers. Organizations, regardless of size, should invest in robust forecasting and risk assessment models that factor in the economic and operational disruptions observed during the pandemic. Leveraging advanced data analytics can help companies anticipate downturns more effectively and develop agile workforce strategies, including diversified talent retention and re-skilling initiatives. In particular, small and medium-sized enterprises should explore collaborative support networks or public-private partnerships to mitigate potential shocks that might otherwise lead to severe layoffs.

Policymakers must also play a proactive role in crafting responsive, targeted economic measures to support affected industries. The disparate impact observed between regions—especially the significant workforce losses in the United States compared to other nations like India—highlights the need for tailored policy interventions that address local economic realities. A focus on incentivizing business resiliency through tax relief, subsidies, or low-interest financing during times of crisis can help stabilize employment levels and ensure that industries most vulnerable to systemic shocks receive the necessary support. Furthermore, investing in programs that enhance workforce adaptability, such as job training and digital skills development, is critical for preparing employees to thrive in rapidly evolving industry landscapes.

In addition to these organizational and governmental strategies, a continued investment in research is essential. Future studies should delve deeper into the interplay between specific industry characteristics and macroeconomic trends to better understand the catalysts behind such workforce disruptions. An in-depth analysis of sector-specific case studies and cross-regional comparisons can uncover best practices and novel approaches, ultimately guiding both strategic business planning and effective public policy formulation. By integrating these recommendations, stakeholders can not only address the immediate challenges highlighted by the data but also pave the way for a more resilient and adaptive employment ecosystem in the future.



---
### Limitations
---

While the analysis provides valuable insights into global layoff trends from March 2020 to March 2023, several limitations must be acknowledged. First, the dataset is confined to publicly available data from reported layoffs, which means that significant events—especially those involving smaller or private companies—might not be fully captured. This limited scope could lead to an underrepresentation of the true extent of layoffs in certain sectors or regions, particularly where disclosure practices vary.

Moreover, the analysis aggregates data over a three-year period, which, while effective for observing long-term trends, may obscure important short-term fluctuations and localized impacts influenced by critical events or policy shifts. The variability in how layoffs are defined and reported across different industries and countries further complicates direct comparisons and may introduce inconsistencies in interpreting the severity of workforce reductions.

Additionally, it is important to note that the dataset does not account for the broader economic or policy contexts that could have influenced these layoffs. Factors such as governmental stimulus packages, regional labor market policies, or concurrent economic pressures are not integrated into the analysis, thus limiting the ability to draw direct causal inferences from the observed trends. This descriptive approach offers a snapshot of the situation without delving into the multifaceted dynamics that drive such large-scale employment changes.

Finally, the inherent challenges of data quality and completeness mean that some layoff events might be misrecorded or subject to reporting biases. Future research with more comprehensive, standardized, or real-time data could address these limitations and provide a more nuanced understanding of the trends. Nonetheless, despite these constraints, the present analysis establishes an important foundation for understanding the widespread impacts of the pandemic on the global workforce and highlights critical areas for further investigation.


---
### References
---

1. [Github](https://github.com/AlexTheAnalyst/MySQL-YouTube-Series).
2. [MySQL](https://www.mysql.com)
3. [Microsoft Excel](https://www.microsoft.com)
4. [Microsoft PowerPoint](https://www.microsoft.com)
5. [Tableau](https://www.tableau.com)
