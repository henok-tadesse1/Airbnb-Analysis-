# Airbnb Data Cleaning and Visualization

## Description

This project focuses on analyzing Airbnb data to develop strategic pricing quotes. I began by cleaning the dataset—sourced from Kaggle—by addressing missing values, outliers, and duplicate records to ensure data quality. The dataset included key variables such as location, pricing, availability, reviews, and host information. I then segmented listings by neighbourhood group and room type, and used metrics like average price, availability and review volume (to gauge demand). With this structured approach, I was able to benchmark performance across regions and room types, identify pricing gaps, and recommend optimized quotes aimed at maximizing profitability while staying competitive in the market.


![My Image](https://drive.google.com/uc?export=view&id=1Qk9cwhTxr6GHo3tuzHEuixRClM0VBgiC)



## Visualization:
Answering key business questions through graphs and charts.                                 
Scripts are in the Data cleaning and Visualization in python folder. Execute them step by step to replicate the cleaning and visualization process.

## Analysis and Visualizations

The analysis includes visualizations created with Matplotlib, Seaborn, and Folium. Here are some key visualizations:

1. **Bar Plots**:
Top 10 Hosts by Number of Listings: 
Identifies hosts with the highest number of listings.

Average Price by Neighbourhood: Compares average pricing for the top 10 neighbourhoods.

Most Active Neighbourhoods: Highlights neighbourhoods with the most listings.

2. **Box and Violin Plots**:
Availability by Room Type: Displays the range of availability for different room types.

Price Distribution by Room Type: Shows price variation for different room types.

3. **Geographical Maps**:

Listing Locations: A Folium map plotting all listing locations with interactive markers. 
Markers are color-coded by room type (e.g., blue for Entire Home/Apt, green for Private Room, orange for Shared Room) and include detailed pop-ups showing the host name, neighborhood, room type, and price."

![geo](https://github.com/user-attachments/assets/ebcf09f9-39ae-421f-84db-7859ad4acf3f)

4.**Heatmaps**:
Correlation Heatmap: Shows correlations between numeric columns like price, number of reviews, service fee, availability, reviews per month.


![heat](https://github.com/user-attachments/assets/91d4a7c7-15fc-455f-abd0-9a1da92ed091)

## Business Use Cases
The cleaned data and visualizations can be applied to answer critical business questions such as:

### Revenue Optimization:

Optimize pricing and service fees to maximize revenue.

### Market Expansion:

Identify underserved neighbourhoods or states for potential expansion.

### Customer Experience:

Improve satisfaction by focusing on high-demand areas and high-scoring properties.

### Seasonal Strategy:
Align marketing efforts with seasonal trends in availability and reviews.

## Key Findings

- Neighbourhood Trends:

The most active neighbourhoods and their pricing trends were identified.
Neighbourhood groups influence pricing significantly.

- Room Type Preferences:

Certain room types have higher average availability and more competitive pricing.

- Host Insights:

Hosts with verified profiles have a larger share of the listings.

- Review Dynamics:

Reviews over time reveal seasonal peaks, aligning with high availability periods.

## Installation and Setup
To run this project locally, follow these steps:

1. **Clone the Repository**:
``` bash
Copy code

git clone https://github.com/your-username/airbnb-data-analysis.git
cd airbnb-data-analysis
```
2. **Create and Activate a Virtual Environment (optional but recommended)**:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. **Install the Required Packages**:
```bash
Copy code
pip install pandas NumPy matplotlib seaborn folium geopandas jupyter
```
4. **Launch Jupyter Notebook**:
```bash
jupyter notebook
```
5. **Open the Notebook**:
Navigate to the folder containing the Python scripts and open the relevant notebooks for cleaning or visualization.

Usage
The project includes Python scripts and notebooks for:

Data Cleaning: Handling null values, duplicates, and outliers.

## Data Sources

The dataset used in this project is sourced from [Airbnb open Data](https://www.kaggle.com/datasets/itsrohitkumarshaw/airbnb-open-data). It includes:

Listings information

- Host details

- Availability and pricing

- Reviews and ratings

The dataset was cleaned to handle missing values, outliers, and inconsistencies.

## Project Structure

airbnb-data-analysis/
```
├── Airbnb_Open_Data.zip            
├── cleaned_Airbnb_dataset.xlsx       
├── Data cleaning and Visualization in python.zip   
├── Graphs.zip               
└── README.md                    
```

## Contact Information
For any questions or inquiries, please contact: 📧[samgetachew2022@gmail.com](samgetachew2022@gmail.com)
