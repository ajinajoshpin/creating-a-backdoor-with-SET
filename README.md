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
![image](https://github.com/user-attachments/assets/58004166-d9a2-4078-b393-eac03fc5eb2e)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![image](https://github.com/user-attachments/assets/f9850666-b2f8-4385-a3b8-c57a2b46ad7b)

![image](https://github.com/user-attachments/assets/6094e4e9-0c28-49da-958f-6ef2a63dbbb5)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/e29aa12a-f32f-446a-bd73-5a23b67c876d)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/0e2e26f1-4103-4f10-8c54-452f88017f26)

The Credential Harvester Attack Method displays the following menu. In git push origin mthis menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/bd4c1c8e-348d-471b-b340-606118478270)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
It shows the following screen in which the option Google can be selected:
![alt text](<Screenshot 2025-05-10 080537.png>)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/bc47be22-178d-4dd3-9761-c0e86c391453)

In windows IE, on giving the url http://192.168.169.88, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/dcc928f4-b7a6-4967-90f5-abbfe4069edd)

SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/878fe613-b0f2-475c-b6e8-5f52e473fdfb)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/da88fe57-1daf-42fe-a6d0-81369f8749ef)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
