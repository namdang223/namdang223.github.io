---
layout: post
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
<img src="hhttps://www.freecodecamp.org/news/content/images/2020/08/wireshark-1.png">
</center>
<br><br>
In this weekly blog I am going to be going over how to download Wireshark and how to capture data packets on it. Wireshark is s a packet sniffer and analysis tool. It captures network traffic on the local network and stores that data for offline analysis. Wireshark captures network traffic from Ethernet, Bluetooth, Wireless (IEEE.802.11), Token Ring, Frame Relay connections, and more. 
<br><br>
To download Wireshark on Linux, open up your Ubuntu and in the terminal enter these commands in this order:
<ol>
<li><code style="background-color: grey">sudo apt-get install wireshark</code></li>  
<li><code style="background-color: grey">sudo dpkg-configuration wireshark-common</code></li> 
<li><code style="background-color: grey">sudo adduser $USER wireshark</code></li> 
</ol>
<br>
If you do not have Ubuntu and have Red Hat Fedora, you will need to enter these commands in this order:
<ol>
<li><code style="background-color: grey">sudo dnf install wireshark-qt</code></li>  
<li><code style="background-color: grey">sudo usermod -a -G wireshark username</code></li> 
</ol>
<br>
To download Wireshark on Mac, open up Homebrew and in the terminal enter type in the command <code style="background-color: grey">brew install wireshark</code>.
<br><br>
Kali Linux should have already have Wireshark downloaded as it is part of the basic Kali Linux package.
<br><br>
These commands allow you to download the Wireshark package and then updating it with user priviledges. Now that you have Wireshark downloaded, go ahead and open it up. To start capturing packets, go to the tab at the top that says <code style="background-color: grey">Capture</code>. Follow that up with the button <code style="background-color: grey">Start</code> or press CTRL+E if you would rather use the hotkey instead. 
<br><br>
<center>
<img src="https://i.imgur.com/vi8MGOa.png"> 
</center>
<br><br>
Wireshark will start its capture and show all the packets that it is currently capturing. To stop the capture, you would repeat the same commands but instead of hitting <code style="background-color: grey">Start</code>, you would hit <code style="background-color: grey">Stop</code> instead.
<br><br>
<center>
<img src="https://i.imgur.com/su4hvJv.png"> 
</center>
<br><br>
</p>
  
</body>
</html>
