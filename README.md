# SPLUNK
Demonstration with screenshots showing Splunk experience

I created A Virtual Machine environment using VMWare running Windows 10.  Showcased the VML.  Used Nessus Essentials to run credentialed scans, remediated some of the vulnerabilities, then performed a rescan to verify remediation.

##### Utilities Used
 
 - Windows Server 2022

 - Splunk
 
 ##### Environments Used
 - VMWare
 - Windows 10


# Program Walk Through

 ![Alt text](https://github.com/BarryGFloyd/Vulnerability-Scan/blob/main/NESSUS%20Program%20First%20photo.jfif)

For the Virtual Machine that I will be managing vulnerabilities on, I’ll configure the network adapter to be bridged, so it can be on the same network as my native. The reason, Nessus has to Secure Server Login (SSL) into the Virtual Machine.  

![Alt text](https://github.com/BarryGFloyd/Vulnerability-Scan/blob/main/2nd%20Project%20photo.jpg)


I open up CMD to locate the IP address I’ll need to run vulnerability scans.  I named the VM Admin. The screenshot shows that the IP address is 192.168.50.185
