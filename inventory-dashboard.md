#  **Inventory Dashboard** 

Tevico enables you to get a real-time view of your AWS resource inventory, helping you make informed decisions and take proactive actions.

You can get a summary of the frequently used cloud services and their distribution across AWS regions. This assists you in Identifying unused resources and having them removed based on the findings.

## **Set up Inventory Dashboard** 

To get a detailed inventory, use following steps:

1. Login to [https://console.tevi.co](https://console.tevi.co). Open Dashboard and navigate to the Inventory tab.

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/1.1.png)

2. You need to set up an S3 Bucket for storing Inventory Reports. Select the appropriate S3 bucket from the dropdown.

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/2.1.png)

3. The bucket policy that needs to be attached to the selected bucket is visible on the UI. Copy the given bucket policy.

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/3.1.png)

4. In the AWS Management Console, go to S3 and open the same S3 bucket. Go to the **Permissions** tab.

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/4.1.png)
     
5. In the **Bucket policy** section, click on the **Edit** button and paste the bucket policy given by Tevico. **Save** the bucket policy.  
   

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/5.1.png)

6. Once the bucket policy is updated, go back to the Tevico tab. Click the **“Generate**” button to get the results.   
   

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/6.1.png)

7. Wait for the inventory dashboard to be ready.  
   

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/7.1.png)

8. Once the inventory dashboard is populated with data, you can see the sections showing various AWS services used in your AWS account. The sub-menu helps you navigate to the appropriate category of AWS services.  
   

![Set up Inventory Dashboard](images/Inventory%20Dashboard/Set%20up%20Inventory%20Dashboard/8.1.png)

## **Compute** 

![Compute](images/Inventory%20Dashboard/Compute/1.1.png)

In this section it provides a summary of the key resources associated with your EC2 instances. 

The Key resources are as follows: 

- EC2 Instance  
- Elastic IPs  
- Images   
- Snapshot  
- Security Group  
- Volumes  
- Load Balancers  
- Reserved Instances  
- Others  
* Lambda Function


The "**View All**" provides access to detailed information for each resource type.

### **EC2**  

![Compute](images/Inventory%20Dashboard/Compute/EC2/1.1.png)  

This section provides specific information about your EC2 instances, broken down into several key metrics.

- **Total Resources:** Indicates the total number of EC2 instances currently active in your AWS environment.  
- **Resource Types :** Indicates the number of different types of EC2 resources like (On-Demand Instances, Savings Plans, Spot Instances, and Reserved Instances (RIs))  
- **Regions :** Indicates the number of AWS regions where the EC2 instances are deployed.   
- **Tags :** Indicates the number of unique tags applied to the EC2 instances.  
- **Distribution By Region :** The pie chart provides the visual representation of EC2s distributed across the Regions by top five/ top 10 / top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/EC2/1.2.png)  

The “**List of EC2 instances**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Elastic IPs** 

![Compute](images/Inventory%20Dashboard/Compute/Elastic%20IPs/1.1.png) 

This section provides specific information about the Elastic IPs, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Elastic IPs currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Elastic IPs.  
- **Regions:** Indicates the number of AWS regions where the Elastic IPs are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Elastic IPs.  
- **Distribution By Region:** The pie chart provides a visual representation of Elastic IPs distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Elastic%20IPs/1.2.png)  

The “**List of Elastic IPs**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Images** 

![Compute](images/Inventory%20Dashboard/Compute/Images/1.1.png) 

This section provides specific information about the Amazon Machine Images, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Images currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Images.  
- **Regions:** Indicates the number of AWS regions where the Images are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Images.  
- **Distribution By Region:** The pie chart provides a visual representation of Images distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Images/1.2.png) 

The “**List of Images**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### Snapshot 

![Compute](images/Inventory%20Dashboard/Compute/Snapshot/1.1.png)

This section provides specific information about the Amazon EBS Snapshots, broken down into several key metrics.

- **Total Resources:** Indicates the total number of EBS Snapshots currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of EBS Snapshots.  
- **Regions:** Indicates the number of AWS regions where the Snapshots are deployed.  
- **Tags:** Indicates the number of unique tags applied to the EBS Snapshots.  
- **Distribution By Region:** The pie chart provides a visual representation of EBS Snapshots distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Snapshot/1.2.png)

The “**List of Snapshot**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Security Group** 

