# Reset Locked Account

<b>Scenario:</b>

A user named anna has locked her account due to multiple wrong login attempts. For this demo, we will unlock her account via powershell.
<br>

First, Let us check if her user account status using the command ``net user <username>``. We will replace the ```<useraname>``` with ```anna```. 
<br>
<img width="385" height="118" alt="image" src="https://github.com/user-attachments/assets/86357d38-a54e-4f0e-afbf-ccd619943c1e" />

Based on the output, we can see that the account is Locked out. To enable her account, We will use the command: ```UnlockADAccount -Identity <username>``` or ``net user anna /unlock``. Once done, Let us verify and check her account status. As you can see, the Lock Out status is now set to ``No``.

<img width="254" height="111" alt="image" src="https://github.com/user-attachments/assets/c2b371ef-00dd-48fc-9c9e-2b02e2a9cb66" />
<br>

