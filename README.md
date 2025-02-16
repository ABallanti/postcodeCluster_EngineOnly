![image](https://github.com/user-attachments/assets/715d0238-eb30-4cd5-93e5-b7df8316368d)

# Postcode Clustering Engine

A Python-based tool for AI-based clustering UK postcodes into geographical (given) number of groups,  visualizing them on an interactive map and also providing the XLSX outputs.

## Features

- Groups UK postcodes into specified number of clusters using K-means algorithm
- Converts postcodes to geographical coordinates using local data files
- Generates interactive map visualization with color-coded clusters
- Handles invalid postcodes
- Exports results to Excel with separate sheets for valid and invalid postcodes

## Prerequisites

- Python 3.11 or higher
- Required Python packages (install via `pip install -r requirements.txt`):
  - pandas
  - scikit-learn
  - folium
  - pyproj

## Installation

1. Clone the repository:
