![Inspire-Me](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/logo.png)   
 Inspire Me is an application for android & a web site where people in search of inspiration can get one from the user's proposition.   

---

To Access to the website click on this [link](#)  
To Acces to play store click on this [one](#)

---   

here is screens from app and website:   
![home website](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/home_website.jpg)
![home app](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/home_app.jpg)
![category website](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/category_website.jpg)
![category app](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/category_app.jpg)
![top website](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/top_website.jpg)
![top app](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/top_app.jpg)
![list website](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/list_website.jpg)
![list app](https://github.com/JujuDesFruits/Inspire-Me/blob/master/img/list_app.jpg)

**Author:** [Julien TRIJEAN](https://am-i-an.unusualperson.com)   
**Contact:** julien.trijean@gmail.com

[Learn more about the project on wiki](https://github.com/JujuDesFruits/Inspire-Me/wiki)

## Technical Documentation
 The project was created using [Ansible](https://www.ansible.com/), [Android studio](https://developer.android.com/studio), [GitHub](https://github.com/), HTML5, CSS, PHP, [MongoDB](https://www.mongodb.com/), [Ubuntu](https://ubuntu.com/)

To deploy and configure the Ubuntu server, I use ansible script you could find in [/deploy](https://github.com/JujuDesFruits/Inspire-Me/blob/master/deploy/) folder.
Website and app store data to an MongoDB Database on the same Ubuntu server hosting the website.
Dump from database are collected on another Ubuntu server in case of troubles.

Android studio was used to create the mobile application. The java code is accessible in [/android](https://github.com/JujuDesFruits/Inspire-Me/blob/master/android/) folder. To download the *.apk* application, follow the play store link above.

The website is store in [/site](https://github.com/JujuDesFruits/Inspire-Me/blob/master/site/) folder. This could be deploy by using the action button in GitHub project.

All contribution would be very welcoming. Contact the author and let him know how you could help him.

## Security
 In order to protect users data, all transaction between the app, the website and the server are crypt with SSL. Also server are protected by a firewall, strong password connection and alerting. Connection to database require identification.

## Collected data
 All user's data are collected with the approbation of the user. To protect users from stolen data, there password are hashed and cannot be retrieve. If a users forgot his password, a process will send him a temporary password to his email. Collected data are necessary to offer the services in the application.   
General Data Protection Regulation from European Union are respected during the hole conception of the project.

Copyright (c) 2020 Copyright Holder All Rights Reserved.
