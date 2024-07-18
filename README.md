# Adventure Works - Sales Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMDAyNGQ4ZDUtMTE3OC00NjA3LWE4NTktYzAzZjllNmFiMWFlIiwidCI6IjY3OWE0MDJlLTAwOWEtNGU2ZC05ODNlLTg5YmEyNDY5OTM5NyJ9

## Problem Statement

This dashboard helps the airlines understand their customers better. It helps the airlines know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average delay & departure time, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted delays.

Since, number of neutral/dissatisfied customers (almost 57 %) are more than satisfied customers (around 43 %), thus in all they must work on improving their services. 

Also since average delay in arrival & departure both is 15 minutes, thus they must try to reduce it.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 :The dates were put in correct format
- Step 5 : In the report view, under the view tab, theme was selected.

- Step 6:  A stack bar column is added, understand the total sales amount and the ship date details
-Step 7:  Total Sales amount is calculated as below:
Total sales amount = SUMX(FactInternetSales,FactInternetSales[Freight] + FactInternetSales[SalesAmount] + FactInternetSales[TaxAmt])
  

        
Snap of new calculated measure ,

![page2](https://github.com/user-attachments/assets/6d333b26-5638-4cf3-b6ed-cf091075f8c4)

        
- Step 8 :
        
A card visual was used to represent count of customers.

![Snap_Count](https://github.com/user-attachments/assets/7e274b2b-8c25-4765-9246-9fcfea46044d)

        
 - Step 9 : 
 
 A card visual was used to represent total Orders.
 
 ![Snap_Percentage](https://github.com/user-attachments/assets/68669d8d-ee31-46df-96f4-cd8425e5f63a)

 
 - Step 10
    
 A card visual was used to represent this total Sales amount.
 
 
 ![Snap_3](https://github.com/user-attachments/assets/0d6a45dc-65fa-457a-813d-032d742b5b28)
 
 - Step 18 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://github.com/user-attachments/assets/145a60bd-5115-40a6-9999-01a4da7fa709)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/user-attachments/assets/8f32e48d-c328-4a5c-b6fd-76fcc11c884c)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/user-attachments/assets/a39ab31b-0d24-41e6-8bdd-664360045544)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.



