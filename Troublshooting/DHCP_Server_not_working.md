## DHCP Server not working

On this demo, we will troubshoot why users cannot obtain an IP Address from the DHCP server on our Windows server.
<br>
Let us go and check our Windows server and open Powershell. To check all the servcices that are running, we will use the ``sc query`` command(Short for Service Control query). 
<br>

<img width="310" height="117" alt="image" src="https://github.com/user-attachments/assets/36d788ce-5e11-4a29-a989-79e17bffd9d8" />
<br>

As you can see on the output, the ``DHCP Server`` status is set to ```STOPPED```. Let us then try and restart the DHCP Server using the command:
```
Restart-Service -Name DHCP Server
```
<br>

Once Restarted, use the ```sc query``` command again and status should be set on ``RUNNING``.
<br>
<img width="342" height="151" alt="image" src="https://github.com/user-attachments/assets/496aba41-81bc-44e3-8bb9-0b3518bfc854" />
<br>