![Compute](images/Inventory%20Dashboard/Compute/Security%20Group/1.1.png)

This section provides specific information about the Security Groups, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Security Groups currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Security Groups.  
- **Regions:** Indicates the number of AWS regions where the Security Groups are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Security Groups.  
- **Distribution By Region:** The pie chart provides a visual representation of Security Groups distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Security%20Group/1.2.png)

The “**List of Security Group**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Volumes** 

![Compute](images/Inventory%20Dashboard/Compute/Volumes/1.1.png)

This section provides specific information about the Volumes, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Volumes currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Volumes.  
- **Regions:** Indicates the number of AWS regions where the Volumes are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Volumes.  
- **Distribution By Region:** The pie chart provides a visual representation of Volumes distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Volumes/1.2.png)

The “**List of Volumes**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

###  **Load Balancers** 

![Compute](images/Inventory%20Dashboard/Compute/Load%20Balancers/1.1.png)

This section provides specific information about the Load Balancers, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Load Balancers currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Load Balancers.  
- **Regions:** Indicates the number of AWS regions where the Load Balancers are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Load Balancers.  
- **Distribution By Region:** The pie chart provides a visual representation of Load Balancers distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Load%20Balancers/1.2.png)

The The “**List of Load Balancers**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Reserved Instance** 

![Compute](images/Inventory%20Dashboard/Compute/Reserved%20Instance/1.1.png)

This section provides specific information about the Reserved Instances, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Reserved Instances currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Reserved Instances.  
- **Regions:** Indicates the number of AWS regions where the Reserved Instances are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Reserved Instances.  
- **Distribution By Region:** The pie chart provides a visual representation of Reserved Instances distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Reserved%20Instance/1.2.png)

The “**List of Reserved Instance**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Lambda Function** 

![Compute](images/Inventory%20Dashboard/Compute/Lambda%20Function/1.1.png)

This section provides specific information about the Lambda Functions, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Lambda Functions currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Lambda Functions.  
- **Regions:** Indicates the number of AWS regions where the Lambda Functions are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Lambda Functions.  
- **Distribution By Region:** The pie chart provides a visual representation of Lambda Functions distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Compute/Lambda%20Function/1.2.png) 

The “**List of Lambda Function**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

## **Containers** 

![Compute](images/Inventory%20Dashboard/Containers/1.1.png)

In this section it provides a summary of the key resources associated with your ECS Service. 

The Key resources are as follows: 

- Clusters  
- Task  
- Task Definition   
- Others   
* EKS Clusters   
* EKS Node Group  


The "**View All**" provides access to detailed information for each resource type.

### **Clusters**   

![Compute](images/Inventory%20Dashboard/Containers/Clusters/1.1.png)

This section provides specific information about the Clusters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Clusters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Clusters.  
- **Regions:** Indicates the number of AWS regions where the Clusters are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Clusters.  
- **Distribution By Region:** The pie chart provides a visual representation of Clusters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Containers/Clusters/1.2.png) 

The “**List of Clusters**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Task** 

![Compute](images/Inventory%20Dashboard/Containers/Task/1.1.png) 

This section provides specific information about the Tasks, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Tasks in the AWS environment.  
- **Resource Types:** Indicates the number of different types of Tasks.  
- **Regions:** Indicates the number of AWS regions where the Tasks are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Tasks.  
- **Distribution By Region:** The pie chart provides a visual representation of Tasks distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Containers/Task/1.2.png) 

The “**List of Task**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Task Definition** 

![Compute](images/Inventory%20Dashboard/Containers/Task%20Definition/1.1.png) 

This section provides specific information about the Task Definitions, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Task Definitions assigned in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Task Definitions.  
- **Regions:** Indicates the number of AWS regions where the Task Definitions are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Task Definitions.  
- **Distribution By Region:** The pie chart provides a visual representation of Task Definitions distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Containers/Task%20Definition/1.2.png) 

The “**List of Task Definition**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **EKS Clusters** 

![Compute](images/Inventory%20Dashboard/Containers/EKS%20Clusters/1.1.png) 

This section provides specific information about the EKS Clusters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of EKS Clusters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of EKS Clusters.  
- **Regions:** Indicates the number of AWS regions where the EKS Clusters are deployed.  
  **Tags:** Indicates the number of unique tags applied to your EKS Clusters.  
