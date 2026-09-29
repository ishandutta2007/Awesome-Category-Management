# Awesome-Category-Management

## Top Category Management Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Assortment Planning, Planogram Optimization, Space Management & Retail Analytics*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Category Management**. These tools help retailers, CPG brands, and merchandising teams optimize product assortments, design shelf layouts (planograms), allocate shelf space, and analyze category performance.



**Examples** include NielsenIQ Spaceman, Blue Yonder Category Management, DotActiv, Planogram Online, Quant Retail, RELEX, Leafio, Scorpion Planogram, JDA Category Management, and PlanoHero (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom optimization logic, and transparent retail data — ideal for merchandising teams that need full control over their category planning infrastructure without per-seat SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[NielsenIQ Spaceman](https://nielseniq.com/)**

  Leading space planning and category management platform. Provides planogram creation, shelf space optimization, and assortment analysis for retailers and CPG brands.



- **[Blue Yonder Category Management](https://blueyonder.com/)**

  Enterprise category management and space planning solution. Integrates with Blue Yonder's supply chain and retail planning suite.



- **[DotActiv](https://dotactiv.com/)**

  Category management software for retail. Provides planogram design, shelf space optimization, and category analytics for retailers, suppliers, and brokers.



- **[Planogram Online](https://planogramonline.com/)**

  Cloud-based planogram software. Provides visual merchandising tools for designing and managing shelf layouts.



- **[Quant Retail](https://quantretail.com/)**

  Space planning and category management platform. Focuses on planogram automation and shelf space optimization.



- **[RELEX](https://relexsolutions.com/)**

  Unified retail planning platform with category management, assortment planning, and space optimization capabilities integrated with supply chain planning.



- **[Leafio](https://leafio.ai/)**

  AI-powered category management and assortment planning platform. Provides demand forecasting and optimization for retail categories.



- **[Scorpion Planogram](https://scorpionplanogram.com/)**

  Planogram software for visual merchandising. Provides shelf layout design and management tools.



- **[JDA Category Management](https://blueyonder.com/)**

  JDA (now Blue Yonder) category management solution. Provides space planning, assortment optimization, and category analytics for retailers and suppliers.



- **[PlanoHero](https://planohero.com/)**

  Cloud-based planogram and category management platform. Provides collaborative shelf layout design and space optimization.



## Open-Source GitHub Projects



### Planogram & Space Planning



- **[GoJS Planogram](https://github.com/NorthwoodsSoftware/GoJS)**

  JavaScript diagramming library with **built-in planogram support** for arranging products on retail shelves or vending machines via drag-and-drop . Used as the foundation for interactive planogram builders. **Commercial license** with free trial.



- **[ShelfSpaceAllocation.jl](https://github.com/gamma-opt/ShelfSpaceAllocation.jl)**

  **Julia package for solving the retail shelf space allocation problem.** Uses **mixed-integer linear programming (MILP)** for mathematical optimization of product placement. **12 stars, 6 forks**. Academic/research-grade optimization tool . **Open source**.



- **[Cactus Foundation Space Planner](https://github-wiki-see.page/m/usersaynoso/cactus-foundation/wiki/Space-planner)**

  **Open-source space planner for retail furniture layout.** Features 2D/3D view, door and window placement, columns/pillars as occupancy blockers, furniture snapping, and collision warnings. Designed for furniture retail planning . **Open source**.



- **[openPlan3D](https://github.com/laanlabs/openPlan3D)**

  **Open-source 2D/3D floor plan editor** built with SvelteKit and Three.js. Supports wall/door/column drawing, furniture placement, and 2D/3D toggle. MIT License . Can be adapted for retail space planning.



### Assortment & Category Optimization



- **[RLASORTI (SKU Optimization System)](https://github.com/dmitriyrayder/RLASORTI)**

  **Reinforcement Learning-based SKU assortment optimization system.** Uses **Deep Q-Network (DQN)** to recommend which SKUs to keep, which to remove, and how to adjust stock depth. Features business metrics (GMV, Profit, ROI, Out-of-Stock cost), interactive dashboards (Plotly), and CSV export for recommendations. Built with Python and Streamlit . **Open source**.



- **[Choice-Learn](https://github.com/artefact-group/choice-learn)**

  **Python library for large-scale choice modeling and assortment planning.** Provides discrete choice models (Conditional Logit, neural networks) to predict customer purchase decisions and optimize assortments. Published in *Journal of Open Source Software* (2024). Features scalable data handling, TensorFlow-based estimation, and downstream assortment/pricing optimization tools . **Open source**.



- **[Crisp AI Blueprints](https://www.businesswire.com/news/home/20250108361065/en/)**

  **Suite of open-source, AI-ready templates for retail analytics.** Includes **Store Clustering** (group locations for targeted strategies), **Weather Analytics** (align inventory with weather patterns), **Anomaly Detection** (flag sales/inventory irregularities), and **On-Shelf Availability** (ensure consistent product availability). Built for Databricks and cloud platforms . **Free, open-source templates**.



### Product Information & Inventory Management



- **[AtroPIM](https://github.com/atrocore/atropim)**

  **Highly configurable, modular open-source Product Information Management (PIM) system.** Manages products, category trees, classifications, channels, and associated products. REST API for integration with any third-party system. **GNU GPLv3** . Ideal for centralizing product data that feeds category planning.



- **[StockIT](https://github.com/stere8/stockit)**

  **Free, open-source inventory management for small businesses.** Features product/category management, real-time stock tracking, CSV/Excel export, and responsive UI. Built with .NET 8, Entity Framework Core, and SQL Server . **Open source**.



### Additional Strong Open-Source Options



- **Planogram Design**: **GoJS** (JS library with planogram support), **openPlan3D** (2D/3D floor plan editor) .

- **Space Optimization**: **ShelfSpaceAllocation.jl** (MILP optimization), **Cactus Foundation** (retail furniture planner) .

- **Assortment Optimization**: **RLASORTI** (DQN-based SKU optimization), **Choice-Learn** (choice modeling) .

- **Retail Analytics**: **Crisp AI Blueprints** (store clustering, on-shelf availability) .

- **Product Data**: **AtroPIM** (PIM for category trees), **StockIT** (inventory management) .



**Frameworks for building custom systems**: Combine **AtroPIM** for product data management, **Choice-Learn** for assortment optimization modeling, **ShelfSpaceAllocation.jl** for MILP-based shelf allocation, and **Cactus Foundation** or **openPlan3D** for visual space planning. Add **PostgreSQL** for persistence and **Streamlit/Plotly** for dashboards.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Category management platforms handle sensitive retail and sales data; ensure compliance with internal policies and data protection regulations.

- **Open-source reality**: The open-source ecosystem for category management is **developing but fragmented**. **ShelfSpaceAllocation.jl** provides rigorous MILP-based shelf optimization but is academic-grade . **RLASORTI** offers ML-based SKU optimization but is a prototype . **Choice-Learn** provides a solid foundation for assortment modeling . **Crisp AI Blueprints** offers practical retail analytics templates . However, **commercial platforms** (NielsenIQ Spaceman, Blue Yonder, DotActiv) provide integrated planogram design, real-time collaboration, and enterprise support that open-source alternatives cannot match without significant assembly and customization.



---



**Made for category managers, space planners, merchandising analysts, and retail operations teams.**

Let's make category management more open, data-driven, and shelf-optimized.
