---
title: "Microsoft delivers best Analytics Data Pro Christmas gift since 1998"
date: 2020-12-24T13:38:30-04:00
categories:
  - architecture & design
  - learning & growth
tags:
  - skilling
---

Check out this past post from the Microsoft Data Architecture Blog in December 2020

![Microsoft delivers best Analytics](/assets/images/postimages/XmasGift/xmasgift.png)

Every December, is a great time to reflect on the past, evaluate and present, and postulate about the future.  Like in Charles Dickens “A Christmas Carol” with Ghosts of Christmas Past, Present, and Future but perhaps less scary - although 2020 has been a frightening year with Covid-19.  While the past and present related to Covid-19 includes staying home, wearing masks, social distancing, and frequent hand washing - hopefully the future is improving with more vaccines in market and the turn of another New Year.

In the world of Data Architecture and Analytics, the future looks very bright for Data Pros.  If you did not catch the Azure Synapse Analytics GA announcement earlier this month on Dec 3rd, 2020 please check out the digital event [Shape Your Future with Azure Data and Analytics](https://azuredataandanalytics2020.eventcore.com/).  The title chosen for the event was pretty significant in my opinion, because  Azure Synapse Analytics (and Azure Purview – will leave for a future post) will definitely shape the careers of Data professionals interested in Analytics for the next decade and beyond.  The basis of my prediction is supported mainly from past experience (27 years in the Data & AI space).  For me, the way Azure Synapse Analytics parallels the release of SQL Server 7.0 back in 1998 (known for its exemplary combination of BI and Data Warehousing capabilities) is a foretelling factor.  But for context let’s first visit the Analytics past, present, and future.

## Past:

Back in 1998, I was taking significant steps to create a healthcare claims and eligibility data mart for University of Washington Physicians.  Thanks to my manager at the time I was able to invest in SQL Server 7.0 for the data mart, Sagent for ETL, and Brio for reporting.  SQL Server was the data management platform that enabled me to be successful in my job and provided our team of data analysts with consolidated datasets that accelerated the decisions made affecting the managed care lives entrusted to UW Physicians.  SQL Server was the target for raw (load - bronze) claims and eligibility data from several health plans; the location (stage - silver) where Clinic and Physician identifiers could be consolidated; and the source (publish - gold) datasets for query and analysis by data analysts.   

I had started a Decision Support and Data Warehousing career 5 years prior using IBM DB2, and IBM Metaphor.  Unfortunately, those tools were expensive, niche, and narrowly adopted - I was not even sure that the Decision Support and Data Warehousing industry would take off and be a good career.  But SQL Server 7.0 started to make these tools mainstream and with the release of SQL Server 2000 and SQL Server 2005 the packaging of a relational database, an OLAP engine, and an ETL engine into a single offering helped make any Data Pro career in BI and Data Warehousing a reality over a 7 year span.  By the time I joined Microsoft in 2005, SQL Server had changed the BI and Data warehousing space forever with Integration Services, the Relational Database engine, Analysis Services, Data Mining, and Reporting Services.  In the 15 years since 2005, Microsoft has continued to leverage this pedigree in BI and Data Warehousing as the unit market leader in the BI and Data Warehousing space, while at the same time expanding its portfolio in both Big Data, and AI and Machine Learning.

So, in the era of client server computing SQL Server running in company data centers (or on a server next to my desk at UW Physicians) in my option drove the BI and Data Warehousing market forward.  It did this by providing tools and infrastructure (mentioned above) that the data professionals of the day (ETL Developer, OLAP Developer, DBA, and Report Developer) could build solutions with. 

## Present:

What does Microsoft have available today to help Data Engineers, Data Scientists, Data Analysts, and Data Officers (Data Owner, Data Stewards, Chief Data Officers)?  Do customers need these tools and are they prepared to employ these Data Pro roles?

![datasnowman](/assets/images/postimages/XmasGift/DataSnowmanModern.JPG)

Here are my GitHub at [https://github.com/DataSnowman](https://github.com/DataSnowman) where I focus on projects that focus on Data & Analytics.

Microsoft’s combination of industry leading Power BI and its complete offering of Cloud Analytics services on Azure has created an environment where the sky is the limit for any customer creating Analytics solutions in any industry.  Analytics has been changing broadly during the last 10 years with Big Data (Hadoop, Spark) and AI and Machine Learning bringing new skills and growth opportunities for Data Pro roles like Data Scientists, and Data Engineers.  The market for Data Pro roles seams very strong.  For example, in the recent [KD nuggets post Introduction to Data Engineering](https://www.kdnuggets.com/2020/12/introduction-data-engineering.html) Xinran Waibel points out the recently published [Dice 2020 Tech Job Report](https://techhub.dice.com/Dice-2020-Tech-Job-Report.html), which reports that data engineer was the fastest-growing tech occupation in 2019, with a 50% year-over-year growth in the number of open job positions.  The report showed Data Scientist as the 3rd fastest-growing tech occupation.

Azure Synapse Analytics is poised to do the same with the Cloud Data and Analytics market as SQL Server did for the on-premises BI and Data Warehousing market between 1998 and 2008.  Only I think it is going to happen way faster because of Azure.  What has Azure Synapse Analytics done to make it compelling for organizations to migrate existing Data Warehouses, or build new Big Data and Data Warehouses solutions on Azure?  Synapse unifies Data Integration, Big Data, and Data Warehousing.

![bizchanging](/assets/images/postimages/XmasGift/BusinessChangingInsightsEngine.jpg)

Synapse also integrates with Power BI, Azure Machine Learning, and Azure Data Share.For me the unification of Data Integration (Azure Data Factory), SQL, and Spark is what makes Synapse special.  Data Engineers can use Data Integration data flows which use Spark job clusters for transformation at scale, and/or Spark Notebook activities can be used as part of data integration pipelines, and pipelines can sink to Azure Data Lake Storage (ADLS) or persistent dedicated SQL Pools.

![synapsel100](/assets/images/postimages/XmasGift/synapseL100.jpg)

External tables can be created on files in ADLS and queried with Transact-SQL using serverless on-demand queries.  Queries can be run against dedicated SQL Pools.  Spark Notebooks can access files (Json, Parquet, CSV) on ADLS storage using PySpark, Scala, Spark SQL, Java, and .Net

![synapsel300](/assets/images/postimages/XmasGift/synapseL300.jpg)

How can you use Azure Synapse Analytics to develop your skills as a Data professional?  Start using it and practice, practice, practice!  Rebecca Sealfon recently mentioned the important of practicing in the towards data science article [Learning Data Science Online Without an Instructor: Tips and Tricks](https://towardsdatascience.com/learning-data-science-online-without-an-instructor-tips-and-tricks-5e15fb886333) “Without intensively practicing, there is no way to gain the experience to become a professional.”  This article was focused on learning Data Science, but all Analytics Data Pro roles need to practice.  Each of these roles tend to do similar categories of work related to capture, curation, and consumption of data throughout the data lifecycle.  The relationships between roles can range from complementary/interdependent to competitive/independent.  For me the Synapse Analytics Studio offers potential for cooperation to win the day, but Azure provides plenty of flexibility that is palatable to any organizational structure (Department, Organization, Enterprise).

| Data Pro Role | Capture | Curate | Consume |
|---------------|---------|--------|---------|
| Data Engineers | Source/Extract | Pipelines/Data flows / Transform (Bronze, Silver, Gold) | Sink / Load / Query ADLS and Database |
| Data Scientists | Datasets | Wrangle/Experiment/Build and Test AI & ML Models | Predict/Score/Inference |
| Data Analysts | Query | Load/Transform/Data Model | Analyze/Visualize |
| Data Officers | Map | Catalog | Access (Compliance) |

![aimlbi](/assets/images/postimages/XmasGift/AnalyticsAI-ML-BI.jpg)

**Note:** You can utilize the 3C’s taxonomy above to look at the offerings and marketectures of other vendors in the space like Snowflakes Compile, View, Analyze and Share data or Databricks Data Lake / Delta Lake: Ingest (bronze), Refine (silver), Feature/Aggregate (gold) data.  The Bronze, Silver, and Gold labels of today were the pasts Load, Stage, and Publish.  It just used to be different network storage landing zones, combined with tables, schemas, and databases.  Now you can still do the same as the past with cloud storage and databases or embrace a modern architecture that leverages ADLS storage and Spark to create Data Lake or Delta Lake solutions.  Synapse embraces Data Lake, Delta Lake, and Data Warehouse.  I love curated data lakes and serverless OnDemand SQL with Synapse.  I developed my affection based on work I have been doing supporting the Stanford CATCH Study [https://catchstudy.stanford.edu/](https://catchstudy.stanford.edu/) .  Working with the team at Stanford has been my opportunity to practice, and you really do need a project to ignite your potential and show what Synapse and some talented customers can accomplish.

**Future:**

When 2021 starts in a week, Synapse is going to be my jam!  Azure Synapse Analytics, with Power BI, and Azure Machine Learning along with your Data Pro talents will accomplish amazing things in 2021.  Just start practicing to ignite your potential.

Stay safe!
Happy Holidays
Best Wishes in 2021

Checkout this Spotify playlist [DataSnowmanChristmas2020Top100](https://open.spotify.com/playlist/7wzQG4q57NQQ5EPrkQsp8M?si=EuQLyBZ_TxSiZBKxCCOy5g)