- **Distribution By Region:** The pie chart provides a visual representation of EKS Clusters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Containers/EKS%20Clusters/1.2.png) 

The “**List of EKS Clusters**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **EKS Node Group** 

![Compute](images/Inventory%20Dashboard/Containers/EKS%20Node%20Group/1.1.png)

This section provides specific information about the EKS Node Groups, broken down into several key metrics.

- **Total Resources:** Indicates the total number of EKS Node Groups currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of EKS Node Groups.  
- **Regions:** Indicates the number of AWS regions where the EKS Node Groups are deployed.  
- **Tags:** Indicates the number of unique tags applied to your EKS Node Groups.  
- **Distribution By Region:** The pie chart provides a visual representation of EKS Node Groups distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Containers/EKS%20Node%20Group/1.2.png)

The “**List of EKS Node Group**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

## **Database** 

![Compute](images/Inventory%20Dashboard/Database/1.1.png)

In this section it provides a summary of the key resources associated with your RDS Service. 

The Key resources are as follows: 

- Database  
- Cluster  
- Snapshot   
- Others   
* DynamoDb Tables 


The "**View All**" provides access to detailed information for each resource type.

### **Database** 

![Compute](images/Inventory%20Dashboard/Database/Database/1.1.png)

In this section it provides a summary of the key resources associated with your Database Service.

- **Total Resources:** Indicates the total number of Databases currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Databases.  
- **Regions:** Indicates the number of AWS regions where the Databases are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Databases.  
- **Distribution By Region:** The pie chart provides a visual representation of Databases distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Database/Database/1.2.png)

The “**List of Database**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Cluster** 

![Compute](images/Inventory%20Dashboard/Database/Cluster/1.1.png)

This section provides specific information about the Clusters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Clusters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Clusters.  
- **Regions:** Indicates the number of AWS regions where the Clusters are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Clusters.  
- **Distribution By Region:** The pie chart provides a visual representation of Clusters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Database/Cluster/1.2.png)

The “**List of Cluster**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Snapshot** 

![Compute](images/Inventory%20Dashboard/Database/Snapshot/1.1.png)

This section provides specific information about the Snapshots, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Snapshots currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Snapshots.  
- **Regions:** Indicates the number of AWS regions where the Snapshots are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Snapshots.  
- **Distribution By Region:** The pie chart provides a visual representation of Snapshots distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Database/Snapshot/1.2.png)

The “**List of Snapshot**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **DynamoDb Tables** 

![Compute](images/Inventory%20Dashboard/Database/DynamoDb%20Tables/1.1.png)

This section provides specific information about the DynamoDB Tables, broken down into several key metrics.

- **Total Resources:** Indicates the total number of DynamoDB Tables currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of DynamoDB Tables.  
- **Regions:** Indicates the number of AWS regions where the DynamoDB Tables are deployed.  
- **Tags:** Indicates the number of unique tags applied to your DynamoDB Tables.  
- **Distribution By Region:** The pie chart provides a visual representation of DynamoDB Tables distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Database/DynamoDb%20Tables/1.2.png)

The “**List of DynamoDb Tables**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

## **Storage** 

![Compute](images/Inventory%20Dashboard/Storage/1.1.png)

In this section it provides a summary of the key resources associated with your AWS Storage Service. 

The Key resources are as follows:  
 

- AWS Backup  
* Backup Plan  
* Recovery Point  
* Backup Vault  
- Others   
* S3 Buckets  
* EFS File Systems  
* Storage Gateway Gateways  
* FSx File System  
* Disaster Recovery Plans

### **Backup Plan** 

![Compute](images/Inventory%20Dashboard/Storage/Backup%20Plan/1.1.png)

This section provides specific information about the Backup Plans, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Backup Plans currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Backup Plans.  
- **Regions:** Indicates the number of AWS regions where the Backup Plans are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Backup Plans.  
- **Distribution By Region:** The pie chart provides a visual representation of Backup Plans distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Storage/Backup%20Plan/1.2.png)

The “**List of Backup Plan**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Recovery Point** 

![Compute](images/Inventory%20Dashboard/Storage/Recovery%20Point/1.1.png)

This section provides specific information about the Recovery Points, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Recovery Points currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Recovery Points.  
- **Regions:** Indicates the number of AWS regions where the Recovery Points are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Recovery Points.  
- **Distribution By Region:** The pie chart provides a visual representation of Recovery Points distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Storage/Recovery%20Point/1.2.png)

