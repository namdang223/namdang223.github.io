---
layout: post
title: "Blog 7 Spring"
date: 2021-04-16 3:23:14 -0700
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
In this weekly blog I am going to be explaining how to apply an IAM password policy. The overall purpose of applying an IAM password policy is to strengthen your account and reducing the chances of your account getting hacked. This is a security measure that everyone with an AWS account should take as spending as little as 5 minutes will protect your account astronomically. Now let's get straight to it! Firstly, what you want to do is go to your AWS Management Console and type into the search box <code style="background-color: grey">Identity and Access Management</code>. Under the section labeled as Security Status, go click on <code style="background-color: grey">Apply an IAM password policy</code>. Follow that up with <code style="background-color: grey">Manage Password Policy</code>. You will be given tons of information about the Security Token Service and Endpoints. For now you can ignore those and click on <code style="background-color: grey">Set Password Policy</code>.
<br><br>
<center>
<img src="https://i.imgur.com/meruWM5.png">  
</center>
<br><br>
Now you will be prompt to add rules to your password policies. I would recommend checking off every single box as it will make a hacker breaching your account much more difficult. For the box <code style="background-color: grey">Password expiration requires administrator reset</code> you can leave that box unchecked as it does not add any security to your account. As for <code style="background-color: grey">Enforce minimum password length</code>, you can add how many characters are required for a password. Remember, more characters means the more secure that your password is. I would recommend having 6 characters as a minimum for your password. You should not go any lower than that as hacking your password will be easier. In the box <code style="background-color: grey">Enable password expiration</code>, you can set how many days it will take before your password expires. This is really helpful as changing your passwords consistently makes the breaching of your account much more difficult. By default, the password will expire in 90 days if you have this box checked. 90 days is a good reset day as every 3 months you will be prompted to change your password. When you are done configuring your password policy, you can click on <code style="background-color: grey">Save changes</code> at the very bottom of the page.
<br><br>
<center>
<img src="https://i.imgur.com/kbl1noU.png">  
</center>
<br><br>
After hitting save changes, you should receive a notification that your password policy has been updated in all green with a little check mark by it. Now that you have successfully created a password policy, go back to the <code style="background-color: grey">Identity and Access Management</code> dashboard. You want to check if you have successfully applied an IAM password policy. If there is a green checkmark by <code style="background-color: grey">Apply an IAM password policy</code>, that means you have done everything correctly and have successfully updated your password policy. Your account should be more secured than before. Congrations, you account is now more secure!
<br><br>
<center>
<img src="https://i.imgur.com/zH6nnRo.png">  
<br><br>
<img src="https://i.imgur.com/C2BKb5m.png">
</center>
<br><br>
</p>
  
</body>
</html>
