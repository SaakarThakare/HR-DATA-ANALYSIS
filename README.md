
# Project Title

A brief description of what this project does and who it's for

# HR Dashboard



## Problem Statement

Develop a dynamic Power BI HR dashboard to analyze attrition rates and employee ratings across departments as per their education field. Provide actionable insights to enhance retention strategies and improve employee satisfaction.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : For calculating average attrition rate i have used some dax functions. 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for two fields named "Education" & "Age".
- Step 9 : Four card visuals were added to the canvas, one representing average attrition rate, another for Active Employees, Number of employees working in company & Average age.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
-   
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some employyees.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

- Step 10 : In the report view, under the insert tab, One text box were added to the canvas, in one of them attrition rate by age were given.
-  
- Step 11 : Calculated column was created in which, customers were grouped into various age groups.

for creating new column following DAX expression was written;
       


![Screenshot 2024-03-12 221822](https://github.com/SaakarThakare/HR-DATA-ANALYSIS/assets/128837809/2fdbfb7b-47ae-4be8-be89-ae1edb0136df)

        
- Step 15 : New measure was created to find total count of Employees.

Some DAX expression was written for the same,

 

 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot 2024-03-12 222315](https://github.com/SaakarThakare/HR-DATA-ANALYSIS/assets/128837809/848f0123-d481-4967-9526-cd30db7b1424)


