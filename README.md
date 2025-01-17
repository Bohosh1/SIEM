<h1>Building a SIEM</h1>

<h2>Description</h2>
In this simple project I created a SIEM using an Azure vitual machine. Then I made an alert that notified me of succcessful RDP login attempts. 
<br />

<h2>Environments </h2>

- <b>Windows 10</b> 

<h2>Walk-through</h2>

<p align="center">
First I created a VM and allowed RDP <br/>
  (https://github.com/user-attachments/assets/fbb0ddb6-5de1-4115-a63d-eb2da32c7450)
<br />
<br />
Next I created a log analytics workspace and added Sentinel <br/>
<br />
<br />
Then I used a data connector to add VM log analytics to Sentinel <br/>
<br />
<br />
I then created a Sentitel rule that checks successful RDP log ins: <br/>
  (https://github.com/user-attachments/assets/0d15192b-9480-49f5-84b7-81bf7715e17b)

<br />
<br />
Lastly I signed in using RDP <br/>
<br />
<br />
Observe the Incidents: <br/>
(https://github.com/user-attachments/assets/57b527cb-2585-483d-bfe9-cf8d470838d8)
</p>
