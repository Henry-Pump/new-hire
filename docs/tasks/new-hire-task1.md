# Task 1 - CompactLogic PLC IP Address

## Equipment Needed

-   RSLinx Classic
-   Ethernet Cable
-   (Optional) USB Cable

## Assumptions

This tutorial assumes that the PLC is being assigned an IP address by a DHCP server. Henry Pump shop computers are configured with a DHCP server to assign IP addresses on the 192.168.1.0 network.

## Procedure (Ethernet)

1.  Ensure your PC IP Address is a member of the same subnet as the PLC.
2.  Open RSLinx Classic
3.  If there is already an EtherNet\IP Devices driver setup, skip to step 9.
4.  Click the "Configure Drivers" button or navigate to "Communications > Configure Drivers".
5.  Under "Available Driver Types" select "EtherNet\IP Devices" and click "Add New..."
6.  Choose a name for the driver or leave it as the default.
7.  Select which network port to use for the driver. This is typically "Windows Default" or the Ethernet Port.
8.  Close the "Configure Drivers" window.
9.  Click the RSWho button or navigate to "Communications > RSWho".
10. Expand the EtherNet\IP Devices driver to begin browsing the network.
11. Locate the CompactLogix PLC in the browse list.
12. Right-click on the PLC and select "Module Configuration".
13. In the "Port Configuration" Tab, select to "Manually configure IP settings" and input the desired IP settings. Click OK.
14. Verify in the browse list that the PLC is now using the correct IP Address.
