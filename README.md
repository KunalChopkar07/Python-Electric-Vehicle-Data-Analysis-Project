# Electric Vehicle Data Analysis Project 🚗🔋

# Overview
This project analyzes a dataset related to Electric Vehicles (EVs) to uncover meaningful insights, conduct hypothesis testing, and provide actionable recommendations. The project is implemented using Python, leveraging libraries such as Pandas, NumPy, Matplotlib, and SciPy for data manipulation, visualization, and statistical analysis.

# Dataset Details
The dataset includes the following attributes:

Car Details: Name, Make, Model

Performance Metrics: Engine Power, Maximum Torque, Acceleration (0-100 kph), Top Speed

Physical Specifications: Dimensions (Wheelbase, Length, Width, Height), Weight, Boot Capacity, Tire Size

Energy Details: Battery Capacity, Energy Consumption, Maximum Charging Power, Driving Range

Other Attributes: Price, Drive Type, Number of Seats, Number of Doors

# Objectives and Tasks

## Task 1: Filtering and Aggregating EVs
Filter EVs within a budget of 350,000 PLN and a minimum range of 400 km.

Group them by manufacturer (Make) and calculate the average battery capacity for each.

## Task 2: Identifying Outliers
Detect outliers in the energy consumption (Mean - Energy consumption [kWh/100 km]).

## Task 3: Battery Capacity vs. Range
Visualize the relationship between battery capacity and range. 

Highlight key insights.
## Task 4: EV Recommendation System
Build a class that recommends the top 3 EVs based on user inputs for budget, desired range, and battery capacity.
## Task 5: Hypothesis Testing
Conduct a two-sample t-test to check for significant differences in engine power between Tesla and Audi vehicles.
## Task 6: Project Presentation
Create a video explaining the project's objectives, methodology, and findings. (Link included in the notebook.)

# Tools and Libraries
Python

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Statistical Testing: SciPy

Jupyter Notebook: For organizing and presenting the analysis.

## How to Run the Project
Clone the repository:
bash

Copy code

git clone https://github.com/yourusername/electric-vehicle-analysis.git

Install dependencies:
bash

Copy code

pip install -r requirements.txt

Open the notebook:
bash

Copy code

jupyter notebook project.ipynb

Follow the instructions in the notebook to explore the analysis.

# Results and Insights
Filtering and Aggregation: Identified EVs that meet specific budget and range requirements, grouped by manufacturer with average battery capacity calculated.

Outlier Detection: Highlighted EVs with unusually high or low energy consumption for further investigation.

Visualization: Showed a strong positive correlation between battery capacity and range.

Recommendation System: Developed a customizable EV recommendation tool.

Hypothesis Testing: Found insights into engine power differences between Tesla and Audi.

# Contributing
Feel free to submit issues or pull requests to improve the project. Contributions are always welcome!
