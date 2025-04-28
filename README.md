# pfsense_setup

pfSense is a firewall/router computer software distribution based on FreeBSD. The open source pfSense Community Edition (CE) and pfSense Plus is installed on a physical computer or a virtual machine to make a dedicated firewall/router for a network. It can be configured and upgraded through a web-based interface, and requires no knowledge of the underlying FreeBSD system to manage.


## Setting up pfSense on VirtualBox

pfSense download link:
```bash
   https://repo.ialab.dsu.edu/pfsense/
```
Note: Download “pfSense-CE-2.7.2-RELEASE-amd64.iso.gz” and unzip with 7zip software

## System Requirements in VirtualBox
- Processor 		      1 core
- Ram (minimum) 	    1GB 	[recommended 2GB] 
- Storage		          20 GB
- Network adapters 1	NAT
- Network adapters 2	Internal Network
- Network adapters 3	Internal Network

## Usage

1. Start a New VM then provide system requirements
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_1.png?raw=true">

2. Then go to settings	>	Network
3. Network adapters 2	>  Internal Network
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_2.png?raw=true">

4. Network adapters 2	>  Internal Network
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_3.png?raw=true">

5. After setting up everything, save the Virtual Matchine and start the matchine
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_4.png?raw=true">

6. Press "Accept"
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_5.png?raw=true">

7. Press "ok"
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_6.png?raw=true">

8.Press "ok" 
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_7.png?raw=true">

9. Press "select"
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_8.png?raw=true">

10. Press "ok"
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_9.png?raw=true">
 
11. Now don't press "ok" yet. Press the “space” button!
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_10.png?raw=true">

12. Press "ok"
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_11.png?raw=true">

13.Press "yes" 
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_12.png?raw=true">

14. Now it will install automatically
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_13.png?raw=true">

15. Don’t press “Reboot” yet!
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_14.png?raw=true">

16. Remove the IOS first. Remove disk from virtual drive
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_15.png?raw=true">

17. Now reboot Or restart.
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_16.png?raw=true">

18. After restart our pfSense is Ready!
<img width="615" alt="main_pic" src="https://github.com/AyanMK/pfsense_setup/blob/main/assets/Screenshot_17.png?raw=true">
