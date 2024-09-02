# **Cost Dashboard**

## **Alignment to account structures** 

![Alignment to account structures](images/Cost%20Dashboard/Alignment%20to%20account%20structures/1.1.png)
![Alignment to account structures](images/Cost%20Dashboard/Alignment%20to%20account%20structures/1.2.png)

Tevico supports the onboarding of organizational account and allows for the integration of multiple child accounts i.e. Within the main organizational account, you can integrate multiple child accounts.  
A dropdown menu is available for both the accounts and region to easily select and switch between different AWS accounts/regions.

## **Cost Summary** 

**1\. Account Consumption**

![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/1.1.png)

- **Month-To-Date Balance** : This shows the current amortized "month-to-date" balance. Amortized means reflecting the effective cost of the upfront and monthly fees spread across the billing period.  
- **Last Month :** The amount spent last month.  
- **Forecast :** Shows the account consumption for the current month and estimates that the account consumption for this month which is anticipated to be less/more than what was consumed last month.

**2\. Services Used**

![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/2.1.png)

- **Last Month :** This shows the number of services used in the last month  
- **This Month :** This shows the number of services used in the current month.  
- **Top Spending Service :** This shows top spent AWS service in the current month.  
  For detailed information on the services used last month that were not utilized this month,   
  \- Click on "**View All**".  
    
![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/2.2.png)

     
- **Services Used :** This shows the name of the AWS Service/tool.  
- **Accounts Count :** This shows the number of accounts used by AWS Service/tool.  
- **Last Month :** This shows whether the AWS Service/tool is used ( ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/correct_sign.png) ) or not ( ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/wrong_sign.png) ) in the previous month.  
- **Current Month :** This shows whether the AWS Service/tool is used ( ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/correct_sign.png) ) or not ( ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/wrong_sign.png) ) in the current month.

**3\. Accounts Used**

![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/3.1.png)

- **Last Month :** This shows the number of accounts used in the last month.  
- **This Month :** This shows the number of accounts  used in the current month.  
- **Top Spending Service :** This shows the top spent account including the amount spent in the current month.

**4\. By Region \- Top five cost-incurring regions** 

![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/4.1.png)

- **Pie Chart :** This shows a graphical representation(pie chart) of the top 5 regions and the amount they spent. You can view it for the previous month and also for Month-to-Date ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/MTD.png).  
- **Region with the maximum spend** : This shows the region with the maximum spend and the amount spent.


Click on "**View All**", for detailed information Spend by every region, you can view it for the previous month and also for Month-to-Date ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/MTD.png). 

![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/4.4.png)

**5\. By Service \- Top five cost-incurring services**

![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/5.1.png)

This section displays an overview of costs incurred by the top 5 AWS Services in the workload and can view the information for the previous month as well as for the current month-to-date ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/MTD.png).

- **Service :** This section shows the name of the service.  
- **Cost :** This section shows the cost incurred for each service.

Click on “**View All**”, To view a detailed breakdown of all AWS services and their associated spending.

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/5.3.png)

**6\. By Accounts \- Top five cost-incurring accounts**

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/6.1.png)

- **Bar chart**: The bar chart displays an overview of costs incurred by the top 5 AWS accounts in the workload.  
  You can view the information for the previous month as well as for the current month-to-date ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/MTD.png).

Click on “View All”, To view a detailed breakdown of all AWS accounts and their associated spending.

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/6.3.png)

**7\. Invoice Trend \- Get the newest insights on invoice trends within a timeframe**

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/7.1.png)

This section shows a graphical representation of the "Invoice Trend" over the last three months using both a bar graph and a line graph. 

- **Invoice Trend :** This highlights the percentage change in invoice amounts between consecutive months.

Click on “View All”, To view a detailed breakdown of all AWS accounts and their associated spending.  
You can view the information for 3 months, 6 months, 9 months ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/3-6-9-months-timeframe.png).

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/7.3.png)

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/7.4.png)

 ![Cost Summary](images/Cost%20Dashboard/Cost%20Summary/7.5.png)

## **Cost Analysis** 

**1\. Total Usage Graph**

 ![Cost Analysis](images/Cost%20Dashboard/Cost%20Analysis/1.1.png)

