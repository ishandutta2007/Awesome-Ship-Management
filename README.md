# Awesome-Ship-Management

## Top Ship Management Ecosystem

**Curated List of SaaS Products & Open-Source / Source-Available GitHub Projects**  
*Focused on Fleet Technical Management, Planned Maintenance Systems (PMS), Procurement, Crewing, QHSE, Compliance & Vessel Operations*  
**Last updated: September 2026**

This repository tracks notable **SaaS/commercial platforms** and **open-source or source-available projects** for **Ship Management**. These systems help ship owners, technical managers, and operators handle planned maintenance, spare parts, procurement, crewing, safety/quality (QHSE), compliance, and shore-vessel coordination across fleets.

**Examples** include DNV ShipManager, SpecTec AMOS, ShipNet, MESPAS, Helm CONNECT, MARAD, MarineManager, NAVTOR ShipManager, OrbitMI, and ABS NS5 / Nautical Systems (the category leaders).

**Open-source emphasis**: Full-featured, production-ready open-source ship management / PMS platforms comparable to commercial maritime ERP systems are limited. The most relevant dedicated option is **SeaVesselManager** (source-available under Business Source License). Supporting open-source tools exist for tracking, vessel systems, simulation, and general fleet maintenance. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DNV ShipManager](https://www.dnv.com/)**  
  Comprehensive maritime fleet management suite covering technical management, planned maintenance, procurement, crewing, QHSE, hull integrity, and compliance, with strong class-society alignment.

- **[SpecTec AMOS](https://www.spectec.net/)**  
  Long-established ship management and planned maintenance system known for robust maintenance, purchasing, inventory, safety, and vessel operations support, including strong offline/replication capabilities.

- **[ShipNet](https://www.shipnet.no/)**  
  Integrated maritime software platform spanning technical, commercial, accounting, voyage, and fleet management functions.

- **[MESPAS](https://www.mespas.com/)**  
  Cloud-oriented ship management solution focused on maintenance, procurement, and operational workflows for vessel operators.

- **[Helm CONNECT](https://www.helmoperations.com/)**  
  Modern platform popular with coastal, harbor, and smaller fleet operators for intuitive operations, maintenance, and compliance management.

- **[ABS Nautical Systems / NS5](https://ww2.eagle.org/)**  
  ABS offering for fleet technical management, maintenance, compliance, and related vessel operations modules.

- **[NAVTOR ShipManager, OrbitMI, MarineManager](https://www.navtor.com/)**  
  Additional solutions covering voyage optimization, performance monitoring, fleet oversight, and operational decision support.

- **[Other maritime fleet platforms](https://www.dnv.com/)**  
  Systems such as SERTICA, BASSnet, MariApps smartPAL, Veson Nautical (more commercial-focused), and regional PMS/ERP suites used by technical managers worldwide.

## Open-Source / Source-Available Projects

- **[SeaVesselManager](https://seavesselmanager.com/)**  
  Source-available (Business Source License) modern Planned Maintenance System and ship management platform designed specifically for maritime fleets. Includes fleet overview, planned maintenance, spare parts inventory, work orders, and offline-first capabilities. Free Community Edition available for self-hosting.

- **[Hackerfleet / HFOS](https://github.com/Hackerfleet/hfos)**  
  Open-source modular vessel board computer and maritime system focused on geo-information, equipment, logbooks, navigation data, and collaborative onboard tools.

- **[Traccar](https://github.com/traccar/traccar)**  
  Popular open-source GPS tracking platform supporting a wide range of devices and protocols. Frequently adapted for vessel and fleet position monitoring.

- **[LOTUSim](https://github.com/naval-group/LOTUSim)**  
  Open-source real-time multi-domain maritime simulator (Gazebo/ROS-based) useful for training, research, and testing maritime operational scenarios.

- **[Vessel / fleet maintenance prototypes](https://github.com/search?q=ship+management+OR+vessel+PMS+OR+%22planned+maintenance%22+maritime)**  
  Community and academic projects exploring vessel information systems, maintenance scheduling, or basic fleet tracking (often educational or early-stage).

- **[General open-source fleet tools](https://github.com/search?q=fleet+maintenance+OR+fleet+management+open+source)**  
  Land-oriented or generic fleet maintenance systems (e.g., vehicle-focused) that can sometimes be adapted for simpler maritime use cases.

### Additional Strong Open-Source Options

- **AIS & vessel tracking libraries**: Tools for processing Automatic Identification System data and integrating vessel positions.
- **Maritime data & NMEA stacks**: Open-source components for handling navigation, sensor, and communication data onboard.
- **Simulation & optimization tools**: Research platforms for maintenance scheduling, route optimization, or port/vessel operations modeling.
- **ERP building blocks**: Broader open-source ERP systems (Odoo, ERPNext modules) occasionally customized for smaller operators’ technical or inventory needs.
- **Document & compliance helpers**: Tools supporting ISM, certificate tracking, or audit trail generation.
- AI/ML prototypes for classifying maintenance records or anomaly detection that can complement a core PMS.

**Frameworks for building custom systems**:  
Commercial platforms dominate regulated ship management because of deep domain features, class approvals, offline resilience, multi-vessel synchronization, and long-term support.  
For operators seeking lower-cost or more controllable options, **SeaVesselManager** currently offers the closest dedicated source-available PMS/ship management experience.  
Combine it (or a custom stack) with **Traccar** for tracking, open GIS tools, and modular workflow engines.  
True drop-in open-source replacements for enterprise systems like DNV ShipManager or SpecTec AMOS remain rare; most open projects serve niches, research, or smaller fleets.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source/source-available.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Ship management and planned maintenance systems are safety- and compliance-critical. They support ISM Code, class surveys, Port State Control, and operational reliability. Any system used on commercial vessels must meet applicable regulatory, audit, and classification requirements.
- Source-available and open-source tools can reduce licensing costs and increase transparency but require careful evaluation of licensing terms (e.g., Business Source License restrictions), implementation quality, offline behavior, and ongoing maintenance. They are not automatically equivalent to class-approved commercial platforms.

---

**Made for technical superintendents, fleet managers, ship operators, and maritime technologists.**  
Let's encourage more accessible, transparent, and community-driven tools in ship management and planned maintenance where feasible.
