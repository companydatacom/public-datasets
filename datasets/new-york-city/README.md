---
datapackage:
  title: Top 1000 Business Dataset in New York City Sample
  description: >
    Open firmographic dataset of 1,000 companies in New York City, including addresses, 
    registration numbers, revenues, SIC industry codes, employee counts, and headquarter linkages. 
    Published by CompanyData.com for free public usage and research.
  created: 2025-09-17
  updated: 2025-09-17
  licenses:
    - path: https://creativecommons.org/publicdomain/zero/1.0/deed.en
      title: Creative Commons Zero v1.0 Universal
  sources:
    - path: https://companydata.com/
      title: CompanyData.com
  resources:
    - name: sample-dataset
      title: Sample New York City Business Dataset
      description: >
        CSV dataset of 1,000 companies in New York City with addresses, 
        registration numbers, SIC codes, revenues, and employee data.
      lastModified: 2025-09-17
      format: csv
      path: new-york-city-business-dataset-sample.csv
---

> [!tip] Free Business Dataset: All Companies in New York City
> [Download the complete New York City Business Dataset with 687,588 Companies here](https://companydata.com/free-business-datasets/)!

## Open Firmographic Dataset of 687,588 Companies with Addresses, Revenues, and SIC Codes in New York City

An open dataset of 687,588 companies with detailed firmographic information, including addresses, registration numbers, SIC industry codes, revenues, employee counts, and headquarter linkages.  
This dataset is designed for researchers, developers, data analysts, and businesses who want to explore company-level economic activity and build data-driven applications.


## 📊 Dataset Contents

Each record contains multiple fields describing company details. Example fields include:

- Company name & trade name  
- Address (street, postal code, city, country)  
- Company registration number  
- Business category codes & descriptions (SIC codes)  
- Yearly revenue (local currency & USD)  
- Employee counts (on site & total)  
- Headquarter linkages (local, national, global)  
- Founding year  
- Import/Export codes  

---

## 🔎 Practical Examples

Here are some example records from the dataset:

1. **G.H. Bass & CO.** 
   - Registration: 0857450  
   - Revenue (USD): $262,375,205  
   - Employees: 4,100  
   - Industry: Men's Footwear, Except Athletic (3143)  

2. **Warnaco INC.** 
   - Registration: 0731101  
   - Revenue (USD): $30,406,605  
   - Employees: 4,656  
   - Industry: Women's, Misses', Children's, and Infants' Underwear and Nightwear (2341)  

3. **Waterbury Garment, LLC** 
   - Registration: N/A  
   - Revenue (USD): $4,048,223  
   - Employees: 316  
   - Industry: Women's, Misses', Children's, and Infants' Underwear and Nightwear (2341)  

4. **Swank, INC.** 
   - Registration: 0349202  
   - Revenue (USD): $2,524,697  
   - Employees: 256  
   - Industry: Apparel and Accessories, Not Elsewhere Classified (2389)

---

## 🌍 Use Cases
- Economic research and market analysis  
- Business intelligence dashboards  
- Startup ecosystem mapping  
- Open data applications and hackathons  

---

## 🎓 Suggested Research Exercises

Here are some example exercises to practice with this dataset:

1. **Industry Distribution Analysis**  
   Count how many companies exist per SIC code or Business Category.  
   *Goal:* Identify the most common industries and visualize the distribution with a bar chart or treemap.

2. **Revenue Insights**  
   Calculate the total revenue per industry and the average revenue per company.  
   *Goal:* Discover which sectors generate the highest revenues. Extend by comparing subsidiaries vs. independent companies.

3. **Company Size Profiling**  
   Categorize companies into Small, Medium, and Large based on employee count.  
   *Goal:* Understand the structure of the local economy. Cross-analyze with revenue to explore patterns.

4. **Headquarter Network Mapping**  
   Identify companies that are subsidiaries of global groups and map them to their global headquarters.  
   *Goal:* Visualize multinational presence and build a network graph of corporate linkages.

5. **Historical Trends**  
   Analyze founding years to see how many companies were established per decade.  
   *Goal:* Spot patterns in business creation over time and compare across industries.

---

## 🔌 Get every company in New York City through the API

This sample holds 1,000 companies. The [Company Data API](https://companydata.com/company-data-api/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=new-york-city) returns every registered company in New York City with the same fields, refreshed every month from the official business registers.

```bash
curl -G "https://app.companydata.com/api/company/search" \
  -H "x-api-key: YOUR_API_KEY" \
  --data-urlencode "countryCode=US" \
  --data-urlencode "cityName=NEW YORK" \
  --data-urlencode "pageSize=25"
```

Search returns a preview of each record with contact details masked. `/api/company/export` returns the full record, including the contact details, for 1 credit per company.

- Start with a 7-day free trial (500 searches and 10 exports). Plans from $34 a month: [get an API key](https://app.companydata.com/signup-api?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=new-york-city).
- [Quickstart](https://companydata.com/api-docs/quickstart/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=new-york-city): your first call in five minutes, with cURL, Python and JavaScript examples.
- [Data dictionary](https://companydata.com/data-dictionary/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=new-york-city): every field and code explained.
- [OpenAPI spec](https://companydata.com/openapi.json), [TypeScript SDK](https://github.com/companydatacom/companydata-sdk) and [MCP server](https://github.com/companydatacom/companydata-mcp-server) for Claude, Cursor and ChatGPT.

---

## About CompanyData.com

CompanyData.com provides trusted data to leading organizations like Uber, Booking, and Statista. We’re now opening up free datasets for the community, offering information on millions of companies worldwide, including email, phone, corporate ownership structures, employees and revenue.

Our database covers more than 375 million companies across the globe.
Learn more at [CompanyData.com](https://companydata.com/company-database/)

---

## ❓ Questions & Contact
For questions, collaborations, or feedback, please reach out via email:  
📧 **info@companydata.com**

---

## 📥 Source & Licensing

- **Source:** Collected and curated by Companydata.com (internal data aggregation).  
- **License:** [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  
  - You are free to share and adapt the dataset all without asking permission.

---

## 🔑 Keywords
`open dataset companies`, `firmographic data`, `business registry`, `company revenue dataset`, `SIC code dataset`, `company addresses`, `public business data`, `open company database`, `new-york-city`

---

