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
ingestion/: Kafka producers for solar/wind/grid data

processing/: Business logic to optimize source usage

dashboard/: Visual insights from processed data
```

📃 License

[MIT](LICENSE)

---

### ✅ Step 4: Next Actions

1. **Create GitHub repo**: Name it `smartgrid-renewable-optimizer`
2. I can help you:
   - Write the initial `package.json` and `tsconfig.json`
   - Build the data simulation script (`generate_fake_data.ts`)
   - Scaffold a Kafka producer for solar/wind data
   - Draft the optimization algorithm

