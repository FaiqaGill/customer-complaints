# customer-complaints
Python project for analyzing customer complaints data.
# Customer Complaints Analysis

This project analyzes a customer complaints dataset to extract insights on complaint volumes, service distribution, and company performance. The notebook includes data cleaning, handling outliers, and visualizations.

## Dataset

The dataset contains customer complaints with columns such as:
 1    Date                          
 2   Complaint ID                   
 3   Service                       
 4   Subcategory                   
 5   Complaint                     
 6   Supporting comments          
 7   Company                      
 8   City                          
 9   State                        
 10   ZIP code                      
 11  Communicated By               
 12  Company response to consumer  
 13  Timely response               
 14  Consumer disputed             
 15  Day of week name              
 16  Month                 
 17  Year                         
 18  Days    

## Features

- Visualizes complaint distribution across companies, services, and days of the week.
- Cleans and standardizes data for further analysis.
- Exports cleaned data for future use.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- pyspan

## Running the Notebook

To run the notebook locally, install the necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn pyspan
