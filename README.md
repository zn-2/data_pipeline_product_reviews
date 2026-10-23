# Product Reviews Data Pipeline
 
## Project Overview
This project demonstrates a simple ETL (Extract, Transform, Load) data pipeline using Python.
 
## Project Structure
- `src/` - Python scripts for processing data.
- `Data/Raw/` - Raw data used in the pipeline.
 
## ETL Process
1. **Extract:** Read product review data from the source.
2. **Transform:** Clean and prepare the data for analysis.
3. **Load:** Save the processed data.
 
## Purpose
This project demonstrates GitHub version control and data pipeline development as part of Module 14 Day 2.
has context menu

## Instructions to run 
1. Add GitHub url to data_pipelines.py if you have a specific repo location you want to use  
2. Run ETL process by executing python -m src.data_pipelines in order to create review_products.processed csv and publish it to Github 
3. gitignore sst2_model folder (before it is created - too large to publish to GitHub)
4. Create model folder sst2 by executing python -m src.download_model 
5. Execute python -m src.model (this creates reviews_products_with_sentiment csv) 
6. Run data_pipelines again to publish reviews_products_with_sentiment csv to Github
 
