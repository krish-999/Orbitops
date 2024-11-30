# Forest Sentinel AI 

# Project: Yellowstone Fire Recovery Analysis

## Project Overview
This project analyzes the ecological recovery of **Yellowstone National Park** following the devastating wildfires of **1988**. Utilizing Landsat satellite imagery from Earth Explorer, we assess the park's vegetation regeneration and land cover changes over time. Our goal is to gain insights into the long-term impacts of the fires and contribute to understanding wildfire recovery in large-scale ecosystems.

## Objectives
- Acquire and preprocess **Landsat satellite imagery** of Yellowstone National Park from before and after the 1988 fires.
- Analyze changes in vegetation health and land cover using indices such as **NDVI (Normalized Difference Vegetation Index)** and **NBR (Normalized Burn Ratio)**.
- Assess the long-term impact of the fires on different vegetation types and land cover classes within the park.
- Contribute to the understanding of **wildfire recovery processes** in large-scale ecosystems.

## Background
The **Yellowstone fires of 1988** were a significant event in the park's history, burning nearly **800,000 acres**. These fires, influenced by drought conditions and strong winds, reshaped the landscape and raised questions about the park's resilience and recovery. This project examines the long-term ecological impact of these fires using satellite imagery analysis.

## Team Members
- **Franck Kasongo**
- **Krishna Vamsi Regulavalasa**
- **Shourya Bhardwaj**

## Project Workflow

### Data Collection
- **Earth Explorer**: Landsat satellite imagery of Yellowstone National Park was acquired through the **USGS Earth Explorer** platform for the years **1984-1989** (Pre-fire and Post-fire images).
- **Data Preprocessing**: Atmospheric correction and cloud masking were applied to the raw satellite imagery to prepare the data for analysis.

### Data Analysis
- **Vegetation Analysis**: We used **NDVI** to assess vegetation health and track recovery over time.
- **Burn Severity Analysis**: We utilized **NBR** to analyze the severity of burn scars and monitor their recovery.
- **Prototype Solution**: While a full land cover classification was not conducted, the prototype solution was set up for future classification. Initial data exploration and analysis were done, leading to insights into the vegetation changes post-fire.

## Tools and Platforms
- **Earth Explorer**: For accessing and downloading Landsat satellite imagery.
- **Python**: Used for data preprocessing, analysis, and visualization.
- **Azure Machine Learning Studio**: Collaborative platform for notebook development and machine learning tasks.
- **Azure Storage Blob**: For storing and sharing large datasets.
- **GitHub**: For version control and collaboration.

## Key Milestones
- Data acquisition and preprocessing.
- NDVI and NBR analysis.
- Initial vegetation recovery insights and prototype setup.
- Report writing and presentation.

## Literature Review
- [Yellowstone Wildfires of 1988](https://en.wikipedia.org/wiki/1988_Yellowstone_fires) — Provides background on the fires and their impact on the ecosystem.
- [Wildfire Recovery and Vegetation Regrowth](https://pubs.usgs.gov/circ/2017/1442/circ1442.pdf) — Discusses the role of remote sensing in post-fire vegetation monitoring.

## Public Data Sources
- **Landsat**: Multi-temporal satellite imagery to assess pre- and post-fire conditions.
- **USGS Earth Explorer**: Platform for accessing historical satellite data.
- **ESPA (Earth Science Processing Architecture)**: Provides processed Landsat and other satellite data, enabling efficient access to ready-to-use geospatial data for analysis.