The “**List of Recovery Point**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Backup Vault** 

![Compute](images/Inventory%20Dashboard/Storage/Backup%20Vault/1.1.png)

This section provides specific information about the Backup Vaults, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Backup Vaults currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Backup Vaults.  
- **Regions:** Indicates the number of AWS regions where the Backup Vaults are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Backup Vaults.  
- **Distribution By Region:** The pie chart provides a visual representation of Backup Vaults distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Storage/Backup%20Vault/1.2.png)

The “**List of Backup Vault**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **S3 Buckets** 

![Compute](images/Inventory%20Dashboard/Storage/S3%20Buckets/1.1.png)

This section provides specific information about the S3 Buckets, broken down into several key metrics.

- **Total Resources:** Indicates the total number of S3 Buckets currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of S3 Buckets.  
- **Regions:** Indicates the number of AWS regions where the S3 Buckets are deployed.  
- **Tags:** Indicates the number of unique tags applied to your S3 Buckets.  
- **Distribution By Region:** The pie chart provides a visual representation of S3 Buckets distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Storage/S3%20Buckets/1.2.png)

The “**List of S3 Buckets**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **EFS File Systems** 

![Compute](images/Inventory%20Dashboard/Storage/EFS%20File%20Systems/1.1.png)

This section provides specific information about the EFS File Systems, broken down into several key metrics.

- **Total Resources:** Indicates the total number of EFS File Systems currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of EFS File Systems.  
- **Regions:** Indicates the number of AWS regions where the EFS File Systems are deployed.  
- **Tags:** Indicates the number of unique tags applied to your EFS File Systems.  
- **Distribution By Region:** The pie chart provides a visual representation of EFS File Systems distributed across the regions by the top five, top 10, or top 15 AWS accounts.  

![Compute](images/Inventory%20Dashboard/Storage/EFS%20File%20Systems/1.2.png)

The “**List of EFS File Systems**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

### **Disaster Recovery Plans** 

![Compute](images/Inventory%20Dashboard/Storage/Disaster%20Recovery%20Plans/1.1.png)

This section provides specific information about the Disaster Recovery Plans, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Disaster Recovery Plans currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Disaster Recovery Plans.  
- **Regions:** Indicates the number of AWS regions where the Disaster Recovery Plans are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Disaster Recovery Plans.  
- **Distribution By Region:** The pie chart provides a visual representation of Disaster Recovery Plans distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Storage/Disaster%20Recovery%20Plans/1.2.png)

The “**List of Disaster Recovery Plans**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

## **Networking And Content Delivery** 

![Compute](images/Inventory%20Dashboard/Networking%20And%20Content%20Delivery/1.1.png)

In this section it provides a summary of the key resources associated with your Networking And Content Delivery. 

The Key resources are as follows:  
 

- Others  
* VPCs  
* CloudFront Distributions


The "**View All**" provides access to detailed information for each resource type.

### **VPC** 

![Compute](images/Inventory%20Dashboard/Networking%20And%20Content%20Delivery/VPC/1.1.png)

This section provides specific information about the VPCs, broken down into several key metrics.

- **Total Resources:** Indicates the total number of VPCs currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of VPCs.  
- **Regions:** Indicates the number of AWS regions where the VPCs are deployed.  
- **Tags:** Indicates the number of unique tags applied to your VPCs.  
- **Distribution By Region:** The pie chart provides a visual representation of VPCs distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Networking%20And%20Content%20Delivery/VPC/1.2.png)

The “**List of VPCs**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

###  **CloudFront Distributions** 

![Compute](images/Inventory%20Dashboard/Networking%20And%20Content%20Delivery/CloudFront%20Distributions/1.1.png)

This section provides specific information about the CloudFront Distributions, broken down into several key metrics.

- **Total Resources:** Indicates the total number of CloudFront Distributions currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of CloudFront Distributions.  
- **Regions:** Indicates the number of AWS regions where the CloudFront Distributions are deployed.  
- **Tags:** Indicates the number of unique tags applied to your CloudFront Distributions.  
- **Distribution By Region:** The pie chart provides a visual representation of CloudFront Distributions distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Networking%20And%20Content%20Delivery/CloudFront%20Distributions/1.2.png)

