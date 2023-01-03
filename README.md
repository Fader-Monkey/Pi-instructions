# Pi-Instructions
Here are some helpful docs on how to adjust settings on CompanionPi


## Changing IP Address

Step 1: Open terminal on Mac or linux device

Step 2: SSH in `ssh pi@deviceIP`
Password=raspberry

Step 3:Change ip `sudo nano /etc/dhcpdc.conf`

Scroll to the Example static IP configuration section  

<img width="497" alt="Screen Shot 2023-01-03 at 9 43 16 AM" src="https://user-images.githubusercontent.com/47360319/210379707-bb9c7d60-ed2b-4f8a-b5d5-f82298d53a56.png">

4: Remove # and set IP Address as needed.

<img width="501" alt="Screen Shot 2023-01-03 at 9 44 50 AM" src="https://user-images.githubusercontent.com/47360319/210381108-6eb942d4-95a8-48d8-a181-809f5b07cf8a.png">

*1. removing # will activate the settings below*
2. remove # and set IP at the end 
