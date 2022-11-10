# PwC PowerBI Experience-01 Call-Center Trends Analysis

I participated in the open-access PwC Data Analytics Virtual Experience Program with Forage. Where I worked as a business data analyst to help an organization named “PhoneNow” to analyze their data and help them understand how they can leverage on their massive amount of data.

Live interact Dashboard on [NovyPro Link](https://www.novypro.com/project/i-participated-in-the-open-access-pwc-data-analytics-virtual-experience-program-with-forage-where-i-worked-as-a-business-data-analyst-to-help-an-organization-named-%E2%80%9Cphonenow%E2%80%9D-to-analyze-their-data-and-help-them-understand-how-they-can-leverage-on)

I worked on this project by following the Pwc virtual Experience on power BI at Forage [Link here](https://www.theforage.com/virtual-internships/prototype/a87GpgE6tiku7q3gu/Power%20BI%20in%20Data%20Analytics?ref=4waMNg8ejozso67A7)

## Project Overview & Business Problem

- Client’s Name: PhoneNow

- Client’s Industry: Telecom Company

I am working as a data analyst intern for PwC Switzerland when one of our important clients, a big telecom company reach out to me, to help visualize their data. Claire, the call center manager at PhoneNow wants me to help bring out insight from their call center data, she wants to know the total number of calls answered and abandoned, speed of answer, length of calls, overall customer satisfaction, and most importantly, she’s interested in knowing the accurate overview of long-term trends in customers and agent’s behavior.

### Request mail

<p align="center">
    <img src='https://github.com/rajeshkumar1312/PwC-PowerBI-Experience-01-Call-Center-Trends-Analysis./blob/main/Pwc%20call%20centre%20Email%20image.png' height="400">
</p>

From Claire’s mail, her KPIs includes (but not limited to):

- Overall customer satisfaction
- Overall calls answered and abandoned
- Calls by time
- Average speed of answer
- Agents performance quadrant.

### Tools Used to Carry Out This Project

- Microsoft Excel: which I used primarily to convert the data into a proper table.

- Microsoft PowerBI: As a PowerBI specialist, I carried out my data cleaning using the power query editor in PowerBI. I also carried out the visualization showing my insights (focusing on my KPIs) using the Data Analysis Expression (DAX) language for creating and calculating columns, measures and custom tables.

### Data Cleaning Process
- Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect, incomplete, irrelevant, duplicate, or improperly formatted.

- Data cleaning plays an important role in the analytical process by making sure that the answers we uncover are reliable, accurate, and of high quality.

- Below are the data cleaning process I carried out using the power query editor in PowerBI:

- I started by importing my data from Excel into PowerBi, however, instead of loading my data directly for visualization, I transform the data by loading it into the power query editor for cleaning.

- One of the reasons why we do data cleaning is to remove incomplete data. However, looking at my data, the incomplete data (Null) have values they represent i.e. they are related to either calls that are not answered (N) or calls that the agents are not able to resolve, hence, removing those data will limited the accuracy of my data and in turn the credibility of my analysis.

### Analysis & Insight

- One of the important insights that Claire, the call center manager wants to know is the overall customer satisfaction score (CSAT), which means how satisfied customers are with there business. This was calculated by diving the positive rating (in this case 4 – 5 ratings) by the total number of responses and multiplying the answer by 100. To get my positive responses, I created a conditional column that only consist of 4 -5 ratings (positive).After all the calculation, the overall customer satisfaction score (CSAT) is 49.90%.

- The call center has 8 agents in total. With Jim having the highest total rating at 1819 and Joi with the lowest at 1612.

- From the total of 5000 calls that came in, the agents were able to answered 4054 calls indicating that 946 were abandoned.

- Out of the 4054 calls answered, the agents were able to resolved 3646 of the problem (customer concern) while they were not able to resolve those issues 408 times.

- The agents average speed of answering calls was 67.52 seconds.

- The peak time of the call center are 11:55 am and 3:21 pm, 30 calls always comes in by these times.

## Overall Visualization.

<p align="center">
    <img src='https://github.com/rajeshkumar1312/PwC-PowerBI-Experience-01-Call-Center-Trends-Analysis./blob/main/Pwc%20Virtual%20intern%20(%20call%20centre)%20image.png' height="400">
</p>

### Recommendations

- With only 49.90% of the customer being satisfied, the call center needs to invest in training the agents and most importantly, organize meetings with the agents to understand (and provide solutions) to the problems they might be facing. 49.9% CSAT is very bad for the business.

- Out of every 10 calls that came in, the agents abandoned 1, this can be improved on. I will suggest employing 1 or 2 more agent.

- With 408 issues not being able to be resolved, this indicates that the agents need more knowledge about the business / and its different services. I will advise the management to organize a workshop for the agents.




