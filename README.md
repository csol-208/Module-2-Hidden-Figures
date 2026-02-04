# Module 2: Spatial Analysis & Environmental Justice

Use AI-driven coding to map the geography of the cloud and analyze its environmental and social impacts.

## Overview

In this module, we explore the physical footprint of the digital world. We will use spatial analysis tools to:
1.  **Map Data Centers**: Visualize the global and local distribution of cloud infrastructure.
2.  **Analyze Environmental Justice (EJ)**: Investigate the relationship between data center siting and social vulnerability.
3.  **Assess Biodiversity Impacts**: Overlay infrastructure maps with species richness data to understand ecological risks.

## Agent-Driven Learning

This module uses an **AI-first pedagogy**. Instead of reading pre-written code, you will learn to **lead the AI**.

### Workflow: Prompt, Generate, Verify

1.  **Open a Notebook**: Start with `01-mapping-data-centers.ipynb`.
2.  **Read the Action Items**: Each section contains a high-level goal and a suggested **Agent Prompt**.
3.  **Prompt Your Assistant**:
    *   Open the Chat (GitHub Copilot or Cursor).
    *   Paste the suggested prompt or write your own based on the requirements.
    *   *Tip: Be specific about library choices (e.g., "Use Ibis and DuckDB").*
4.  **Generate & Run**: Let the AI write the code. Run the cell.
5.  **Verify & Refine**: Does the output look right? If not, ask the AI to fix it (e.g., "The map is empty, check the coordinate projection").

## The Notebooks

*   **`01-mapping-data-centers.ipynb`**: Introduction to spatial data. Load lat/lon data, create geometries, and visualize points on a map using `anymap`.
*   **`02-ej-analysis.ipynb`**: Vector analysis. Perform spatial joins between data centers and Social Vulnerability Index (SVI) / Redlining data.
*   **`03-biodiversity-impacts.ipynb`**: Raster analysis. Work with extensive biodiversity GeoTIFFs to measure species richness at infrastructure sites.

## Prerequisites

*   **VS Code** with **GitHub Copilot** or **Cursor**.
*   **Python environment** with `ibis`, `geopandas`, `rasterio`, `rioxarray`, `anymap`, `altair`.
