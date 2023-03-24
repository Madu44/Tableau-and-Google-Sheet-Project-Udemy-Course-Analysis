# UDEMY COURSE ANALYSIS PROJECT
An Excel and Tableau project carried out during my Data Analyst training with EntryLevel. This happens to be my first case study project.

# PROJECT DESCRIPTION

**Situation:** I was given a real-world Udemy course dataset to work with, analyze their course revenue, and track their performance. 

**Task:** The purpose of this report was to identify where opportunities to increase revenue may lie. Data was collected for four different courses in a spreadsheet and combined into one spreadsheet for analysis. Data collected were Business Courses, Music Courses, Design Courses, and Web Development Courses. 

**Action:** I uploaded one of the course dataset in Google spreadsheet and appended the other three, I performed data cleaning, created pivot tables and charts in excel and finally created dashboard using Tableau Public for more visualizations. 

**Result:** From the report, Web Development courses has the highest number of subscribers and should be considered for increase in price especially at the Expert Level. Also, Graphics Design course at the Expert Level have the highest average reviews and the lowest average cost, hence, should be considered for cost increment too.

# THE PROBLEM

**What is the business problem?** The business problem is to Identify opportunities to increase Udemy's revenue and report on course performance to the CEO.

**How long do I have to work on this project?** I have to work on this project in less than 3 weeks.

**What data should be collected to understand this problem?** How should it be presented? Data on course revenue and performance from different topics should be collected. It should be presented through visualizations and insights on opportunities to increase revenue.

**What questions would I ask to better understand the business problem?** What are the current revenue and performance trends of courses? What are the most popular topics? How can revenue be increased without sacrificing course quality?


# DATA DESIGN

The Udemy course data collected was unclean. I removed the duplicates, and the blank cells, ensured my headers are well written, ensured that there is consistency in the data, and made sure all the columns matched. Below were the steps I used to clean the data;

**Duplicates:**  I removed duplicates from my spreadsheet (Google Sheets) with the ‘Remove Duplicate Function’ by selecting the entire datasheet by pressing the ctrl + A on my keyboard. Clicked on Data > Remove Duplicates. 

**Blank Cells:** This can create gaps in the data and can make the data inconsistent and dirty. I used the Filter Function to remove blank cells by selecting the entire sheet and clicking on Data > Create filter. I clicked on the filter icon at the top of one of the columns which look like an inverted pyramid. In the dropdown menu that appeared, I clicked on the ‘Clear’ which deselects the filters then I clicked on ‘Blanks’ after I clicked on ‘Clear’ in the previous step and clicked OK. All the blank rows were filtered out together and all the rows with data were hidden. Then I selected all the empty rows and deleted them. After deleting the blank rows, I now removed the filter by clicking on Data > Turn off Filter. The dataset was now free of blank rows. 

**Headers:** I ensured the headers are clear and concise by using underscores in between words. 

**Consistent Data:** In the dataset, I noticed that the Web Development subject title is not the same as the other subject titles. So, I used the Edit > Find and Replace function to make the web development subject consistent with the other subjects.

I used Google Sheets to create pivot tables and charts, then used Tableau Public for creating visualizations and dashboards not only because of its speed, and scalability, but also, it is the best tool to create visual answers to most of business questions, from bar charts to more complex visualization.


# FINDINGS

Web Development subjects have the highest total and an average number of subscribers (1,868,711 subscribers) which is 67.9% of the total subscribers while Musical Instrument subjects have the least number of subscribers (846,689 subscribers) accounting for 7.2% of total subscribers.
     
The most expensive courses are Web Development courses at the Intermediate Level while the least expensive web development courses are at the Expert Level. 

Graphics Design courses at the Expert Level have the highest average reviews and the lowest average cost.



### Figure 1: Percentage Subscriptions by Subject

![Fig 1](https://user-images.githubusercontent.com/127628021/227483810-7bb4c91a-0ac4-4d1a-aeee-8a1f3be01941.png)

Web Development courses has the highest percentage of subscribers (67.9%) followed by the Business Finance course (15.9). Musical Instrument subjects have the least subscribers accounting for 7.2% of the total subscribers.

### Figure 2: Cost by Skill Level

![fig 2](https://user-images.githubusercontent.com/127628021/227483992-b8253235-a9f1-402a-94f4-ddc40e3d3ffa.png)

Web Development courses are the most expensive courses especially at the Intermediate level. Graphics Design course at the Expert level is the least expensive course

### Figure 3: Average Reviews by Subjects

![fig 4](https://user-images.githubusercontent.com/127628021/227484133-a5cef5fe-1794-44b8-9124-cc74d64a72e0.png)

Web Development course has the highest Average reviews.

### Figure 4: Sum of Subscribers by Subject

![fig 5](https://user-images.githubusercontent.com/127628021/227484371-251a59b6-31c2-4497-80d1-d07018ea7396.png)

Web Development courses has 7,981,935 number of subscribers which is the highest. While Musical Instrument has the least number of subscribers 846,689

### Table 1: Average Subscribers by Subject

![table 1](https://user-images.githubusercontent.com/127628021/227485147-e56afaf1-e1f2-41a9-9b14-2ca8442b4904.png)

### Figure 5: Free/Paid Courses

![fig 3](https://user-images.githubusercontent.com/127628021/227485336-ec63b0f8-0fad-4543-a3af-8c1c2463dfce.png)


# ANALYSIS

**Root Cause Analysis (RCA):** Root cause analysis is the process of discovering the root causes of problems in order to identify appropriate solutions. The first goal of root cause analysis is to discover the root cause of the Udemy course problem. The second goal is to fully understand how to fix, compensate, or learn from any underlying issues within the root cause. The third goal is to apply what we learn from this analysis to systematically prevent future issues or to repeat successes.

We will use the 5 Whys technique to determine the root cause by repeatedly asking the question “Why”.

1. Why does Udemy want to increase their revenue? Because some courses generate low earnings.

2. Why does the business has low earnings on some courses? Because of low number of course subscribers.

3. Why are there low number of subscribers in some courses? Because they are low value courses

4. Why are there low value courses? Because the course creators may lack expertise or resources to create high-quality courses.

5. Why may course creators lack expertise or resources to create high-quality courses.? Because they may not have received proper training or guidance on how to create effective and engaging course content.


# CONCLUSION

In conclusion, Web Development is the most popular subject on Udemy with the highest number of subscribers and total revenue. In addition, we found that the most expensive Web Development courses are at the Intermediate Level while the least expensive are at the Expert Level. Furthermore, Graphics Design courses at the Expert Level have the highest average reviews and the lowest average cost.
Using the 5 Whys technique, I discovered that the root cause of low earnings on some courses is that they are low-value courses, which may be due to course creators lacking expertise or resources to create high-quality courses. This suggests that providing proper training and guidance to course creators on how to create effective and engaging course content could improve the value of courses and increase earnings for Udemy.

