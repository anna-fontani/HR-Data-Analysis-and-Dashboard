# HR Data Analysis and Dashboard

**Project Tasks**
- Create a dashboard to demonstrate salary and gender distribution in different teams. 
- Prepare report for HR on current trends in the copmany. 

**Data**

Employees dataset (open source) contains following information for over 900 employees: first name, gender, salary, bonus, senior management, team.  

![image](https://github.com/anna-fontani/HR-Data-Analysis-and-Dashboard/assets/149007143/ea1652bc-4102-4a5d-ad62-24b53f7ff8f9)

The dataset was preprocessed using Python and further exported for Power Bi dashboard creation.

## Data Cleaning
A number of corrupt values had to be addressed (like "n.a.", "?", etc.). All these values were converted to NaN. 

Missing values were replaced by mean (salary, bonus) and "No Gender" category for gender feature. 

Records with remaining missing values (first name, senior management, team) were removed for the purpose of this visualization. 

Overall, in real-life scenarios, such records must be treated with attention and their values have to be restored / investigated. 

## Dashboard using Power BI

Power BI was used to create customizable dashboard based on this data. All charts are interactive and can be filtered to display needed information.  

![image](https://github.com/anna-fontani/HR-Data-Analysis-and-Dashboard/assets/149007143/b4dc71ca-98bf-43cd-a76c-c4a01034738d)


