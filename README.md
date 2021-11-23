# How to remotely access the MANDELA Windows machine using Chrome Remote Desktop
**Step 1:** 	On https://remotedesktop.google.com/, click "Access my computer"

**Step 2:** 	Connect using the Tastes of Nuclear Physics account.

**Step 4:** 	Under "Remote Access" and "Remote devices", click on MANDELA and connect using the PIN.

**Step 4:** 	On the menu on the right of the screen, click "Disconnect".

**Bonus Step:**   Under "Set up via SSH", there are instructions to install a plug-in to SSH from Windows or Linux :-)


# How to remotely access a Linux machine from a Linux machine
**Step 1:**   Install UWC VPN: GlobalProtect or https://iamuwc.uwc.ac.za/ (20-GB limit per month)

**Step 2:**   Connect to UWC VPN.

**Step 3:**   Open a terminal and ssh as normal: ssh -X username@IPaddress.


# How to remotely access a Linux machine from a Windows machine
**Step 1:**   Install UWC VPN: GlobalProtect or https://iamuwc.uwc.ac.za/ (20-GB limit per month)

Install XMing :		https://sourceforge.net/projects/xming/
  
Install PuTTY :		https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
  
**Step 2:**	  Connect to UWC VPN.		

**Step 3:**	  Open XMing (it should be running before you open a terminal).		

**Step 4:** 	Open PuTTY. Type in Host Name as "username@IPadress".

**Step 5:** 	In Connection -> SSH -> X11, check "Enable X11 forwarding".

**Step 6:** 	You can save the session so you don't have to set it up again. Then click "Open" to connect.


# How to remotely access a Windows machine from a Windows machine	using Windows Remote Desktop
**Step 1:** 	Install UWC VPN: GlobalProtect or https://iamuwc.uwc.ac.za/ (20-GB limit per month)

**Step 2:** 	Connect to UWC VPN.

**Step 3:** 	In the search box on the taskbar, type Remote Desktop Connection, and then select it.

**Step 4:** 	In Remote Desktop Connection, type the name of the lab desktop, and then select Connect.


# How to remotely access a Windows machine from a Linux machine	
**Step 1:**	  Install UWC VPN: GlobalProtect or https://iamuwc.uwc.ac.za/ (20-GB limit per month)

**Step 2:** 	Connect to UWC VPN.

**Step 3:**	  Search “Remote Desktop” to find and open the Remmina Remote Desktop Client.

**Step 4:**	  Once Remmina Remote Desktop Client is open, click the "plus" icon next the letters RDP

**Step 5:**	  A pop up window will appear, the basic section will be in focus. 

**Step 6:**	  Enter the IP address, username , password and the domain of the Windows machine.

**Step 7:**	  Go to color depth and change it to "High color (16bpp)"

**Step 8:** 	Click "Connect".
