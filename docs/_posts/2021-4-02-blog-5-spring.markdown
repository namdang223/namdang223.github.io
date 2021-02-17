---
layout: post
title: "Blog 5 Spring"
date: 2021-04-02 3:23:14 -0700
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
<br>
<center>
<img src="https://www.logicata.com/wp-content/uploads/Amazon-EC2@4x-e1593195270371.png">
</center>
<br><br>
In this week's blog I am going to be going over how to create an EC2 Instance. If you do not know what an EC2 is, it stands for Amazon Elastic Compute Cloud (Amazon EC2) and is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Advantages of using an EC2 is that you can increase and decrease capacity within minutes instead of waiting longs hours. Now that you know a little bit more about what an EC2 instance is, let's get straight to it! Starting off, you want to go to your AWS Management Console and type in <code style="background-color: grey">EC2</code> into the search box. Once you are on the EC2 dashboard, go ahead and click on <code style="background-color: grey">Launch Instance</code>.
<br><br>
<center>
<img src="https://i.imgur.com/pildHx1.jpg">  
</center>
<br><br>
There will be a lot of Amazon Machine Images(AMI) that you can choose from. Depends on what type of Operating System you want you use, you would click the one that is necessary for it. For me I am going to use <code style="background-color: grey">Amazon Linux 2 AMI(HVM), SSD Volume Type</code>. Hit <code style="background-color: grey">Select</code> once you have selected your AMI. The next thing that is prompted is for you to choose an instance type. This is going to be the size of your instance. I recommend using the default <code style="background-color: grey">t2.micro</code> because it is free compared to the others that charge you heavily by the hour. 
<br><br>
<center>
<img src="https://i.imgur.com/euhHBQX.jpg">
<br><br>
<img src="https://i.imgur.com/pAwdGke.jpg">
</center>
<br><br>
The next thing you want to do is click on <code style="background-color: grey">Next: Configure Instance Details</code> at the bottom right corner. This is where you get to customize your instance details. You can set the amount of instances you want to run, which network it is running on, and auto-assign public IP to the instance. For the tab that says <code style="background-color: grey">IAM Role</code>, you should add any IAM role you have or create a new one if you do not have one. This gives your instance specific permissions for when it runs. When you have all that ready and good to go, click on <code style="background-color: grey">Next: Add Storage</code> at the bottom of the page. 
<br><br>
<center>
<img src="https://i.imgur.com/fwzHwVL.jpg">  
</center>
<br><br>
This is where you get to choose the amount of storage your instance gets. By default, the storage size for an EC2 is 8gb. Keep it on 8gb and for volume type, keep it on the default <code style="background-color: grey">General Purpose SSD(gp2)</code>. After that, click on <code style="background-color: grey">Review and Launch</code> at the bottom of the page. Following that, click <code style="background-color: grey">Launch</code> once more that the bottom of your page. You will now be prompted to select a key pair or to create a new key pair. You can either choose an existing key pair or create a new one but for the purpose of this demonstration, I am going to be clicking on <code style="background-color: grey">Proceed without a key pair</code>. Last but not least, you can hit <code style="background-color: grey">Launch</code>.
<br><br>
<center>
<img src="https://i.imgur.com/1vIAftc.jpg">  
</center>
<br><br>
If you did everything correctly, you should be prompted with a green box saying that your instances are now launching. Click on <code style="background-color: grey">View Instances</code> to see your newly created instance. It takes a few minutes for the instance to successfully launch so refresh every minute or two until it has a green check mark and says that it is running. Congratulations, you have successfully launched an EC2 instance!
<br><br>
<center>
<img src="https://i.imgur.com/M8SQTul.jpg">  
</center>
<br><br>
</p>
  
</body>
</html>
