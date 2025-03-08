# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

### NAME: JASWANTH S
### REG. NO: 212223220037

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![image](https://github.com/user-attachments/assets/6b1d25c6-e76a-4e7d-aa1f-996d7fd5bb49)


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of youtube .com

## OUTPUT:
![image](https://github.com/user-attachments/assets/aefe7c3b-e7cc-424d-98ac-f4667694979b)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT :
![image](https://github.com/user-attachments/assets/aec67ad6-9aa5-4143-99f2-6c7b2d3109bd)

## History of the website:
https://web.archive.org/
## OUTPUT :
![image](https://github.com/user-attachments/assets/6679090a-57b9-46a4-ad00-77c38db928bb)

![image](https://github.com/user-attachments/assets/b153f879-64b9-42a2-8a32-a3a4f7326139)

## Webserver Fingerprinting:
## Netcat:
nc 172.17.52.118 80

## OUTPUT:
![image](https://github.com/user-attachments/assets/741ec3b4-e73f-4c6f-83d3-4b24017f0200)


## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT :
![image](https://github.com/user-attachments/assets/98222da8-d5f9-4ba8-aa3c-1bd1db0cd024)



## Whatweb:
## OUTPUT:
![image](https://github.com/user-attachments/assets/ff5c1585-9f62-4025-b1cc-43c6f17d3890)



## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT :
![lab2(9)](https://github.com/user-attachments/assets/ab3f61a1-c3f7-4787-8c4a-cc92f2b65b9d)

## Tracing the Location:
## TCP Traceroute:
sudo traceroute -T www.instagram.com
## OUTPUT :
![image](https://github.com/user-attachments/assets/a0f70fdb-b8d0-4057-9929-2c0ab196a050)


## UDP Traceroute:
sudo traceroute -U www.instagram.com
## OUTPUT :
![image](https://github.com/user-attachments/assets/67c51b61-0a08-4088-a5e9-2c9579b54522)

## ICMP Traceroute:
sudo traceroute  www.facebook.com
## OUTPUT :
![image](https://github.com/user-attachments/assets/35760abc-2122-4221-8c61-d0edcfb91868)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
