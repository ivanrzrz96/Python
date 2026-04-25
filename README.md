# Synthetic Data Generation and Infrastructure Visualization

## Project Overview
This project demonstrates the ability to algorithmically generate, process, and visualize synthetic data using Python. It simulates an IT infrastructure environment by generating 1,500 rule-based server hostnames, parsing the strings into a structured dataset, and visualizing the resulting distributions to analyze system allocation.

## Tech Stack & Skills
* Languages: Python.
* Libraries: Pandas, Matplotlib, Seaborn, Random.
* Core Skills: Synthetic Data Generation, Data Parsing, String Manipulation, Data Visualization.

## Key Analysis Workflows

### 1. Algorithmic Data Generation
* Objective: Create a realistic, weighted synthetic dataset.
* Insight: Developed a function to create unique hostnames based on predefined probability weights for Operating Systems (e.g., Linux 40%, Solaris 30%), Environments (Production, Testing, etc.), and geographical locations across Europe. Implemented logic to ensure sequential and unique node numbering.

### 2. Data Parsing and Structuring
* Objective: Transform raw string data into a structured format.
* Insight: Built distinct extraction functions to parse the generated hostnames based on character positioning. Constructed a clean Pandas DataFrame mapping each hostname to its specific OS, Environment, Country, and Node number, subsequently exporting the data to a CSV file.

### 3. Infrastructure Visualization Dashboard
* Objective: Visually analyze the generated IT infrastructure distribution.
* Insight: Engineered a comprehensive 2x2 dashboard using Seaborn and Matplotlib. The visualizations include:
    * Horizontal bar charts detailing the type of OS grouped by country.
    * A pie chart displaying the total percentage share of each Operating System.
    * Bar charts breaking down the total number of hosts per country.
    * Grouped bar charts showing the distribution of environments within each country.

## Strategic Conclusion
This project proves proficiency in core Python programming concepts, showing the ability to write custom algorithms for data generation, perform programmatic data wrangling with Pandas, and build professional-grade visual dashboards.
