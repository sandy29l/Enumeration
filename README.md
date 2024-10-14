# Reg no:212222100046

# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

# STEPS:

## Step 1:

Install kali linux either in partition or virtual box or in live mode

## Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


## Step 3:
Open terminal and try execute some kali linux commands

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

### site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

![Screenshot (114)](https://github.com/user-attachments/assets/e28e7d61-c97c-4272-b3c6-8117836c5f44)


### filetype:
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

![Screenshot (115)](https://github.com/user-attachments/assets/40a2d5fd-73ef-49e1-a9b4-7e2726a856f8)



### intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![Screenshot (116)](https://github.com/user-attachments/assets/76f32a3c-1604-4805-bb16-f23dd17cad41)




### inurl:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![Screenshot (117)](https://github.com/user-attachments/assets/9cacb2f8-87c0-48e0-b837-998dd4013aba)



### intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![Screenshot (120)](https://github.com/user-attachments/assets/d4678dd8-a8c6-4a33-9cab-f7cd008057d2)




### link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![Screenshot (118)](https://github.com/user-attachments/assets/a782ad38-ff3b-47a4-b259-eed3d9124922)



### cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
![Screenshot (119)](https://github.com/user-attachments/assets/9b12bf01-bf01-411d-bb68-5424321ac42a)


 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![WhatsApp Image 2024-10-14 at 13 09 35_2fb2f57e](https://github.com/user-attachments/assets/d021e292-7f19-4ace-add9-a98a89407600)


## Dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

## Output:
![WhatsApp Image 2024-10-14 at 13 11 13_4e7d7f32](https://github.com/user-attachments/assets/c3e74c6c-ebdb-4d02-aaff-b674a0f35dc0)



## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output:
  
  ![image](https://github.com/user-attachments/assets/f02e546e-6e88-43dc-a31a-6e7a08456a0d)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

## Output:
![image](https://github.com/user-attachments/assets/247ec7fb-69c9-41f4-9540-235ffdd30f68)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

