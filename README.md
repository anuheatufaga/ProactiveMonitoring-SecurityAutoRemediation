<h1>AWS- Proactive Monitoring & Security Auto-Remediation for EC2 Instances</h1>



<h2>Description</h2>

This project involves setting up and configuring a proactive monitoring and security response system in AWS.

The project begins with launching and configuring two Amazon EC2 instances, Dev-Server and Dev-Prod, and installing tools to simulate system performance issues.

The Amazon CloudWatch Agent is then installed on both instances to collect additional system-level metrics, providing more detailed visibility into instance performance and health.

CloudWatch alarms are configured to monitor these metrics and detect when predefined thresholds are exceeded. When an alarm is triggered, an AWS Lambda function automatically responds by tagging the affected EC2 instance, helping identify resources that require attention.

The overall goal is to gain hands-on experience with cloud infrastructure monitoring, automated responses, and foundational cloud security practices.


<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Security AutoRemediation"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Security AutoRemediation"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Security AutoRemediation"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Security AutoRemediation"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Security AutoRemediation"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Security AutoRemediation"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Security AutoRemediation"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
