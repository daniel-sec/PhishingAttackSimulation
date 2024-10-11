<h1>Phishing Attack Simulation</h1>

<h2>Description</h2>
A comprehensive Security Information and Event Management (SIEM) lab set up in a home environment to practice and refine cybersecurity skills. This project simulates real-world network conditions and threats, enabling hands-on experience in log analysis, threat detection, and incident response. 
<br />

<h2>Project Hurdles and Outcome</h2>
Unfortunately, this project did not succeed as intended. While I successfully generated security events on the Kali VM, the logs were not successfully forwarded to the SIEM for analysis. This failure in log transmission prevented me from further analyzing the security events within the SIEM environment. Although the project wasn't entirely successful, it gave me valuable first-hand experience in setting up a SIEM for the first time, helping me understand the foundational steps and challenges involved. 
<br />

<h2>Languages and Utilities Used</h2>

- <b>Railway (a modern app hosting platform)</b> 
- <b>Gophish (an open-source phishing framework)</b>

<h2>Environments Used </h2>

- <b>Windows 11 (23H2)</b>

<h2>Program walk-through:</h2>

<p align="center">
Fork the Gophish repository: <br/>
<img src="https://i.imgur.com/QXSs0dH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log into Railway and deploy from GitHub repo:  <br/>
 <img src="https://i.imgur.com/rtVDWpT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate Domain to expose the service to the public internet: <br/>
<img src="https://i.imgur.com/ITx5qO9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a new variable PORT with the value 3333: <br/>
<img src="https://i.imgur.com/gKiIkYr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Temporary credentials to log into the admin server: <br/>
<img src="https://i.imgur.com/OyORVxd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Edit config.json File in the forked Gophish repository (original): <br/>
<img src="https://i.imgur.com/SEFqsAD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Edited File (modefied): <br/>
<img src="https://i.imgur.com/Akyhiik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch the deployment URL: <br/>
<img src="https://i.imgur.com/3FASbmK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Changing password after using the temporary credentials: <br/>
<img src="https://i.imgur.com/lNsi4nw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a csv to Import Users: <br/>
<img src="https://i.imgur.com/504FiwV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
Creating a new Group of Users: <br/>
<img src="https://i.imgur.com/Rkq8F4K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a simple Email Template: <br/>
<img src="https://i.imgur.com/ljDoBxj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Edit config.json File in the forked Gophish repository (original): <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Edit config.json File in the forked Gophish repository (original): <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Edit config.json File in the forked Gophish repository (original): <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