The “**List of  CloudFront Distributions**” provides the details about it’s Account ID, Region, Resource Type, Resource, and Tags.

## **Analytics** 

![Compute](images/Inventory%20Dashboard/Analytics/1.1.png)

In this section it provides a summary of the key resources associated with your AWS Analytics services. 

The Key resources are as follows:  
 

- AWS Glue  
* Crawler  
* Job  
* Trigger  
- Others   
* QuickSight Dashboard  
* Kinesis Stream  
* Kafka Cluster  
* Open Search Domain  
* EMR Cluster  
* Redshift Cluster  
* Redshift Cluster Parameter


The "**View All**" provides access to detailed information for each resource type.

### **Crawler** 

![Compute](images/Inventory%20Dashboard/Analytics/Crawler/1.1.png)

This section provides specific information about the Crawlers, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Crawlers currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Crawlers.  
- **Regions:** Indicates the number of AWS regions where the Crawlers are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Crawlers.  
- **Distribution By Region:** The pie chart provides a visual representation of Crawlers distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Crawler/1.2.png)

The "**List of Crawler**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **Job** 

![Compute](images/Inventory%20Dashboard/Analytics/Job/1.1.png)

This section provides specific information about the Jobs, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Jobs currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Jobs.  
- **Regions:** Indicates the number of AWS regions where the Jobs are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Jobs.  
- **Distribution By Region:** The pie chart provides a visual representation of Jobs distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Job/1.2.png)

The "**List of Job**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **Trigger** 

![Compute](images/Inventory%20Dashboard/Analytics/Trigger/1.1.png)

This section provides specific information about the Triggers, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Triggers currently active in your AWS  
  Environment.  
- **Resource Types:** Indicates the number of different types of Triggers.  
- **Regions:** Indicates the number of AWS regions where the Triggers are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Triggers.  
- **Distribution By Region:** The pie chart provides a visual representation of Triggers distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Trigger/1.2.png)

The "**List of Trigger**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **QuickSight Dashboard** 

![Compute](images/Inventory%20Dashboard/Analytics/QuickSight%20Dashboard/1.1.png)

This section provides specific information about the QuickSight Dashboards, broken down into several key metrics.

- **Total Resources:** Indicates the total number of QuickSight Dashboards currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of QuickSight Dashboards.  
- **Regions:** Indicates the number of AWS regions where the QuickSight Dashboards are deployed.  
- **Tags:** Indicates the number of unique tags applied to your QuickSight Dashboards.  
- **Distribution By Region**: The pie chart provides a visual representation of QuickSight Dashboards distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/QuickSight%20Dashboard/1.2.png)

The "**List of QuickSight Dashboard**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **Kinesis Stream** 

![Compute](images/Inventory%20Dashboard/Analytics/Kinesis%20Stream/1.1.png)

This section provides specific information about the Kinesis Streams, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Kinesis Streams currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Kinesis Streams.  
- **Regions:** Indicates the number of AWS regions where the Kinesis Streams are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Kinesis Streams.  
- **Distribution By Region:** The pie chart provides a visual representation of Kinesis Streams distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Kinesis%20Stream/1.2.png)

The "**List of Kinesis Stream**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **Kafka Cluster** 

![Compute](images/Inventory%20Dashboard/Analytics/Kafka%20Cluster/1.1.png)

This section provides specific information about the Kafka Clusters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Kafka Clusters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Kafka Clusters.  
  **Regions:** Indicates the number of AWS regions where the Kafka Clusters are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Kafka Clusters.  
- **Distribution By Region:** The pie chart provides a visual representation of Kafka Clusters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Kafka%20Cluster/1.2.png)

The "**List of Kafka Cluster**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **OpenSearch Domain** 

![Compute](images/Inventory%20Dashboard/Analytics/OpenSearch%20Domain/1.1.png)

This section provides specific information about the OpenSearch Domains, broken down into several key metrics.

- **Total Resources:** Indicates the total number of OpenSearch Domains currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of OpenSearch Domains.  
- **Regions:** Indicates the number of AWS regions where the OpenSearch Domains are deployed.  
- **Tags:** Indicates the number of unique tags applied to your OpenSearch Domains.  
- **Distribution By Region:** The pie chart provides a visual representation of OpenSearch Domains distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/OpenSearch%20Domain/1.2.png)

