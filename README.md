# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1888" height="1090" alt="image" src="https://github.com/user-attachments/assets/8fa1ed77-9c4c-4a97-b267-f22554fb6bd8" />


### Finding Hosting Company :
<img width="1895" height="1077" alt="image" src="https://github.com/user-attachments/assets/8c7214a7-3662-4398-b91d-6fb3f6a01635" />

### History of the website :
<img width="1897" height="983" alt="Screenshot 2025-08-30 180248" src="https://github.com/user-attachments/assets/d531a3e2-e085-4b13-9620-5e02b3433be1" />


### ping command :
<img width="1920" height="1056" alt="image" src="https://github.com/user-attachments/assets/8b5da8a2-d190-4c04-af74-53ae6348872f" />

### whois :
<img width="1920" height="1056" alt="image" src="https://github.com/user-attachments/assets/58a4eea3-7e30-458c-8816-c9f03e9a9184" />


### netcat :
<img width="751" height="112" alt="image" src="https://github.com/user-attachments/assets/d66f2ed8-b800-4f95-adc6-f416e3940937" />


### nmap :
<img width="1913" height="129" alt="image" src="https://github.com/user-attachments/assets/f9925791-a5c7-4fe4-8d88-664e55990fcf" />


### whatweb :
<img width="1911" height="131" alt="image" src="https://github.com/user-attachments/assets/81ed3cf0-8f52-40de-a717-6dbdbffe8f21" />



### httprint :

### TCP traceroute :
<img width="954" height="86" alt="image" src="https://github.com/user-attachments/assets/342d7320-324c-4ec5-b3da-3abacefe52bc" />


### UDP traceroute :
<img width="843" height="78" alt="image" src="https://github.com/user-attachments/assets/1667f4bd-a49d-439e-89b1-ef83ab4a3fcf" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
