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
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

![1](https://github.com/user-attachments/assets/1e949712-da6b-425c-b906-ef4165d36abc)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

![2](https://github.com/user-attachments/assets/319adfec-e0e2-4de5-afdc-3043e0c595dd)


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

![3](https://github.com/user-attachments/assets/b3662400-e5cd-45a8-95a3-1c0df9b4f27f)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

![4](https://github.com/user-attachments/assets/b0955c19-752e-480d-bab5-5a9c935afbcd)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

![5](https://github.com/user-attachments/assets/64989cc0-b3d9-4ed6-acac-e80d88f18e36)



It shows the following screen in which the option Google can be selected:
## OUTPUT

![6](https://github.com/user-attachments/assets/e1329544-2a42-47b4-9488-22f7b6a4afdc)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

![7](https://github.com/user-attachments/assets/62c4c693-5c68-4b61-a4ce-9077f4c8b557)



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
![8](https://github.com/user-attachments/assets/638b9c53-c67d-4c9c-a483-41e2d328268b)




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
