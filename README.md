> [!tip] Free Business Datasets: All Companies in Amsterdam, Berlin, New York, Los Angeles, Rome, Paris, Madrid and London
> [Download the complete Business Datasets at CompanyData.com](https://companydata.com/free-business-datasets/)!

## Open Firmographic Dataset of Business Companies with Addresses, Revenues, and SIC Codes of Cities worldwide

An open dataset of companies with detailed firmographic information, including addresses, registration numbers, SIC industry codes, revenues, employee counts, and headquarter linkages.  
This dataset is designed for researchers, developers, data analysts, and businesses who want to explore company-level economic activity and build data-driven applications.

---

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

Here is an example record from the Amsterdam business dataset:

1. **Luxottica The Netherlands B.V.**  
   - Registration: 33281895  
   - Revenue (USD): $87M  
   - Employees: 377  
   - Industry: Professional Equipment and Supplies (SIC 5049)  


## 🌍 Use Cases
- Economic research and market analysis  
- Business intelligence dashboards  
- Startup ecosystem mapping  
- Open data applications and hackathons  

---

## 🎓 Suggested Research Exercises

1. **Industry Distribution Analysis**  
   Count companies per SIC code or Business Category.  
   *Goal:* Identify the most common industries.  

2. **Revenue Insights**  
   Calculate total and average revenue per industry.  
   *Goal:* Discover top-earning sectors.  

3. **Company Size Profiling**  
   Categorize companies by employee size.  
   *Goal:* Understand the structure of the local economy.  

4. **Headquarter Network Mapping**  
   Link subsidiaries to their global HQ.  
   *Goal:* Visualize multinational presence.  

5. **Historical Trends**  
   Analyze founding years per decade.  
   *Goal:* Spot business creation patterns.  

---

## 🔌 Get the full, live data through the API

Each dataset here is a 1,000-company sample. The [Company Data API](https://companydata.com/company-data-api/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=root) returns every registered company in these cities, and in 190+ countries, with the same fields, refreshed every month from 1,200+ official business registers.

```bash
curl -G "https://app.companydata.com/api/company/search" \
  -H "x-api-key: YOUR_API_KEY" \
  --data-urlencode "countryCode=NL" \
  --data-urlencode "cityName=AMSTERDAM" \
  --data-urlencode "pageSize=25"
```

| City | `countryCode` | `cityName` | Sample |
|---|---|---|---|
| Amsterdam | `NL` | `AMSTERDAM` | [README](datasets/amsterdam/README.md) |
| Berlin | `DE` | `BERLIN` | [README](datasets/berlin/README.md) |
| London | `GB` | `LONDON` | [README](datasets/london/README.md) |
| Los Angeles | `US` | `LOS ANGELES` | [README](datasets/los-angeles/README.md) |
| Madrid | `ES` | `MADRID` | [README](datasets/madrid/README.md) |
| New York City | `US` | `NEW YORK` | [README](datasets/new-york-city/README.md) |
| Paris | `FR` | `PARIS` | [README](datasets/paris/README.md) |
| Rome | `IT` | `ROMA` | [README](datasets/rome/README.md) |

Search returns a preview of each record with contact details masked. `/api/company/export` returns the full record, including the contact details, for 1 credit per company.

- Start with a 7-day free trial (500 searches and 10 exports). Plans from $34 a month: [get an API key](https://app.companydata.com/signup-api?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=root).
- [Quickstart](https://companydata.com/api-docs/quickstart/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=root): your first call in five minutes, with cURL, Python and JavaScript examples.
- [Data dictionary](https://companydata.com/data-dictionary/?utm_source=github&utm_medium=readme&utm_campaign=public-datasets&utm_content=root): every field and code explained.
- [OpenAPI spec](https://companydata.com/openapi.json), [TypeScript SDK](https://github.com/companydatacom/companydata-sdk) and [MCP server](https://github.com/companydatacom/companydata-mcp-server) for Claude, Cursor and ChatGPT.

---

## About CompanyData.com

CompanyData.com provides trusted data to leading organizations like Uber, Booking, and Statista. We’re now opening up free datasets for the community, offering information on millions of companies worldwide, including email, phone, corporate ownership structures, employees and revenue.

Our database covers more than 375 million companies across the globe.
Learn more at [CompanyData.com](https://companydata.com/company-database/)

---

## ❓ Questions & Contact
For questions, collaborations, or feedback, please reach out:  
📧 **info@companydata.com**

---

## 📥 Source & Licensing

- **Source:** Collected and curated by Companydata.com (internal data aggregation).  
- **License:** [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  
  - You are free to share and adapt the dataset all without asking permission.

---

## 🔑 Keywords
`open dataset companies`, `firmographic data`, `business registry`, `company revenue dataset`, `SIC code dataset`, `company addresses`, `public business data`, `open company database`
