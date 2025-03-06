
### Title:   " Data Visualization Tycho2.0 "

### Author: "Kakadiya Tushal [ Tushal.Kakadiya@stud.th-deg.de ]"

### Date: "20-06-2022"

# Tycho 2.0

## Data Visualisation 

### Data Visualisation of Medical data from U.S. health department.

This project is aiming to analyse massive data that contains the details of 50 diseases that occurred in all states of the U.S during the time 1888 to 2014. The Source of this data is from Project Tycho which works with national and global health institutes and researchers to make data easier to use and free to access for public to do analysis and research.

R provides quick and simple tools that make it easier to transform data into visually insightful pieces like graphs. The data gets easier to read and comprehend from the graphs. The following is a list of the various types of graphs are plotted here using Descriptive statistics and ggplot2.

### Note:- 
The generated graphs and plots provided here are offers an overview of the Overall Analysis. For more detailed insights and access to the complete analytical file, please navigate to the GitHub page by clicking on the blue button located at the top of this page. There, you'll find the comprehensive analysis, including additional visualizations, code, and explanations.

## following few graphs are the representation of visualisation used in this Analysis.

- Tree map
- Tree map shows how the spread of disease varies in terms of magnitude in relation to one another. The most prevalent diseases are shown in the largest quadrilateral region, while the least prevalent diseases are shown in the smallest quadrilateral. Additionally, it provides data insights for two events, cases and deaths in terms of the occurrence ratio.
![image](https://github.com/user-attachments/assets/fc32abc0-ea13-411c-a816-673ab2937054)


  ![Tree map](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/2356f7d6-33ac-4570-b05f-9649446aad18)
  
  
- Scatter Plot1
- Over the duration of the observation period, the scatter plot compares the cases. This graph generated using log10 scale to compare all Dieses cases across all 50 states in U.S.![image](https://github.com/user-attachments/assets/47a662dc-f704-413d-87b8-e3257a1f29d9)


  ![Scatter1](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/ee3cb774-d02f-4d8b-a3a3-6d6ede736ed8)

- Scatter Plot2
- This graph compares the Deaths throughout the course of the observation period using a scatter plot. This graph compares all deaths events among all 50 states using a log10 scale. ![image](https://github.com/user-attachments/assets/def12f08-83d0-49b9-8a88-0f675bcbba3e)


  ![Scatter2](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/6db5922c-b954-4797-bce5-d8830c9d1745)

- Choropleth Map1
- This graphical plot, is an interactive choropleth map, displays all deaths for all 50 States in the United States from 1888 to 2014 in sequance of years. It explains why particular states, like New York, have lighter hues more frequently in the US's northwest side, which particularly follows the high number of cases.![image](https://github.com/user-attachments/assets/ec6be4e9-a1b2-49b3-92de-668619287f26)


  ![newplot (1)](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/f2022069-f3d7-4982-95f4-7abd0248e77a)

- Choropleth Map2
- This graphical plot, is also an interactive choropleth map, displays all cases for all 50 States in the United States from 1888 to 2014 year wise. It explains why particular states, like New York, have lighter hues more frequently in the US's northwest.![image](https://github.com/user-attachments/assets/b79e31f1-2a25-462f-b60d-9fac36337a28)


 ![newplot](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/5e05847b-0856-4702-bf4a-403a20cb4cad)

  
- Bar Plot1
- The graph, compares the number of cases and fatalities for each disease in the United States for the relevant time frames. There are exactly half (25) of the diseases that fall within the group of diseases with more than 55000 cases.![image](https://github.com/user-attachments/assets/2173592d-55ed-4e0a-b878-01ff87281170)


  ![Barplot_1](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/9908a2e5-e50d-4871-9607-b29ddebe943d)

  
- Bar Plot2
- The remaining half (25) of the diseases are included in the category of cases and deaths with fewer than 55,000 cases. In the United States over the relevant time periods, the number of cases and death for each disease is compared in the graph beside.![image](https://github.com/user-attachments/assets/20864394-5fd7-4fc9-bdb1-738b084b6fa4)


  ![Barplot_2](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/b580c24f-770e-451d-834f-757d864cd962)
  
- Heat map1
- The heat map shows how three diseases—tuberculosis, influenza, and pneumonia—had a significant influence on almost all states. Additionally, it was discovered that yellow fever, dengue, cholera, varioloid, and typhus fever had the least influence. It also shows the New York state had vital impact of three disease.
![image](https://github.com/user-attachments/assets/ac0e6a19-dfba-421d-a35a-f040f726a8ee)


  ![Heatmap_1](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/9f31f400-01a5-4d7f-aa53-325da2a57fb6)

- Heat map2
- The heat map shows that Anthrax, Babesiosis, Leprosy, Dengue, Coccidioidomycosis, Ehrlichiosis/Anaplasmosis, and Yellow Fever are the diseases that are least affected throughout all states. Measles, influenza, hepatitis B, hepatitis A, Gonorrhoea, Whooping cough, chlamydia, and chicken pox are the illnesses that have the most impact..

In this heat map, it can also be see that five states—American Samoa (AS), Guam (GU), MP, PT, and Virgin Islands (VI) had less impact on the number of cases than the other states.
![image](https://github.com/user-attachments/assets/e89c6c1a-4a94-4fc3-b4cf-6c49f800c1db)


  ![Heatmap_2](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/25497daf-284d-432d-adc0-d30a06dbbb83)
  
- Heat map3
- The heat map shows how almost all states were greatly influenced by all illnesses. Almost all states were affected, where if we compare with scatterplot 1 this plot gives more detailed view for affection over state on particulate year. The darker hue in the outcome indicates greater influence.![image](https://github.com/user-attachments/assets/1fbaeacc-630c-495f-8531-20c5660012e6)


  ![Heatmap_3](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/26d3a7be-8985-4525-861e-788a39b3b9da)
    

- Box Plot
- This box plot shows comparison between cases and deaths for 14 disease. To compare Fatal disease, we compare cases with dates using box plot.![image](https://github.com/user-attachments/assets/8f1d32b8-e83c-4b3b-af90-8f5da526c820)


  ![Boxplot](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/41bc023e-89f1-4f20-b495-feaa0ddf4d0c)
  
- Animation Plot
- According to the animation plot shown beside, Measles cases increased exponentially from a low level in 1905 to a peak around 1936. Thereafter, cases gradually declined until the measles vaccine was released in the US in 1962, at which point they abruptly began to decline.  So that  makes clear the rise and fall of Measles.
![image](https://github.com/user-attachments/assets/40f70be3-1803-4e29-9bcd-fad73af96ffc)


  ![Scatter_3_Animated](https://github.com/KAKADIYAS/Kakadiya_Tycho.github.io/assets/97363259/de095096-f672-44f1-8a62-27893011d512)


### References

 [Data Link](https://www.tycho.pitt.edu/version-2/)
 
 

