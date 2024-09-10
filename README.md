# 2024-Data Analyst References 
Helpful resources to come back to for Tech-Moms Data Analytics class. 
The resources used throughout the course in the fall of 2024.  

## Helpful Web Links
[https://www.geeksforgeeks.org/data-analysis-tutorial/](url)
This website provides the basic definitions of data types and the processing cycle. 
-Statistical Data
-Machine Learning
-Data Mining
-Data Visualization

[https://www.youtube.com/watch?v=ShBTJrdioLo](url) YouTube: 10 Important Formulas

Average: Random numbers, find the average =Average(highlighted data to average)  
Sum: =SUM(highlighted data)  also =SUM(100+200+300) numeric range only
SUMIF: selected sum, certain element only. =SUMIF(range (first column sort),name of thing sorting, name of thing counting.  
Formula looks like:=SUMIF(B2:B11,B14(click the cell you want a name for),C2:C11)
			=SumIf(B2:B11,B14,C2:C11) 	
You need two things, first: like car type: a column of names to sort, 
=Count() only counts numbers
=COUNTA() counts any non-empty data like dates, letters and so on. 


## Alex the Analyst: Data Analyst Boot Camp 
### Excel YouTube videos from class
[https://www.youtube.com/watch?v=PSNXoAs2FtQ&t=22498s](url) **Excel: Data Cleaning**

[https://www.youtube.com/watch?v=PSNXoAs2FtQ&t=17175s](url) **Excel: Formulas** 

[https://www.youtube.com/watch?v=PSNXoAs2FtQ&t=16121s](url) **Excel Pivot Tables**

[https://www.youtube.com/watch?v=PSNXoAs2FtQ&t=21589s](url) **Excel Charts**

[https://www.youtube.com/watch?v=PSNXoAs2FtQ&t=23762s](url) **Holy Grail: Excel Dashboards** 


**Writing/Formatting on GitHub** _So helpful. I printed this off for reference so I could flip back and forth on paper while editing on GitHub._ 
[https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github](url)

**GitHub Tables/Images/Quotes** how to set up your README files.
[https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github](url)

## Helpful Articles

## Helpful Videos
**Pluralsight Video,** skills learning. _Fundamentals of Data Storytelling,_ by **Renganathan Padmanabhan**
[https://app.pluralsight.com/library/courses/fundamentals-data-storytelling/table-of-contents](url)

**Basic Summary** Explain how data flows through a company. What measurements **KPI** are gathered, and how will others understand and visualize the data?
- 	Information Collected
- 	Categorize Data 
- 	Cleanse Data 
- 	Fill in the Gaps
- 	Transform and Format

_Different People look at the **same data** and come to **different** conclusions._

- 1)What's the Motivation?
- 2)What's the Challenge?
- 3)Do they understand the data? 
- 4)How do they take action?

 _YouTube Influencer_ **Alex the Analyst** sharing his personal advice on what he would do to become a Data Analyst now. 
  [https://www.youtube.com/watch?v=K0-8G3DgjA4](url)
 
## Helpful Books 

  ***May Contain Lies, by Alex Edmans*** 
  
  **Basic Summary**- don't trust the numbers; people generally fall back on their biases, and the data supports their thoughts and feelings. He's pretty _snarky_ and pokes holes in many theories of books I've previously **read and enjoyed**. He definitely is not a Malcolm Gladwell, Angela Duckworth, or Amy Cuddy fan. He encourages folks to use _critical thinking_ by asking people to measure what data they are being presented. 
- A Statement is Not Fact
- A Fact is Not Data
- Data is Not Evidence: Data Mining
- Data is Not Evidence: Causation
- When Data is Evidence
- Evidence is Not Proof
_Can this statement have another explanation? Can this story be interchangeable?_ 

Was it **worth** the _listen_? He's snarky and condescending, with a lovely English accent. His insight is interesting, but at the end of the day, I may be interested in facts and solid data, but most people are not. I think they'll continue listening and following misinformation and made-up facts. 


***Storytelling with data, by Cole Nussbaumer***

**Basic Summary** A job candidate's proficiency with Microsoft Office is the bare minimum. You need to be able to tell the story with the data.
	- Who is the audience? (background, biases, decision makers. Risks- don't forget to talk risks, people don't believe a Cinderella story) 
 	- What do you need them to know?
 	- What do you need to know abt them, communication, and tone being considered?
  	- Ask for action; how will they get to a decision that makes them react? 
  	- How can you use data to make your point? 
  	- What types of visuals will be used, text, tables, heat maps, graphs, charts? **AVOID pie, donut and 3-D charts**
Plan a single sentence to tell the audience to grab their attention, if you get cut short make sure your story can be said in 3 mins or less. 
3 min story, your point of view and what's at stake, make it a complete statement. 
Storyboard visually draw it out with sticky notes or pen and paper, don't use electronics. (Funny point: she says you get attached to your electronic work and can't let it go; don't wanna waste your effort.)
    Graph decisions include how to use them, the thickness of lines, color, and size, as well as their position on the page. Keep things simple and clutter-free.
    Think like a designer; draw your audience to the story you want them to see.

    **Exploratory analysis** is the hunt, looking for good data that's interesting. You may only find two interesting/supportive details in this phase. Don't show empty finds; nobody cares.
    **Explanatory analysis** the specific thing you found to support your story. This may be the two things out of one hundred things you found. 
Keep your slides simple and clean. 

Once you have your audience in mind, you can move to the data,_What data is available to help me speak the point to the audience?_	
    
### Books to Explore in the Future.

***Data Points, Nathan Yau*** discusses the data and how to explore and analyze it. 

***Resonate, Nancy Duarte*** think of the audience as the hero, get to know them and find common ground. She has a free version on [duarte.com](url) 



# SQL _(Structured Query Language)_ is a system built to query and manipulate data. It allows users to manipulate data that is essential for data analysis and reporting. **Sally SQL** only speaks to _Relational Databases_, by using rows and columns searches.   
	•	Select: retrieve data * all columns & all rows,
	•	Top number 
	•	Distinct values (gender,ID)
	•	Count (Lastname)
	•	AS() allows you to name something 
	•	MAX(Salary)
	•	Min()
	•	Avg()
**FROM-Database-Table**
**SELECT**: * includes all
**FROM**:
**WHERE**: (usually includes text information)
	**SELECT * FROM employees WHERE department = 'Sales';**   
 	=< will include the specific number and above in your query. 
	< will include the number of people above this number
	**Where**: filter data and return only the row that meets the specific criteria. Limit data.
The WHERE clause can use operators like **=, >, <, <does not equal>, LIKE, OR, Null, Not Null, AND, IN  */  %** (wildcard) to define the conditions.
**GROUP BY**: groups rows that have the same values in specified columns, often used with aggregate functions like COUNT, SUM, or AVG 
**ORDER BY**: clause sorts the query results based on specified columns, either in ascending (ASC) or descending (DESC) order. For example, ORDER BY salary DESC, can use the row number instead of the column number.
Aggregation functions: **COUNT, SUM, AVG** to summarize information. 

## Helpful SQL WEBLINKS

[sqlbolt.com](url)

[deepnote.com](url)

[https://www.youtube.com/watch?v=h0nxCDiD-zg](url) 
YouTube ***Kevin Stratvert: SQL Tutorial for Beginners (youtube.com)*** 
Retrieve data from databases to get information and hidden insights.
A database is a collection of tables that have a relationship. 
Helpful hint: _Design Query_ in **Editor*: Right Click or (Control Shift Q), choose Tables to pull data from, ADD & Close. Columns within Tables. 
Auto writes the SQL statements for SELECT & FROM, FILTER provides WHERE & GROUP BY

