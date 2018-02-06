# Task 1 - IP Address via RSLinx

## Equipment Needed

-   RSLinx Classic
-   Ethernet Cable
-   (Optional) USB Cable

## Assumptions

The Ethernet procedure assumes that the device is being assigned an IP address by a DHCP server. Henry Pump shop computers are configured with a DHCP server to assign IP addresses on the 192.168.1.0 network.

## Procedure (Ethernet)

1.  Ensure your PC IP Address is a member of the same subnet as the device.
2.  Open RSLinx Classic
3.  If there is already an EtherNet\IP Devices driver setup, skip to step 9.
4.  Click the "Configure Drivers" button or navigate to "Communications > Configure Drivers".
5.  Under "Available Driver Types" select "EtherNet\IP Devices" and click "Add New..."
6.  Choose a name for the driver or leave it as the default.
7.  Select which network port to use for the driver. This is typically "Windows Default" or the Ethernet Port.
8.  Close the "Configure Drivers" window.
9.  Click the RSWho button or navigate to "Communications > RSWho".
10. Expand the EtherNet\IP Devices driver to begin browsing the network.
11. Locate the device in the browse list.
12. Right-click on the device and select "Module Configuration".
13. In the "Port Configuration" Tab, select to "Manually configure IP settings" and input the desired IP settings. Click OK.
14. Verify in the browse list that the device is now using the correct IP Address.


## Procedure (USB)

1.  Open RSLinx Classic
2.  Expand the USB driver to begin browsing the network.
3.  Locate the device in the browse list.
4.  Right-click on the device and select "Module Configuration".
5.  In the "Port Configuration" Tab, select to "Manually configure IP settings" and input the desired IP settings. Click OK.
6.  Connect an ethernet cable from the PC to the device and ensure that the PC has an IP Address on the same subnet as the device.
7.  If there is already an EtherNet\IP Devices driver setup, skip to step 9.
8.  Click the "Configure Drivers" button or navigate to "Communications > Configure Drivers".
9.  Under "Available Driver Types" select "EtherNet\IP Devices" and click "Add New..."
10. Choose a name for the driver or leave it as the default.
11. Select which network port to use for the driver. This is typically "Windows Default" or the Ethernet Port.
12. Close the "Configure Drivers" window.
13. Click the RSWho button or navigate to "Communications > RSWho".
14. Expand the EtherNet\IP Devices driver to begin browsing the network.
15. Verify in the browse list that the device is now using the correct IP Address.
