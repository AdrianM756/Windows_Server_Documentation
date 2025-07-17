## Create a banner

On the ```Server Manager```, click ```Tools``` then, select ```Group Policy Management```.
<br>
<img width="625" height="287" alt="image" src="https://github.com/user-attachments/assets/84a60638-4b9e-4995-92e3-72366a8e6d11" />
<br>
<br>

On the ```Group Policy Management``` prompt, select on ```Forest:<Your Domain Name>```
<br>
<img width="624" height="290" alt="image" src="https://github.com/user-attachments/assets/8aa4b261-deb0-4bf5-b05d-bdb0bf322ec0" />
<br>
<br>

Under the ```Forest:Your Domain Name>Domains>Domain Name```, right-click on ```Group Policy Object``` and select ```New```.
<br>
<img width="459" height="253" alt="image" src="https://github.com/user-attachments/assets/ac2bf925-53bc-4732-a074-abedb18ad107" />
<br>
<br>

Type ```Banner``` as the name of the policy and click ```OK```.
<br>
<img width="456" height="219" alt="image" src="https://github.com/user-attachments/assets/51ec9b2a-618e-4907-82de-588324b6acec" />
<br>
<br>

Right-click on ```Banner``` then, select ```Edit```.
<br>
<img width="240" height="97" alt="image" src="https://github.com/user-attachments/assets/8224deba-4def-4c37-a112-339fa8659a81" />
<br>
<br>

On the ```Group Policy Management Editor``` prompt, click on ```Computer Configuration>Policies>Windows Settings>Security Settings>Local Policies>Security Options``` then, select ```Interactive logon: Message text for users attempting to log on```. 
<br>
<img width="617" height="310" alt="image" src="https://github.com/user-attachments/assets/1ee1d60a-4a1d-4c0c-a268-12b72708875c" />
<br>
<br>

Just below, click on ```interactive logon: Message Title``` then, click on ```Properties```.
<br>
<img width="611" height="348" alt="image" src="https://github.com/user-attachments/assets/07cc0922-1d92-4213-a385-c464dd52f5e6" />
<br>
<br>

Click on ```Define this policy setting``` then, type ```WELCOME!```. Once done, click on ```Apply``` and ```OK```.
<br>
<img width="325" height="402" alt="image" src="https://github.com/user-attachments/assets/8645150a-5294-47d2-9630-04f61fbbb5f2" />
<br>
<br>

This should be the expected output:
<br>
<img width="616" height="330" alt="image" src="https://github.com/user-attachments/assets/117134c7-e024-4d00-85cc-4cfc495ba41b" />
<br>
<br>

Right-click on your ```Domain``` then, select ```Link an Existing GPO```.
<br>
<img width="347" height="210" alt="image" src="https://github.com/user-attachments/assets/af9d655a-8602-4cc8-83ea-8152398737d5" />
<br>
<br>

Select ```Banner``` then, click ```OK```.
<br>
<img width="350" height="317" alt="image" src="https://github.com/user-attachments/assets/c80dd389-effd-4ed5-a98a-34b558543678" />
<br>
<br>


