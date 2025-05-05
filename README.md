# creating-a-backdoor-with-SET
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
![Screenshot 2025-05-05 132543](https://github.com/user-attachments/assets/81e4eac8-f448-462f-82cf-b25194c2182e)

The command sudo setoolkit in the prompt gives menu with set prompt:
![Screenshot 2025-05-05 132556](https://github.com/user-attachments/assets/c5a871b1-dcff-4b30-82ee-82418b06f3a7)

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-05-05 132607](https://github.com/user-attachments/assets/816f89a0-6dcb-44a1-95f5-b29ebeed4b9b)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![Screenshot 2025-05-05 132911](https://github.com/user-attachments/assets/7bba7ca9-1340-4aeb-a756-c7be588daeae)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![Screenshot 2025-05-05 132931](https://github.com/user-attachments/assets/41c45b06-848b-4aeb-a2c0-2acb53307457)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![Screenshot 2025-05-05 132951](https://github.com/user-attachments/assets/c7e3bae7-66c8-4be2-a839-e68e9b7fd280)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![Screenshot 2025-05-05 133118](https://github.com/user-attachments/assets/9bbaf44d-27ca-4dcf-8293-8549e699a9ab)

SET logs the information in the xml file under /root/.set directory:
![Screenshot 2025-05-05 133139](https://github.com/user-attachments/assets/358b07c1-b7f5-4972-b912-08eec039979f)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
