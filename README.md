# matplotlib-challenge
Python code uses Pandas and Matplotlib libraries to analyze real-world situation and dataset.

### Scenario

 As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. **The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens**. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

#### Summary Statistics Table

![image-20210522050303984](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522050303984.png)

#### Bar plot using both Pandas's and Matplotlib's shows  the number of total mice for each treatment regimen throughout the course of the study:

![image-20210522050422206](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522050422206.png)

![image-20210522050450741](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522050450741.png)

#### Pie charts plot using both Pandas's and Matplotlib's shows the distribution of female or male mice in the study:

![image-20210522050757052](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522050757052.png)![image-20210522050825323](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522050825323.png)



#### Using Matplotlib, generate a box and whisker plot of the final tumor volume for four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftaminand. Highlight any potential outliers in the plot by changing their color and style

#### ![image-20210522064304609](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522064304609.png)



#### Line plot of tumor volume vs. time point for a mouse treated with Capomulin:



![image-20210522070251494](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522070251494.png)



#### Scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen:

![image-20210522073059423](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522073059423.png)

![image-20210522081715323](C:\Users\franc\AppData\Roaming\Typora\typora-user-images\image-20210522081715323.png)



### OBSERVATIONS

* Although Capomulin and Ramicane results seem to be quite close, mice treated with Capomulin had tumor volumes that were not significantly smaller than Ramicane. One could believe both treatments could yield the same results. On the other hand Capomulin, did perform significantly better than Infubinol and Ceftaminand. 
* The results of the study can be considered reliable as it was very consistent. The percentage of female to male mice was almost identical. At the same time, each of Drug Regimens had about the same number of mice per drug. At the same time there was only one outlier in the subset of data. 
* Based on the Mouse Weight vs Average Tumor Volume tables, it is noticeable that the heavier mice had large tumors. This could lead one to believe the treatment (Drug Regimen) loses it's efficiency as the on larger mice. The linear regression seems to support this assumption.