- **Total Usage Graph :** This section shows a graphical representation of the AWS services spent over a time period. The costs are broken down by top five/ top 10 / top 15 AWS services/accounts.  
  The time periods include 1 week (1W), 2 weeks (2W), 1 month (1M), 3 months (3M), 6 months (6M), 1 year (1Y), month to date (MTD), and year to date (YTD).  
  The graph is set to show spending by service or per account. ![Cost Analysis](images/Cost%20Dashboard/Cost%20Analysis/tabOption-acc-service.png)

 ![Cost Analysis](images/Cost%20Dashboard/Cost%20Analysis/1.3.png)

**2\. Daily Cost Trend**

 ![Cost Analysis](images/Cost%20Dashboard/Cost%20Analysis/2.1.png)

- **Daily Cost Trend** : This section shows a graphical representation( line graph ) of daily cost trends.  
  The time periods include 1 week (1W), 2 weeks (2W), 1 month (1M), 3 months (3M), 6 months (6M), 1 year (1Y), month to date (MTD), and year to date (YTD).

## **Resource Right Sizing** 

**1\.  EC2 Compute Optimization** 

 ![Resource Right Sizing](images/Cost%20Dashboard/Resource%20Right%20Sizing/1.1.png)

- **Total :** This shows the total number of Elastic computes present in the account.  
- **Over Provisioned :** This shows the number of EC2s that are over provisioned.  
- **Under Provisioned :** This shows the number of EC2s that are under provisioned.  
- **Optimized** **:** This shows the number of EC2s that are optimized.  
  Additionally a stacked bar chart is provided to visually represent EC2 Compute Optimization. This chart will assist you in identifying areas for cost optimization and implementing recommendations to reduce expenses.

Click on “**View All**”, To view all EC2 Right-Sizing Recommendations and can export the data in CSV/Excel by clicking on the “Export”. ![Resource Right Sizing](images/Cost%20Dashboard/Resource%20Right%20Sizing/export-button.png)

 ![Resource Right Sizing](images/Cost%20Dashboard/Resource%20Right%20Sizing/1.3.png)

**2\. EBS Volumes Optimization**

 ![Resource Right Sizing](images/Cost%20Dashboard/Resource%20Right%20Sizing/2.1.png)

- **Total Volumes** : This shows the total number of EBS Volumes present in the account.  
- **Attached** :  This shows the number of EBS volumes attached to the EC2s.  
- **Unattached** :  This shows the number of EBS volumes unattached to the EC2s.  
  Additionally a bar chart is provided to visually represent the EBS optimization status, aiding in identifying areas for improvement and cost reduction.  
  The optimization levels are follows :  
  \< 40%: Not Optimized (Red)  
  40-70%: Optimized (Yellow)  
  \> 70%: Highly Optimized (Green)

**3\. EBS Operations Cost** 

 ![Resource Right Sizing](images/Cost%20Dashboard/Resource%20Right%20Sizing/3.1.png)

- A bar graph for visual representation is provided to represent the EBS (Elastic Block Store) operations costs over a week, highlighting the most and least cost-consuming operations.  
- Each bar represents the total cost of these operations for each day, with the height of each color segment showing the respective operation's cost contribution.  
- This section helps in identifying which EBS operations are the most and least expensive over the specified time frame.  
- The time periods include 1 week (1W), 2 weeks (2W), 1 month (1M), 3 months (3M), 6 months (6M), 1 year (1Y), month to date (MTD), and year to date (YTD).

## **EC2 Coverage**  

**1\. Cost Distribution EC2 Compute**

 ![EC2 Coverage](images/Cost%20Dashboard/EC2%20Coverage/1.1.png)

- **Total** : This shows the total cost incurred by the EC2s present in the account over the specified time frame.  
- **Spot** :  This shows the cost incurred by the Spot instances in the account over the specified time frame.  
- **On-Demand** :  This shows the cost incurred by the On \- Demand instances in the account over the specified time frame.  
- **Reserved** :  This shows the cost incurred by the Reserved instances in the account over the specified time frame.  
  The time periods include Last 7 days, Last 14 days, Last 1 month (selected), Last 3 months, Last 6 months, Last 1 year, MTD, and YTD.  
  Additionally a stacked bar chart is provided to visually represent the cost distribution of different types of EC2 instances, helping to identify areas for cost optimization. 

**2\. Cost Distribution EC2 Processors**

 ![EC2 Coverage](images/Cost%20Dashboard/EC2%20Coverage/2.1.png)

