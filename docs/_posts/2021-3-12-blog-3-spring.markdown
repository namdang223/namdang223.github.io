---
layout: post
title: "Blog 3 Spring"
date: 2021-03-12 3:23:14 -0700
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
In this weekly blog I am going to be going how to change your billing preferences with budgets and set up alarms so that you do not get over billed. You will be able to check and see what you are being billed for and an alarm will be set so that if you are over your billing limit you will be notified just in case you forget to turn off an instance and it keeps running. Let's get straight to it! First off at the top right of your account click on your account name and then the <code style="background-color: grey">My Billing Dashboard</code>. Once you did that, click on <code style="background-color: grey">Billing Preferences</code> at the left hand tab. I would recommend checking off all three of the available billing preferences so that you will receive a PDF invoice by email, free tier usage alerts, and to receive billing reports. 
<br><br>
<center>
<img src="https://i.imgur.com/CqhnQ1d.jpg">
</center>
<br><br>
Now that all of your billing preferences at set up. Go back to your AWS Management Console and type in <code style="background-color: grey">"Budgets"</code> into the search box. Check off cost budget and then select <code style="background-color: grey">Set your budgets</code>. This should take you to the next step where you have to create your own budget. So for this, add a <code style="background-color: grey">name</code> for your budget, it can be anything you want. Keep the <code style="background-color: grey">period</code> on monthly so that you can receive reports on a monthly basis. Next up keep the budget effective dates on <code style="background-color: grey">Recurring budget</code> and make sure that the budget amount is on <code style="background-color: grey">Fixed</code>. After that set a budgeted amount. This is how much you want to set your budget as so when you do go over, a notification will pop-up telling you that you have passed your limit. For <code style="background-color: grey">Aggregated Costs</code> keep everything on default. It should be on <code style="background-color: grey">Unblended costs</code> and everything cost related to should be checked off. Click <code style="background-color: grey">Configure Alerts</code> at the bottom when you are done.
<br><br>
<center>
<img src="https://i.imgur.com/aXXtZyk.jpg">  
</center>
<br><br>
Next up is to configure your alerts. In the <code style="background-color: grey">Email contacts</code> box, add your email contact so that the alert will send a notification to your email. In the <code style="background-color: grey">Alert threshold</code> box, add the % of the budgeted amount you want for the alert. I recommend keeping it at 100% so that when you do go past your 100% threshold you will be alerted instantly. Once that is all set up, click <code style="background-color: grey">Confirm budget</code> followed by <code style="background-color: grey">Create Budget.</code>
<br><br>
<center>
<img src="https://i.imgur.com/RxnjgY7.jpg">
</center>
<br><br>
The last thing you need to do is create the alarm. Go back to the AWS Management Console and type in <code style="background-color: grey">CloudWatch</code> into the search box. On the left hand side, click on <code style="background-color: grey">Alarms</code>. You get 10 free alarms with the AWS free tier so click on <code style="background-color: grey">Create alarm</code>. Leave everything on default except for the <code style="background-color: grey">threshold value</code>. Set this to your desired amount so that when the threshold is surpassed, an alarm will go over for you. Click on next and check off <code style="background-color: grey">Select an existing SNS topic</code> and that should auto-config your alarm state to <code style="background-color: grey">in Alarm</code>. Add an email list so that you will receive the email personally. Click on next and add a unique name for you alarm. Click next and then <code style="background-color: grey">Create alarm</code>. You have successfully set up your budget with a billing alarm.
<br><br>
<center>
<img src="https://i.imgur.com/4cSLjGG.jpg">  
</center>
<br><br>
</p>
  
</body>
</html>
