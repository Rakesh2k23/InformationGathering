# InformationGathering
Information Gathering Techiques
```
Rakesh Kumar.S
212221040137
CSE (III)
```
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

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/bc2f096c-5019-4539-b58d-70374c2bd538)


# Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/99b4b518-e723-4228-b7e8-fa84b3ea1e94)


# Finding Hosting Company
get further detail by using ip2location.com website.
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/49214f31-22cd-423d-9f51-2b46cb5e1c1f)


# History of the website:
```
https://web.archive.org/
```
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/541a42e9-02ff-47fa-ac2d-a9ed91ca492a)


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/2d1cb00c-5bd4-4d66-8956-a6301dacd0ae)


## nmap:
## #output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/fb840480-094a-4101-afff-122ccfdd23d7)



# Whatweb
## output

  ![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/509e35ed-fd7f-4483-b0f6-281d7b6e4314)



# httprint
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/b6968d8d-31ad-49a6-b566-a8a23dde04fe)


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/17bc20e8-8319-4fd9-9937-ad9c45cb9730)


# UDP Traceroute:
sudo traceroute -U www.google.com
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/6e37892b-332a-4153-a2a5-6b858083f8ed)


# ICMP Traceroute:
sudo traceroute  www.google.com
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/df891a78-278b-46fb-965a-26548e7fc969)


# Netcraft
## output
![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/8dbaf351-da4e-40eb-bf6b-04d544434259)


# Wapplyzer
## output

![image](https://github.com/Rakesh2k23/InformationGathering/assets/141472158/13ce3e49-a219-4e03-a589-a68c3ffaeac3)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
