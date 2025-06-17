<!-- markdownlint-configure-file { "MD004": { "style": "consistent" } } -->
<!-- markdownlint-disable MD033 -->
#

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/cb/Raspberry_Pi_Logo.svg/512px-Raspberry_Pi_Logo.svg.png" 
     alt="Raspberry Pi Logo" width="168" height="270">
  <br>
  <strong>Homework source code and guide how to set up a pihole  https://core-electronics.com.au/guides/raspberry-pi/pi-hole-raspberry-pi/</strong>
</p>

<!-- markdownlint-enable MD033 -->

# How to set up a PiHole on a Raspberry Pi - Block All Ads and More! What You Need Below is everything you need to set up your Raspberry Pi to become a fully functional Pi-Hole.

- **A Raspberry Pi** Single-Board Computer (in my case I have used a Raspberry Pi Zero W Rev 1.1 Model 512MB but this can be done perfectly with an earlier lower-spec Pi like the Raspberry Pi 3)
- Micro-SD card: flashed with Raspberry Pi OS
- Micro-HDMI to HDMI Cord to connect the system to a Monitor
- Power Supply
- Mouse and Keyboard
- Ethernet Cable (Can use just Wi-Fi if desired)
- Operational Internet Connected Modem/Router
- Software Build
- If prompted, type and enter | Y | to continue/confirm installations.
- sudo apt-get update && sudo apt-get upgrade

 <strong>curl -sSL https://install.pi-hole.net | bash
 
**follow the defult setting!**: [Installation_Process_Step_by_step_2](https://docs.pi-hole.net/main/prerequisites/)

**Modem/Router Set Up Windows DNS settings are specified in the TCP/IP Properties window for the selected network connection.**

Go to the Control Panel Click Network and Internet > Network and Sharing Center > Change adapter settings Select the connection for which you want to configure Right-click Local Area Connection > Properties Select the Networking tab Select Internet Protocol Version 4 (TCP/IPv4) or Internet Protocol Version 6 (TCP/IPv6) Click Properties Click Advanced Select the DNS tab Click OK Select Use the following DNS server addresses Replace those addresses with the IP addresses of your Pi Restart the connection you selected in step 3 Repeat the procedure for additional network connections you want to change. 

Setup
macOS
Click Apple > System Preferences > Network
Highlight the connection for which you want to configure DNS
Click Advanced
Select the DNS tab
Click + to replace any listed addresses with, or add, your Pi's IP addresses at the top of the list:
Click Apply > OK
Repeat the procedure for additional network connections you want to change.


 type in the provided IP Address followed by | /admin | into the URL of any internet browser. In my case I typed | http://192.168.0.132/admin |. It will then request the Pi-Hole Password to access the Web Interface
then you will see the dashboard for all the status and how advertiment gets block
