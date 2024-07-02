<h1> Deploying an Application with AWS Elastic Beanstalk (AWS) </h1>


<h2>Description</h2>
In this lab, I worked with an AWS Elastic Beanstalk environment that was pre-created for me. I deployed code to it and observed the AWS resources that make up the Elastic Beanstalk environment. First, I accessed the AWS Management Console and launched the lab environment. Then, I navigated to the Elastic Beanstalk console, where I verified the health of the pre-created environment. I tested the environment by accessing its domain link, which initially displayed a 404 error as expected since no application was running yet. Next, I downloaded a sample application and deployed it to the Elastic Beanstalk environment using the Upload and Deploy feature. Once the deployment was complete, I accessed the domain link again, and this time, the web application displayed successfully. I explored the Elastic Beanstalk console further, noting details such as EC2 Security groups, instance types, and scaling configurations. I also explored the EC2 instances supporting the application, which included a load balancer and an Auto Scaling group.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Amazon Web Services (AWS) Management Console: For managing the Elastic Beanstalk environment.</b>
- <b>AWS Elastic Beanstalk: For deploying and managing the web application.</b>
- <b>AWS EC2: For the instances running the web application.</b>
- <b>ZIP: For packaging the sample application.</b>

<h2>Program Screenshots:</h2>

<p align="center">
Environments settings: <br/>
<img src="https://i.imgur.com/hbQfLVf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
HTTP Status 404 Error - Application Server doesn't have an application running on it yet. :  <br/>
<img src="https://i.imgur.com/KzQeKwK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deploy a sample application to Elastic Beanstalk: <br/>
<img src="https://i.imgur.com/5HypS3x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Results of the refreshed web page  :  <br/>
<img src="https://i.imgur.com/ntb7Fyn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
CPU Utilization graph: <br/>
<img src="https://i.imgur.com/iSWgNwW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Status of EC2 instances :  <br/>
<img src="https://i.imgur.com/i6dvBfH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
