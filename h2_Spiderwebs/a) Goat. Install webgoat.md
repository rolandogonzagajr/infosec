# STEPS in Webgoat Installation in VirtualBox ( MAC OS )

1. Install Java (and some helpful tools) by typing the following in the terminal:

$ sudo apt-get update

Then will look like  screenshot below after. 
<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Update.png">

then type the following on the terminal

$ sudo apt-get -y install openjdk-17-jre ufw wget bash-completion

then will look like the below screenshot after.
<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.2.png">

Then enable firewall by typing the following:

$ sudo ufw enable
 screenshot looks like this after

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Firewall.png">
 
then Install by typing the below in the terminal

$ wget https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar

scrreenshot below shows after

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Install.png">


then run by typing the below

$ java -jar webgoat-server-8.0.0.M26.jar
then screenshot below ehen succesful

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.webgoat.png">

then open Open WebGoat in browser
http://localhost:8080/WebGoat/

then follow the registration process after which youre ready to hack.

screenshor below inside Webgoat

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.WebgoatPage.png">

