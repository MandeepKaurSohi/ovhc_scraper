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


## Tools & Technologies
- **Python**
- **BeautifulSoup** (web scraping)
- **Pandas** (data manipulation)
- **Matplotlib** & **Seaborn** (visualization)
- **Jupyter Notebook**


## Key Visual Outputs
## 1. Average monthly Premium by Company

![comapnies offer best value](https://github.com/MandeepKaurSohi/ovhc_scraper/blob/main/output/company_offers_best_value.png)

## 2. Comapnies Offering Coverage for Children

![Companies cover children](https://github.com/MandeepKaurSohi/ovhc_scraper/blob/main/output/companies_covers_children.png)

## 3. Monthly Premium Distribution for Policies Covering Children Under 12

![monthly distribution cover children <12](https://github.com/MandeepKaurSohi/ovhc_scraper/blob/main/output/monthly_distribution_covers_children.png)

## 4. Visa Types with Children Under 12

![visa types children under 12](https://github.com/MandeepKaurSohi/ovhc_scraper/blob/main/output/visa_type_children_coverage.png)

## 5. Grouped ED Payment Methods for Children under 12 Coverage

![ED payment methods](https://github.com/MandeepKaurSohi/ovhc_scraper/blob/main/output/ed_payment_grouped.png)


## Insights

- **Majority of insurers** offer coverage for children under **family or couple** plans.
- ED payment methods vary:
  - Some offer **direct billing** with listed providers
  - Others require **reimbursement claims**
- **Bupa, Medibank, GMHBA, AHM** all include coverage for children under 12 in specific plans.
- **Premiums** range from ~$80 to $140/month depending on plan level and inclusions.


## Limitations

- Coverage for **undocumented or visa-less families** is **not available** via OVHC.
- Such families may rely on **community clinics, NGOs, or emergency public hospital access** on compassionate grounds.
- Due to the lack of formal coverage, **no public datasets** exist for undocumented children's health access.
