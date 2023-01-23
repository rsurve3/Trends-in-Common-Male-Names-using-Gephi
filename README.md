# Trends-in-Common-Male-Names-using-Gephi

**Background**
A name is a powerful thing. It is a crucial factor in developing your sense of self.
It is a descriptor that allows people to make quick judgments and assumptions about us.
When a new person introduced themselves to us, our first instinct is to assemble a rough mental sketch of everyone we have ever known named the same.
Maybe someone named the same bullied us in school or they were once our good friend. We subconsciously judge this person, at least a little, based on all the other people we know named the same.
Now with increasing usage of unique names, it is not that common for us to meet people with same names.
However, in this project I have attempted to find the most common names in males for the years 2015 and 2020 so that this data can be used further for analysis.


**Dataset - 2020**
I have already worked on this dataset for my midterm. 
It comprises with top 10 most common names in the 50 States and District of Columbia.
For the purpose of keeping the visualization clear, I have only worked with the top 5 most common names while keeping all the regions. 
I found this data from the SSN website.
However, I extracted the same data from Wikipedia website as there it was in a tabular form. 
Here is the link for the dataset - https://en.wikipedia.org/wiki/List_of_most_popular_given_names_by_state_in_the_United_States


**Dataset - 2015**
After doing analysis on 2020 Dataset, I decided to go with the year 2015.
I believed these 5 years of difference between two data points would be sufficient for this study as changes in preference to name their child seemed to grow exponentially during this period.
Just like 2020, I have used the top 5 most common names for my Gephi social network. However, I have also interacted with the rest of the names to come to my conclusion. 
To avoid confusion and data discrepancy, I have only used one name in cases where two or more names were ranked the same in a certain state. The name was picked at random.
Here is the link for the original 2015 dataset - https://en.wikipedia.org/wiki/List_of_most_popular_given_names_by_state_in_the_United_States


**Observations about Data**
I have created two Gephi social networks for the year 2015 and 2020.
In both the networks, the different names of males are at the center of the network.
The various states comprises the boundary of the network.
The states are placed in the network according to the geographical location of the  respective state on the United States map.
For the year 2015, I divided the states region wise and created 5 more Gephi social networks for each region.
The data being used is made up of top 5 most common names used and subsequently the most common name is connected to its respective state with an edge having weight 5. 
The least most common name is connected to state with an edge having weight 1.


**Country Wide Analysis - 2015**
![image](https://user-images.githubusercontent.com/122759737/213981642-938ba5f7-366f-4db4-a012-7ef2c4d98b81.png)
Out of total 255 spots of 5 most common names in 51 United States of America (including District of Columbia) these 10 names comprises of 199 spots. 
The top 5 most common names for the year are Liam, Noah, Mason, William and James.


**Country Wide Analysis - 2020**
![image](https://user-images.githubusercontent.com/122759737/213981757-c6fcf1b9-0977-400e-b0dc-9ad230f7f3c7.png)
Out of total 255 spots of 5 most common names in 51 United States of America (including District of Columbia) these 10 names comprises of 212 spots. 
The top 5 most common names are  Liam, Noah, Oliver, William and Elijah.


**Northeastern States Analysis - 2015**
![image](https://user-images.githubusercontent.com/122759737/213981811-3052d88d-dcfe-4be4-b8b5-27a6a40282c0.png)
Here, we can see there are three groups of popularity: 
Liam, Mason and Noah
Jacob and Michael
Alexander, Benjamin, Logan, Joseph and Lucas


**Northeastern States Analysis - 2020**
![image](https://user-images.githubusercontent.com/122759737/213982385-76cd0d12-5013-4901-838c-c15334fc4391.png)
A gradual shift can be seen when Northeastern States are compared with the entire United States of America.


**Conclusions**
During the span of 5 years between 2015 and 2020, a gradual shift can be noticed with the popularity of names.
Names like Mason, Jacob and Jackson which were among the most common names in 2015 did not even make the list in 2020.
Instead, Benjamin, Theodore and Jackson made their way in the top 10 list even though they were at the bottom in the sequence as mentioned. 


**Next Steps**
With the collection of such data, it is now possible to delve deeper into the idea of “what effects does a person’s name has on their life”
It has been observed in various psychological studies that people having specific names tend to act or make decisions in a certain way. 
With the availability of this data, further research can be done on this hypothesis. 






