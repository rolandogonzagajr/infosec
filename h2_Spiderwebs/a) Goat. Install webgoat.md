# STEPS in Webgoat Installation in VirtualBox ( MAC OS )

1. Install Java (and some helpful tools) by typing the following in the terminal:

$ sudo apt-get update

Then will look like  screenshot below after. 
<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Update.png">

then type the following on the terminal

$ sudo apt-get -y install openjdk-17-jre ufw wget bash-completion

then will look like the below screenshot after.
<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Update.png">

This command works with Debian 12-Bookworm. If you run an older system, you might need an older version of OpenJDK Java. For example, Debian 11 Bullseye has "openjdk-11-jre". Webgoat version 8 used in this article works with both Java versions.

Enable firewall.

$ sudo ufw enable
Install and Run WebGoat
Download and run Webgoat 8:

$ wget https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar
$ java -jar webgoat-server-8.0.0.M26.jar

<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Update.png">

