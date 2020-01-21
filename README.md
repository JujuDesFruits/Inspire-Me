# Inspire Me
 Inspire Me is an application for android & a web site where people in search of inspiration can get one from the user's proposition.   

---

To Access to the website click on this [link](#)  
To Acces to play store click on this [one](#)

---   

here is screens from app and website:   
![home website](#/img/home_website.jpg)
![home app](#/img/home_app.jpg)
![category website](#/img/category_website.jpg)
![category app](#/img/category_app.jpg)
![top website](#/img/top_website.jpg)
![top app](#/img/top_app.jpg)
![list website](#/img/list_website.jpg)
![list app](#/img/list_app.jpg)

**Author:** [Julien TRIJEAN](https://am-i-an.unusualperson.com)   
**Contact:** julien.trijean@gmail.com

[Learn more about the project on wiki]()

## Technical Documentation
 The project was created using [Ansible](), [Android studio](), [GitHub](), [HTML5](), [CSS](), [PHP](), [Hbase](), [Ubuntu]()

To deploy and configure the Ubuntu server, I use ansible script you could find in [/deploy](#/deploy/) folder.
Website and app store data to an Hbase Database on the same Ubuntu server hosting the website.
Dump from database are collected on another Ubuntu server in case of troubles.

Android studio was used to create the mobile application. The java code is accessible in [/android](#/android/) folder. To download the *.apk* application, follow the play store link above.

The website is store in [/site](#/site/) folder. This could be deploy by using the action button in GitHub project.

All contribution would be very welcoming. Contact the author and let him know how you could help him.

## Security
 In order to protect users data, all transaction between the app, the website and the server are crypt with SSL. Also server are protected by a firewall, strong password connection and alerting. Connection to database require identification.

## Collected data
 All user's data are collected with the approbation of the user. To protect users from stolen data, there password are hashed and cannot be retrieve. If a users forgot his password, a process will send him a temporary password to his email. Collected data are necessary to offer the services in the application.   
General Data Protection Regulation from European Union are respected during the hole conception of the project.

Copyright (c) 2020 Copyright Holder All Rights Reserved.
