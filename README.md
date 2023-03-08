# Cloud-Solution-Architecture-Project-for-Data-Lakes-and-Analytics-Solutions

<h2>
Deploying Workloads on AWS
</h2>

<p align="center">
<img src="https://github.com/kedibeki/Cloud-Solution-Architecture-Project-for-Data-Lakes-and-Analytics-Solutions/blob/main/Cover-%20Cloud%20Solution%20Architecture%20Project%20for%20Data%20Lakes%20and%20Analytic.jpg" alt=""/>
</p>

[Click On Here For My Full Presentation](https://github.com/kedibeki/Cloud-Solution-Architecture-Project-for-Data-Lakes-and-Analytics-Solutions/blob/main/Cloud%20Solution%20Architecture%20Project%20for%20Data%20Lakes%20and%20Analytics%20Solutions.pdf)
 
<h2>
Project Background:
</h2>

<h4>   
I’m working at a company that is planning to use Amazon Simple Storage Service (Amazon S3) as the storage layer for their data lake solution. Initially, the data that will be ingested into the data lake will come from three locations:
&nbsp;
 
Internet of Things (IoT) sensors that send real-time data
&nbsp;

A database with historical records
&nbsp;

Supplemental data from third-party entities for enriching internally generated data
&nbsp;

These components are currently running in the data center on physical servers. Currently, if a power outage occurred in the data center, all systems would be brought offline. Because of this issue (in addition to other benefits of the cloud), my customer wants to migrate all components to the cloud and, when possible, use AWS services to replace on-premises components.
</h4>

<h2>
What will I do as a Cloud Solutions Architect?
</h2>

<h4>
The company has tasked me with designing solutions for ingesting this data into their data lake, and each location (IoT sensors, database, and third party) will need its own ingestion solution.                                                                                                                            
&nbsp;

From there, I will need to also design a solution for how to clean or transform the data so that it can be analyzed. The company currently uses Apache Hadoop-based software. When possible, they prefer to use similar technologies in the cloud so that they don’t need to retrain their analytics team on too many new technologies at one time. 
&nbsp;

The company also has a requirement to create dashboards that show visual representations of the insights they derive from the data.
</h4>
