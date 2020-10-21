+++
title = "Intro to AWS Management Console"
chapter = false
weight = 1
+++

### Intro to AWS Management Console

The AWS Management Console is a simple web interface for interacting with Amazon Web Services. There are other interfaces, including the command line (awscli) and software development kits (SDKs or libraries) for interacting with AWS directly from your code. For this workshop, we'll use the AWS Management Console.

### Go to the AWS Console

If you haven't already set up your AWS account, follow [these instructions](/01_prerequisites/01_aws_temporary_account.html) now and return here to continue with the workshop.

When you log into your AWS account, you'll be presented with the console home page.

![](/images/aws-management-console.png)

Note the region selector in the upper right of the navigation bar. For the purposes of this workshop, we'll always leave this set to "N. Virginia" or "US East (N. Virginia) us-east-1". This is the AWS region that where we'll create our AWS resources. If the region is not already set to this value, go ahead and select "US East (N. Virginia) us-east-1" from the region selector.

{{% notice tip %}}
If you are ever looking for resources you've created but don't see them in the console, check the Region you have selected. Some AWS resources are created in a specific Region and so they will only show when that Region is selected.
{{% /notice %}}
