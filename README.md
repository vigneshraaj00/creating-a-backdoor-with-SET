# Exp.No--7 creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

## OUTPUT:
![image](https://github.com/user-attachments/assets/52936afe-3c54-442f-b65d-194886c32bf9)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.

## OUTPUT:
![image](https://github.com/user-attachments/assets/e6a95c60-0b61-431d-a728-c19842938990)

The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:
## OUTPUT:
![image](https://github.com/user-attachments/assets/4daa1895-27ee-47e4-b6a6-3d69dda35d5b)
The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:
## OUTPUT:
![image](https://github.com/user-attachments/assets/aa9e2bd3-a454-4c13-b204-9a0cab488b26)

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.
It shows the following screen in which the IP address of the attacker needs to be given (default value):

## OUTPUT:
![image](https://github.com/user-attachments/assets/cc23fcc6-d300-4a50-b65a-f845eefa0142)

It shows the following screen in which the option Google can be selected:
## OUTPUT:
![image](https://github.com/user-attachments/assets/2133dead-0ed0-4b53-8357-7ddefa923879)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done
## OUTPUT:
![image](https://github.com/user-attachments/assets/fd6fac92-af00-4818-ac15-51c526e4c237)

In Windows IE, on giving the URL http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password.

## OUTPUT:
![image](https://github.com/user-attachments/assets/adf26a92-766d-4e8a-9e9b-1642cf3422be)

SET logs the information regarding the Google credentials:
## OUTPUT:
![image](https://github.com/user-attachments/assets/4dfb15be-c3a9-4c7c-8e19-5bc6a5b47665)

SET logs the information in the XML file under /root/.set directory:
## OUTPUT:
![image](https://github.com/user-attachments/assets/95a427d8-a09a-4a52-abf7-56a1a2e97451)
















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
