# InformationGathering
Information Gathering Techiques
```
NAME: BASKAR U
REG NO: 212223220013
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

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## OUTPUT:
![Screenshot 2025-03-10 112946](https://github.com/user-attachments/assets/81b65b66-fc98-4775-9c1f-30ab85405ef2)

## Finding IP address:
Ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:
![Screenshot 2025-03-21 133349](https://github.com/user-attachments/assets/3b21b999-c607-4c7d-a837-5b63bd74e625)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT:
![Screenshot 2025-03-10 113229](https://github.com/user-attachments/assets/1bf728ad-7d82-4768-b31b-eca2b1392eda)

## History of the website:
## OUTPUT:
![Screenshot 2025-03-20 233025](https://github.com/user-attachments/assets/d8088472-3459-46db-bf2f-e2f70ee9bcb1)

## Webserver Fingerprinting:
# Netcat:
```
nc 172.17.52.118 80
```
## Output:
![EH NC](https://github.com/user-attachments/assets/9117f8c5-53ee-4cd5-8838-76fea794eb19)


## nmap:

```nmap -p 21 -sV --script=banner ftp.vim.org```

## OUTPUT:

![EH NMAP](https://github.com/user-attachments/assets/31d2bdec-0367-4d5d-91de-60cd6077a232)


## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:

![EH WHATWEB](https://github.com/user-attachments/assets/f128617f-7f80-4793-9fd4-297b18b3efad)


## httprint:

```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

## OUTPUT:

![EH HTTPRI](https://github.com/user-attachments/assets/3562176e-fbe9-4e07-8fbf-e459e53e2c0e)


## Tracing the Location

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:
![TCP](https://github.com/user-attachments/assets/95950f17-5009-4ae5-ab13-3c7b5d7ea723)


## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:

![ICT TRACE](https://github.com/user-attachments/assets/0d19a07e-df3b-4a4b-ab02-208c61a1f4d2)


## ICMP Traceroute:

```sudo traceroute  www.saveetha.ac.in```

## OUTPUT:

![ICMP](https://github.com/user-attachments/assets/8f94883a-13c9-47d5-8177-ff91afe422d0)


## RESULT:

The Information gathering techniques tools/procedure were  identified successfully.
