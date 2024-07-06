### Spiderfoot-4-0  Lab

### Introduction 
Open Source Intelligence (OSINT) is an important for Security analysts tool , used particularly during security investigations. Having a  platform like Spiderfoot simplifies the process of gathering information on indicators of compromise (IOCs) and potential threat actor infrastructure. Spiderfoot is an automation tool designed to integrate with various sites for data enrichment and reconnaissance.

### Objective
Spiderfoot aims to provide a comprehensive, automated open-source intelligence (OSINT) solution to assist cybersecurity professionals in their reconnaissance and investigation tasks. It simplifies the process of gathering and analyzing information on various indicators of compromise, threat actors, and network infrastructur

### Purpose
This tool is designed to

 Enhance Efficiency: Automate data collection and analysis to save time and resources for security analysts.
Data Enrichment: Integrate with multiple data sources and APIs to provide enriched and comprehensive intelligence on targets.
Versatility: Serve a wide range of use cases, including vulnerability assessment, threat hunting, and security investigations.
Accessibility: Offer an easy-to-use web interface for configuring and running scans, making OSINT capabilities accessible to analysts with varying levels of expertise.
Visualization: Provide detailed correlation and visualization of collected data to help analysts quickly identify patterns, relationships, and potential threats.
Ethical Use: Encourage responsible and ethical use of OSINT to protect against misuse and ensure compliance with legal and organizational policies


### Installation
I installed spiderfoot on Ubuntu version 22.04.3 LTS. I began by updating and upgrading repositories sudo apt-get update && apt-get upgrade) and installed Python 3 and pip (sudo apt install python3-pip). I downloaded the stable build package from Spiderfoot's GitHub page (https://github.com/smicallef/spiderfoot) and followed the installation instructions. After installation,  I configured Spiderfoot by running it with your machine’s IP address. I used the command (ip a) to get the IP address of my virtual machine. i ran the command (python3 ./sf.py -l my_ip_address:5001. I entered the VM ip address on a web browser and was able to access spiderfoot GUI. To configure and add functionality, I clicked on settings. I configured the AbuseIPDB API, To get the API key, I created an account at(www.abuseipdb.com) and saved the changes after the configuration

### Application
Scan the following for malicious activities
IP address,
Domain/sub-domain name,
Hostname,
Network subnet (CIDR),
E-mail address,
Phone number,
Username,
Person's name,
Bitcoin address.

### Tools Used
Spiderfoot stable build
 wget https://github.com/smicallef/spiderfoot/archive/v4.0.tar.gz
 tar zxvf v4.0.tar.gz
 cd spiderfoot-4.0
 pip3 install -r requirements.txt
 python3 ./sf.py -l 127.0.0.1:5001


 
![Screenshot 2024-07-06 160954 sf](https://github.com/albertakhim/Spiderfoot-Lab/assets/174826500/35e173ca-6b18-4bc3-bd4c-6270772d577c)

 ![Screenshot 2024-07-06 161116](https://github.com/albertakhim/Spiderfoot-Lab/assets/174826500/4b67bf45-c944-49e2-a878-c8a2fa0eca30)

 ![Screenshot 2024-07-06 162542](https://github.com/albertakhim/Spiderfoot-Lab/assets/174826500/5c3b8748-baa4-41de-9719-0bf39cfa8228)
 
![Screenshot 2024-07-06 162613](https://github.com/albertakhim/Spiderfoot-Lab/assets/174826500/f1a38912-b32f-46cb-af47-a5cbc216febd)

![Screenshot 2024-07-06 162648](https://github.com/albertakhim/Spiderfoot-Lab/assets/174826500/6c75c5e3-c5a8-4674-89fc-7a9a7e3bb565)
