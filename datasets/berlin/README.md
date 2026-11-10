---
datapackage:
  title: Top 1000 Business Dataset in Berlin Sample
  description: >
    Open firmographic dataset of 1,000 companies in Berlin, including addresses, 
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
      title: Berlin Business Dataset
      description: >
        CSV dataset of 1,000 companies in Berlin with addresses, 
        registration numbers, SIC codes, revenues, and employee data.
      lastModified: 2025-09-17
      format: csv
      path: berlin-business-dataset-sample.csv
---

> [!tip] Free Business Dataset: All Companies in Berlin
> [Download the complete Berlin Business Dataset with 304,890 Companies here](https://companydata.com/free-business-datasets/)!

## Open Firmographic Dataset of 1,000 Companies with Addresses, Revenues, and SIC Codes in berlin

An open dataset of 1,000 companies with detailed firmographic information, including addresses, registration numbers, SIC industry codes, revenues, employee counts, and headquarter linkages.  
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

1. **Europump GMBH**  
   - Registration: 42103B14525  
   - Revenue (USD): $826K  
   - Employees: 117  
   - Industry: Pumps and Pumping Equipment (SIC 3561)  

2. **Lb Holding GMBH**  
   - Registration: 10623B160946B  
   - Revenue (USD): $19.6M  
   - Employees: 110  
   - Industry: Offices of Holding Companies (SIC 6719)  

3. **Hgz Karosserie- Und Fahrzeugbaumeisterbetrieb GMBH**  
   - Registration: 10623B72134B  
   - Revenue (USD): $19.3M  
   - Employees: 100  
   - Industry: Motor Vehicles and Passenger Car Bodies (SIC 3711)  

4. **Psd Bank Berlin-Brandenburg EG**  
   - Registration: 10623G560B  
   - Revenue (USD): $43.3M  
   - Employees: 192  
   - Industry: Commercial Banks, Not Elsewhere Classified (SIC 6029)  


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

## 🔌 Get every company in Berlin through the API

This sample holds 1,000 companies. The [Company Data API](https://companydata.com/company-data-api/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=berlin) returns every registered company in Berlin with the same fields, refreshed every month from the official business registers.

```bash
curl -G "https://app.companydata.com/api/company/search" \
  -H "x-api-key: YOUR_API_KEY" \
  --data-urlencode "countryCode=DE" \
  --data-urlencode "cityName=BERLIN" \
  --data-urlencode "pageSize=25"
```

Search returns a preview of each record with contact details masked. `/api/company/export` returns the full record, including the contact details, for 1 credit per company.

- Start with a 7-day free trial (500 searches and 10 exports). Plans from $34 a month: [get an API key](https://app.companydata.com/signup-api?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=berlin).
- [Quickstart](https://companydata.com/api-docs/quickstart/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=berlin): your first call in five minutes, with cURL, Python and JavaScript examples.
- [Data dictionary](https://companydata.com/data-dictionary/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=berlin): every field and code explained.
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
`open dataset companies`, `firmographic data`, `business registry`, `company revenue dataset`, `SIC code dataset`, `company addresses`, `public business data`, `open company database`, `berlin`

---

