# ❄️ Snowstorm Issues: Snow & Ice Preparedness Plan

> A cloud-based data engineering project integrating historical NOAA weather data with real-time Open-Meteo API streams to support city-level snow and ice preparedness planning.

## 📊 Overview

This project builds a full data pipeline on Google Cloud Platform to help city emergency management teams make proactive decisions during winter storms. It combines static historical climatology data with live streaming weather forecasts to detect risk patterns and support operational planning.

## 🛠️ Tools & Technologies

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

## 📁 Project Structure

```
snowstorm-preparedness/
│
├── Snowstorm_final.docx   # Full project documentation
└── README.md
```

## 🔍 Data Pipeline

| Stage | Tool | Description |
|-------|------|-------------|
| Ingestion | GCP Cloud Storage | NOAA historical data + Open-Meteo API streams |
| Processing | Hadoop / Dataproc | Hive and Spark for cleaning and transformation |
| Storage | BigQuery | Data quality checks and curated analytics tables |
| Analysis | Hive / Spark | Pattern detection and risk scoring |

## 📈 Key Outcomes

- Integrated static NOAA dataset with real-time Open-Meteo streaming data
- Built Hive tables and Spark jobs for scalable data processing
- Performed BigQuery data quality checks across weather variables
- Developed foundation for predictive road icing risk models

## 👥 Team

Group project — University of North Texas, ADTA 5240

## 📬 Contact

**Visalakshi Polepalli** — [LinkedIn](https://linkedin.com/in/visalakshi-polepalli17)
