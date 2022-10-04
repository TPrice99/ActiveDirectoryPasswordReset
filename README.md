<h1>Active Directory Password Reset</h1>


<h2>Description</h2>
Project will deminstrate how to use Active Directory to reset a user's password. When a user forgets their password they will be unable to access their
account and the user should contact the IT team for help.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<h4>Mike is the IT help desk worker and Cristina Barrier is the user.<br>
Cristina is unable to login to her account and she doesn't remember her password.<br>
Cristina tells Mike that she can't login into her account and thinks she forgot her password.<br>
Mike asks for her username so he can do a password reset. She said her username is cbarrier.</h4>



<p align="center">
Windows Server: Select Active Directory Users and Computers <br/>
<img src="https://i.imgur.com/Fuv68e3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right Click User folder and select Find  <br/>
<img src="https://i.imgur.com/GVzpRfz.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Search the username then right click the user and select Reset Password <br/>
<img src="https://i.imgur.com/nUJqZX6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter in a password and select Unlock user account  <br/>
<img src="https://i.imgur.com/O9NNEdX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Double left click user account. Then select Account tab, select User must change password at next logon  <br/>
<img src="https://i.imgur.com/9HyUqBu.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The user should then login with the password from Mike  <br/>
<img src="https://i.imgur.com/6oZYJ1h.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If the password was entered correctly it will display this  <br/>
<img src="https://i.imgur.com/0wkNOAO.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next the user will enter a password they should remember  <br/>
<img src="https://i.imgur.com/RvuglnU.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The user's password is now changed. I hope this helps!
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
