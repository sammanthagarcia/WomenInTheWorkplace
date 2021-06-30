# Women in the Workplace
## By Sammantha Garcia 
#### Digital Humanities Summer 2021
#### Prof. Adam Anderson


![WomenintheWorkplace](https://github.com/sammanthagarcia/WomenInTheWorkplace/blob/c714ae08cf57aa424e69111ccdb36c1040876313/Poster.pdf)

## Current Team 
2021: Sammantha Garcia (PI)

## Project Description
*DISCLAIMER: Gender and race have no scientific or biological bias. Both are social constructs with real consequences.*
 
Women, especially Women of Color, experience discrimination in education and in the workplace. This project is using datasets provided by Current Population Survey (CPS) in 2019 to compare the difference in annual income, occupation, and educational level between White Women and Women of Color (Black, Asian, Hispanic). Provided by the CPS, this project will also use an article from 2000 that reported Women of different races' occupation and annual income. 

The goal is to visualize how Women of Color are lower on the social hierarchy simply because of their gender and race. This project will spread awareness on the systemic issues Women face everyday and how Women of Color are still at a severe disadvantage, even after several efforts to change the patriarchy. The results of this project will help pose different ways Women of Color can overcome gender and racial discrimination. 

## Hypothesis
Because gender and racial discrimination are still prevalent today, I expect my results to show that there are more White Women in management positions; they will also have a higher degree of education and a higher income. In contrast, the total amount of Women of Color at each educational level will be consistently lower than White Women. I predict that Women of Color will generally have more menial labor jobs and have a lower income. 

## Methods and Tools for Analysis
After retrieving the datasets from the Census Population Survey (census.gov), I saved them as .csv files in Google Sheets. Then, I imported them into Jupyter Notebook for data cleanup and for generating visualizations. 

In my Jupyter Notebook, I used the following Python libraries to create my visualizations: 
 1) matplotlib: This library was used for creating the horizontal bar charts for each table. 
 2) numpy: I used numpy for simple functions, such as finding the length of a list or using a specific range of numbers. 
 3) pandas: This was used to import and read the .csv files, subsequently storing them into a Data Frame.

Using horizontal bar charts for my visualizations allowed me to see how there are less Women of Color in education and in the workforce. It also showed that there were more Women of Color with service occupations and White Women in management/professional occupations. 

## Inside My Repository 
1) Jupyter Notebook.ipynb: Python notebook for visualizations
2) Occupation - Black,  Asian, Hispanic.csv: dataset for occupations (Women of Color)
3) Occupation - White Women.csv: dataset for occupations (White Women)
4) Poster.pdf 
5) Storyboard.pdf
6) Women 25-64 (Black, Asian, Hispanic).csv: dataset for income (Women of Color)
7) Women 25-64 (White Alone).csv: dataset for income (White Women)