The "**List of OpenSearch Domain**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **EMR Cluster** 

![Compute](images/Inventory%20Dashboard/Analytics/EMR%20Cluster/1.1.png)

This section provides specific information about the EMR Clusters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of EMR Clusters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of EMR Clusters.  
- **Regions:** Indicates the number of AWS regions where the EMR Clusters are deployed.  
- **Tags:** Indicates the number of unique tags applied to your EMR Clusters.  
- **Distribution By Region:** The pie chart provides a visual representation of EMR Clusters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/EMR%20Cluster/1.2.png)

The "**List of EMR Cluster**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **Redshift Cluster** 

![Compute](images/Inventory%20Dashboard/Analytics/Redshift%20Cluster/1.1.png)

This section provides specific information about the Redshift Clusters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Redshift Clusters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Redshift Clusters.  
- **Regions:** Indicates the number of AWS regions where the Redshift Clusters are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Redshift Clusters.  
- **Distribution By Region:** The pie chart provides a visual representation of Redshift Clusters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Redshift%20Cluster/1.2.png)

The "**List of Redshift Cluster**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

### **Redshift Cluster Parameter** 

![Compute](images/Inventory%20Dashboard/Analytics/Redshift%20Cluster%20Parameter/1.1.png)

This section provides specific information about the Redshift Cluster Parameters, broken down into several key metrics.

- **Total Resources:** Indicates the total number of Redshift Cluster Parameters currently active in your AWS environment.  
- **Resource Types:** Indicates the number of different types of Redshift Cluster Parameters.  
- **Regions:** Indicates the number of AWS regions where the Redshift Cluster Parameters are deployed.  
- **Tags:** Indicates the number of unique tags applied to your Redshift Cluster Parameters.  
- **Distribution By Region:** The pie chart provides a visual representation of Redshift Cluster Parameters distributed across the regions by the top five, top 10, or top 15 AWS accounts.

![Compute](images/Inventory%20Dashboard/Analytics/Redshift%20Cluster%20Parameter/1.2.png)

The "**List of Redshift Cluster Parameter**" provides the details about its Account ID, Region, Resource Type, Resource, and Tags.

##  **RDS Recommendations** 

![Compute](images/Inventory%20Dashboard/RDS%20Recommendations/1.1.png)

This section provides detailed insights into the recommendations for your Amazon RDS.  
The recommendations are categorized based on their status and severity.

**Total Recommendations:** Displays the total number of recommendations available for your RDS instances.

* **Active:** Indicates the number of active recommendations that require your attention.  
* **Pending:** Shows the number of recommendations that are pending action.   
* **Resolved:** Displays the number of recommendations that have been resolved.   
* **Dismissed:** Indicates the number of recommendations that have been dismissed. 

**Recommended Actions Summary:** Displays the total number of Recommended Actions available for your RDS instances.

* **Ready:** Displays the number of recommendations that are ready to be addressed.  
* **Applied:** Shows the number of recommendations that have been applied.  
* **Scheduled:** Indicates the number of recommendations that are scheduled for action.  
* **Resolved:** Reflects the number of recommendations that have been resolved after taking action.

Recommendations Based on Severity : Shows the number/count of recommendations for each severity level i.e High, Medium, Low, Informational. 

**Informational Recommendations:** This section provides a summary of these recommendations suggesting that your system is running properly.

The "**View All**" provides access to detailed information for each recommendation.

![Compute](images/Inventory%20Dashboard/RDS%20Recommendations/1.2.png)

- **Total Recommendations:** Displays the total number of recommendations.  
- **Active:** Shows the number of active recommendations that need your attention.  
- **Pending:** Indicates the number of recommendations that are pending.   
- **Resolved:** Shows the number of recommendations that have been resolved.  
- **Dismissed:** Indicates the number of recommendations that have been dismissed.  
- **Recommendation Title:** The title of the recommendation. It provides a brief description of the action to be taken.  
- **Severity:** Indicates the severity level of the recommendation.   
- **Resource Name:** The name of the resource associated with the recommendation.  
- **Status:** The current status of the recommendation.   
- **Recommended Actions:** Indicates the number of actions recommended for each recommendation.  
- **Region:** The AWS region where the resource is located.  
- **Category:** The category of the recommendation. Categories include Reliability, Security, Operational Excellence.  
- **Action:** Provides an option to view more details about the recommendation.

