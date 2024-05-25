# README

## Overview

This project is designed for watershed delineation using geospatial data. The primary code integrates various geospatial processing libraries to delineate watersheds based on input coordinates.

## Prerequisites

Ensure you have the following dependencies installed:
- Python 3.x
- numpy
- pandas
- geopandas
- shapely
- pyproj
- matplotlib
- flask
- sigfig

You can install these dependencies using `pip`:

```bash
pip install numpy pandas geopandas shapely pyproj matplotlib flask sigfig


**## Project Structure**

- delineate.py: Main script for watershed delineation.
- config.py: Configuration file with various settings.
- app.py: Flask application to handle web requests for delineation.
- templates/index.html: HTML template for the Flask app.


**## Running the Flask Application**
The Flask application provides a web interface for watershed delineation. It allows users to input coordinates and get the delineated watershed as a response.

**## Running the Flask App**
1. Ensure you have the Flask dependency installed.
2. Run the Flask application:

```bash
python app.py
