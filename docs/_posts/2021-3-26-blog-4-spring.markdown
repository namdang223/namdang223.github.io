---
layout: post
title: "Blog 4 Spring"
date: 2021-03-26 3:23:14 -0700
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
<center>
<img src="https://img.wonderhowto.com/img/25/02/63554002480751/0/hack-like-pro-metasploit-for-aspiring-hacker-part-4-armitage.1280x600.jpg"> 
</center>
<br><br>
In this weekly blog I am going to be showing you how to attack Metasploitable using armitage on Kali Linux all within a virtual machine. Before you start, make sure that you have properly configured both Metasploitable and Kali Linux onto your virtual machine. The virtual machine I will be demonstrating this hack on is Oracle VM Virtual Box. Once you have all of that ready to go, you are now ready to start. Let's get to it! Within your Kali Linux VM, you will need to set up a metasploit-framework and Armitage. To do this, open up your terminal and type in the code <code style="background-color: grey">systemctl start postgresql</code>. Then type in the code <code style="background-color: grey">msfdb init</code>. Once everything is loaded, type into your console <code style="background-color: grey">Armitage.</code>
<br><br>
<center>
<img src="https://i.imgur.com/ohzSNH8.jpg">  
</center>
<br><br>
Keep everything on default and then click <code style="background-color: grey">Connect</code>. A pop-up message will ask if you want to start up Metasploitable and you will click <code style="background-color: grey">YES</code>. The Armitage GUI should automatically open up and everything should be set. On the top tab, click on <code style="background-color: grey">Host</code> followed by <code style="background-color: grey">MSF Scans</code>, and then <code style="background-color: grey">Quick Scan(OS Detect)</code>. This will start a scan of your system. This takes a few minutes so go ahead and get yourself a drink or something to eat in the meanwhile. 
<br><br>
<center>
<img src="https://i.imgur.com/Q24SgI2.jpg">  
</center>
<br><br>
When the scan is finished, click on <code style="background-color: grey">Attack</code> at the top tab. After that click on <code style="background-color: grey">Find attack</code> and then enter in the IP address for Metasploitable. You can find the IP address for your Metasploitable by typing <code style="background-color: grey">ifconfig</code> into your Metasploitable command line. Next up, you want to right click on the monitor with the penguin and click <code style="background-color: grey">Attack</code> and then select any hack you want. For this hack, select any trojan backdoor attack.
<br><br>
<center>
<img src="https://i.imgur.com/ts0ri0w.jpg">  
</center>
<br><br>
After you have selected your attack, the penguin on the monitor should be enraged and there should be lightning around the penguin. This is to show that the IP address is currently being attacked. Right click on the penguin with lightning in the monitor, and click <code style="background-color: grey">host</code> followed by <code style="background-color: grey">shell</code> and then click <code style="background-color: grey">Interact</code>. The next step is to deface the website. In the terminal of Armitage, type <code style="background-color: grey">rm -r</code> to remove any files you do not want on that IP address. You can upload a file on Armitage by clicking on <code style="background-color: grey">Upload</code> but make sure to type <code style="background-color: grey">CHMOD 777</code> after it so it has proper permissions. You will now be able to change or add any files to the attacked computer. 
<br><br>
<center>
<img src="https://i.imgur.com/j75GWBn.jpg">  
</center>
<br><br>
You can do anything you want to the attacked computer. Keep in mind computer integrity and morals so do not do to others what you would not want to do to yourself. With great power comes great responsibility.
</p>
  
</body>
</html>
