# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="633" height="393" alt="image" src="https://github.com/user-attachments/assets/252853a1-77d0-4d0d-b133-bc21d2a61ffc" />


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

<img width="930" height="394" alt="image" src="https://github.com/user-attachments/assets/2365051c-60f4-4ea0-a717-95fd6531dece" />


## OUTPUT:

<img width="766" height="125" alt="image" src="https://github.com/user-attachments/assets/07e32bdd-4201-4733-bd0c-4a9db21e4221" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="995" height="586" alt="image" src="https://github.com/user-attachments/assets/6b0e8354-1643-41f7-b246-b5e6900005b1" />

<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/d8e2bb7c-774e-4002-8f0a-76c32342ae9d" />



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
