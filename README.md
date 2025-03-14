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
![image](https://github.com/user-attachments/assets/2ed0bd7b-eb6e-4e4c-9179-4934b7206062)
## ip2Location:
![image](https://github.com/user-attachments/assets/7ddf2f0d-9117-400c-8b41-d940fbabb2ed)
## History of the website:
![image](https://github.com/user-attachments/assets/95210d14-c7ea-4993-9ac5-3722115723ac)
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
