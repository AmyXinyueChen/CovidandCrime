# NYC Crime / COVID-19 Correlation Analysis
- author(s): Hanqing Chen, Xinyue Chen, Candice Lee
- date created: 5/14/2021
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were:
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages
### Project Planning                    
Motivation for project:
The U.S is seeing a massive spike in hate crime since the COVID-19 pandemic. There appears to be more violent attacks against certain minority groups recently, making these types of groups easier targets and more vulnerable to hate crimes. As students and residents in New York City, we are eager to help change the situation and stop the violence. 

Description of the issues or opportunities the project will address:
The COVID-19 has been spreading in the United States for almost a year, and many assumed Asian communities (and many other groups, including women and elderly people) have ever since been facing a surge of hate crimes targeting them. With categories of different crimes committed, our project seeks to analyze datasets extracted from public sources to verify whether these types of assumptions are true or not and how crime rate is impacted by COVID- 19. If true, by using our analysis we hope to push local authorities and volunteer groups to better utilize their resources to protect our residents. 

Project Business or Organization Value:                
Reduce the crime rates and provide a more secure living environment for residents. It will be beneficial in improving local business and property prices. 

Data Sources:
1. New York State Statewide COVID-19 Testing_NY state https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Testing/xdss-u53e 
2. NYC Complaint Data__NYC Open Data  https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-Year-To-Date-/5uac-w243 
                        
### Business Requirements Definition            
List of Data Warehouse KPI's:
1. Numbers of crime grouped by month
2. Crime counts by borough
3. COVID-19 cases counts by borough
4. Total crime counts / Total COVID-19 cases by month
5. Total crime counts / Total COVID-19 cases by borough
                
### Dimensional Model
This project's Dimensional Model consists of (x) Facts and (y) Dimensions                        
![Alt text](/img/DimensionalModel.png)
            
This project's Kimball Bus Matrix:                    
![Alt text](/img/KimballBusMatrix.png)
            
### Business Intelligence Design and Development                
List of Visualizations for each KPI:
1. Line graph for the month distribution of the number of crimes
2. Bar graph for the area distribution of the number of crimes
3. Bar graph for the area distribution of the number of covid-19 cases
4. Line graph for the month distribution of the ratio of total crime counts divided by total covid-19 cases
5. Bar graph for the area distribution of the ratio of total crime counts divided by total covid-19 cases

BI Application Wireframe design:            
![Alt text](/img/Wireframe.png)
            
Picture of final Dashboard:
![Alt text](/img/Dashboard.png)
    
### Deployment
The project was deployed on Tableau Public: https://public.tableau.com/profile/zack.chen#!/vizhome/crime_covid1_16205293248190/Dashboard1?publish=yes
