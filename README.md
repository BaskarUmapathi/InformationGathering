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
## Whois:
![Screenshot 2025-03-10 112946](https://github.com/user-attachments/assets/81b65b66-fc98-4775-9c1f-30ab85405ef2)

## ip2Location:
![Screenshot 2025-03-10 113229](https://github.com/user-attachments/assets/1bf728ad-7d82-4768-b31b-eca2b1392eda)

## History of the website:
![Screenshot 2025-03-20 233025](https://github.com/user-attachments/assets/d8088472-3459-46db-bf2f-e2f70ee9bcb1)

## Webserver Fingerprinting:
# Netcat:
```
sudo nc ticfiber.com 80
GET / HTTP/1.1
Host: ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/3a0d762b-92e9-4390-840d-40b2817a638f)
# Nmap:
## Output:
![image](https://github.com/user-attachments/assets/083524f4-8b2e-435e-a230-4247cc532611)
![image](https://github.com/user-attachments/assets/e495efac-6238-47bb-81d1-da044c751806)
# Whatweb:
## Output:
![image](https://github.com/user-attachments/assets/03dca286-28da-4df4-bcc2-967574cd7beb)
## Tracing the Location:
```
TCP Traceroute:
sudo traceroute -T ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/794e1cea-c363-480d-aaea-2dbbf6fb5d77)
# UDP Traceroute:
```
sudo traceroute -U ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/4bf1787c-81a9-4c39-921d-af5fc8f67c3a)
## ICMP Traceroute:
```
sudo traceroute ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/97e5cbcf-af14-4ef4-9ead-7b91905fbd91)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully.
