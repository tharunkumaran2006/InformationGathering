# InformationGathering
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

## Pen Test Tools Categories:  

#### Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.


# OUTPUT:
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
![lab2.1](<Screenshot 2024-03-13 092105.png>)

#### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example of find out the IP address of amazon.com.
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_07_31.png)

#### Finding Hosting Company:
get further detail by using ip2location.com website.
![lab2.3](<Screenshot 2024-03-13 092344.png>)

#### History of the website:

https://web.archive.org/

![lab2.4](<Screenshot 2024-03-13 092607.png>)

## Webserver Fingeprinting:
### Netcat:

sudo nc 172.17.52.118  80
GET / HTTP/1.1
Host: amazon.com


# InformationGathering
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

## Pen Test Tools Categories:  

#### Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.


# OUTPUT:
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
![lab2.1](<Screenshot 2024-03-13 092105.png>)

#### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example of find out the IP address of amazon.com.
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_07_31.png)

#### Finding Hosting Company:
get further detail by using ip2location.com website.
![lab2.3](<Screenshot 2024-03-13 092344.png>)

#### History of the website:

https://web.archive.org/

![lab2.4](<Screenshot 2024-03-13 092607.png>)

## Webserver Fingeprinting:
### Netcat:

sudo nc 172.17.52.118  80
GET / HTTP/1.1
Host: amazon.com


![alt text](<Screenshot 2024-04-10 091007.png>)

### nmap:
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_07_46.png)

### Whatweb:
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_08_06.png)

### httprint:
![alt text](<Screenshot 2024-04-10 091020.png>)

### Tracing the Location
#### TCP Traceroute: 
sudo traceroute -T amazon.com
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_13_49.png)
#### UDP Traceroute:
sudo traceroute -U amazon.com
 ![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_14_17.png)

#### ICMP Traceroute:
sudo traceroute amazon.com
![alt text](VirtualBox_kali-linux-2024.1-virtualbox-amd64_10_04_2024_09_14_42.png)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully