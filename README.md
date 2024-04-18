# DirectDNS
The all Python DNS Proxy Solution!

# Required External Modules

DNSPython

Asyncio

# Description
This program was created for my capstone course over the course of 2.5 months. It is meant to be a lightweight local DNS with domain blocking and logging as well as high customization via port selection and upstream choice. The "file-only" version is significantly smaller than the Windows version, with its customization settings configured within the terminal, while the Windows release is a single executable with GUI support and a windowed query monitor. Both versions of the program create two text files named "dnslogs.txt" and "blocked_domains.txt" as they are needed for the program to run successfully. Users can paste their desired blocked domains in the blocklist file, where the resolver will account for this and its sub-domains when applying blocking. Client devices have their local IP addresses logged within the terminal (within application for Windows release), while all query information (including blocked domains) are saved to the log file where it can be analyzed by the user. The application supports both IPV4 and IPV6 for hosting and upstream communication, where the user is able to choose which IP family to host on at startup. The program is also friendly to multihost support given its small file size, allowing the user to host more than one instance of the program on different machines simultaneously for concurrent resolving through both IP families. 
