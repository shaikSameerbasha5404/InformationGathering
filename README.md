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

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

```
Tested By: Shaik Sameer Basha
Register no.: 212222240093
```
## OUTPUT:

![2 1](https://github.com/user-attachments/assets/69219a72-133a-4765-9c6d-dbc8cbee538f)

## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```ping saveetha.ac.in```

## output:

![2 2](https://github.com/user-attachments/assets/1c629e73-04ad-4b24-87db-7fec9c8b202e)

## Finding Hosting Company:

get further detail by using ip2location.com website.

## output:

![2 3](https://github.com/user-attachments/assets/b6cc6e52-2a15-4bbc-8338-3fda802e1885)

## History of the website:

## Output:

![2 4](https://github.com/user-attachments/assets/aa72ff31-e2bc-4a01-b6f0-acae489c70ae)

## Webserver Fingerprinting:

## Netcat:

```nc 172.17.52.118 80```

## OUTPUT:

![2 5](https://github.com/user-attachments/assets/3a201abd-7998-4e17-a859-193bc4a8e480)

## nmap:

```nmap -p 21 -sV --script=banner ftp.vim.org```

## OUTPUT:

![2 6](https://github.com/user-attachments/assets/186d6f72-7c1c-4ea5-8cc6-cd0260c201c1)

## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:

![2 7](https://github.com/user-attachments/assets/a67c789a-e281-4409-b591-a37a88a6bbf7)

## httprint:

```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

## OUTPUT:

![2 8](https://github.com/user-attachments/assets/d20f931b-f6ad-44a8-b8d5-b53e230a94d9)

## Tracing the Location

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:

![2 9](https://github.com/user-attachments/assets/de3c7b3d-261b-4a50-a591-dbd1ab5a4369)

## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:

![2 10](https://github.com/user-attachments/assets/5c0e1b1c-464d-4b8a-a5ec-bc7b888191a7)

## ICMP Traceroute:

```sudo traceroute  www.saveetha.ac.in```

## OUTPUT:

![2 11](https://github.com/user-attachments/assets/799ab7e4-76a8-4a56-a13e-72a66e69354d)

## RESULT:

The information gathering techniques tools/procedure were  identified successfully
