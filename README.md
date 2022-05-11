# BetWorm
BetWorm is a Petty Worm that run under Linux Environment to check possible attacks on end point security from Attacker point of view 

In the begging i want to mention that BetWrom project is collection of online scripts that has been modified by me + my own script being added, so i want to  
Thank (Mike Czumak) 

BetWorm is a petty Worm that you install it on your infrastructure to check end point security from attacker point of view 
so what actually the Worm do

* The worm scan an entire range you specify for open SSH service running on that range once it identify it connect to SSH with credentials you specify 

* It view /tmp/ path and drop Betwrom on /tmp/ and you can modify any path you want 

* After dropping it check all system information (Kernel, hostname – OS – Logged in Users – Environment), Running Application - All current users 

* Analyze all attacking points - Client Side Attack, Outdated Application - Process that being used for (Privilege escalation)

* Detecting Live connections on target machine by downloading last malicious domains from http://www.malwaredomainlist.com/ and cross references with your  
current live connections if you are connect to one of them

