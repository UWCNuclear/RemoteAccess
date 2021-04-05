# How to remotely access a Linux machine from a Linux machine
Step 1:   Install UWC VPN: https://iamuwc.uwc.ac.za/

Step 2:   Connect to UWC VPN.

Step 3:   Open a terminal and ssh as normal: ssh -X username@IPaddress.


# How to remotely access a Linux machine from a Windows machine
Step 1:   Install UWC VPN: https://iamuwc.uwc.ac.za/

Install XMing :		https://sourceforge.net/projects/xming/
  
Install PuTTY :		https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
  
Step 2:	  Connect to UWC VPN.		

Step 3:	  Open XMing (it should be running before you open a terminal).		

Step 4: 	Open PuTTY. Type in Host Name as "username@IPadress".

Step 5: 	In Connection -> SSH -> X11, check "Enable X11 forwarding".

Step 6: 	You can save the session so you don't have to set it up again. Then click "Open" to connect.


# How to remotely access a Windows machine from a Windows machine	
Step 1: 	Install UWC VPN: https://iamuwc.uwc.ac.za/

Step 2: 	Connect to UWC VPN.

Step 3: 	In the search box on the taskbar, type Remote Desktop Connection, and then select it.

Step 4: 	In Remote Desktop Connection, type the name of the lab desktop, and then select Connect.


# How to remotely access a Windows machine from a Linux machine	
Step 1:	  Install UWC VPN: https://iamuwc.uwc.ac.za/

Step 2: 	Connect to UWC VPN.

Step 3:	  Search “Remote Desktop” to find and open the Remmina Remote Desktop Client.

Step 4:	  Once Remmina Remote Desktop Client is open, click the "plus" icon next the letters RDP

Step 5:	  A pop up window will appear, the basic section will be in focus. 

Step 6:	  Enter the IP address, username , password and the domain of the Windows machine.

Step 7:	  Go to color depth and change it to "High color (16bpp)

Step 8: 	Click connect.
