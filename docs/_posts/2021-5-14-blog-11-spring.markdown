yout: post
title: "Blog 10 Spring"
date: 2021-05-07 3:23:14 -0700
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
<img src="https://p2zk82o7hr3yb6ge7gzxx4ki-wpengine.netdna-ssl.com/wp-content/uploads/Amazon-RDS-1.png">  
</center>
<br><br>
In this week's blog I am going to be going over how to create an Amazon RDS database. Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups. It frees you to focus on your applications so you can give them the fast performance, high availability, security and compatibility they need. Now, let's get straight to it. Open up your Amazon Management Console and inside the search box, type in <code style="background-color: grey">Amazon RDS</code>. On the left hand side, click on <code style="background-color: grey">Databases</code> and click on the orange <code style="background-color: grey">Create database</code>. You will now be prompted to create your database. Under choose a database creation method, keep it on the default <code style="background-color: grey">Standard Create</code>. For engine options, you can choose whichever engine you want but I recommend staying away from Amazon Aurora as it is the most expensive of the engines. 
<br><br>
<center>
<img src="https://i.imgur.com/ZnOqsB3.png">  
</center>
<br><br> 
Under Templates, select the <code style="background-color: grey">Free Tier</code>. The only thing you need to do left on this page is to create a <code style="background-color: grey">Master Password</code>. Type in any password you want and then re-type it in the <code style="background-color: grey">Confirm password</code> box right under it. Under DB instance size select the instance size you want. <code style="background-color: grey">t.2 Micro</code> is the default instance size as it is small and enough for the database. Though nano is the smallest, it is not available for Amazon RDS. Under storage, the default allocated storage is <code style="background-color: grey">20</code> and the storage type is <code style="background-color: grey">General Purpose(SSD)</code>. You can go ahead and uncheck <code style="background-color: grey">Enable storage autoscaling</code> under Storage autoscaling because you do not need that.
<br><br>
<center>
<img src="https://i.imgur.com/uSrVs4Q.png">  
</center>
<br><br> 
Under additional configurations, type in an <code style="background-color: grey">Initial database name</code> to name your RDS. You can decide whether or not you want to <code style="background-color: grey">Enable automatic backups</code> or not. If you have it disabled, the chances of you losing data is higher but the RDS will boot up and load way faster. Under performance insights, uncheck the box <code style="background-color: grey">Enable Performance Insights</code> and you should be done. Hit the orange <code style="background-color: grey">Create database</code> at the very bottom. You will be alerted with a green text box that says your database has successfully been created. If you click on the RDS database you can view connectivity and security.
<br><br>
<center>
<img src="https://i.imgur.com/wQ7xn8M.png">  
</center>
<br><br> 
Congratulations, you have successfully created an Amazon Relational Database. If you ever do want to delete your database, click on <code style="background-color: grey">Actions</code> and then <code style="background-color: grey">Delete</code>. Type in <code style="background-color: grey">delete me</code> into the box and then the orange <code style="background-color: grey">delete</code>. Hit refresh and your current database will be deleted.
<br><br>
</p>
  
</body>
</html>
