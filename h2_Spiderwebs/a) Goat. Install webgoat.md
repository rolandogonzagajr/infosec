# WebGoat Installation on VirtualBox (macOS)

I installed WebGoat on VirtualBox running macOS, and I these are the steps I followed. Here's how it went:

## Step 1: Installing Java and Useful Tools
First, open the terminal and make sure everything is up to date by running:

 sudo apt-get update

<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Update.png">


Then, install Java and some helpful tools with:

 sudo apt-get -y install openjdk-17-jre ufw wget bash-completion

<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.2.png">

## Step 2: Enabling the Firewall
Enhance security by enabling the firewall using:

 wget https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Firewall.png">

## Step 3: Downloading WebGoat
Download the WebGoat application using the wget command:

 wget https://terokarvinen.com/2020/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.Install.png">

## Step 4: Running WebGoat
Start WebGoat by executing:

 java -jar webgoat-server-8.0.0.M26.jar

 <img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.webgoat.png">

## Step 5: Accessing WebGoat
With WebGoat running, open your web browser and go to http://localhost:8080/WebGoat/. Follow the registration process to set things up.

And that's it! You're all set up with WebGoat for some practice.

<img src="https://github.com/rolandogonzagajr/infosec/blob/main/Screenshots/Screenshot.WebgoatPage.png">

