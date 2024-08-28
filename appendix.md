# Appendix 

In a cross-account IAM role, Tevico requires the following permissions in your AWS account to capture insights and display them in the dashboard.

<table>
  <tr>
    <td style="background-color: #434343; color: white;width:100%">
    <pre style="color: white; background-color:	#434343;width:100%">

{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": [
        "events":"&ast;"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "cloudwatch:List&ast;",
        "cloudwatch:PutMetricAlarm",
        "cloudwatch:Get&ast;",
        "cloudwatch:SetAlarmState",
        "cloudwatch:DeleteAlarms",
        "cloudwatch:Describe&ast;",
        "events:List&ast;",
        "events:Put&ast;",
        "events:DeleteRule",
        "events:DisableRule",
        "events:EnableRule",
        "ce:Describe&ast;",
        "ce:List&ast;",
        "ce:Get&ast;",
        "pricing:Get&ast;",
        "compute-optimizer:Get&ast;",
        "cloudformation:ListStacks",
        "guardduty:List&ast;",
        "guardduty:Get&ast;",
        "budgets:Describe&ast;",
        "budgets:ViewBudget",
        "budgets:ModifyBudget",
        "organizations:ListAccounts"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "wellarchitected:&ast;"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "securityhub:Get&ast;",
        "securityhub:Describe&ast;",
        "securityhub:BatchEnableStandards",
        "securityhub:EnableSecurityHub",
        "securityhub:UpdateSecurityHubConfiguration",
        "config:DescribeConfigurationRecorderStatus"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "access-analyzer:createAnalyzer",
        "access-analyzer:deleteAnalyzer",
        "access-analyzer:getAnalyzer",
        "access-analyzer:listAnalyzers",
        "access-analyzer:ListFindings",
        "wafv2:ListWebACLs",
        "wafv2:ListLoggingConfigurations"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "SSM:List&ast;",
        "SSM:Get&ast;",
        "SSM:CreateDocument",
        "SSM:DeleteDocument",
        "SSM:Describe&ast;",
        "SSM:SendCommand"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "SNS:CreateTopic",
        "SNS:Subscribe",
        "SNS:Publish",
        "SNS:Get&ast;",
        "SNS:Set&ast;",
        "SNS:List&ast;",
        "SNS:DeleteTopic",
        "SNS:Unsubscribe"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "ec2:Describe&ast;",
        "ec2:Copy&ast;",
        "ec2:CreateImage",
        "ec2:CreateTags",
        "ec2:DeleteSnapshot",
        "ec2:DeregisterImage",
        "elasticloadbalancing:Describe&ast;"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "iam:Get&ast;",
        "iam:List&ast;",
        "iam:SimulatePrincipalPolicy",
        "iam:PassRole",
        "iam:CreateServiceLinkedRole"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "s3:ListAllMyBuckets",
        "S3:GetBucketLocation",
        "S3:GetBucketPolicyStatus",
        "S3:GetBucketAcl",
        "S3:GetBucketPublicAccessBlock"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "sns:AddPermission",
        "sns:CreateTopic",
        "sns:DeleteTopic",
        "sns:ListTopics",
        "sns:SetTopicAttributes",
        "sns:GetTopicAttributes"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": "cloudtrail:&ast;",
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "lambda:GetFunction",
        "lambda:ListFunctions",
        "lambda:InvokeFunction"
      ],
      "Resource": "&ast;"
    },
    {
      "Effect": "Allow",
      "Action": [
        "autoscaling:DescribeAutoScalingGroups",
        "ce:CreateAnomalyMonitor",
        "ce:CreateAnomalySubscription",
        "ce:DeleteAnomalyMonitor",
        "ce:DeleteAnomalySubscription",
        "ce:UpdateAnomalyMonitor",
        "ce:UpdateAnomalySubscription",
        "cloudformation:DescribeStackResources",
        "cloudformation:DescribeStacks",
        "cloudformation:GetTemplate",
        "cloudfront:ListDistributions",
        "cloudwatch:DescribeAlarms",
        "cloudwatch:GetMetricStatistics",
        "cloudwatch:ListMetrics",
        "config:DescribeConfigurationRecorders",
        "config:DescribeDeliveryChannelStatus",
        "config:DescribeDeliveryChannels",
        "cur:DescribeReportDefinitions",
        "cur:PutReportDefinition",
        "dynamodb:DescribeContinuousBackups",
        "dynamodb:DescribeTable",
        "dynamodb:ListTables",
        "ecs:ListClusters",
        "eks:ListClusters",
        "elasticache:DescribeCacheClusters",
        "elasticache:DescribeCacheSubnetGroups",
        "elasticache:DescribeReplicationGroups",
        "elasticfilesystem:DescribeFileSystems",
        "elasticloadbalancing:DescribeLoadBalancers",
        "es:DescribeElasticsearchDomains",
        "inspector:ListAssessmentRuns",
        "kms:ListKeys",
        "lambda:GetPolicy",
        "rds:DescribeDBInstances",
        "rds:DescribeDBSnapshots",
        "rds:DescribePendingMaintenanceActions",
        "rds:ListTagsForResource",
        "redshift:DescribeClusters",
        "s3:GetBucketLogging",
        "s3:GetBucketPolicy",
        "s3:GetBucketVersioning",
        "s3:GetEncryptionConfiguration",
        "ssm:ListComplianceSummaries",
        "support:DescribeCases",
        "support:DescribeTrustedAdvisorCheckRefreshStatuses",
        "support:DescribeTrustedAdvisorCheckResult",
        "support:DescribeTrustedAdvisorChecks",
        "tag:GetResources",
        "tag:GetTagKeys",
        "tag:GetTagValues",
        "workspaces:DescribeWorkspaceDirectories",
        "workspaces:DescribeWorkspaces"
      ],
      "Resource": "&ast;"
    }
  ]
}
</pre>
</td>
</tr>
</table>
