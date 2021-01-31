---
layout: post
title: "Blog 0 Spring"
date: 2021-02-19 3:23:14 -0700
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
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Virtualbox_logo.png">
</center>
In this weekly blog I am going to be going over how to use Kali Linux inside of a virtual machine using a disc image file. First off, you are going to need a virtual machine to run Kali Linux. I recommend using Oracle Virtual Machine which can be downloaded <a href="https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html" target="_blank">here</a>. Along with the virtual machine, download the Kali Linux disc image file which can be found <a href="https://mycsun.box.com/s/83gdhcbt4kwqc7vbhfqte14ol9qobd2p" target="_blank">here</a>.
<br><br>
Once both the virtual machine application and Kali Linux disc image file are downloaded, go ahead and open up Oracle Virtual Machine. At the top, click on <code style="background-color: grey">New</code> and you should be able to name your operating system. Name your virtual machine anything you want and choose a destination where you want the files to be downloaded onto your computer. Select <code style="background-color: grey">Linux</code> for what type of operating system this virtual machine is going to be running on and for version select <code style="background-color: grey">Linux 2.6/3.x/4.x(64bit)</code> to ensure that you are running the latest version available. Hit next to continue to the next steps.
<br><br>
<center>
<img src="https://i.imgur.com/XQGExkU.jpg">
</center>
<br><br>
Next up select your memory size. The default memory size is 1024 but you should increase it if you have more than 8gb of RAM. Hit next and selection the option <code style="background-color: grey">Create a virtual hard disk now</code>. Hit create and select <code style="background-color: grey">VDI(Virtual Disk Image)</code>. Press next and select dynamically allocated. Press next once again and now select how much file size you are willing to input into the virtual machine with 8gb being the default. Once you select how much file size you want, create your virtual machine.
<br><br>
<center>
<img src="https://i.imgur.com/rhQf1Ui.jpg">
</center>
<br><br>
  Once you have configured your virtual machine, click on <code style="background-color: grey">settings</code> at the top. Find the <code style="background-color: grey">storage</code> tab on the left and click on the disk with a green plus sign on it. Select the Kali Linux ISO file that you downloaded earlier and hit choose. Press <code style="background-color: grey">OK</code> at the bottom and your virtual machine is ready to run.
<center>
<img src="https://i.imgur.com/LnAcUQe.jpg">
</center>
<br><br>
Finally you can run your virtual machine by clicking on the green <code style="background-color: grey">start</code> button at the top. An option on the virtual machine will pop up telling you to select a virtual optical disk file and make sure it is your Kali Linux ISO. Press start once again and your virtual machine should be running Kali Linux.
<br><br>
<center>
<img src="https://i.ytimg.com/vi/Q59X30GoJvg/maxresdefault.jpg">
<br><br>
</center>
</p>
  
</body>
</html>