- **Total** : This shows the total cost incurred by the EC2 processors present in the account over the specified time frame.  
- **AMD** :  This shows the cost incurred by the AMD processor  in the account over the specified time frame.  
- **Graviton** :  This shows the cost incurred by the Graviton processor in the account over the specified time frame.  
- **Intel** :  This shows the cost incurred by the Intel processor in the account over the specified time frame.  
  Additionally a stacked bar for visual representation of the cost distribution of different types of EC2 instances.   
  Purple: Spot, Pink: On-Demand, Blue: Reserved.

## **Cost Comparison** 

**1\. By Service**

 ![Cost Comparison](images/Cost%20Dashboard/Cost%20Comparison/1.1.png)

- **Services used :** This column shows the name of AWS service/tool over the specified time frame.  
- **Column 2** : This column shows the cost incurred by the AWS service/tool over the specified time frame.(Week 1 / Month 2).  
- **Column 3 :** This column shows the cost incurred by the AWS service/tool over the specified time frame.(Week 2 / Month 2).  
  The time periods include Weekly, Monthly, and MTD.  
- **Change(%) :**  This column shows the cost difference for each service between the two time periods. It displays the absolute change in dollars, followed by the percentage change relative to the cost in the first period.

**NOTE:** Cost comparison will be available when at least 2 months of data is available.

Click on "**View All**" to see all the AWS services and their associated costs in the account.

 ![Cost Comparison](images/Cost%20Dashboard/Cost%20Comparison/1.2.png)

## **Tag Explorer**  

 ![Tag Explorer](images/Cost%20Dashboard/Tag%20Explorer/1.1.png)

- **Total Resources :** This shows the total number of resources associated with the account.  
- **Tagged Resources :** This shows the number of tagged resources  along with the percentage.  
- **Untagged Resources :** This shows the number of untagged resources associated with the account.  
  Additionally a pie chart is used for visual representation of the Tagged and Untagged resources.


Click on “**View All**”, to view All/Tagged/Untagged resources and their Resource, Service Name, Tag Details, Tagged Status, Cost.

 ![Tag Explorer](images/Cost%20Dashboard/Tag%20Explorer/1.2.png)

You can also download the report in CSV format by, clicking on the ![][image85]icon.

**2\. Resource Cost Distribution**

 ![Tag Explorer](images/Cost%20Dashboard/Tag%20Explorer/2.1.png)

- **Total Cost of Resources :** This shows the total amount spent on AWS resources.  
- **Cost Distribution by Tag Status:** This shows the cost incurred by tagged and untagged resources.

Click on “**View**”, to view how costs are incurred by Cost Distribution Tag Keys/ Cost Distribution of Untagged Resources By Service can be viewed either by tag/service.

 ![Tag Explorer](images/Cost%20Dashboard/Tag%20Explorer/2.2.png)

 ![Tag Explorer](images/Cost%20Dashboard/Tag%20Explorer/2.3.png)

## **AWS Budget**  

 ![AWS Budget](images/Cost%20Dashboard/AWS%20Budget/1.1.png)

- **Budget :** This section shows the budget set for the AWS service.  
- **Spent :** This shows the amount spent by the AWS service.  
- **Spare**: This shows the remaining budget.

To create custom budget, Click on “Add Custom Budget”  ![AWS Budget](images/Cost%20Dashboard/AWS%20Budget/1.2.png).

 ![AWS Budget](images/Cost%20Dashboard/AWS%20Budget/1.3.png)

 ![AWS Budget](images/Cost%20Dashboard/AWS%20Budget/1.4.png)

- **Budget Name:** A mandatory field where you enter the name of the budget you're creating.  
- **Service List:** This dropdown allows you to select specific AWS services that you want to include in the budget.   
- **Budget Limit:** A mandatory field where you set the maximum amount (in currency) that you want to allocate for the budget.  
- **Granularity:** This dropdown likely allows you to select the time period over which the budget applies, such as daily, monthly, or yearly.  
- **Set Alerts:** Here, you can configure notifications that will be sent out when certain thresholds of your budget are reached.

 ![AWS Budget](images/Cost%20Dashboard/AWS%20Budget/1.5.png)


## **Analytics** 

**1\. Amazon Athena Cost**

 ![Analytics](images/Cost%20Dashboard/Analytics/1.1.png)

