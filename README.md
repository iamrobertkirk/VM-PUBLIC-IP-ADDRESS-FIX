<p align="center">
</p>

<h1>Missing Public IP Address For VM FIX! </h1>
This tutorial shows the process of Creating A Public IP when there is no IP for a VM.<br />

![image](https://github.com/user-attachments/assets/113eb46e-e468-4549-abf9-13e9d0a4e410)


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 11 Pro (21H2)



- 6 Steps to complete objective

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/16cfbd08-fd03-488b-8285-e1df8c9cb31a)



<p>

</p>
<p>
Click on "ipConfig1" to proceed. Now, on the IP configuration page, you'll see options for Private and Public IP addresses. Under the Public IP address settings, you'll have the option to associate or create a new public IP. Choose the appropriate option based on your needs.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/e3aa3087-b371-4a5a-9f8f-e3e99f28d664)


</p>
<p>
In step two, after going to Network Settings and selecting 'Configure' next to Public IP, navigate to the network interface, look for the blue 'ipconfig1' text under IP configurations, and click it. There you go!


</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/9bc29d98-f135-466d-a42d-316e028ea8a7)



<p>
After clicking 'ipconfig1', a tab opens to edit IP settings. Click 'Associate' under Public IP address. Simple!
<br />

![image](https://github.com/user-attachments/assets/ea1b7e90-452b-40b3-9e35-b11b28706828)



In step four, after selecting 'ipconfig1', choose to create a Public IP. Click the tab next to 'Name,' select the first name that appears, and then press OK. Easy as that!


![image](https://github.com/user-attachments/assets/b26bd250-77a7-48ec-bb99-67ebd737b806)


Once you've double-checked everything, click 'Save' to ensure all your settings are applied. That locks in your configuration. You're all set!


![image](https://github.com/user-attachments/assets/d9b69bd3-164d-445a-ba9a-e8e6f90700f7)


For step six, just wait a few minutes for your Public IP and Virtual Machine to update. Once done, you should be good to go!

