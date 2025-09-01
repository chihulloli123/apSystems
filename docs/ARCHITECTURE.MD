# System Architecture

## Stack
- **Core Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Data Layer:** ETL pipelines for ingesting and transforming Spotify, Apple Health, and other sources
- **Visualization Layer:** Interactive dashboards (e.g., matplotlib, seaborn, or web-based frameworks)
- **AI/ML Layer:** Proof-of-signal systems (trend detection, anomaly detection, applied models)

## Flow
1. Data ingestion (Spotify API, Apple Health exports, CSV/JSON files)
2. Transformation + cleaning with Pandas
3. Analysis & anomaly detection (NumPy, custom models)
4. Visualization & dashboards
5. Optional deployment to apps or web interfaces
