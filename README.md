# Call center-Dashboard
<!DOCTYPE html>
<html lang="en">
<body>
    <header>
        <h1>Call Center Data Analysis</h1>
        <nav>
            <ul>
                <li><a href="https://us3.ca.analytics.ibm.com/bi/?perspective=dashboard&pathRef=.my_folders%2Fprojectcomplete&action=view&mode=dashboard&subView=model0000018fed11c2bc_00000006">Dashboard</a></li>
                <li><a href="https://www.spectrum.net/contact-us">Contact</a></li>
            </ul>
        </nav>
    </header>

### Dashboard Link : https://us3.ca.analytics.ibm.com/bi/?perspective=dashboard&pathRef=.my_folders%2Fprojectcomplete&action=view&mode=dashboard&subView=model0000018fed11c2bc_00000006


## Problem Statement

This is a project that combines an operational database model with IBM Cognos to analyze call center data in real-time. It enables businesses to monitor call volumes, agent performance, and customer satisfaction in real-time. The project aims to identify areas for improvement, optimize
resources, and enhance overall call center performance. By leveraging real-time insights, it helps businesses provide exceptional customer experiences, improve operational efficiency, and drive customer loyalty.

![Snap_1](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*5nA_vq6Ra7bow_CZyW4VeQ.jpeg)



### Key metrics to track

-Call volume: This metric tells you how many calls your call center receives each day, week, or month. It is important to track call volume so that you can make sure that you have enough agents to handle the workload.

-Average handle time: This metric tells you how long it takes your agents to handle each call. A long average handle time can indicate that your agents are not efficient, or that they are spending too much time on each call.

-Customer satisfaction: This metric tells you how satisfied your customers are with your call center service. It is important to track customer satisfaction so that you can identify areas where you can improve.

-SLA Compliance: Determine the percentage of interactions that fall within, below, or above the defined Service Level Agreement (SLA) response time.

-Channel Distribution: Examine the distribution of inquiries across different communication channels to identify popular channels.

Reason Analysis: Explore the most common reasons for customer inquiries, helping prioritize areas for improvement.

-Sentiment Analysis: Analyze customer sentiment to gauge overall satisfaction and identify trends in positive/negative feedback.

Geographic Insights: Evaluate call distribution across cities and states to identify potential regional issues or opportunities.

-Steps involved: Data Gathering, Data Cleaning, Data Manipulation, Data Analysis, Data Visualization

#### Data Gathering:

Meta data: This is a daily data for the month of October 2020 which contains 32942 rows and 12 columns, and the file extension is a .csv file.

![Snap_Count](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*mssz0epTQGWdm0Le3XA2wg.png)

        
 ##### Data Cleaning:

 Cleaning and preparing the data for analysis. This means removing any errors or outliers, and formatting the data in a way that makes it easy to analyze.

The column ‘call_timestamp’ had mixed formatting both text and date.
 
 ![Snap_Percentage](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*f7gnVATUqSx8pi0PhSR7sw.png)

Data Analysis:

Using Pivot tables and Basic Statistics, we calculated metrics like 


 
 ![Snap_3](https://ibmblueview.com/wp-content/uploads/2019/07/image-14-1024x520.png)
 





![Publish_Message](https://ibagroupit.com/wp-content/uploads/2020/05/ibm-cognos-analytics.png)
# Snapshot of Dashboard (IBM Cognos Analytics)

![dashboard_snapo](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*SD_I4AOh2lDfJDMGC_9gtQ.png)

# Insights

A single page report was created on IBM Cognos Desktop & it was then published to Cognos BI Service.

