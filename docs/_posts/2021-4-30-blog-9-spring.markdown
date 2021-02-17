 ---
layout: post
title: "Blog 9 Spring"
date: 2021-04-30 3:23:14 -0700
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
<br><br>
<center>
<img src="https://miro.medium.com/max/581/1*ZAIUpqHK0Y8PUJK0prW8KA.png">  
</center>
<br><br>
In this weekly blog I am going to be going over how to use AWS CloudFront. Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment. The benefits of using AWS CloudFront is that this service is globally scaled meaning that its content delivery is at top speed. Not only is it fast, but it is highly secure and cost-effective making it a reliable and trusted service to use to delivery your content all around the world. 
<br><br>
<center>
<img src="https://d2908q01vomqb2.cloudfront.net/5b384ce32d8cdef02bc3a139d4cac0a22bb029e8/2017/12/19/Picture2.jpg">  
</center>
<br><br>
To start, go ahead and type into the search box <code style="background-color: grey">CloudFront</code> located in the AWS Management Console. When you are on the CloudFront dashboard, click on <code style="background-color: grey">Create Distribution</code> and then <code style="background-color: grey">Get Started</code>. You will be prompted to fill in information about your distribution. The only thing you really need to do here is type the name of your bucket for the <code style="background-color: grey">Origin Domain Name</code>. You can leave everything else here on default and then scroll down all the way to the bottom and hit the blue <code style="background-color: grey">Create Distribution</code>. CloudFront will automatically connect to the bucket that you attached and distributed it worldwide. 
<br><br>
<center>
<img src="https://i.imgur.com/fO7OAjC.png">  
</center>
<br><br>
Your bucket should now be delivered worldwide. Make sure that CloudFront is running by checking under Status. There should be two arrows spinning in a circle saying  <code style="background-color: grey">In Progress</code>. If you see that message, that means your content is now being distributed all around the world. If you ever do want to stop your Distributions, go ahead and click the gear above the distribution and hit <code style="background-color: grey">Stop Distribution</code>. You will know that your distribution is no longer running when the state displays Disabled in all red. Congratulations, you have successfully created a global network delivery system.
</p>
  
</body>
</html>
