+++
title = "Intro to AWS Amplify"
chapter = false
weight = 1
+++

### Intro to AWS Management Console

The AWS Management Console is a simple web interface for interacting with Amazon Web Services. There are other interfaces, including the command line (awscli) and software development kits (SDKs or libraries) for interacting with AWS directly from your code. For this workshop, we'll use the AWS Management Console.

When you log into your AWS account, you'll be presented with the console home page.

![](../../images/aws-management-console.png)

Note the region selector in the upper right of the navigation bar. For the purposes of this workshop, we'll always leave this set to "N. Virginia" or "US East (N. Virginia) us-east-1". This is the AWS region that where we'll create our AWS resources.

{{% notice tip %}}
If you are ever looking for resources you've created but don't see them in the console, check the Region you have selected. Some AWS resources are created in a specific Region and so they will only show when that Region is selected.
{{% /notice %}}

### Intro to AWS Amplify

AWS Amplify is one of the services we can interact with in the AWS Management Console. We'll use the Amplify Console to host our website so the world can see it.

AWS Amplify enables web and mobile developers to build and deploy secure, scalable full-stack applications. With Amplify, you can quickly create a backend with cloud resources such as GraphQL, REST APIs, authentication, file, and data storage and then connect it with your frontend code.

With the Amplify Console, you can deploy and host a static website, manage production and test environments, set up continuous deployment, connect your custom domain to your site, and even see how your site is rendered on different devices.

Let's deploy our site!