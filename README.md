<h1> Azure Conditional Access + MFA Enforcement Lab </h1>

<h2> Description: </h2>

This lab demonstrates how to configure and enforce Conditional Access policies in Azure AD, including MFA setup and blocking legacy authentication. It simulates real-world identity protection strategies used to secure cloud access.

<h2> Tools Used: </h2>

-  Entra ID

<h2> Program Walk-Through: </h2>

<p align="center">
Signing into portal.azure.com: <br/>
<img src="https://i.imgur.com/1lET8dq.png" height="80%" width="80%"/>
<br />
<br />
Head over to Entra ID using the search bar: <br/>
<img src="https://i.imgur.com/e36dbMt.png" height="80%" width="80%"/>
<br />
<br /> 
Click on “Manage groups” on the left-hand side: <br/>
<img src="https://i.imgur.com/FfpiBZZ.png" height="80%" width="80%"/>
<br />
<br />  
Click “New group”: <br/>
<img src="https://i.imgur.com/ewh3W09.png" height="80%" width="80%"/>
<br />
<br />  
Create a new group: <br/>
<img src="https://i.imgur.com/M23ENH0.png" height="80%" width="80%"/>
<br />
<br />  
Head back to Entra ID and search for “Security” on the left-hand side: <br/>
<img src="https://i.imgur.com/T4ZHxGH.png" height="80%" width="80%"/>
<br />
<br />  
Click on “Conditional Access”: <br/>
<img src="https://i.imgur.com/a6e07eQ.png" height="80%" width="80%"/>
<br />
<br />  
Create a new policy, adding the “MFA Conditional Access” group: <br/>
<img src="https://i.imgur.com/5T79Wlj.png" height="80%" width="80%"/>
<br />
<br />  
Set the target apps we want the policy to apply to: <br/>
<img src="https://i.imgur.com/c7V2Mkv.png" height="80%" width="80%"/>
<br />
<br />  
Enable MFA: <br/>
<img src="https://i.imgur.com/cFQlhK0.png" height="80%" width="80%"/>
<br />
<br />  
Click Create to finalize the setup. You’ve now successfully created a new Conditional Access and MFA enforcement policy. <br/>
<img src="https://i.imgur.com/X6YIhz4.png" height="80%" width="80%"/>
<br />
<br />  

<h2> What Security Outcome Was Achieved: </h2>

Identity is the new perimeter in cloud environments. This project demonstrates how to implement and enforce secure access policies using Azure AD Conditional Access and MFA. It highlights my ability to reduce unauthorized access risks, respond to modern threats, and manage identity securely in a cloud-first infrastructure.
