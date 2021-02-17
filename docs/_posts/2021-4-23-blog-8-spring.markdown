---
layout: post
title: "Blog 8 Spring"
date: 2021-04-23 3:23:14 -0700
categories: Senior Design
---

<html>

<style>

.site-title, .site-title:visited {
    color: #ffffff;
}

.site-nav .page-link {
    color: #fff;
    line-height: 1.5;
}

html, body, h2, h3, p {
color:white;

}

h1 {
  font-family:impact;
}

body {
background-image: url("https://www.musictruth.com/wp-content/uploads/2018/05/Screen-Shot-2018-04-28-at-7.46.41-PM.jpg");
background-size: cover;
}

</style>

  
<body style="background-color:black;">
<p style="font-family:verdana;color:white">
In this weekly blog I am going to be going over how to create an AWS Cost and Usage report. The AWS Cost & Usage Report contains the most comprehensive set of AWS cost and usage data available, including additional metadata about AWS services, pricing, Reserved Instances, and Savings Plans. Now let's get straight to it. The first thing that you want to do is log into your AWS account and at the top right hand corner, click on your name and then my billing dashboard. After that you want to click on <code style="background-color: grey">Cost & Usage Reports</code> on the tabs located at the left side of the page. Once you have done all that, you are set to create a report. Click on the blue <code style="background-color: grey">Create Report</code>.
<br><br>
<center>
<img src="https://i.imgur.com/s66aTtZ.png">  
</center>
<br><br>
The first thing that you need to do in the report content is create a <code style="background-color: grey">Report Name</code>. Name it whatever you want and check off the boxes <code style="background-color: grey">Include resources IDs</code> under the section additional report details and check off <code style="background-color: grey">Automatically refresh your Cost & Usage Report when charges are detected for previous months with closed bills</code> under the section Data refresh settings. When that is done you can go ahead and click on the blue <code style="background-color: grey">Next</code>.
<br><br>
<center>
<img src="https://i.imgur.com/e2RuIkL.png">  
</center>
<br><br>
Within the delivery options, you want to click <code style="background-color: grey">Configure</code>. You are given the option to either create a new bucket or select an existing bucket. You will be prompted to verify the policy and you can click <code style="background-color: grey">Save</code>. Now back in the delivery options, you can decide whether or not you want to have your Cost & Usage report measured hourly or daily. Select which one you like the best. Under report versioning, check off the box <code style="background-color: grey">Create new report version</code> so that you will get brand new reports every single time rather than having previous reports overwritten. Under compression type, choose any type you want but <code style="background-color: grey">ZIP</code> is the most standard one and should be the one you use. Click on the blue <code style="background-color: grey">Next</code>. Finally you can create the report by clicking <code style="background-color: grey">Review and Complete</code> at the bottom.
<br><br>
<center>
<img src="https://i.imgur.com/WCvrnf3.png">  
</center>
<br><br>
You will receive a green confirmation stating that your report has been created successfully. Depending on whether or not you chose hourly or daily, you will receive a Cost & Usage Report based on the time granularity that you chose. Congratulations, you have successfully created an automated Cost & Usage Report. If you want to view your report, you can simply find your bucket that you created for your Cost & Usage Report and then click on it. It should open up an Excel document for you with all the data and usage reported. 
<br><br>
<center>
<img src="https://i.imgur.com/up0xI2i.png">  
</center>
<br><br>
</p>
  
</body>
</html>
