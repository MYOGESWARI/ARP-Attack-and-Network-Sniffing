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

<img width="859" height="543" alt="image" src="https://github.com/user-attachments/assets/f6014574-85bf-42c4-8f3e-2c42f006ae31" />




 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org


<img width="837" height="501" alt="image" src="https://github.com/user-attachments/assets/82026e5e-0ad8-4878-b803-f50e1185c75c" />



<img width="811" height="486" alt="image" src="https://github.com/user-attachments/assets/f158b15e-f5c6-4791-bce3-2a3894928df7" />


## OUTPUT:

<img width="849" height="586" alt="image" src="https://github.com/user-attachments/assets/4d775bb2-9389-4b8c-b79b-27ee8aa95216" />


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1634" height="684" alt="image" src="https://github.com/user-attachments/assets/8c77aeda-06b4-479f-8337-93c74a9db1f7" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
