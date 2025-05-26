# Smart Grid Renewable Optimizer

A real-world data engineering pipeline for optimizing renewable energy integration into smart grids. The system simulates solar, wind, and traditional energy sources, ingests them via Kafka, processes and optimizes the energy mix using TypeScript, and visualizes results via Streamlit.

## 💡 Key Features
- Real-time ingestion of energy data
- Renewable-traditional balancing logic
- Battery/storage optimization
- Postgres/TimescaleDB for storage
- Airflow for orchestration
- Streamlit dashboards

## 🧰 Tech Stack
- TypeScript
- Apache Kafka
- PostgreSQL / TimescaleDB
- Apache Airflow
- Streamlit
- Docker / Terraform

## 🚀 Getting Started
```bash
git clone https://github.com/stevehoober254/smartgrid-renewable-optimizer.git
cd smartgrid-renewable-optimizer
cp .env.example .env
docker-compose up --build
```
📊 Demo
Coming soon...

📁 Folder Overview
```
smartgrid-renewable-optimizer/
├── README.md
├── data/
│   ├── simulated_sources/
│   │   ├── solar.csv
│   │   ├── wind.csv
│   │   └── grid_demand.csv
├── ingestion/
│   └── kafka_producers.ts         # Simulate data streams
├── processing/
│   └── optimizer.ts               # Core optimization logic (TypeScript)
├── storage/
│   └── schema.sql                 # Postgres or Timescale schema
├── orchestration/
│   └── airflow_dags/
│       └── daily_optimizer_dag.py
├── infrastructure/
│   ├── docker-compose.yaml        # For local dev (Kafka, DB, Airflow)
│   └── terraform/                 # Cloud deployment configs
├── dashboard/
│   └── streamlit_app.py           # Visualization frontend
├── notebooks/
│   └── analysis.ipynb             # Exploratory data analysis, models
├── scripts/
│   └── generate_fake_data.ts
├── .env.example
└── package.json

```

📃 License

[MIT](LICENSE)

---
