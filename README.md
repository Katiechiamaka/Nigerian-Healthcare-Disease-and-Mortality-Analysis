# Nigerian Healthcare Disease and Mortality Analysis

![35653997-kvinna-lakare-besok-en-patient-liggande-pa-sjukhus-sang-patient-sjukhusvistelse-begrepp-vektor-tecknad-serie-illustration-vector](https://github.com/user-attachments/assets/1a954a92-0740-48b6-ae27-c3c75c51046a)

# Project Overview 
This project explores disease incidence and mortality trends across states, years, age groups, and rural/urban populations. The analysis identifies high-risk states, most affected age groups, and year-over-year disease patterns to support data-driven public health decisions.

# Problem Statement
Infectious diseases vary across different Nigeria regions, populations, and time, impacting public health planning. This analysis addresses key questions on incidence, mortality, and vulnerable groups.

- Which states has the highest incidence of Malaria and Cholera?
- Which State has the highest death rate due to Cholera?
- Which group do we have the highest disease occurrence, rural or urban?
- Which diseases has the highest death rate in 2010 and 2018?
- Which year do we have highest incidence of Meningitis?
- Which Age group are more susceptible to Diarrhoea?

# Business Objectives
To analyze disease incidence, mortality trends, and demographic vulnerability across states and years, enabling data-driven public health decisions and targeted interventions.

# Dataset Description
The dataset contains healthcare records capturing disease incidence, mortality, and demographic information across multiple states and years. 
Each row represents a patient or reported case and includes attributes such as
- **Location:** Nigeria
- **State:** 37 States
- **Report:** From 2009 to 2018
- **Disease:** 
- **Status:** Alive/Dead
- **Age Group**
- **Location:** Rural/Urban.
  
  The dataset enables analysis of disease occurrence, death rates, demographic vulnerability, and temporal trends for public health planning and decision-making.

# Tools and Techniques
### Tool

- **Power BI** – Used for data cleaning, data transformation, analysis, and dashboard visualization.

### Techniques
- Data Transformation using Power Query
- DAX Calculations for metrics such as total cases, deaths, and death rate
- Data Visualization using charts (bar charts, line charts, donut charts, and cards)
- Interactive Dashboard Design using slicers and filters

# Dashboard

<img width="1097" height="727" alt="NIgerian Healthcare Dashboard" src="https://github.com/user-attachments/assets/932941dd-d29e-49b0-bf7f-cf76f5e687e7" />

# Key Business Questions Answered
### Which states has the highest incidence of Malaria and Cholera?

<img width="652" height="350" alt="Malaria And Cholera cases across States" src="https://github.com/user-attachments/assets/390f29c6-2d43-4efe-8fce-b2ad4991a26e" />

#### Insights
- Sokoto and Abia show the highest combined incidence of Cholera, indicating higher cholera disease burden in these states.
- Abia has the lowest reported case for malaria, suggesting either better disease control or lower incidence.
- In most states, Cholera cases appear slightly higher than Malaria, indicating cholera may require more targeted interventions in these areas.

### Which State has the highest death rate due to Cholera?

<img width="399" height="243" alt="Cholera Moratlity rate" src="https://github.com/user-attachments/assets/2fce1863-02f4-46de-8618-90db3b9b9381" />

#### Insights
- Bayelsa and Cross River recorded the highest cholera mortality rate at 100%, indicating extremely severe outcomes for reported cases.
- Enugu and Yobe follow with 80% mortality, which is also significantly high.
- The high mortality rates across several states highlight possible gaps in access to timely treatment and healthcare resources.
  
### Which group do we have the highest disease occurrence, rural or urban?

<img width="310" height="247" alt="Disease occurence by location" src="https://github.com/user-attachments/assets/4bd33a78-272f-4715-a562-54a163fbefb9" />

#### Insights
- Disease occurrence is almost evenly distributed between rural and urban areas.
- Urban areas account for about 50.24% of cases, slightly higher than rural areas.
- The small difference suggests that disease spread affects both locations similarly, emphasizing the need for nationwide public health interventions rather than location-specific focus alone.

### Which diseases has the highest death rate in 2010 and 2018?

<img width="354" height="298" alt="Top disease by death rate" src="https://github.com/user-attachments/assets/7935d538-4ebc-47ad-8f37-6e87a09e5bd1" />

#### Insights
- Measles experienced the largest increase in death rate, rising from 50% in 2010 to 67% in 2018.
- Viral Hemorrhagic Fever also increased from 50% to 57%, indicating worsening outcomes.
- Rubella showed a decline in death rate, suggesting improved treatment or vaccination coverage.
- Ebola maintained a consistently high death rate (63%), highlighting its continued severity.

### Which year do we have highest incidence of Meningitis?

<img width="401" height="299" alt="Meningitis Incidence rate" src="https://github.com/user-attachments/assets/a989b9e5-4e40-4fcd-b6d2-4250c4e74693" />

#### Insights
- The lowest incidence occurred in 2010, with 10 cases.
- The highest meningitis incidence occurred in 2015, with 28 reported cases, indicating a significant increase after 2010 low occurance.
- After the peak in 2015, there was a steady decline in cases, suggesting improved disease control measures and interventions over time.

### Which Age group are more susceptible to Diarrhoea?

<img width="318" height="298" alt="Diarrhoea Incidence across age group" src="https://github.com/user-attachments/assets/76b80619-a7e9-416b-90fb-2df34126906a" />

#### Insights
- Young adults recorded the highest diarrhoea incidence (61 cases), making them the most affected group.
- Adults and teenagers also show relatively high incidence levels.
- The elderly group recorded the lowest incidence (11 cases).

This pattern suggests that working-age populations may have higher exposure to risk factors such as contaminated food or water sources.

# Recommendation
- High-incidence states such as Sokoto, Kebbi, and Niger should receive targeted public health interventions, including mosquito net distribution, sanitation programs, and improved access to clean water.

- States with extremely high cholera mortality rates should strengthen emergency healthcare response by improving early diagnosis, treatment availability, and rapid medical intervention.

- Healthcare infrastructure should be expanded in both urban and rural areas since disease occurrence is almost evenly distributed across the two settlement types.

- Vaccination and disease control programs should be intensified to reduce the rising death rates observed in diseases such as measles and viral hemorrhagic fever.

- Public health education campaigns should focus on young adults and adults, as they show the highest incidence of aome disease e.g., diarrhoea.

- Health authorities should implement stronger disease surveillance and early warning systems to detect and respond quickly to outbreaks such as the spike in meningitis cases.


# Conclusion
The analysis reveals significant variations in disease incidence and mortality across Nigerian states, years, and population groups. Certain states experience higher cases of malaria and cholera, while some diseases exhibit notably high mortality rates. Disease occurrence is almost evenly distributed between rural and urban areas, and specific age groups are more affected by illnesses such as diarrhoea. These findings highlight the need for targeted public health interventions, improved disease monitoring, and strengthened healthcare systems to reduce disease burden and mortality.

