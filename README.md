# Documentation
by Group 11: Gerald Carique, John Mark Ruam, Randolf Brigola, Arnold Rei Sejera, John Paul Quial

.    
##  Step-by-step documentation on how to do the following:
### 1. Prepare and Install Headless Raspbian OS in Raspberry Pi.
* **Step 1:** Download Raspbian OS by visiting (https://www.raspberrypi.com/software/) and obtaining the most recent iteration of Raspbian OS, which is currently referred to as Raspberry Pi OS.
* **Step 2:** Insert your microSD card into your computer; ensure it has a capacity of 8GB or more. Proceed to download, install, and launch the Raspberry Pi Imager.
* **Step 3:** Choose the "Choose Device" option, and a list of available Pi boards will be displayed. Pick the **Raspberry Pi 3** from the list.
  <img src= "https://github.com/MarkRuam/Info_assure/assets/146324538/c6b5602d-90d9-4980-bd18-1d8b95626421">
* **Step 4:** Select the "Choose OS" option, and opt for the **Raspberry Pi OS (Legacy)**. Click on "Choose Storage" and pick your card from the menu, then proceed to click "Next."
   <img src= "https://github.com/MarkRuam/Info_assure/assets/146324538/abe92959-4728-4d0c-b6a7-6ac308bba209">
* **Step 5:** Click Edit Settings from the pop-up.
  <img src= "https://github.com/MarkRuam/Info_assure/assets/146324538/38445234-37ee-4224-9601-48b5e9dcdab7">
* **Step 6:** Complete all the fields on the General tab, including the hostname, username/password, wireless LAN details (if you intend to use Wi-Fi), and locale settings.  
  <img src= "https://github.com/MarkRuam/Info_assure/assets/146324538/b1c0a2da-bcd4-4c9c-9b73-9f7785596db2">
* **Step 7:** Navigate to the Services tab and switch the "Enable SSH" option to the "On" position. Then, choose "Use password" from the available options.  
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/a9220edd-fd70-42c9-8d5e-e37891c94e73">
* **Step 8:** Press "Yes" to apply the OS customization settings. Confirm your intention to write to the microSD card by clicking "Yes."
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/bcbe3a0c-cd55-42d3-90ac-55770135e021" >
* **Step 9:** The process will take a few minutes as the system downloads the OS and writes it to your card. It will appear as completed when the verification and writing processes are finished.
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/49eb3d28-0c7f-491a-8606-40b0d5e239a6" >
### 2. Connecting to Raspberry Pi via SSH using the terminal. 
* **Step 1:** Discover the IP address of your Raspberry Pi by employing a network scanning tool or checking your router's list of connected devices to identify the assigned IP address.
* **Step 2:** Access the terminal on your computer and establish an SSH connection to the Pi with the following command, substituting `<pi_ip>` with your Raspberry Pi's IP address: `ssh user@<pi_ip>`. When prompted, enter the default password (raspberry).
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/c9f6434b-fef8-4a3a-a310-6260810f8801"> 
* **Step 3** Execute the following command to update and upgrade package lists: sudo apt update, sudo apt upgrade
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/f5648614-22f2-4575-b3c4-b8b91733dd81">
### 3. Deploying LAMP (Linux Apache MySQL PHP) Stack in raspberry Pi  
* **Step 1**  Install LAMP stack. Install Apache, MySQL, and PHP using the following command:
sudo apt install apache2.
sudo apt install mariadb-server.
sudo mysql_secure_installation.
sudo apt install php libapache2-mod-php php-mysql.
sudo apt-get install php*.
sudo apt install phpmyadmin.
* **Step 2:**  Run the sudo apt install apache2 on your terminal.
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/1bc0e75f-22d1-4bc4-9f72-628af94011b7">
* **Step 3:** After installing Apache, next run the sudo apt install mariadb-server on your terminal
  <img src="https://github.com/MarkRuam/Info_assure/assets/146324538/a6b22191-9475-43f3-a88b-e6f005c3ac22">
* **Step 4:** After installing the mariadb-server, next run sudo mysql_secure_installation on you terminal. 


