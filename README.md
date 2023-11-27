# Data Analysis of Marital status based Gender and Religious coummunity across Districts of Karnataka
Using Excel For data Cleaning and Power Bi for visualization  and Analysis

# Project Overview 
A Census Data about The marital Status of Karnataka Population By Gender and Religious Community in the year 2011 is Selected to Analyze the marital status of males and females according to their district and religion. 
### Data Source:
- Data- [DDW-2900C-03 link](https://censusindia.gov.in/nada/index.php/catalog/10528/study-description) or 
- [DDW-2900C-03.xlsx](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/files/13476717/DDW-2900C-03.xlsx)

  ### Tool Used and Methodology
  -Excel for data cleaning
  
  -Power BI for Data visualisation
  
  -Used power Query to transform given data into Table
  
  -Used Data validation, Filtering and Sorting function to Clean Data and
  
  -Finally Power BI DAX and visualisation
  

  # Data Analysis Process

  When I downloaded Excle File From Data it was in Unpivot form of data. which was used to look like this
  
  ![Screenshot 2023-11-27 205734](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/assets/152152421/4e2987fd-2c14-4098-933e-468e94960694)

  so,  I Removed most of the Unwanted cells in the table and made Some of the Cells(Religion names) as headings by using text alignment: center across selection

  ![Screenshot 2023-11-27 210044](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/assets/152152421/d829d97d-2d3f-44a6-accc-7a4d5f219953)


 -The data was initially manipulated in the Power Query editor to transform it into a Pivot Table format. Subsequently, during the data analysis phase, 
 it was discovered that there was an additional gender category labeled "Persons," which lacked clarification in the dataset or on the website. Consequently,
 this category was removed, as the visualization plan focused on the distinct genders of Male and Female.
 
 -Furthermore, the marital status column contained a category labeled "Unspecified," which consistently held zero values across all columns, 
 rendering it irrelevant for visualization purposes. Therefore, the decision was made to eliminate this category. 
 
 -Despite containing comprehensive details, the dataset included a "Total" column, resulting in a duplication of the overall population value. 
 To address this, the total columns were removed. With these refinements,after some sorting the data was deemed ready for visualization in Power BI.
 (data was looking like this)

 
![Screenshot 2023-11-27 213158](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/assets/152152421/ddd74ed0-bdbe-46ad-a1c9-e2fc9148e0d0)

### Imported data to Power BI

In the Power BI Desktop, navigate to the "Data" view to create calculated columns or measures using DAX (Data Analysis Expressions).
for creating new measure to find the value for the unmarried male and unmarried females.


![Screenshot 2023-11-27 214214](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/assets/152152421/baba5fd2-a111-431c-aac0-26695f9cccab)

after all the procees final dashborad was looking like this 

![Screenshot 2023-11-27 215809](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/assets/152152421/9a17e6c2-af60-4478-a616-94c7d6211394)


### Dashborad 

[Karnataka Population Census.pdf](https://github.com/varunkumarkj/Data-Analysis-of-Gender-and-Religious-based-Marital-status-across-Districts-of-Karnataka/files/13477754/Karnataka.Population.Census.pdf)

