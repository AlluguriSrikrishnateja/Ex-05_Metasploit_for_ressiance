# Ex-05_Metasploit_for_ressiance
Metasploit for reconnaissance in pentesting
```
Register Number : 212222040006
Name: Alluguri Srikrishna Teja
```
# Aim :
To get introduced to Metasploit Framework and to perform reconnaissance in pentesting.

# Design Steps: 
1. Install kali linux either in partition or virtual box or in live mode.
2. Investigate on the various categories of tools as follows.
3. Open terminal and try execute kali linux commands.

# Execution Steps and it's Output:
## Step1: Identify the Attacker's IP Address
Determine the IP address of the attacker's system.
<img width="476" alt="image" src="https://github.com/user-attachments/assets/9733fba4-18a7-496d-b114-e8c364210d70" />
## Step2:Launch the Metasploit Console
Invoke the msfconsole
<img width="473" alt="image" src="https://github.com/user-attachments/assets/b2b24b39-2233-4399-a808-07c24efeb8bd" />
## Step3:Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.exe 
<img width="472" alt="image" src="https://github.com/user-attachments/assets/8ab90359-d750-48c3-8839-cfdd75fbf419" />
## Step4: SetUp an HTTP Server
Once the payload file is created, navigate to the hime directory.Right-click and select "open terminal here"
![Screenshot 2025-04-07 104955](https://github.com/user-attachments/assets/c713a321-790f-475b-8199-f51f792a3722)
Run the Python command to establish an HTTP server  for file distribution.
![Screenshot 2025-04-07 105056](https://github.com/user-attachments/assets/605ecd93-ee08-46de-9fa2-7d42ae78a592)
## Step5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server. Once the victim downloads and executes the file,the exploit is triggered.
<img width="958" alt="image" src="https://github.com/user-attachments/assets/4dff4866-464e-40a5-a8be-595fcd706721" />
<img width="950" alt="image" src="https://github.com/user-attachments/assets/5fc58546-772a-4ff6-b1a1-f64821cc59b4" />
## Step6: Establish a Connection
On Kali linux, reopen the terminal and invoke "msfconsole".Follow the necessary steps to establish a connection with the victim's device.
<img width="473" alt="image" src="https://github.com/user-attachments/assets/123debe7-9cd0-4ccd-897c-e064ed3cfa7d" />

## Step7:List Commands
Use the help command to list available operations.

<img width="473" alt="image" src="https://github.com/user-attachments/assets/6e31ca21-f0f7-4ab9-b4ab-887d5a77dae0" />
## Step8:
For example,the "screenshot" command captures the victim's screen and saves it in the attacker's home directory.













