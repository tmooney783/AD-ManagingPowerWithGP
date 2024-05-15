<h1>Managing power plan with Group Policy</h1>

<h2>Environments used:</h2>

- Oracle VirtualBox
- Windows Server 2022
- Windows 10

<h2>Project Walk-through</h2>

<p align="center">
In group policy management tools, created a new GPO within an OU: <br/>
<img src="https://i.imgur.com/NoGQ6r8.png" height="80%" width="80%"/>
<br />
<br />
Created a new power plan in Group policy management tools>OU>power settings>edit>prefrences>control panel settings>power options>new>Power plan: <br/>
<img src="https://i.imgur.com/s8P0K02.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://i.imgur.com/y5Tdrz0.png" height="80%" width="80%"/>
<br />
<br />
<img src="https://i.imgur.com/iZhPmuq.png" height="80%" width="80%"/>
<br />
<br />
Once it was setup, I forced a group policy update on a connected Windows 10 client
</p>
