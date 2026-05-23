## Izan Arnaiz Gallego
### Cloud & Platform Support Engineer
Eligible for Skilled Worker Visa (New Entrant route) | Open to immediate relocation to the UK

---

### Professional Summary
Cloud & Platform Support professional with 2 years of enterprise experience in infrastructure monitoring, incident management, and SLA-driven operations. Focused on maintaining system availability, optimizing CI/CD pipeline workflows, and resolving complex technical incidents in multi-cloud environments.

---

### Technical Skills
- **Cloud Platforms:** AWS, Azure
- **Observability & Monitoring:** Grafana, OpenSearch, Prometheus
- **Systems & Access Management:** Linux, Windows, Crowd, Citrix
- **CI/CD & Version Control:** Jenkins, GitHub, Bitbucket, Artifactory, Harbor, SonarQube
- **Ticketing & Collaboration:** Jira, ServiceNow, Confluence

---

### Featured Project: Local Infrastructure Monitoring Stack

Deployed a local monitoring environment using Docker containers to scrape and visualize system metrics.

* **The Architecture:** Deployed Prometheus and Grafana as isolated multi-container services using Docker Compose, interconnected via a shared Docker network.
* **Metric Aggregation:** Configured Prometheus to scrape local core infrastructure metrics.
* **Visualization:** Interconnected Grafana with the Prometheus data source and imported a pre-built community dashboard template to visualize system performance metrics in real time.
* **Repository Architecture:** Includes `docker-compose.yml` for multi-container deployment, a dedicated `config/` directory containing the `prometheus.yml` scrape configurations, and a comprehensive `README.md`.

📂 enterprise-monitoring-lab

├── 📄 docker-compose.yml

├── 📂 config/

│   └── 📄 prometheus.yml

└── 📄 README.md
