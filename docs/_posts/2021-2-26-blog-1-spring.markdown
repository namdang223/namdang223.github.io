---
layout: post
title: "Blog 1 Spring"
date: 2021-02-26 3:23:14 -0700
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
In this weekly blog I am going to be going over how to create an individual IAM user on Amazon Web Services. So to start off, go to your IAM Management Console by searching in <code style="background-color: grey">IAM Management Console</code> into the search box at the top. After that, click on <code style="background-color: grey">Manage Users</code>. Next click <code style="background-color: grey">Add User</code> in blue at the top.
<br><br>
<center>
<img src="https://i.imgur.com/4mDOcDM.jpg">
</center>
<br><br>
Next is to create a user. Type in any username you want and under the access types, check off <code style="background-color: grey">Programmatic Access</code> and <code style="background-color: grey">AWS Management Console access</code>. Keep the password on <code style="background-color: grey">Autogenerated password</code> and make sure that <code style="background-color: grey">Requires password reset is checked off</code>.
<br><br>
<center>
<img src="https://i.imgur.com/8fdqq60.jpg">
</center>
<br><br>
Once all of that is done, add the user into the group that you want. If you do not have a group, you can simply create a group in the tab at the top. Select the new the user that you created and add it into the group. Hit create user at the bottom and an access key should be created for the user. 
<br><br>
<center>
<img src="https://i.imgur.com/z8XjVCK.jpg">  
</center>
<br><br>
Congratulations! You new IAM user has been created. You can double check this by going back to the <code style="background-color: grey">Identity and Access Management Console</code> and see if <code style="background-color: grey">Create individual IAM users</code> has a green check mark next to it.
<br><br>
<center>
<img src="https://i.imgur.com/Qn6gQrf.jpg">  
</center>
<br><br>
</p>
  
</body>
</html>
