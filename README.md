<h1> - AWS BUDGET</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this lab I	Used AWS Budgets to set custom budgets for tracking costs and usage of resources in an AWS account. Setting up alerts by email when actual or forecasted cost and usage exceed budgeted threshold.
<br />




<h2>Environments Used </h2>

- <b>AWS CONSOLE </b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch AWS CONSOLE AND LOG IN: <br/>
<img src="https://i.imgur.com/j9g8KMv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On AWS console home navigate to AWS BUDGETS:  <br/>
<img src="https://i.imgur.com/eDT2vgd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click on create budget: <br/>
<img src="https://i.imgur.com/9BzEnQ3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select customized (advanced) and click on cost budget the scroll down and click on 'Next':  <br/>
<img src="https://i.imgur.com/Au457NM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Input the name you want for your budget :  <br/>
<img src="https://i.imgur.com/e57jASt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Set budget amount in this case I set my budget to 1$ :  <br/>
<img src="https://i.imgur.com/FycfmDq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For budget scope, click on the drop down arrow and select all the budgeting will cover, I selected all then click on 'Next'  <br/>
<img src="https://i.imgur.com/aEs0kkj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Then configure alerts by selecting 'Add alert threshold'  <br/>
<img src="https://i.imgur.com/lsFC7Gk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Set the percentage of your threshold, In my case I set it to 80% so When your actual cost is greater than 80.00% ($0.80) of your budgeted amount ($1.00), the alert threshold will be exceeded,Also input an E-mail that would be notified if you have exceeded your threshold.. After that click on 'Next'  <br/>
<img src="https://i.imgur.com/YM7fnf8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Review all you have inputed if correct scroll down and click on 'Create Budget'  <br/>
<img src="https://i.imgur.com/FvrkLiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Budget successfully created!:  <br/>
<img src="https://i.imgur.com/tYKXCYP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
