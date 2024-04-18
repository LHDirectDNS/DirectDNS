# DirectDNS
The all Python DNS Proxy Solution!

# Required External Modules

DNSPython

Asyncio

Socket

Logging

Tkinter

Sys

Os

Threading

# Project Description
This program was created for my capstone course over the course of 2.5 months. It is meant to be a lightweight local DNS with domain blocking and logging as well as high customization via port selection and upstream choice. The program creates two text files named "dnslogs.txt" and "blocked_domains.txt" as they are needed for the program to run successfully. Users can paste their desired blocked domains in the blocklist file directly or use the GUI to input their domains automatically through comma seperated domains. Client devices have their local IP addresses logged within the terminal (within application for Windows release), while all query information (including blocked domains) are saved to the log file where it can be analyzed by the user. The application supports both IPV4 and IPV6 for hosting and upstream communication, where the user is able to choose which IP family to host on at startup.
