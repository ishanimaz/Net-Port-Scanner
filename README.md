Pytheas22
=========




Created by: Ishani Mazundar

Pytheas22 is an innovative Port Scanner. It scans IP-Cameras of countries, your home network and individual IP-Addresses or websites. Analysis of the IP-Cameras and the scanned home network will be saved in a database. Every open port will have a documentation. Pytheas22 can also arpsooof a device on your network (only on linux).

If the port 22 of an IP-Address or a website is open pytheas22 will try to login to the host via bruteforce.


Pytheas22 is recommended to be used in Kali linux but works on every linux distro as well on Windows

First of all
===========

Change to root (on Linux):

`sudo su`


Clone my project with (works also on Windows):

`git clone https://github.com/ishanimaz/Pytheas22`


Change to Pytheas22 directory:

`cd Pytheas22`


Install requirements:

`python requirements.py`

If finished run the main.py file

`python main.py`

It is very easy to use so everything will be explained in main.py

Thank you for using Pytheas22

Additional
==========
* Works on Linux and Windows
  
* It takes around 1.11 seconds to scan a list with 31 elements

* Pytheas22 is very easy to use.

* Bruteforce list is trained on ip-cameras

Change Log
==========

0.0.1 (01/06/2023)
-----------------
- First Release

0.0.2 (05/06/2023)
-----------------
- New Internal database
- Files on GitHub now work on windows
- "question" function now also works on windows

0.0.2.1 (10/06/2023)
--------------------
- (small fixes)

0.0.3 (28/07/2023)
--------------------
- prints hostnames of internal network
- new printing system
- more efficient port information

0.0.4 (01/08/2023)
--------------------
- 15x faster port scanning

0.0.5 (10/09/2023)
--------------------
- Better Code
- New Arp Poisoning Feature (only on Linux)
- Better Port scanning on Windows
- Shows Seconds over run seconds when scanning lots of ip's
- Multithreading Error fixed

0.0.6 (17/09/2023)
------------------
- New Printing Modell
- New Python_Port_Scanner.py Script

0.0.7 (12/12/2023)
-------------------
- IPv6 port scanning
- new terminal look
- Getting the exact location of the target's IP

0.0.7.1 (15/12/2023)
-------------------
- Download fix

0.0.7.2 (15/12/2023)
--------------------
- Error fix

0.0.8 (16/12/2023)
--------------------
- New Portscanning Model in Linux
- New Hostname features in Linux
- Port scanning error fixed in Linux

