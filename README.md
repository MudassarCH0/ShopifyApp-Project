
***Table of Content***<br>

* Description
* Tools & Data
* Execution
* Result
* Recommendation
* Project Link  

\
***Description***<br>

Project involved review for landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites. The goal was to figure out what are the key factors that play into the success of a Shopify app.   

\
***Tools & Data***<br>

* Tools
  * Power BI
* Data
  * apps: Details of the apps on Shopify apps marketplace
  * apps_categories: Join tables to connect apps with categories
  * categories: Categories of the apps. Each app has multiple categories
  * reviews: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present 
 

\
***Execution***<br>

* Data Processing: explore data, backup data, filter, DAX calculation, data visualization mockups
* Key Performance Indicators (KPIs): number of apps, total reviews, average reviews, average rating, sum of rating, review per developer, developer responsiveness, App reviews count
* Visualization: KPI card, Line Chart, Scatterplot, Bar Chart
* Process: found types of apps that are out there, created DAX column with review weigh values, DAX column with average developer review values, new table with many-to-one, filter to
  select review count greater than 500

\
***Result***<br>

* Most apps ratings were between 4 to 5 ratings with few outliners
* Average review weigh was 5.48
* Apps reviews and ratings showed correlation
* Weekly review count stayed around 25K<br><br>


![image](https://github.com/user-attachments/assets/8195736f-cf27-444c-9b1d-49662891d00a)


\
***Recomnendation***<br>
* Apps with review count around 5K have greater success on the platform
* Apps with rating count of 4 or more will be successful on the platform
* To measure success new apps should have built-in weekly review and rating count mechanism <br><br> 

> [!Note]
> [Project Link](https://app.powerbi.com/links/9krEHbu_8-?ctid=ce93940e-3941-4cfe-8621-96d0e849135e&pbi_source=linkShare)
