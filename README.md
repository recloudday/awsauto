<h1>Deploying a Basic Infrastructure Using CloudFormation Templates</h1>

<h2>Description</h2>
In this lab, I successfully deployed a basic infrastructure using AWS CloudFormation Templates. Initially provided with a JSON template, I converted and edited it to YAML format, making a key modification to change the instance type from 'small' to 'micro.' 
After ensuring the accuracy of the revised YAML template, I proceeded to deploy it using CloudFormation. This exercise enhanced my understanding of CloudFormation syntax and processes, demonstrating my ability to customize and deploy infrastructure efficiently in AWS.
<br />


<h2>Concepts and Utilities Used</h2>

- <b>AWS - CloudFormation</b>
- <b>JSON & YAML</b>
- <b>Automation</b>

<h2>Environments Used </h2>

- <b>AWS</b>
- <b>VPC, EC2, CloudFormation</b>

<h2>Environment walk-through:</h2>

<p align="center">
In CloudFormation -> Resources tab -> Open InternetGateway and WebserverInstance in the tab: <br/>
<img src="https://imgur.com/Ftrqn9f.png" height="80%" width="80%" alt="CloudFormation Steps"/>
<br />
<br />
Update Template, Edit in designer -> Change small to micro in YAML:  <br/>
<img src="https://imgur.com/jeQbM3o.png" height="80%" width="80%" alt="CloudFormation Steps"/>
<br />
<br />
Replace current template and deploy template: <br/>
<img src="https://imgur.com/mHe9fG6.png" height="80%" width="80%" alt="CloudFormation Steps"/>
<br />
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
