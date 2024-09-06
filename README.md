# Network-Security

In this project I and other team members attacked a server using various security tools and tactics. Through this project, we learned how security breaches occur and how to defend systems and networks.

During this endeavor we used two virtual machines in a VLAN. The first was a Kali box and the second was an ecommerce server. Using Kali, we attacked the server and tested its defense mechanisms. While completing the exercise, we were to assume that the e-commerce server was not visible and therefore we did not attempt to log in.

## Injection Number 1

In injection one we were tasked with creating a security policy and introducing the team to the instructor. The security policy and team introduction we wrote can be found here: https://github.com/TristanJRogers/Network-Security/blob/main/Injection%201.docx 

## Injection Number 2

In injection two the team and I were tasked with the following. 

1. Scan the network to find find the IP address of the e-commerce server
2. Scan the e-commerce server and detect the version of the services that were running

For task 1 the team and I used NMAP to scan the entire subnet. In the picture below you will see a hit for 192.168.1.1 which was most likely a router and a hit for 192.168.1.220. We were able to identify 192.168.1.220 as the e-commerce server due to port 80 and port 3306 being open along with the url given in the scan.
![image](https://github.com/user-attachments/assets/22d9fa04-afaa-47dc-bad0-0d3e0be807d4)

For task 2 we used the command nmap -sV on the e-commerce servers IP to display the version of all services open on the e-commerce server. 
![image](https://github.com/user-attachments/assets/0e3b9e18-2af9-4d05-b8a8-42ea459a58e7)

## Injection Number 3





