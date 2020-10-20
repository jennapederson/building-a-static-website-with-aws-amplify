+++
title = "Deploy Your Site"
chapter = false
weight = 3
+++

### Create Zip File of Website

Before we go into the AWS Console, go to the `website` folder located on your desktop. We will need to create a zip file of the contents of this folder (not of the folder itself). Inside the `website` folder, select all of the files, right-click and select the menu item to compress those files. A new `.zip` file should be created inside the `website` folder. This is the file you'll upload to AWS Amplify to deploy your site.

### Go to the AWS Console

TODO

### Go to the AWS Amplify Console

After logging into your AWS account, use the "Find Services" search box to search for "AWS Amplify" or use the "Services" menu to navigate there under the "Front-end Web & Mobile" section.

![](../../images/open-amplify.png)

You'll see the AWS Amplify Console landing page.

![](../../images/amplify-landing-pg.png)

Under the Deploy section, click the "Get Started" button.

### Choose Deployment Source

If we were managing our website's code in a Git source control repository, we could connect it directly to the repository. Instead, we'll upload the website's files directly to the Amplify Console to deploy it.

![](../../images/deploy-without-git-provider.png)

Choose "Deploy without Git provider" and click on the "Continue" button.

### Upload Website Files

Set the "App name", something memorable like the name of your website. You can leave "Environment name" empty or set it to a value like "prod" or "test". Choose "Drag and Drop" for the Method. Then, drag your `website.zip` file you created earlier to the drop section of the Amplify Console.

![](../../images/manual-deploy.png)

Once it's finished uploading, click the "Save and deploy" button to deploy your site.

### Congratulations!

🎉 You've deployed your first website to AWS Amplify! Go check it out by clicking on the URL under the "Domain" section.

![](../../images/site-url.png)
