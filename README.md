# cARs-WebXR

## Setup Guide:

1. Download node.js 
2. Enter the Unity build folder 
3. Press Alt+F
4. Open Windows Powershell
   P.S. You should find the directory of the file open
5. Type to open server: 
npx http-server -o 
6. Open build on laptop
   P.S. make sure that the URL is : 
	localhost:8080
		OR
	127.0.0.1:8080
7. If you want to open it on your mobile open Chrome browser both 
   on laptop & mobile
8. Go to link Chrome://inspect
9. Connect mobile with USB cable 
10. Check Discover USB devices
11. When detected click on Port Forwarding
12. Type in in 
	Port: 8080
	IP: localhost:8080
13. Check Enable Port Forwarding 
14. Click Done
15. Port will be detected and forwarding (next to device name turns green with port number) 
16. If it is not working disconnect USB cable and reconnect it
		& 
	Make sure Chrome is open on BOTH mobile & laptop
17. In url tab click the URL: localhost:8080
