# **Prerequisites**

1. To begin using Tevico as a cloud management platform, a Cross-Account IAM role is utilized. All necessary resources for this access are provisioned using a CloudFormation Template provided by the platform upon subscription.

   Users require the following access to create the required resources in their AWS account and grant necessary permissions to Tevico:

<table>
  <tr>
    <td style="background-color: #434343; color: white;">
    <pre style="color: white; background-color:	#434343;">
    {
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "FullAccess",
            "Effect": "Allow",
            "Action": [
                "aws-marketplace:Subscribe",
                "aws-marketplace:ViewSubscriptions",
                "aws-marketplace:Unsubscribe",
                "config:*",
                "cloudformation:CreateStack",
                "cloudformation:UpdateStack",
                "cloudformation:DeleteStack",
                "cloudformation:CreateChangeSet",
                "cloudformation:ContinueUpdateRollback",
                "cloudformation:DeleteChangeSet",
                "cloudformation:DescribeChangeSet",
                "cloudformation:DescribeStacks",
                "cloudformation:DescribeStackEvents",
                "cloudformation:ListChangeSets",
                "cloudformation:DetectStackDrift",
                "cloudformation:DescribeStackDriftDetectionStatus",
                "cloudformation:DescribeStackResourceDrifts",
                "cloudformation:ListStackInstanceResourceDrifts",
                "cloudformation:GetTemplateSummary",
                "cloudformation:ListStacks",
                "cloudformation:ListStackResources",
                "cloudformation:ListStackSets",
                "cloudformation:ListTypes",
                "cloudformation:ListTypeVersions",
                "cur:DescribeReportDefinitions",
                "cur:PutReportDefinition",
                "cur:ModifyReportDefinition",
                "cur:GetClassicReport",
                "cur:GetUsageReport",
                "cur:DeleteReportDefinition",
                "iam:CreateRole",
                "iam:CreateInstanceProfile",
                "iam:CreateServiceLinkedRole",
                "iam:CreatePolicy",
                "iam:CreatePolicyVersion",
                "iam:PutRolePolicy",
                "iam:UpdateRole",
                "iam:AttachRolePolicy",
                "iam:DetachRolePolicy",
                "iam:GetRole",
                "iam:ListRoles",
                "iam:PassRole",
                "iam:GetPolicy",
                "iam:ListPolicyVersions",
                "iam:DeleteRole",
                "iam:DeleteRolePolicy",
                "iam:DeletePolicyVersion",
                "iam:AddRoleToInstanceProfile",
                "iam:RemoveRoleFromInstanceProfile",
                "iam:GetInstanceProfile",
                "iam:DeleteInstanceProfile",
                "lambda:CreateFunction",
                "lambda:ListFunctions",
                "lambda:GetFunction",
                "lambda:InvokeFunction",
                "lambda:ListVersionsByFunction",
                "lambda:PublishVersion",
                "lambda:UpdateFunctionCode",
                "lambda:DeleteFunction",
                "license-manager:ListReceivedLicenses",
                "sns:ListTopics",
                "s3:ListBucket",
                "s3:CreateBucket",
                "s3:PutBucketPolicy",
                "s3:GetBucketPolicy",
                "s3:DeleteBucketPolicy",
                "s3:GetBucketAcl",
                "s3:GetBucketLocation",
                "s3:PutBucketOwnershipControls",
                "s3:DeleteBucket",
                "s3:GetObject",
                "s3:PutObject"
            ],
            "Resource": ["*"]
        }
      ]
    }
    </pre>
    </td>
  </tr>
</table>

2. Users who create a stack using the CloudFormation template must use a valid email ID to receive an activation link.