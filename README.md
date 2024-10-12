<h1>Phishing Attack Simulation</h1>

<h2>Description</h2>
This project aims to simulate real-world phishing attacks to test and assess the cybersecurity awareness of employees within an organization. By creating realistic phishing emails and landing pages, the simulation helps identify potential vulnerabilities and educates employees on recognizing and responding to malicious attempts, enhancing overall security measures. The results of the simulation will provide valuable insights into employee behavior and guide future security training and policy improvements.
<br />

<h2>Project Hurdles and Outcome</h2>
During the project, I encountered significant challenges, particularly in setting up the sending profile. While most aspects went smoothly, there was a minor hurdle with Gmail's login process. Instead of using my regular Gmail password, I had to generate an App Password. This was necessary because Gmail often restricts third-party apps from accessing accounts with standard credentials, enforcing extra security measures. Despite this, the issue was resolved, and the project proceeded successfully.
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
<img src="https://i.imgur.com/ymSqSNR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up a sending profile: <br/>
<img src="https://i.imgur.com/zwONGuZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up Landing Page: <br/>
<img src="https://i.imgur.com/uA9lRft.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up the Campaign: <br/>
<img src="https://i.imgur.com/5lqb3ZY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launching Campaign: <br/>
<img src="https://i.imgur.com/wKecYXR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
