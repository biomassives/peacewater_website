---
heading: Infrastructure
sub_heading: Engineering and Health Sciences
layout: home
title: Database infrastructure
banner_image: ''
hero_button:
  text: ''
  href: ''
textline: ''
services: []
show_news: true
partners: []
show_staff: false

---

Digital ocean Strapi hosting provides a backbone of reliability and security to our project..

ECHO Peace uses http://143.198.0.252 

as the primary source of truth for our database.

Backup methodology:

   Log in via ssh, 

   create pgsql dump file

   pwd  // note directory 

   ls // (note backclip filename)

   exit // ( to local terminal environment)

   scp -i key.pem ubuntu@{server_ip}/path/filename .

note key.pem refers to the security key downloaded from digital ocean, 'secure file transfer' SCP allows use of user,password as well

   scp ubuntu@{server_ip}/path/filename .

note that ubuntu refers to the user on D.O.'s Ubuntu server.

scripted backup:

connect to server via ssh

   

digital ocean with docker

via 'marketplace' install for digital ocean

143\.198.0.252