- The “**Amazon Athena Cost**” pie chart provides a visual representation representing the costs associated with AWS Athena.   
  You can select based on Account/ Usage type and different timeframes to view and analyze these costs.  
  The time frames include 1 month and month to date (MTD).

**2\. AWS Glue Cost**

 ![Analytics](images/Cost%20Dashboard/Analytics/2.1.png)

- The "**AWS Glue Cost**" pie chart provides a visual representation of the cost associated with AWS Glue service for a specific account.  
  You can select based on Account/ Usage type and different timeframes to view and analyze these costs.  
  The time frames include 1 month and month to date (MTD).

## **Database**

**1\. Database Services Cost**

 ![Database](images/Cost%20Dashboard/Database/1.1.png)

- The **"Database Services Cost"** pie chart provides a visual representation of the total cost associated with database services like Amazon Relational Database Service (RDS) and Amazon ElastiCache and can view it daily by selecting 1M /month to date (MTD). ![Database](images/Cost%20Dashboard/Database/MTD.png)

**2\. Database Cost Trend**

 ![Database](images/Cost%20Dashboard/Database/2.1.png)

- The **“Database Cost Trend”** graph provides a visual representation into the cost trends associated with database services and can view it daily by selecting 1M /month to date (MTD) ![Database](images/Cost%20Dashboard/Database/MTD.png).  
- **X-Axis (Dates):** The horizontal axis represents dates within the month and each date corresponds to a daily measurement point.  
- **Y-Axis (Cost in Dollars):** The vertical axis represents cost values in dollars.

## **Compute** 

**1\. Spend on EC2 By Accounts**

 ![Compute](images/Cost%20Dashboard/Compute/1.1.png)

The **"Spend on EC2 By Accounts"** pie chart visually represents spending related to Amazon Elastic Compute Cloud (EC2) by top five/ top 10 / top 15 AWS accounts.

**2\. Spend on Top 10 EC2 Instances By Accounts**

 ![Compute](images/Cost%20Dashboard/Compute/2.1.png)

- The **"Spend on EC2 By Accounts"** bar chart visually represents top 10 spending related to Amazon Elastic Compute Cloud (EC2) by top five/ top 10 / top 15 AWS accounts.


**3\. EC2 Daily Cost By Instance Family**

 ![Compute](images/Cost%20Dashboard/Compute/3.1.png)

- The **“EC2 Daily Cost By Instance Family”** bar chart visually  represents the daily cost of different EC2 instance families and for each date, there are stacked bars showing the cost contribution from different instance families.


## **Storage**  

**1\. Cost Division By S3 Storage Classes**

 ![Storage](images/Cost%20Dashboard/Storage/1.1.png)

- **The “Cost Division By S3 Storage Classes”** pie chart visually represents the costs associated with different Amazon S3 storage and the total spend on the S3 Storage classes, can view by top 5 / top 10 / top 15 AWS S3 storage classes.


**2\. Amazon S3 Cost Trend**

 ![Storage](images/Cost%20Dashboard/Storage/2.1.png)

- The **“Amazon S3 Cost Trend”** bar chart visually represents the daily cost trend associated with Amazon S3 (Simple Storage Service).

**3\. Amazon EBS Cost Trend**   
 ![Storage](images/Cost%20Dashboard/Storage/3.1.png)

- This section  provides insights into the cost trends associated with Amazon S3 (Simple Storage Service) over a specific time period.


**4\. Cost Division By Usage Type (EBS)** 

 ![Storage](images/Cost%20Dashboard/Storage/4.1.png)

- The section provides insights into the cost distribution based on usage types for Amazon Elastic Block Store (EBS) and also total cost incurred.  
- 

## **Network & Content Delivery** 

**1\. Network Usage Trend**

 ![Network & Content Delivery](images/Cost%20Dashboard/Network%20&%20Content%20Delivery/1.1.png)

- The "Network Usage Trend" graph provides a visual representation of network usage across different accounts over a specified time period.  
- **X-Axis (Horizontal Axis):** Represents the date and each bar corresponds to a single day within this period.  
- **Y-Axis (Vertical Axis):** Represents the cost associated with network usage in dollars ($).

2\. Data Transfer Trend (Inter Region)

 ![Network & Content Delivery](images/Cost%20Dashboard/Network%20&%20Content%20Delivery/2.1.png)

