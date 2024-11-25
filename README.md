# EX 07: CREATING A BACKDOOR WITH SET:
creating a backdoor with SET - Ethical Hacking Techniques course

## AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## PROCEDURE AND OUTPUT:


 Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 

 The command sudo setoolkit in the prompt gives menu with set prompt:

### OUTPUT:
![image](https://github.com/user-attachments/assets/e34d79e7-ac3b-4aa5-9693-5ef9bf8bddc1)



 It displays the following menu and select 2 for Website Attack Vectors:

### OUTPUT:
![image](https://github.com/user-attachments/assets/10e9a79a-a209-466e-af01-cbf3d06c6d97)



 The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

### OUTPUT:
![image](https://github.com/user-attachments/assets/fe7d1b8a-0e08-4995-bcd9-88fdab1d0197)



 The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

### OUTPUT:
![image](https://github.com/user-attachments/assets/76f7495d-2077-4ea3-a3ed-2fe5146b69d4)



 It shows the following screen in which the ip address of the attacker need to be given which is the default value:


### OUTPUT:
![image](https://github.com/user-attachments/assets/74b5d4b0-51b6-4fc4-a1c2-791ed161d8a5)



It shows the following screen in which the option Google can be selected

### OUTPUT:
![image](https://github.com/user-attachments/assets/c6394b00-34f1-482c-b5d4-79953bb65706)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

### OUTPUT:
![image](https://github.com/user-attachments/assets/aabd9b19-0b25-4da9-9e46-440927bd149d)



In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password

### OUTPUT:

![image](https://github.com/user-attachments/assets/1278eb2f-4148-4caa-93d0-13a8866f2d6f)


SET logs the information regarding the Google credentials:

### OUTPUT:
![image](https://github.com/user-attachments/assets/5862f5b4-e5b2-4053-853f-fca313cbeb77)



SET logs the information in the xml file under /root/.set directory:

### OUTPUT:
![image](https://github.com/user-attachments/assets/9d7673ec-de75-4694-a9db-94ac9a73df25)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is examined successfully
