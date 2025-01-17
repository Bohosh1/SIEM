<h1>Building a SIEM</h1>

<h2>Description</h2>
In this simple project I created a SIEM using an Azure vitual machine. Then I made an alert that notified me of succcessful RDP login attempts. 
<br />

<h2>Environments </h2>

- <b>Windows 10</b> 

<h2>Walk-through</h2>

<p align="center">
First I created a VM and allowed RDP <br/>
<br />
<br />
Next I created a log analytics workspace and added Sentinel <br/>
<img src="https://imgur.com/xZKdXpD"/>
<br />
<br />
Then I used a data connector to add VM log analytics to Sentinel <br/>
<img src=""/>
<br />
<br />
I then created a Sentitel rule that checks successful RDP log ins <br/>
<img src=""/>
<br />
<br />
Lastly I signed in using RDP <br/>
<img src=""/>
<br />
<br />
Observe the Logs: <br/>
<img src=""/>
</p>
