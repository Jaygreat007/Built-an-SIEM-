# Built an SIEM

<h2>Description</h2>
The project consists of building a Security Information and Event Management (SIEM) system in Microsoft Azure. Which involves creating a robust solution for monitoring, analyzing, and responding to security events and incidents across your organization's cloud and on-premises environments. Below is a detailed description of the steps and considerations involved in setting up a SIEM with Microsoft Azure:
<br />


<h2>Programs used </h2>

- <b>Microsoft Azure</b> 
- <b>Diskpart</b>
- <b>Powershell</b>
  
<h2>Environments Used </h2>

- <b>Windows 10</b> 
<b>Virtual machine</b> 
<h2>Program walk-through:</h2>
<br />Step 1: Define Objectives and Requirements

In this project, I chose to use Azure resources for my (SIEM) because of how easy and practical the program was to set up and use. I also chose to use Azure because of the compatibility it has with third-party systems. With that being said you do not have to use Azure and you can use any other virtual machine and still use my virtual Machine just accommodate my directions with your setup and program.

Step 2: Azure Subscription Setup

Ensure you have access to an Azure subscription. If not, sign up for one and familiarize yourself with the Azure portal. I should also say that Azure is not free but first-time users get two hundred dollars. Please after you perform this project make sure to delete all the resources you use or Azure will continue to use your money and eventually you will have to pay.

Step 3: Resource Group Creation
Create a Virtual machine and then create a new resource group. Everything in this project will be in the same resources

Step 4: Network Infrastructure

Create a new inbound rule that allows everything inside the Virtual Machine. This allows all traffic from the internet into your Virtual Machine

Step 5: SIEM Software Deployment

Create a log analytics workspace. This workspace will allow your logs to be stored. Azure (SIEM) will work with the log workspace to display the geo data on the map.

Step 6: Virtual machine
Click log analytics and click your virtual machine to connect it.You wanna set up Azure sentinel  all you have to do is click the virtual machine

Step 7:
Go to remote access on your computer or laptop you want to take the passcode you made earlier for your virtual machine and the ip address it gave you and log into the virtual machine

Step 8: Detection and Alerting

Implement real-time log analysis and detection rules. Create custom detection rules or use pre-built rules, depending on your SIEM choice. Configure alerts to notify your security team of critical security events.

Step 9: Incident Management

Establish incident management processes and workflows. Define how incidents are categorized, prioritized, and assigned for investigation and response. Implement incident response playbooks to guide your team in handling security incidents.

Step 10: Monitoring and Reporting

Set up continuous monitoring of your SIEM system. Monitor dashboards and real-time alerts to stay informed about security events. Generate compliance reports to meet regulatory requirements using tools like Kibana or Azure Sentinel's reporting features.

Document your SIEM architecture, configurations, and incident response procedures. Train your security team on SIEM usage and best practices for incident handling.
<br /> 


<p align="center">
Create the virtual machine by going to Microsoft azure: <br/>
<img src="(https://imgur.com/EIfAaOW)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You then want to create your own inbound rule that allows everything inside the virtual machine so that we can see all the attacks of people trying to get into the virtual machine <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
