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


## OUTPUT:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

### output


![Alt text](<img/Screenshot at 2025-03-15 12-53-49.png>)

Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

### output
![Alt text](<img/Screenshot at 2025-03-17 14-05-36.png>)




Finding Hosting Company
get further detail by using ip2location.com website.
### output

![Alt text](<img/Screenshot at 2025-03-15 13-03-10.png>)

### output

![Alt text](<img/Screenshot at 2025-03-17 14-40-58.png>)


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

### output
![Alt text](<img/Screenshot at 2025-03-17 14-23-07.png>)

![Alt text](<img/Screenshot at 2025-03-17 14-23-21.png>)

![Alt text](<img/Screenshot at 2025-03-17 14-23-37.png>)

## nmap:
### output

![Alt text](<img/Screenshot at 2025-03-17 10-07-25.png>)

## Whatweb
### output

![Alt text](<img/Screenshot at 2025-03-17 10-08-52.png>)


![Alt text](<img/Screenshot at 2025-03-17 10-20-11.png>)

![Alt text](<img/Screenshot at 2025-03-17 10-21-39.png>)

## httprint
### output

![Alt text](<img/Screenshot at 2025-03-17 15-23-55.png>)


![Alt text](<img/Screenshot at 2025-03-17 15-24-05.png>)



# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

![Alt text](<img/Screenshot at 2025-03-17 14-26-01.png>)

UDP Traceroute:
sudo traceroute -U www.google.com
## output
![Alt text](<img/Screenshot at 2025-03-17 14-29-16.png>)


ICMP Traceroute:
sudo traceroute  www.google.com
## output

![Alt text](<img/Screenshot at 2025-03-17 14-31-17.png>)














## RESULT:
The information gathering techniques tools/procedure were  identified successfully
