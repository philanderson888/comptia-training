# comptia-training
A repository for teaching notes on the CompTIA suite of products : A+, Net+, Security+ and labs

## Labs

<pre>
Networking Theory	
https://www.submarinecablemap.com/	
Internet Mapping Project	
IGP	
OpenNMS Network Management System	
SYN..ACK  FIN..ACK on both sides	
https://www.telnet.org/htm/places.htm	
nc instead of telnet on mac	
nc telehack.com 23	
nc towel.blinkenlights.nl 23	
Windows freeSSHd telnet server	
shasum -a 512 myfile.txt  on MAC	
Get-FileHash -Algorithm SHA512 	
CHAP compares HASHes at each end	
VLAN Pooling	
ICS Industrial Control System	
DCS Distributed Control System	
Netflow Cisco 	
LiveAction Network Monitoring 	
SIEM	
dig	
mtr my traceroute : non-stop	
ss Linux equivalent of Netstat	
CAAS  	
DaaS	
MaaS	
	
	
	
	
	
	
	
Networking - On Pause	
mike@totalsem.com	
https://www.totalsem.com/store/category/comptia-network-practice-tests/	
	
	
	
	
	
	
	
	
	
	
	
	
	
A+ Labs	
Storage  	
ADD 3 HARD DRIVES TO SERVER 5GB SIZE EACH	
CREATE BASIC PARTITION	
RAID 0 : STRIPE	
RAID 1 : MIRROR	
RAID 5 : STRIPE WITH PARITY	
CREATE NEW PARTITION AND DON'T GIVE IT A DRIVE LETTER BUT PUT IT INSIDE A FOLDER (MOUNT IT)	
DISKPART	
LIST DISK	
SELECT DISK	
LIST PARTITION	
CREATE PARTITION PRIMARY SIZE=500	
FORMAT	
ASSIGN DRIVE LETTER	
REPEAT FOR RAID 0/1/5 WITH CREATE VOLUME RAID5 DISKS=1,2,3 ETC..	
Recovery	
Put in DVD and boot to WinRE environment	
WinRE : Dir E:\ to view Windows	
WinRE : MD E:\newfolder to create a folder	
Other Random A+ Labs  	
VIEW BOOT SETTINGS (ORDER OF BOOT DEVICES)	
STRIP AND REBUILD PC	
MULTIMETER READ VOLTAGES COMING OUT OF A POWER SUPPLY ** CARE HEALTH AND SAFETY RISK OF ELECTRICAL SHOCK **	
	
	
Networking Labs	
	
	
	
Networking Tools	
REMOTE DESKTOP FROM CLIENT TO SERVER	
Create DNS records A, AAAA, MX, CNAME	
Create Share on Server and Share	
NET SHARE my_share_name=c:\path-to-share	
NET SHARE display all shares	
NET USE Z: \\SERVER\SHARE	
Wifi : Go to http://ui.linksys.com/E1200/2.0.04/	
Install And Run IIS Web Server	
CONNECT TO IIS WEB SERVER	
HTTP://LOCALHOST	
HTTP://<IP>	
HTTP://127.0.0.1	
HTTP://::1	
HTTP://<HOSTNAMEOFSERVER>	
Printing 	
Create Printer On Server and Print	
	
