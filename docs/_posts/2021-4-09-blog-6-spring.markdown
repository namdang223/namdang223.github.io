---
layout: post
title: "Blog 6 Spring"
date: 2021-04-09 3:23:14 -0700
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
<img src="https://images.squarespace-cdn.com/content/v1/51814c87e4b0c1fda9c1fc50/1528473310893-RH0HG7R5C0QURMFQJBSU/ke17ZwdGBToddI8pDm48kOyctPanBqSdf7WQMpY1FsRZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpyD4IQ_uEhoqbBUjTJFcqKvko9JlUzuVmtjr1UPhOA5qkTLSJODyitRxw8OQt1oetw/600px-AWS_Lambda_logo.svg.png?format=500w">
</center>
<br><br>
In this weekly blog, I am going to be going over how to run an AWS Lambda function. AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers, creating workload-aware cluster scaling logic, maintaining event integrations, or managing runtimes. With Lambda, you can run code for virtually any type of application or backend service with zero administration. Now that you know a little bit more about AWS Lambda, let's get straight to it! First off, you will need to type in <code style="background-color: grey">Lambda</code> into the search box located in your AWS Management Console. When you are on the Lambda dashboard, go ahead and click on <code style="background-color: grey">Create Function</code>. Here you will need to fill in basic information such as the <code style="background-color: grey">Function name</code> and the <code style="background-color: grey">Runtime</code>. For the function name, you can put whatever name you want. For runtime, select whatever language you prefer to use. Under all of that, there will be a section that says permissions. Here you want to give the execution role <code style="background-color: grey">Create a new role with basic Lambda permissions</code>. Once all of that is complete, go ahead and click on <code style="background-color: grey">Create function</code> at the bottom right corner. 
<br><br>
<center>
<img src="https://i.imgur.com/98iJhnZ.png">  
</center>
<br><br>
Your Lambda function should now be up and running. Note that Lambda runs the code without using a server with the trade-off that it does not run very long. Add the bottom of the Lambda function, there is a section that says <code style="background-color: grey">Function code</code> and this is where you will be inputting your code to run without a server. Next up, you should test if your Lambda function works. Within the function code, type in <code style="background-color: grey">puts "Hello world"</code> if you are using Ruby as your main language. After that, scroll all the way to the top of the page and hit <code style="background-color: grey">Test</code>. Give your test an <code style="background-color: grey">Event Name</code>. Again it can be anything you want to name it as. Go ahead and click <code style="background-color: grey">Create</code>.
<br><br>
<center>
<img src="https://i.imgur.com/DyTnKmt.png">  
</center>
<br><br>
You will now be prompt with an execution result saying it succeeded in all green. If you expand the details arrow it should give you a log of your execution result. Make sure to click <code style="background-color: grey">Save</code> next to the test tab as Lambda will not automatically save your work. If you did all of this correctly your log output message should say <code style="background-color: grey">Hello World</code>. Congratulations, you have successfuly created a Lambda function. Now you can enter in whatever code you want to run and AWS Lambda should provision your code with a server.
<br><br>
<center>
<img src="https://i.imgur.com/tNc16jI.png">  
</center>
<br><br>
</p>
  
</body>
</html>
