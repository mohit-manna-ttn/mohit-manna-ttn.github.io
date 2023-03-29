---
layout: post
title:  "How I reused my old android phone"
date:   2023-03-29 11:24:28 +0530
categories: flask, ubuntu, android
---
# Why did I do this ?
I have a personal website written in Flask and Javascript which I wrote back in winter of 2020 when I was trying my hands on Flask, Mongo DB and Javascript.
I wrote the website in order to learn Flask and Mongo. It is not quite ploished one but I do have a regular user who uses it daily.My only motivations to keep it running. 
I have been hoisting it in AWS EC2 Free Tier accounts since 2020 but was fed up of ignoring AWS Bill mails and redeploying everything in new account whenever account got seized by AWS.
As I write this blog AWS is asking for Rs 800/mnth for AWS Micro instance. As fas as I can remember I've been paying Rs 140/mnth for same thing in 2021. So i can not rely much on AWS.
Also, the website that I wrote is not completely deployed in AWS! The Database is in MonogDB Cloud (Another Free Service). So even if my website goes down the data is safe, only the webserver stops. 
Once the webserver starts it automatically connects to MongoDB cloud and everything is as it is. 

##### What about pricing of MongoDB?
MongoDB cloud is free and since I am using storing only textual data. It is quite small. It would be max 5 MB. So it is not going to need paid subscription in near future. 