Group Policy	
Group Policy : Set Password Policy	
Group Policy : Set Account Lockout Policy	
GROUP POLICY : SET PASSWORD POLICY TO MIN 6 CHARACTERS LONG, CHANGING 30 DAYS	
GROUP POLICY : SET ACCOUNT TO LOCK FOR 10 MINUTES IF 3 PASSWORDS ENTERED WRONG	
PRINTER : ADD TO SERVER AND SHARE IT. LIST IN THE DIRECTORY. PRINT TEST PAGE FROM WIN7	
INSTALL UBUNTU	
Scripting Labs	
CD \ TO ROOT	
MD SCRIPTS CREATE FOLDER	
CD C:\SCRIPTS	
MD FOLDERA	
CD FOLDERA	
COPY NUL ABC.TXT	
COPY CON DEF.TXT (ADD CONTENT AND CONTROL-Z TO SAVE AND EXIT)	
REN ABC.TXT ABCD.TXT	
COPY ABCD.TXT ABCDE.TXT	
DEL ABCDE.TXT	
REGEDIT : VIEW 5 HIVES	
REGEDIT : CREATE A REGISTRY KEY (HACK THE REGISTRY!)	
REGEDIT : BACK UP THE REGISTRY	
REGEDIT : DELETE YOUR REGISTRY KEY	
REGEDIT : RESTORE THE REGISTRY TO GET YOUR KEY BACK	
WIFI 	
CONNECT TO http://ui.linksys.com E1200 ROUTER AND LOOK AT ALL THE SETTINGS	
SSID	
CHANNEL	
WIFI PASSWORD	
ENCRYPTION WPA OR WEP	
DHCP ADDRESSES GIVEN OUT	
GATEWAY	
FIREWALL ON/OFF	
GAMING : PORT SETTINGS	
	
	
MMC	
MMC.EXE ADD SNAP-IN (CHECK OUT TWO MODES : AUTHOR=ADMIN AND USER=READ-ONLY)	
	
WIFI 	
FILTER SYSTEM LOG TO ERRORS AND WARNINGS LAST 24 HOURS	
Powershell   	
Powershell Help	
Get-Help *get*	
Get-Service *a*	
Get-Command *a*	
Get-Service | where-object {$_.Status -eq 'Stopped'}	
	
	
	
	
	
