# Real_Estate_and_Property_Management_Analysis
### Cleaning and Analyzing data in Power query and Power BI

## Introduction
This project is about real estate industry and property management. I investigated the number of properties in various locations, different types of floors, waterfront, and location. The analysis examines the status of the properties in order for decision makers to determine which properties require immediate attention and repair.

## Data Cleaning 
After importing my data into power query, I checked for duplicates(found none),the validity of my data using column distribution, quality and profiling and truncated columns not needed for my analysis. New columns were also added (conditional columns) to know the total number of bedrooms and floors in an apartment, the waterfront status, renovation status and the properties' condition status. To navigate easily through the analysis, dimension tables were created from the fact table
I also made sure my columns were in the right data type.

![{207D3515-2017-4201-BF34-3E2E9299EFE7} png](https://user-images.githubusercontent.com/115374063/199231320-77fd37a7-d545-4091-b318-0e361f511663.jpg)

## Data Modelling 
After importing my cleaned data into power bi workspace, I linked the dimension tables with their primary keys (IDs) for create relationship between the dimension tables. 

![{F9C936F2-6021-4F47-89BA-8872F72A2920} png](https://user-images.githubusercontent.com/115374063/199229528-e321204f-b3c3-4cc0-97e5-7da6910b779e.jpg)

## Data Analysis and Visualization
1. The highest number of properties were built in 2007 with a total of 1,787 prooperties and was 4,602.63% higher than 2015, which had the lowest Total Properties at 38. 2007 accounted for 8.27% of total properties.

![{FAEF3F83-95DB-43E4-B9FB-F1D667F93C98} png](https://user-images.githubusercontent.com/115374063/199229644-f9af4e52-5edb-4273-bb4f-6d6de8093c1a.jpg)

2. The analysis of the 11.83% increase in total properties between 2006 and 2007 shows that; California and Arizona accounted for the majority of increase in property location, offsetting the decrease of Hawaii. The relative contribution made by California, Arizona ans Hawaii changed the most.

3. Most of the properties are 3 bedrooms apartment. This accounted for 45.45% of the total properties.

![bedroom](https://user-images.githubusercontent.com/115374063/199229875-78c409f4-6bd7-4793-96e8-66aa1c3da15a.jpg) 

4. Almost half of the total properties are in need of renovation. This accounted for 48% of the total properties across all locations. Almost all the properties are also without waterfront. 

![Renovation status](https://user-images.githubusercontent.com/115374063/199229992-d1455e6d-4133-4b77-b89c-01d16e88ce39.jpg) ![renovatiin](https://user-images.githubusercontent.com/115374063/199230037-f1bd05ac-32f7-4633-b44b-69d5388a25df.jpg)

5. Lastly, the analysis shows that, over half of the total properties are in 'very good condition' while about 16.1% of the total properties are in 'bad condition' which in turn needs immediate renovation.

![property condition](https://user-images.githubusercontent.com/115374063/199230267-bbfbc9aa-ea71-4108-b993-e55d15fc1af8.jpg)

Dashboard here


[Real Estate.pdf] (https://github.com/VictorOluniyi/Real_Estate_and_Property_Management_Analysis/files/9909729/Real.Estate.pdf)


