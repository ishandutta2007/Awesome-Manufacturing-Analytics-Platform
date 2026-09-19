# Awesome-Manufacturing-Analytics-Platform

## Top Manufacturing Analytics Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on OEE, Machine Data, Predictive Maintenance, Production Intelligence, Shop-Floor Analytics & Industrial AI*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Manufacturing Analytics**. These systems connect to machines and production systems, calculate OEE and other KPIs, detect anomalies, enable predictive maintenance, and deliver real-time and historical insights for continuous improvement.



**Examples** include Sight Machine, MachineMetrics, Tulip, Seeq, Augury, FactoryFour, Drishti, TrendMiner, Falkonry, and C3 AI Manufacturing (the category leaders).



**Open-source emphasis**: Full industrial analytics platforms are mostly commercial, but strong open building blocks exist. **Libre** (Grafana + Influx), **OpenMES**, Node-RED, Prometheus/Grafana industrial stacks, and related IIoT projects allow teams to build capable OEE and machine-data solutions. This section lists the strongest available open resources.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Sight Machine](https://sightmachine.com/)**  

  Manufacturing intelligence platform that creates a digital twin of production processes for quality, throughput, and loss analysis across plants.



- **[MachineMetrics](https://www.machinemetrics.com/)**  

  Industrial IoT and analytics platform focused on CNC and discrete manufacturing, delivering real-time machine monitoring, OEE, and operator insights.



- **[Tulip](https://tulip.co/)**  

  Frontline operations platform with no-code apps, machine monitoring, and analytics that connect people, machines, and processes on the shop floor.



- **[Seeq](https://www.seeq.com/)**  

  Advanced analytics platform specialized in time-series process data for process manufacturing engineers and data scientists.



- **[Augury](https://www.augury.com/)**  

  Machine health and predictive maintenance platform using vibration, ultrasound, and AI to diagnose and prescribe actions for industrial equipment.



- **[FactoryFour](https://www.factoryfour.com/)**  

  Manufacturing operations and analytics platform helping teams track production, capacity, and performance in real time.



- **[Drishti](https://www.drishti.com/)**  

  Video-based AI platform for assembly-line analytics, station-level insights, and continuous improvement in discrete manufacturing.



- **[TrendMiner](https://www.trendminer.com/)**  

  Self-service industrial analytics platform for process manufacturing, enabling search, diagnostics, and monitoring on time-series data.



- **[Falkonry](https://falkonry.com/)**  

  Operational AI platform that learns normal and abnormal patterns from machine and process data for predictive insights.



- **[C3 AI Manufacturing](https://c3.ai/)**  

  Enterprise AI application suite applied to manufacturing use cases including predictive maintenance, quality, and yield optimization.



## Open-Source GitHub Projects

- **[Libre (Spruik)](https://github.com/Spruik/Libre)**  

  Open-source manufacturing execution and performance monitoring system built on Grafana, InfluxDB, and Postgres—focused on OEE and production analytics.



- **[OpenMES](https://getopenmes.com/)**  

  Free, open-source Manufacturing Execution System with real-time OEE, downtime analysis, production monitoring, and shop-floor integration capabilities.



- **[Node-RED](https://github.com/node-red/node-red)**  

  Flow-based open-source programming tool widely used in industrial IoT for collecting, transforming, and routing machine data into analytics pipelines.



- **[Prometheus + Grafana industrial stacks](https://github.com/prometheus/prometheus)**  

  Open metrics collection and visualization stack frequently adapted for machine telemetry, OEE calculation, and plant dashboards.



- **[InfluxDB + Telegraf industrial collectors](https://github.com/influxdata)**  

  Open time-series database and collectors commonly used as the backbone of manufacturing analytics and historian-style workloads.



- **[OPC UA open stacks and clients](https://github.com/)**  

  Open implementations of OPC UA for securely connecting to PLCs and industrial equipment to feed analytics platforms.



- **[OEE calculation open libraries and samples](https://github.com/)**  

  Reference implementations and IoT samples for computing Availability, Performance, and Quality components of OEE.



- **[Apache StreamPipes / industrial stream processing](https://github.com/apache/streampipes)**  

  Open-source self-service industrial IoT toolbox for analyzing industrial data streams without heavy coding.



- **[Frappe / ERPNext manufacturing analytics extensions](https://github.com/frappe/erpnext)**  

  Open ERP manufacturing modules that can be extended with custom analytics and reporting for production KPIs.



- **[Edge and MQTT open brokers for machine data](https://github.com/)**  

  Lightweight open brokers and edge agents used to collect and forward high-frequency machine data to analytics backends.



### Additional Strong Open-Source Options

- Building an OEE and machine-monitoring stack with **Libre** or **OpenMES** on top of Grafana/Influx.

- Using **Node-RED + MQTT + Prometheus/Grafana** for flexible, low-cost machine data pipelines.

- Combining open historians (Influx, Timescale) with open visualization for process and discrete analytics.

- Accepting that advanced AI diagnostics, video analytics, multi-plant digital twins, and turnkey industrial support still favor commercial platforms (Sight Machine, MachineMetrics, Augury, Seeq, Tulip, C3 AI, etc.).

- Focusing open-source efforts on data ownership, cost control, and avoiding lock-in to proprietary machine connectors.



**Frameworks for building custom systems**: Connect machines via OPC UA / MQTT / native protocols → store time-series in Influx or Prometheus → calculate OEE and KPIs → visualize in Grafana or Libre/OpenMES → layer anomaly detection with open ML tools. Suitable for plants with internal engineering capacity. Many manufacturers still adopt commercial analytics platforms for faster time-to-value and vendor-supported machine integrations.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Manufacturing analytics systems interact with production equipment and can influence operational decisions. Open-source or self-built solutions require proper OT/IT security, validation, and change control. This list is not operational or safety advice.



---

**Made for manufacturing engineers, plant managers, and industrial data teams seeking open analytics options.**

Let's keep production intelligence actionable, transparent, and as open as practical.
