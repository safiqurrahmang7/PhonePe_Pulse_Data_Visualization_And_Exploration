# PhonePe Pulse Data Analysis

## Project Overview
This project involves extracting, transforming, and visualizing data from the PhonePe Pulse GitHub repository. It provides insights through an interactive geo-visualization dashboard, allowing users to explore data in a user-friendly manner.

### Key Objectives:
1. **Data Extraction**: Clone the PhonePe Pulse GitHub repository and extract relevant data.
2. **Data Transformation**: Clean, preprocess, and transform the data for analysis.
3. **Database Storage**: Insert the transformed data into a MySQL database.
4. **Dashboard Creation**: Develop a live geo-visualization dashboard using Streamlit and Plotly.
5. **Dynamic Data Retrieval**: Fetch data dynamically from the MySQL database for live updates on the dashboard.
6. **Interactive User Options**: Provide at least 10 dropdown options for users to explore different metrics.

## Features
- Interactive dropdown options to display different metrics.
- Geo-visualization map using Plotly for an engaging user experience.
- Efficient data storage and retrieval using MySQL.
- Secure, user-friendly dashboard built using Streamlit.

## Approach

### 1. Data Extraction
- Clone the PhonePe Pulse GitHub repository using a Python script.
- Save the data in CSV/JSON format.

### 2. Data Transformation
- Clean and preprocess the data using Pandas.
- Handle missing values, format data for analysis.

### 3. Database Storage
- Use `mysql-connector-python` to connect and insert transformed data into the MySQL database.

### 4. Dashboard Creation
- Build an interactive dashboard using Streamlit.
- Use Plotly for geo-map visualizations.
- Provide 10+ dropdown options for users to choose different metrics.

### 5. Data Retrieval
- Fetch data from the MySQL database dynamically into a Pandas DataFrame.
- Use the data to update dashboard visualizations in real-time.

## Tech Stack
- **Languages**: Python
- **Libraries**: Pandas, Streamlit, Plotly, `mysql-connector-python`
- **Database**: MySQL
- **Version Control**: Git, GitHub

## Installation

1. **Clone the repository**:
    ```bash
    git clone <your-repo-url>
    ```

2. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up MySQL database**:
   - Create a MySQL database and update the connection details in the Python script.

4. **Run the dashboard**:
    ```bash
    streamlit run app.py
    ```

## Dashboard Demo

![Dashboard Preview](dashboard-screenshot.png)

## Learning Outcomes

1. **Data Extraction**: Learn how to script GitHub data extraction.
2. **Data Transformation**: Gain skills in data cleaning, preprocessing, and transformation using Pandas.
3. **Database Management**: Store and retrieve data using MySQL efficiently.
4. **Visualization**: Create an interactive dashboard using Streamlit and Plotly.
5. **Dynamic Updating**: Develop a dashboard that dynamically updates from the database.
6. **Geo-Visualization**: Implement visualizations on a geographical map using Plotly.

## Project Structure

```bash
.
├── data/
│   └── extracted_data.csv
├── app.py
├── README.md
└── requirements.txt
