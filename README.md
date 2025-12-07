# Airflow-s-cicd
This project is an end-to-end data engineering pipeline built on GCP using Airflow for orchestration, Dataproc Serverless for Spark processing, and BigQuery for analytics. Raw flight data is stored in GCS, transformed using PySpark, and loaded into BigQuery for date-wise flight performance analysis.

We follow a simple branching strategy with dev (development/testing) and main (production). Once changes are validated, they are merged into the main branch via CI/CD using GitHub Actions.

Tech Stack: Airflow • PySpark • Dataproc Serverless • BigQuery • GCS • GitHub Actions
Key Features: Automated scheduling, serverless compute, clean transformations, fast analytics.

This pipeline helps automate flight data processing and provides reliable, scalable insights for reporting and dashboards.
<img width="420" height="250" alt="image" src="https://github.com/user-attachments/assets/e6b62338-0570-4564-a5d8-de3a0b26bb3c" />
<img width="940" height="279" alt="image" src="https://github.com/user-attachments/assets/828cb8ae-5022-4a06-af3c-0389576de212" />
<img width="815" height="398" alt="image" src="https://github.com/user-attachments/assets/ed38f69e-59c1-458f-b809-ae402907cb1d" />
<img width="708" height="365" alt="image" src="https://github.com/user-attachments/assets/5c185b5a-1107-4544-ba4e-34954bd1501b" />
<img width="703" height="213" alt="image" src="https://github.com/user-attachments/assets/8d7d9fc7-2d20-4127-adfd-f2f1116dc8f7" />
<img width="753" height="554" alt="image" src="https://github.com/user-attachments/assets/8b7664f0-d511-4402-aa81-88564e0d470e" />
<img width="709" height="490" alt="image" src="https://github.com/user-attachments/assets/9eaf2131-efac-4a91-928b-236f4432840d" />
<img width="701" height="206" alt="image" src="https://github.com/user-attachments/assets/0d3b63a3-62f2-459e-9dd2-084c3fd6dade" />
<img width="815" height="353" alt="image" src="https://github.com/user-attachments/assets/6c7a1e89-983a-4e27-ab05-1c284ac92cdc" />
<img width="709" height="173" alt="image" src="https://github.com/user-attachments/assets/86eae5b4-ef30-4e38-a84d-8c6bcb1e5732" />







