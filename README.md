# Alcohol Consumption Among Students

## About Us:
Tyler Brannon - TylerBran <br>
Patrick Guerin - guerinp19<br>
Eric D’Souza - ericdagoat<br>
Mohammadreza Rahbar - MRR02
## Introduction:
 The data set we chose is about alcohol consumption among secondary school students, which is a topic normally associated with college/university students. However, this topic isn’t talked about often with secondary school students, which is why this dataset is so important. These two datasets were obtained by surveying the students of a math class and a Portuguese language class, they were surveyed about several attributes including sex, free time, quality of health, parent’s jobs, etc. These datasets were made by two students at the University of Camerino named Fabio Pagnotta and Hossain Mohammad Amran. This dataset can be found at: https://www.kaggle.com/uciml/student-alcohol-consumption. 
## Discussion:
### 1. This question asks “which ages drink the most?”. To solve this, we looked at the age group of students that drink, and graphed it to find which ages drink the most, as well as find out what our outliers are. First, we had to get the count of students of each age. Once this was found out, our outliers seemed to be ages 19-22, which essentially just means that there were only a handful of students of this age. Then, we took each age number, and found the average alcohol consumption for weekdays (Dalc) and weekends (Walc). After doing this, we graphed our findings and came to the conclusion that students aged 15-18 are close in terms of alcohol consumption, but students aged 17 seemed to drink the most, even though they are on the low side of just 2.5 on the consumption scale. It is also important to note that the legal drinking age in Italy, which is where our data is from, is 18. So even though students aged 18 are legally allowed to drink, they still seem to not consume too much on weekends or weekdays.
![Question 1](https://user-images.githubusercontent.com/90166780/144950229-96d55cfc-fc23-4a12-8997-4a59fbeed9c0.png)

### 3. This question asks: Do more socially active students drink more? Check if the sociable students that have more free time tend to drink more. The answer to this question may seem obvious at first but the results may not be what you expect. To answer this question, we must take the average alcohol consumption for each of the five levels of how often a student goes out with their friends. After this we will graph it to get a visual on how that relationship looks. While looking at the graph it is clear to see that on average students who go out more tend to consume more alcohol. But this graph alone doesn’t give us enough information, so we must look at other attributes that may affect this. One of these attributes is how much free time each student has. By using free time along with how often a student goes out we get a much more diverse graph that shows some interesting information. When examining this graph, we can see some large spikes of alcohol consumption for students that consider themselves to have less free time and less alcohol consumption for those with more free time. The only exception to this is students go out very often and have lots of free time. Some explanations for these results could be that students with less free time usually are more stressed, this often leads students to turn to other things to relieve that stress. This can often take the form of alcohol or other substances. This can be seen as on average many of the students who don’t go out often and have more free time tend to drink less.

### 6. This question asks “does family size impact whether or not the student will drink?”. In order to solve this, we have to find the average alcohol consumption per each type of family size. In this case, it was either LE3 which is less than 3, or GT3 which is greater than 3. We also have to do this for weekday consumption (Dalc) and weekend consumption (Walc). When we determined the average for weekday consumption, we found that for students with family sizes greater than 3, the value was 1.4, whereas for students with less than 3 family members, it was 1.6. 
### The findings were similar for weekend consumption as well, the value was 2.2 for students with more than 3 family members, and for students with less than 3 members, it was 2.4. These values are all on a scale from 1-5, with 5 being the highest tendency to consume alcohol. In conclusion, we found that family size does impact whether or not a student will drink. Students with less than 3 members tend to drink more than students with more than 3 family members, by a margin of 0.2 for both weekend, and weekday consumption.
![Question 6 1](https://user-images.githubusercontent.com/90166780/144950568-301cd7bf-edcb-41c6-8705-1a54c5e4fe3f.png)
![Question 6 2](https://user-images.githubusercontent.com/90166780/144950570-56caf737-ef71-4326-adee-fde1eedb9a39.png)

### 7. his Question asks, “if a students has at least one parent at home are they less likely to drink”.  To answer this, we first need to add a variable to the table that tracks whether a student has one parent at home. We will do this by checking the Fjob and Mjob column and if one or both read “at_home” we will say that one of the parents are at home. We can then divide up the students based off this statistic and then further subdivide then based on what drinking habit category they fall under. Once we have this, we can find what proportion of students fall under what drinking category for both groups of students. Once we graph the trend, we see that with the Dalc graph the line representing the students with one parent at home is near identical to the one representing the one representing the graph for students with no parents at home. For the Walc graph see a similar trend, and we do see that the lines are more distinct but not enough distinct enough to call it a relation. From this we can conclude with a strong degree of confidence that there is not relation between whether a student has one parent at home and how much they drink.
![Question 7 1](https://user-images.githubusercontent.com/90166780/144954280-c70ff184-d8f2-49af-bfd8-d487209ab5e9.png)

![Question 7 2](https://user-images.githubusercontent.com/90166780/144954296-a9e77f82-5c82-4bdc-ac1e-c14951f39935.png)


### 8. This question asks, “do students worse with family relations tend to drink more?”. To answer this question, we first needed to divide the students into groups based on there family. We can then check what proportion of students fall under each drinking habit category for each group of family relations. If the proportion of students who’s fall under 1 and 2 category gets larger as a student relationship with their family gets better. After all these steps are done, we see that proportion of students in the 1 and 2 categories is moderately larger when family relations are good compared when are poor. As we can see from the graphs below the cohorts that have better family relation (i.e., the line labeled 4,5) have the larger proportion of students in the lowest drinking category and smaller proportion in the highest drinking category (i.e., Dalc and Walc 1). We also see that there is a general trend amongst all groups of having the largest proportion of students in lowest drinking category with each consecutive drinking category having a smaller proportion of the students in it. looking at this we can conclude of moderate degree of certainty that the worse the relationship a student’s relationship with their family and how much they drink. However, it’s likely a weak one as the general trend still holds for the all the graphs and if it were a strong trend, we would expect that the group of students with worse family relationships have the largest proportion of students skewed towards the 4 and 5 drinking categories. However, this result may not be the most accurate as we are wildly different sized cohorts and if were to near evenly sized cohorts might see that the proportions would balance out to be almost identical which would invalidate our conclusion.

![Question 8 1](https://user-images.githubusercontent.com/90166780/144954319-eda2c310-db92-49d9-b87d-41f02d6dce76.png)

![Question 8 2](https://user-images.githubusercontent.com/90166780/144954330-ccd5bbd6-1b26-476d-a7b7-9b639efd5735.png)


## Acknowledgements: 
This project was submitted as the final course project for CSCI 2000U “Scientific Data Analysis” during Fall 2021. The authors certify that the work in this repository is original and that all appropriate resources are rightfully cited.”

### How to Run
Clone this repository, and CD into it, and simply run the docker container.
