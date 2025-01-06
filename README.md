# EBOLA-OUTBREAK-AND-MONITORING-DASHBOARD


# Ebola outbreak and Monitoring Dashboard (Excel to Power BI Project)
## Problem Statement

The Ebola outbreak demonstrates significant geographic and systemic disparities in case management and outcomes. While overall cases and deaths have declined over time, showing the effectiveness of public health interventions, Liberia and Sierra Leone continue to report the highest number of cases and deaths, depicting the need for sustained resource allocation. Guinea, despite lower case numbers, exhibits disproportionately high case fatality rates (CFR), suggesting challenges in healthcare capacity, early detection, and treatment. Additionally, a substantial proportion of cases remain classified as probable or suspected, highlighting the critical need for rapid testing and confirmation to ensure accurate reporting and timely intervention. These trends point to the necessity of tailored public health strategies, enhanced healthcare infrastructure, and strengthened diagnostic capabilities to mitigate the impact of current and future outbreaks.


### Steps followed 

- Step 1 : Load data into Microsoft Excel, dataset is a csv file
- Step 2 : Data cleaning using find and replace to shorten character length of variable names.
- Step 3: Using filtes and conditional formating to identify blanks cleaning using find and replace missing data.
- Step 4 : New varaible were created Month and year using the text function.
- Step 5 : Load data into Power BI Desktop, dataset is a csv file
- Step 6 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 7 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 8 : In the report view, under the view tab, theme was selected.
- Step 9 : A bar chart was also added to the report design area representing a plot of the indicators against the countries.

![Sum value by indicator and country](https://github.com/user-attachments/assets/d8c65646-40c6-455c-9ad5-e07db084732d)

- Step 10 : A donut chart was also added to the report design area representing the sum of ebola indicators.

![Sum value of Ebola indicators](https://github.com/user-attachments/assets/e0e08236-b4c3-463e-9bd4-80c25f1be2f1)

- Step 11 : A bar chart was also added to the report design area representing the top sales.

![Sum value by number of cases and country](https://github.com/user-attachments/assets/d4e326db-b671-4dfa-a0f3-4b4787b571d9)


- Step 12 : A bar chart was also added to the report design area representing the case fatality rate per country.

![Sum value by case fatality per country](https://github.com/user-attachments/assets/53b2f1fc-4764-4076-bd4e-f473f60cedc5)
 

# Snapshot of Dashboard (Power BI Service)

![Ebola outbreak and monitoring dashboard](https://github.com/user-attachments/assets/ce1ee0b5-6d4d-469e-93d9-54b58639afd1)
 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following recommendations can be drawn from the dashboard;


1. The "Sum of value by Month" chart indicates a consistent decline in Ebola cases and deaths over time. This decline  may suggest that interventions, such as treatment, containment measures, and public health campaigns may have been effective.

2. The donut chart shows that the majority of cases (37.89%) are confirmed, probable, and suspected cases, followed by confirmed Ebola deaths (21.38%). This may highlight the need for rapid testing and confirmation to differentiate between real and suspected cases.

3. The bar chart for geographical hotspots ("Sum of value by Indicator and Country") shows that Liberia and Sierra Leone reported the highest number of confirmed, probable, and suspected cases and Liberia has the most confirmed Ebola deaths, while Sierra Leone also has a significant share. However, Nigeria and Senegal show comparatively lower case numbers.

4. The Case Fatality Rate (CFR) chart shows High CFR for confirmed Ebola cases across all countries, with Guinea showing particularly elevated rates. CFR for probable and suspected cases is lower, possibly due to misclassification or delays in diagnosis.  The high CFR for confirmed cases indicates the lethality of Ebola when properly diagnosed, emphasizing the need for early detection and treatment.

5. In the "Sum of value by Indicator and Country" horizontal bar chart:Liberia and Sierra Leone dominate in terms of reported cases and deaths. Whereas, Guinea shows high case fatality rates, suggesting limited healthcare capacity or delayed interventions.
Guinea might face challenges in healthcare delivery compared to Liberia and Sierra Leone.

# Recommendations

1. Deploy resources (e.g., medical supplies, healthcare workers) heavily to Guinea, Liberia and Sierra Leone.
2. Continued containment efforts in countries with fewer cases to prevent escalation.
3. Increase awareness about early symptoms to encourage prompt medical intervention.
4. Improve healthcare infrastructure to manage confirmed cases more effectively.


