# ineuron_powerbi_assignment
# 1) List and explain different PowerBi products?
# Power BI Desktop

It is the main Power BI Application where an Analyst can connect application to multiple data sources and analyze data to create reports to business stakeholder. This product comes with free, pro and premium versions which costs accordingly. Free version doesn't allow analysts to share reports to other users.

# Power BI service

It is a product where stakeholders can get access to reports created by developers/Analyst to see performance of their business or whatever task assigned to the Team. stakeholders can get access to them oce analyst publishes them in the shared workspace. They can also create and modify dashboards of their own.

# Power BI Mobile

It is similar to Power BI Service. Stakeholders can access the reports and dashboards through Mobile/Tablet device and view them. It is meant only for viewing contents which means users can't create dashboards in this platform.

# 2. What limitations of Excel, Microsoft solved by PowerBi ?
The maximum number of rows and columns is limited in Excel. Power BI doesn't limit users on dimension of data.
Power BI exceeds Excel feature in Data sources. Power BI can get multiple static, dynamic and streaming data. There 80+ available data sources.
The charts and visualizations are much advanced and interactive in Power BI.
The analytical engine is Power BI is much more faster than Excel which can save hours in processing.
Power BI allows users to share reports and data and collaborate with organization where excel cannot.
# 3. Explain PowerQuery?
Power Query is the Heart of Power BI. Power Query Editor allows user to transform data and create queries in much faster way and load them to main window. Power BI allows a massive variety of ways to transform data. Power Query is just one piece of the suite of Power BI and Excel products from Microsoft.

These data transformations could include tasks like:

Remove columns, rows, blanks
Convert data types – text, numbers, dates
Split or merge columns
Sort & filter columns
Add calculated columns
Aggregate or summarize data
Find & replace text
Unpivot data to use for pivot tables
It is the mostly used tool by the analyst to get data and pre-process them to use it for final report. It is a must known skill for any developers to user power BI.

# 4. Explain PowerMap?
Power Map feature comes with Power BI as well as Excel from Microsoft. It is a data 3D-visualization tool that lets you map your data and plot more than a million rows of data visually on Bing maps in 3-D format. It is used to plot geo-spacial data in 3D mode. Based on a geographical location, the data can be highlighted.

# 5. How powerBi eliminated the need to host SharePoint Server on premises?
There has been a lot of buzz and questions around connecting your Office 365 tenant to data located on Premises. This is a common requirement and is now made possible with PowerBI.

Connecting to your data source is made possible with the Data Management Gateway(DMG) The awesome part of the DMG is that is makes the connection outside the firewall. That means, no reverse proxies, custom web services or firewalls to deal with!

Overall, there are few requirements and caveats that I encountered while setting up my demo environment. FYI, I set this up in under and hour, including the time is took to spin up a PowerBI trial.

The DMG must be installed on a non-SQL server in your on premises environment. I could not get anything to work on my SQL server so I am thinking this has to be done on a member server.
A new Gateway must be created via your bi admin center.
You must register the gateway with the on premises DMG client.
You can then store your credentials for the data sources on premises OR in the cloud. The benefit to storing the creds in the cloud is you can recover quicker from a system failure.
6. Explain the updates done in Power Bi Service(power BI 2.0) as compared to older version ?
Admin & governance
Email subscriptions access via Admin API
Allow sharing links to include your changes to the report
Announcing Public Preview of Hybrid Tables in Power BI Premium
Deployment pipelines: assign a workspace to all pipeline stages
