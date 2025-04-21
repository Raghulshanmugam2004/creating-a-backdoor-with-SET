# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212222040128
Name: RAGHUL S
```
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

![1](https://github.com/user-attachments/assets/10add262-8722-4fe7-b8a0-931df7a15cdc)



sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![2](https://github.com/user-attachments/assets/723bc901-534b-4a27-a295-c0b904ef702d)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![3](https://github.com/user-attachments/assets/be08781c-b1f1-42da-ba7e-c0a3ab63f28c)




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![4](https://github.com/user-attachments/assets/f991e423-4d45-487c-83d4-2c0493254377)




It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![5](https://github.com/user-attachments/assets/18075dde-b6b1-42f1-9547-de71234dc436)



It shows the following screen in which the option Google can be selected:

![6](https://github.com/user-attachments/assets/d7e655f7-be9a-4f05-b1cc-0eb6cd8dccf3)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:


In windows IE, on giving the url http://192.168.11.152, the fake Google page is displayed. The victim can enter the username and password

![7](https://github.com/user-attachments/assets/ec00dbcb-9760-4079-a865-a8b1b9872dab)



SET logs the information regarding the Google credentials:

![8](https://github.com/user-attachments/assets/84eab899-702e-42e1-afd4-bfc00c71c8e4)



SET logs the information in the xml file under /root/.set directory:

![9](https://github.com/user-attachments/assets/89d11f97-3a35-4183-a293-8d7819a9d944)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
