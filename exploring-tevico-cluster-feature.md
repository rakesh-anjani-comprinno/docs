# **Exploring Tevico Cluster Feature** 

1. Click **Cluster** on the navigation bar on the left from the menu on the left-hand side of the webpage.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.1.png)

2. Once you've clicked on the Cluster, you'll be directed to the Cluster overview page

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.2.png)

\- Within the Cluster Detailed Page, you'll find five sections to explore:  
      1\. Node   
      2\. Job  
      3\. Scanner  
      4\. Backup   
      5\. Users

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.3.png)

**Node**:  
Each EC2 instance within the cluster is referred to as a node. Users can add multiple nodes and perform tasks on specific nodes.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.4.png)  
     
**Jobs**:  
Jobs are categorized into three sections: 

1. Auto Healing  
2. Scheduled Job  
3. Manual Job.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.5.png)

* Auto Healing: This feature automatically triggers specific actions when predefined conditions for a particular service on an instance are met. For example, if the set condition is met, Tevico on behalf of the User will trigger the action on the EC2 instance.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.6.png)

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.7.png)

* Scheduled Jobs: These jobs run actions based on a set schedule, independent of any conditions. Users can configure these jobs to execute at regular intervals, such as daily, weekly, or yearly, or by using cron expressions for more desired scheduling. This is useful for routine maintenance tasks, health checks, updates, that need to occur at consistent times.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.8.png)

* Manual Job: Allows users to execute tasks manually whenever needed, without any predefined conditions or schedules. This provides flexibility for ad-hoc operations or troubleshooting, enabling users to perform specific actions on demand.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.9.png)

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.10.png)

- **Scanners:**  
  The Scanner continuously monitors the selected metric based on the conditions you have specified. It actively scans this metric to ensure it meets the desired performance and operational thresholds. When any of these conditions are met, the Scanner triggers an alert, notifying the user immediately. This enables proactive monitoring and timely intervention to maintain node health.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.11.png)

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.12.png)

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.13.png)


- **Backup:**  
  The backup of an instance can be managed through the Backup option under the Cluster section. Backups can be scheduled to occur daily, weekly, yearly, using a cron expression, or as a one-time event. Additionally, you can set a retention policy to specify the number of most recent backups to keep, ensuring efficient storage management and data protection.  
  Backups can be done for Instances in Multiple regions.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.14.png)

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.15.png)

- **Users**:  
  The Users section facilitates collaboration by allowing you to manage and assign permissions to other users. You can designate roles such as Cluster Admin, Node Admin, or Cluster Viewer, ensuring that each user has the appropriate level of access and control based on their responsibilities.

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.16.png)

![Exploring Tevico Cluster Feature](images/Exploring%20Tevico%20Cluster%20Feature/1.17.png)
