# 🏥 Healthcare Analytics Dashboard

This project demonstrates a complete **end-to-end data pipeline** for healthcare analytics with interactive dashboards.

## 🔗 Tech Stack
- **PostgreSQL** → Source database  
- **Apache NiFi** → Data ingestion, ETL, and automation  
- **ClickHouse** → High-performance analytical database  
- **Power BI / Tableau** → Visualization and reporting  

## 📊 Features
- Patient demographics overview  
- Visit & workload trends  
- Department-wise analytics  
- Automated ETL pipeline with near real-time data updates  

## 🚀 Data Flow
`PostgreSQL → Apache NiFi → ClickHouse → Power BI / Tableau`

## 📂 Project Structure
```
healthcare-analytics-dashboard/
│
├── data/                     # Sample datasets (anonymized / dummy data)
├── nifi_flows/               # Apache NiFi flow templates
├── sql/                      # SQL scripts (schema + queries)
├── powerbi/                  # Power BI reports (.pbix file)
├── screenshots/              # Dashboard & pipeline screenshots
├── docs/                     # Documentation & architecture diagram
├── requirements.txt          # Python dependencies
└── README.md                 # Project description
```

## ⚡ Setup Instructions
1. Clone the repository  
   ```bash
   git clone https://github.com/Rushikesh2010/healthcare-analytics-dashboard.git
   cd healthcare-analytics-dashboard
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Setup PostgreSQL & ClickHouse databases using provided SQL scripts in `/sql/`.  

4. Import Apache NiFi flow templates (`/nifi_flows/`).  

5. Open the Power BI / Tableau report in `/powerbi/` and connect to ClickHouse.

## 🔥 Highlights
- Automated data transfer and cleaning using **Apache NiFi**  
- Optimized analytics storage with **ClickHouse**  
- Interactive dashboards built in **Power BI / Tableau**  

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


