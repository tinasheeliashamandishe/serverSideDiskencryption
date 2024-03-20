<h1>Encrypt a Data disk using Azure Server-Side disk encryption</h1>

<h2>Description</h2>
This lab will Encrypt a Data disk using Azure Server-Side disk encryption. The encryption willbe done using Customer Managed Keys.<br />
This lab assumes that you have already created a Windows virtual machine server, and added a data disk to the machine.
<br />

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Step 1</h4>
Create a Key Vault Service Resource<br/>
<img src="https://i.imgur.com/7ch1xH7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<h4>Step 2</h4> 
In the Key Vault Resource, Generate a new Key.<br/>
<img src="https://i.imgur.com/WvHH41m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

<br />

<h4>Step 3</h4> 
Create a Disk Encryption Sets Rescource<br/>
<img src="https://i.imgur.com/LBcBZcy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

<br />

<h4>Step 4</h4> 
Go to your VM, Deallocate the VM and go to Encryption, select the disk you want to encrypt and select CMK<br/>
<img src="https://i.imgur.com/VZXCKyH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

<h4>Step 5</h4> 
The new disk is now ready for use on the virtual machine server<br/>
<img src="https://i.imgur.com/W9mzewH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

