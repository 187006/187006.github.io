---
layout: post
title: Lab activity
subtitle: Digitalisation
categories: Cybersecurity
tags: [Cybersecurity]
---

### Identifying Search Options in Metasploit

first we started with the command line 
  
    service postgressql start 
    
![datacamp certification](/assets/images/banners/labactivity1/1.png)
 
 to initialize the database we wrote this command
 
    msfdb int
 
 then to display the search command option 
      
    msfconsole search -h
      
![datacamp certification](/assets/images/banners/labactivity1/2.png)

to search the common vunubitlys we wrote 

     msfconsole search CVE-2013-2465
   
![datacamp certification](/assets/images/banners/labactivity1/3.png)

### Analysing the Capture File to Find the Attack(s)

first we started with open caputre file window then we started to open a file and to  observe detail bevor i contuine hocam you wanted us to download i file that i couldnt find so i download antoher file from the internet and did the lab with it:

![datacamp certification](/assets/images/banners/labactivity1/w4.png)

then i click on the menu bar statistic and clicked on conversation normaly we need to click on tcp but my file didnt had any so i countined with udp:

![datacamp certification](/assets/images/banners/labactivity1/w5.png)

after that we sorted the list:
![datacamp certification](/assets/images/banners/labactivity1/w6.png)
 
 in the end we safed the file:
![datacamp certification](/assets/images/banners/labactivity1/w7.png)
## Assessing the impact of malware

for this project  we download a test Malware
![datacamp certification](/assets/images/banners/labactivity1/v10.png)

then we check the details for it in theard history

![datacamp certification](/assets/images/banners/labactivity1/v11.png)

then we click see details
![datacamp certification](/assets/images/banners/labactivity1/v12.png)

## Analysing Protocols with Wireshark
after we ping 10.0.0.1 we opoend wireshark to capture packes
![datacamp certification](/assets/images/banners/labactivity1/2w13.png)

after we captured packes we clickt stop
![datacamp certification](/assets/images/banners/labactivity1/2w14.png)

then we filter the packes 

![datacamp certification](/assets/images/banners/labactivity1/2w15.png)
## Confirming the Spoofing Attack in Wireshark

 first we tip in ipconf and ping 8.8.8.8
 
![datacamp certification](/assets/images/banners/labactivity1/3w16.png)

then we started to capture packes  and filter them

![datacamp certification](/assets/images/banners/labactivity1/3w17.png)

## Exploiting a Website Using SQL Injection
for that we couldnt do it becouse we didnt had a localhost:
![datacamp certification](/assets/images/banners/labactivity1/18.png)


## Reflection

One lab activity we couldn't do was using the GMER software because our antivirus programs gave us warnings about its safety. After conducting some research, we discovered that the last update for GMER was in 2016. Another problem my friend and I faced was the lab activity of uploading the Trojan horse simulator to VirusTotal. We didn't have the file, and honestly, we didn't know where to download it from. Due to the risk involved, we decided to skip this lab activity.

First of all, the lab activities were diverse and interesting, especially the test malware activity that allowed us to see how our antivirus software works. I didn't even know something like that existed. Additionally, the Wireshark activities were fascinating, as they showcased the various capabilities of Wireshark.

Overall, it was a fun and truly interesting experience. I learned new things such as how Confirming the spoofing , how to analyze capture files, and how to identify search options in Metasploit, among others. It was a new and valuable learning experience, and I'm happy that I had the opportunity to participate in it.
