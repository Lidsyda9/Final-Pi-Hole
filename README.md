<!-- markdownlint-configure-file { "MD004": { "style": "consistent" } } -->
<!-- markdownlint-disable MD033 -->
#

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/cb/Raspberry_Pi_Logo.svg/512px-Raspberry_Pi_Logo.svg.png" 
     alt="Raspberry Pi Logo" width="168" height="270">
  <br>
  <strong>Homework source code and guide how to set up Web Server  https://forums.raspberrypi.com/viewtopic.php?t=24441</strong>
</p>

<!-- markdownlint-enable MD033 -->

# How to Set Up a Web Server on a Raspberry Pi – Host Your Own Website! What You Need. Below is everything you need to set up your Raspberry Pi to become a fully functional personal web server.


- **A Raspberry Pi** Single-Board Computer (in my case I have used a Raspberry Pi Zero W Rev 1.1 Model 512MB)
- First, you’ll need to install Raspberry Pi OS on your Pi.
- Raspberry Pi Zero 2 W
- microSD card (8GB or larger)
- micro USB power supply
- Internet connection (Wi-Fi or Ethernet)
- (Optional) External monitor/keyboard OR SSH access
- Power supply


 # Update Raspberry Pi
 
 >sudo apt update && sudo apt upgrade -y
 
# Install Apache (basic web server)

> sudo apt install apache2 -y


Setup
macOS
Click Apple > System Preferences > Network
Highlight the connection for which you want to configure DNS
Click Advanced
Select the DNS tab
Click + to replace any listed addresses with, or add, your Pi's IP addresses at the top of the list:
Click Apply > OK
Repeat the procedure for additional network connections you want to change.


 type in the provided IP Address followed by | /admin | into the URL of any internet browser. In my case I typed | http://192.168.0.28/ |. It will then request the Pi-Hole Password to access the Web Interface
then you will see the dashboard for all the status and how advertiment gets block
