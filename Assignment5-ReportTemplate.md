**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       | 22  |
|-----------------|---|
| Student Names:  |  Dave Sharma |
|                 |  Jaron Baldazo |
|                 |  Angelo Gonzales |
|                 |  Manjot Singh |

# Introduction
The purpose of this lab was to become familiar with integration analysis techniques using Reliabilty Growth Testing and Reliability assessment using Reliability Demonstration Chart (RDC). Using data given in a CSV form, integration analysis will be performed and plotted using tools such as CSFRAT or SRTAT. The data that will be plotted using these tools will be the failure rate and reliability. Gaining understanding of the usefulness of reliabilty growth testing, measuring MTTF, failure rate, and reliability will be important aspects of the laboratory.  
# 

# Assessment Using Reliability Growth Testing 
![image](https://user-images.githubusercontent.com/48339672/160703809-a3b3c78e-e335-4dad-9ade-eb070d0a85cd.png)
![image](https://user-images.githubusercontent.com/48339672/160703832-ea8d43ef-9960-4d2c-bc82-84599fea6c99.png)

The above chart shows the cumulative failure as a function of time using the CSFRAT tool imported with the .csv file.  The NB2(E,F,C) and TL(F,C) prediction models were used as best fit for the cumulative failure graph. As can be seen from the graph, the total number of failures start to plateau as the time increases, indicating that the total number failures does not increase that much. As time increases the number of failures decreases indicating a larger reliabilty in the test data that we have.

# Assessment Using Reliability Demonstration Chart 
![image](https://user-images.githubusercontent.com/48339672/160703735-9973cab6-7326-41a9-a068-de5271d30c83.png)
![image](https://user-images.githubusercontent.com/48339672/160703759-fb6b4325-5511-4a64-9bf8-8adb6044083e.png)
![image](https://user-images.githubusercontent.com/48339672/160703768-b2b693a4-a561-434f-8184-5397a52e09ab.png)


# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques
  The main difference between the two techniques of Reliability Growth Testing (RGT) and Reliabiliy Demonstration Chart (RDC) is that RDC is based on inter failure times and MTTF whereas RGT takes failure count and MTTF into account. For this assignment, RGT was done to show the relationship between the cumulative failures of the system as a function of time. On the other hand, RDC was done to show how the relationship between the failure number as a function of failure time where different risk parameters (customer risk, developer risk) are changed. A similarity that RGT and RDC share are its ability to determine the reliability of the system through integration analysis.

# How the team work/effort was divided and managed
  Team work was divided equally, as all team members worked together one each part of the lab. Each member of the team went through the familirization of CSFRAT and SRTAT, and were responsiblle on checking the coverage of the tests. As a team we went through the graphs and chart and determined from which we were able to visualize the data. Through this process we were able to familiarize ourselves with RDCs and RGT. Finally, the lab report writeup, was split equally between members. Throughout the lab, each member was responsible for keeping each other accountable, and make sure that the work was done in time.

# Difficulties encountered, challenges overcome, and lessons learned
 We learned the importance of utilizing RDC and RGT, and how to implement them in the different tools we used. In part 1, we utilized CSFRAT in order to convert the failure data provided into different graphs and models. For part 2, we utilized SRTAT to create RDC's and how the different variables, such as customer risk, developer risk, and failures per second manipulated it.
 
 Our group found difficulty using SRTAT for the relaibiilty growth testing section, thus we had to resort to using CSFRAT instead. 
# Comments/feedback on the lab itself
  This assignment was helpful in familiarizing ourselves with two techniques used in analysis of integration testing data. We were able to understand differences between Reliability Growth Testing and Reliability Demonstration Chart using testing tools such as CSFRAT and SRTAT. The assignment handout was easy to follow, giving instructions on how to use the testing tools in order to understand software reliability assesment.
