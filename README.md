# Spa-Data-Pipeline

Data engineering project focused on collecting, organizing, processing and analyzing motorsport data from Circuit de Spa-Francorchamps.

The project currently focuses on telemetry and metadata from Audi vehicles, with the goal of building a reproducible data pipeline that can later incorporate geospatial data, database systems and further analysis.

## Project Overview

This project uses data collected from motorsport simulations to explore how telemetry can be transformed into structured and reusable datasets.

The initial dataset includes telemetry logs and metadata from Audi vehicles at Spa-Francorchamps.

The project is designed to evolve from raw data collection into a complete data pipeline:

Raw Data → Parsing → Processing → Storage → Analysis

## Current Data

The repository currently contains data related to:

- Audi R8 LMS GT3 EVO II
- Audi R8 V10 Performance quattro
- Spa-Francorchamps circuit data
- Telemetry logs
- Vehicle and session metadata

Additional datasets may be incorporated as the project develops.

## Data Pipeline

The planned workflow is:

```text
Raw telemetry
      ↓
Data parsing
      ↓
Data validation
      ↓
Data transformation
      ↓
Structured datasets
      ↓
Database / storage
      ↓
Analysis and visualization
