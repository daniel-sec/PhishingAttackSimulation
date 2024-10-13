<h1>Phishing Attack Simulation</h1>

<h2>Description</h2>
This project aims to simulate real-world phishing attacks to test and assess the cybersecurity awareness of employees within an organization. By creating realistic phishing emails and landing pages, the simulation helps identify potential vulnerabilities and educates employees on recognizing and responding to malicious attempts, enhancing overall security measures. The results of the simulation will provide valuable insights into employee behavior and guide future security training and policy improvements.
<br />

<h2>Project Hurdles and Outcome</h2>
During the project, I faced a few challenges. Setting up the sending profile required an app-specific password because Gmail restricts third-party apps from accessing accounts with standard credentials. Initially, I tried to deploy the project publicly via Railway, a modern app hosting platform, but ran into issues where the landing page links in the email redirected to the admin server instead. Unable to find a solution, I moved the project to a local environment. Additionally, since the landing page only had an email input field, it only captured email addresses, not passwords, but it would work the same way if a password input field were added. Despite these issues, the project was successful in creating and launching an initial phishing campaign.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Gophish (an open-source phishing framework)</b>

<h2>Environments Used </h2>

- <b>Windows 11 (23H2)</b>

<h2>Program walk-through:</h2>

<p align="center">
Installing gophish: <br/>
<img src="https://i.imgur.com/Ik1bnQF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Execute Gophish Application:  <br/>
 <img src="https://i.imgur.com/xwnzYK3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Link to the admin panel and temporary credentials: <br/>
<img src="https://i.imgur.com/4scQjdN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login Page admin server: <br/>
<img src="https://i.imgur.com/NxeCuFt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up a Sending Profile: <br/>
<img src="https://i.imgur.com/rIitMXX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up a Group of Users in my case only 1 Person (Bulk importing users is also possible through a CSV file): <br/>
<img src="https://i.imgur.com/o0FctZl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a simple email template by importing the original 'Updating Our Terms of Service' message from a Google email: <br/>
<img src="https://i.imgur.com/DjtVpon.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating the google login page as a new Landing page (capture Submitted Data/Passwords and redirect to the real google login page): <br/>
<img src="https://i.imgur.com/ZDLS8WJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a new Campaign: <br/>
<img src="https://i.imgur.com/WnRgC3B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Dashboard of the Campaign: <br/>
<img src="https://i.imgur.com/E5mY3qe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
Received Email (Every link in this email redirects to the previously created landing page): <br/>
<img src="https://i.imgur.com/c1zwZU0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upon clicking any link in the email, the user will be redirected to the landing page: <br/>
<img src="https://i.imgur.com/qlas9na.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Results of the Campaign: <br/>
<img src="https://i.imgur.com/ZO7izPi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Submitted Data, such as email address: <br/>
<img src="https://i.imgur.com/LcpdzJw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