- The "**Network Usage Trend**" graph provides a visual representation of network usage across different accounts over a specified time period.  
- **X-Axis (Horizontal Axis):** Represents the date and each bar corresponds to a single day within this period.  
- **Y-Axis (Vertical Axis):** Represents the cost associated with network usage in dollars ($).

**3\. Data Transfer Cost By Region**

 ![Network & Content Delivery](images/Cost%20Dashboard/Network%20&%20Content%20Delivery/3.1.png)

- **Bar Graph :** A bar graph is used for visual representation of cost incurred by data transfer by the region. 

## **Cost Optimization** 

**1\. EC2 Unallocated Elastic IP**

 ![Cost Optimization](images/Cost%20Dashboard/Cost%20Optimization/1.1.png)


- This section displays data related to Elastic IP addresses in Amazon EC2 that are currently unallocated. And the data can be filtered by Accounts/Region/Usage type.

## **Management & Governance**

 ![Management & Governance](images/Cost%20Dashboard/Management%20&%20Governance/1.1.png)

- The **“AWS Config”** bar chart provides a visual representation of the cost trends related to AWS Config services.  
- **X-Axis (Dates):** The horizontal axis represents specific dates and each date corresponds to a data point.  
- **Y-Axis (Cost):** The vertical axis represents cost values in dollars.

## **Generate Cost Report** 

1\. To download the Cost and Usage report, click on the icon  ![Generate Cost Report](images/Cost%20Dashboard/Generate%20Cost%20Report/1.1.png) as shown in the picture. 

![Generate Cost Report](images/Cost%20Dashboard/Generate%20Cost%20Report/1.2.png)

2\. Once clicked, the customize cost report  dashboard appears. Here, you can select the accounts, timeframe, and region, and choose which features to include or exclude in the report.  

![Generate Cost Report](images/Cost%20Dashboard/Generate%20Cost%20Report/2.1.png)

- Whenever you download or generate reports, they will automatically appear in the  **Report History**. This convenient feature ensures that all your past reports are easily accessible in one place, enabling you to track and reference them whenever needed. Whether you're revisiting previous reports for analysis or simply need to reference them, the Report History provides a centralized location for managing and accessing your generated reports.

![Generate Cost Report](images/Cost%20Dashboard/Generate%20Cost%20Report/2.2.png)

![Generate Cost Report](images/Cost%20Dashboard/Generate%20Cost%20Report/2.3.png)


[image85]: data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAUCAYAAAAwaEt4AAACN0lEQVR4Xu2UzWsaQRiH80d58mQIGAISSoIH8SCk5CQ0tNRboYdCQYSwh7CXkD1EekgKNQchEGwpMaXFUoMmoGxJEErEgJV01xQWhF/nY3XYjdO1bKEtnQfWmXnn3WHn8Z2Zg2Iqc/6AgqPESFBiJCgxEpQYCYFiCp8qYtCv4vlFT4z/MJbjj8yOc2PDGfmjgkAxj0+rYkDEJD4aYhyAvq25TxH9EJuQsVHu+kMzo0WzOLj2RwW/JoYw/GZh7/QFygNPeCqRrboY2PVQG5lGmPV+uxhKmYrp+6N38YghnBRiePLaBq5L2Gl8ZbFnqRXy28X+l3FWB8lUdtI/vAGaWzESW2elb5lF7Hf47FhM/zCLJsnDyCF5GosVy+c8aWQjunnM85fWWWuZJST/JjF0g3QzO6vjjVPqOCHHLL+qo01GbYOIsiui777HhLqM12ViTB3Lj0qTOTQ0sFNrd1CrfWBPLkplnXtEhK6YoX33cnDs259eXGP8YuafVmCRtrYZF8GWjivakg3Nk/zkLv+nk7Rv8D4VozXEKx4xzjHyCw8nc20jwdr8e/HdeSbGQe6IVyllOayYt2d76I1arF/4fInh9wEeNKsk5kucQiQac584tCPTM6flEkjfi+PAFJVw+TLFxFGuXmW4MASIcdkgay0uxNF2l3tTyCC9lkI6kyXVwY+Xc1FCZGkFizk9fMW8OzMwABcz6LWw273F/WYNM9y9/zSBYv5XlBgJSowEJUaCEiNBiZHwA/edQPf+2nzqAAAAAElFTkSuQmCC