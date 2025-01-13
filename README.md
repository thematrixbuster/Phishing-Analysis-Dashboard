# Phishing-Analysis-Dashboard
This repository features a screenshot of a dashboard analyzing phishing threats targeting GreenWorld Foodmart. 

**Project Overview**

**The analysis revealed:**
Nearly 50% of analyzed URLs were phishing links.
57% of the company's web traffic was diverted to fraudulent sites, significantly impacting customer trust, security, and company operations.

Key insights were derived by analyzing attributes such as Safe Anchor, Link_in_Tags, Page Rank, Google Index, and Web Traffic. 
Using Power BI, Python (Jupyter Notebook), and Excel, we identified patterns and correlations to inform actionable cybersecurity recommendations.

**Key Features**

Interactive Dashboard: A Power BI dashboard visualizing phishing trends, web traffic vulnerabilities, and key indicators.
Comprehensive Analysis: Detailed exploratory data analysis, including metrics that distinguish phishing URLs from legitimate ones.

**Process:**
Data Collection & Cleaning:
-	Imported raw data into Excel and Python, removed duplicates, filtered unnecessary columns, and identified missing values.
-	Used Excel’s Remove Duplicates tool and Python’s drop_duplicates() method for consistency.
-	Consolidated relevant columns for analysis (e.g., Safe Anchor, Link_in_Tags, and Status).
  
**Exploratory Data Analysis:**
-	In Excel: Created pivot tables to summarize key metrics (e.g., average Safe Anchor and Links in Tags by status).
-	In Python: Calculated averages and percentages for phishing and legitimate URLs using Pandas and visualized patterns with Matplotlib.
-	Analyzed URL distributions across metrics like Page Rank, Google Index, and web traffic patterns.
•	Phishing Indicator Identification:
-	Identified patterns such as phishing URLs having lower Safe Anchor values (below 30.29) and Link-in-Tags (below 44), while legitimate URLs showed higher averages.
-	Analyzed Google Index numbers, revealing that 84% of URLs with a Google Index of "1" were phishing links.
-	Highlighted the disproportionate web traffic (57%) directed to phishing URLs.
  
**Visualization:**
-	Developed detailed dashboards in Power BI with KPIs, pie charts, and bar charts to showcase trends.
-	Enhanced visual storytelling by integrating Python-generated charts into Power BI.
  
**Key Outcomes:**
-	Established strong correlations between URL attributes and phishing risks, such as Page Rank "0" having a 96% phishing rate.
-	Delivered insights into traffic vulnerabilities and areas requiring security enhancement.

**Instrumentation**

Tools: Excel for data cleaning & analysis, Power BI for visualization, Jupyter Notebook for analysis.




**Actionable Insights:** 
1. Real-time Monitoring and Response:
•	Employ real-time monitoring tools to detect and respond to phishing attacks promptly.
•	Implement incident response plans to minimize the impact of successful attacks.
•	Focus on optimizing legitimate URLs with Google Index "1" and deprioritizing phishing-friendly parameters.

2. Enhanced URL Filtering:
•	Utilize Safe Anchor and Link_in_tags thresholds to flag suspicious URLs.
•	Implement robust URL filtering solutions to block malicious URLs and redirect users to legitimate websites.
•	Leverage AI-powered threat intelligence feeds to stay updated on the latest phishing techniques.

3. Proactive Customer Communication:
•	Transparent Communication: Regularly communicate with customers about potential phishing threats and the steps being taken to mitigate them.
•	Phishing Awareness Campaigns: Conduct awareness campaigns to educate customers about common phishing tactics and how to identify and avoid them.
•	Incident Response Communication: In the event of a significant phishing incident, provide timely updates to affected customers, outlining the steps taken to address the issue and protect their data.

4. Data-Driven Decision Making:
•	Continuously analyze website traffic data to identify emerging threats and adjust security measures accordingly.
•	Use data analytics to prioritize security efforts and allocate resources effectively.



This repository includes screenshots of the dashboard, an overview of the tools and techniques used, and the key insights derived from the analysis.
