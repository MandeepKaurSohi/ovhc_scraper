# Overseas Visitor Health Cover (OVHC) Analysis in Australia
## Project Objective
This project focuses on analyzing Private Health Insurance providers in Australia that offer Overseas Visitor Health Cover (OVHC) — particularly with insights into:

 1.Emergency Department (ED) payment methods

 2.Visa type coverage

 3.Children under 12 years policy coverage

 4.Monthly premium pricing patterns


## Dataset Sources
Data was collected from official health insurance websites of 10 major Australian providers using Python web scraping (BeautifulSoup). The results were cleaned and exported into:

    combined_ovhc_insurance.csv (Full data)

    children_under_12_ovhc.csv (Filtered data for children under 12 coverage)


## Key Features Collected
Column    Description
Company    Insurance provider name
Visa Types    Visa categories covered (e.g., 600, 485, 482)
ED Payment Method    Whether ED costs are billed directly or reimbursed
Children <12 Covered    Indicates if policies include children under 12
Coverage Details    General coverage description
Monthly Premium (AUD)    Stated monthly price 


