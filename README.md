# MLS Data Cleaning and Wrangling Project

# Project Description

This project involves cleaning and wrangling MLS (Major League Soccer) streaming data received from Apple TV+ to align it with Trajektory's dimension tables and landing tables. The goal is to properly structure AMA (Average Moment Audience) viewership data to facilitate MLS game valuation.

# How the Code Works
1. Data Loading
Imported necessary Python libraries: pandas, numpy, and re.
Loaded all datasets into Pandas DataFrames:
MLS data (source viewership data)
2023 Trajektory events (reference for event mappings)
Trajektory_mls_team_dim (reference for team mappings)
Streaming landing (target format)
2. Data Cleaning and Standardization
Event Matching:
Standardized event names and event keys from MLS data.
Merged with the 2023 Trajektory events table to ensure consistency.
Team Mapping:
Mapped team names and team keys using the Trajektory_mls_team_dim table.
Ensured uniformity in naming conventions (e.g., removing special characters or formatting inconsistencies).
Date and Time Formatting:
Standardized timestamps where applicable.
3. Data Transformation and Formatting
Extracted necessary columns from the cleaned MLS data.
Renamed columns to match the streaming landing tab format.
Ensured data integrity and structure consistency.
4. Final Output
Exported the cleaned and formatted data as a CSV file matching the streaming landing table requirements