VIEW UAC Settings	
VIEW READ-ONLY FILE ATTRIBUTE	
VIEW COMPRESSED FILE ATTRIBUTE	
VIEW ENCRYPTED FILE ATTRIBUTE	
VIEW READY TO ARCHIVE FILE ATTRIBUTE	
ATTRIB +R -S -H -A ABC.TXT	
ATTRIB -R -S -H -A ABC.TXT	
NET SHARE TO VIEW SHARES	
NET SHARE MYSHARE=C:\PATH TO CREATE A SHARE	
NET USE \\SERVER\SHARE T: /PERSISTENT:YES TO MAP A SHARE	
ECHO %TEMP%	
ECHO %WINDIR%	
ECHO %PATH%	
ECHO %SYSTEMROOT%	
TREE	
XCOPY FOLDERA FOLDERB	
.EXE => COMPATIBLE WITH EARLIER OS	
MSCONFIG	
SERVICES	
COMPUTER MANAGEMENT	
LOCAL USERS AND GROUPS	
SHARES	
TASK MANAGER	
RESOURCE MONITOR	
PERFORMANCE MONITOR	
RELIABILITY MONITOR	
TURN OFF AERO FEATURES	
SERVER : MOVE THE PAGING FILE TO ANOTHER DRIVE	
TASKLIST	
TASKKILL /PID:1234 /F	
DRIVES => POOL => SPACE WITH A VIRTUAL DISK => CREATE AND FORMAT A VOLUME	
Pool : Create from UNUSED DISKS	
Storage Pool : Drives must be initialized	
Pool : 2-way needs 2 disks, 3 way needs 5 disks to allow for 2 disks failing	
Space : Thin/Fixed provision	
Space : From Pool => Create Virtual Disk => Create Volume	
CHECK DISK (GUI)	
CHKDSK C: /F (COMMAND LINE)	
DEFRAG (GUI)	
DEFRAG C: (COMMAND LINE)	
DOWNLOAD EICAR TEST VIRUS AND SCAN AND REMOVE IT	
HOSTNAME	
NBTSTAT -n	
NETSTAT -a	
FIREWALL : BLOCK / ALLOW A PING INTO A WINDOWS 7 CLIENT	
Net+ Labs	
DHCP LAB	
DNS : ADD AN ‘A’ RECORD TO DNS SERVER	
DNS : ADD AN ‘AAAA’ IPV6 RECORD TO DNS SERVER	
DNS : ADD AN ‘MX’ EMAIL RECORD TO DNS SERVER	
DNS : ADD AN ‘WWW’ ALIAS RECORD TO DNS SERVER	
IIS : INSTALL IIS ROLE ON YOUR SERVER	
IIS : VIEW DEFAULT WEBSITE WITH HTTP://LOCALHOST	
HTTP://127.0.0.1	
HTTP://<IP-OF-YOUR-SERVER>	
HTTP://<NAME-OF-YOUR-SERVER>	
VIEW DEFAULT WEBSITE FROM WIN7 MACHINE	
CHANGE DEFAULT WEBSITE TO ‘HELLO WORLD’	
ADD A HEADER <H1>Heading</H1> YOUR WEBSITE	
DISKMGMT.MSC VIEW HARD DRIVE INFORMATION	
COMPMGMT.MSC VIEW COMPUTER MANAGEMENT OVERVIEW	
SERVICES.MSC VIEW RUNNING SERVICES ON YOUR COMPUTER	
EVENTVWR.MSC VIEW EVENT VIEW LOGS (GO TO WINDOWS => SYSTEM LOG)	
GROUP POLICY : SET PASSWORD POLICY	
GROUP POLICY : SET ACCOUNT LOCKOUT POLICY	
whatismyip : FIND OUT THE IP ADDRESS OF YOUR PUBLIC ROUTER	
Sec+ Labs	
Port scan	
tcpdump on Linux	
Network Monitor Page 175	
Static Routing Lab Page 233	
Dynamic Routing Lab Page 245	
DHCP Lab Page 261	
Computer Name Lab Page 268	
Add DNS Record Page 274	
Ping and Tracert Lab Page 279	
Virtual Switch Lab : Page 344	
Permissions Lab Page 372	
Install Certificate Server Page 436	
NAT Lab Page 460	
WINDOWS FIREWALL LAB : PAGE 471	
SUPERSCAN LAB PAGE 487	
Superscan4.1.exe	
ipscan-3.4.1-setup.exe	
ipscan24.exe	
NM34_x64.exe	
nmap-7.10-setup.exe	
SET UP RADIUS PAGE 508	
RDP LAB PAGE 512	
VPN LAB PAGE 526	
NETMON MONITORING PAGE 546	
PERFMON LAB PAGE 559	
FIREWALL TROUBLESHOOTING PAGE 628	
UI.LINKSYS.COM	
PORT SCAN	
NETSTAT	
NBTSTAT	
WHICH SCANNING UTILITIES	
WIRESHARE	
ANGRY IP SCANNER	
NETMON GET IT WORKING!	
STATIC ROUTING	
DYNAMIC ROUTING	
DHCP	
RENAME	
DNS	
VIRTUAL SWITCH HYPERV	
PERMISSIONS	
CA	
NAT	
FIREWALL	
SUPERSCAN	
RADIUS	
RDP	
VPN	
NETMON	
PERFMON	
Advanced Labs	
LINUX RESCUE ENVIRONMENT	
APPLE RESCUE ENVIRONMNET	
PORT FORWARD	
PORT TRIGGER	
RPC AND WS-RM REMOTE MANAGEMENT : AUTO START	
ADD ROLE RRAS => YES DIRECTACCESS + VPN + ADD FEATURES = ROUTING + IIS	
ALLOW USERS TO LOG ON LOCALLY : GROUP POLICY : DEFATULS DC POLICY : COMPUTER => WIN => SEC => LOCAL USER RIGHTS YES LOG ON LOCALLY ==> AUTHENTICATED USERS	
ADD BACKUP ROLE	
CONFIGURE RRAS	
Shortcuts	
MAC	
View Desktop - pinch 3 fingers on trackpad	
Function F11 - view desktop	
Move between open applications - Control + Left/Right	
Top/Bottom - Option Up/Down	
Move item - Option-Command-V or Option with Paste (becomes move)	
Sublime Shortcuts	
Surround with tags : Control - Shift - W	
Command Shift P	
Command P	
Excel	
Shift Spacebar then Control Shift + Insert Row	
Shift Spacebar Select Row	
Shift Spacebar then Control - Delete Row	
	
	
	
Server	
SCCM Install     https://prajwaldesai.com/sccm-1802-install-guide/	
	
	
Server Labs - Advanced Challenge!!!	
Install SCCM	
Buy a domain and connect Azure AD to it, then sync to local domain also!	
Set up IIS website on real domain	
Set up exchange on real domain	
Azure labs	
	
	
	
	
		
</pre>
