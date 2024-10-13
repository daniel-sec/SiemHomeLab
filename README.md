<h1>Siem Home Lab -- Failed</h1>

<h2>Description</h2>
A comprehensive Security Information and Event Management (SIEM) lab set up in a home environment to practice and refine cybersecurity skills. This project simulates real-world network conditions and threats, enabling hands-on experience in log analysis, threat detection, and incident response. 
<br />

<h2>Project Hurdles and Outcome</h2>
Unfortunately, this project did not succeed as intended. While I successfully generated security events on the Kali VM, the logs were not successfully forwarded to the SIEM for analysis. This failure in log transmission prevented me from further analyzing the security events within the SIEM environment. Although the project wasn't entirely successful, it gave me valuable first-hand experience in trying to set up a SIEM for the first time, helping me understand the foundational steps and challenges involved. 
<br />

<h2>Languages and Utilities Used</h2>

- <b>Elastic Agent</b> 
- <b>VMware</b>

<h2>Environments Used </h2>

- <b>Kali VM</b>

<h2>Program walk-through:</h2>

<p align="center">
Setting up the agent to collect logs: <br/>
<img src="https://i.imgur.com/EO7tCvV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Elastic Agent on Host:  <br/>
 <img src="https://i.imgur.com/ROlbVRu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/wOd1N9V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Succesfull installation: <br/>
<img src="https://i.imgur.com/mTRrVVP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/OrsVIi0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating Security Event on the Kali VM: <br/>
<img src="https://i.imgur.com/dKnNjgq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
