Microsoft Activation Scripts (MAS)
Open-source Windows and Office activator featuring HWID, Ohook, TSforge, KMS38, and Online KMS activation methods, along with advanced troubleshooting.

How to Activate Windows / Office?
Method 1 - PowerShell (Windows 8 and later) ❤️
info
Open PowerShell
To do that, press the Windows key + X, then select PowerShell or Terminal.

Copy and paste the code below, then press enter.

irm https://get.activated.win | iex

Alternatively, you can use the following (this will be deprecated in the future):

irm https://massgrave.dev/get | iex

You will see the activation options. Choose the activation options highlighted in green.

That's all

Method 2 - Traditional (Windows Vista and later)
Click here to view
To activate additional products such as Office for macOS, Visual Studio, RDS CALs, and Windows XP, check here.
To run the scripts in unattended mode, check here.
Not working ❓
If you are unable to launch MAS using the PowerShell method, please refer to Method 2 above.
If MAS launches but displays errors, check for troubleshooting steps highlighted in blue and follow them.
If issues persist, feel free to reach out to us here.
note
The IRM command in PowerShell downloads a script from a specified URL, and the IEX command executes it.
Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files.
Be cautious, as some spread malware disguised as MAS by changing the URL in the IRM command.
MAS Latest Release
Last Release - v3.4 (3-June-2025)
GitHub / Azure DevOps / Self-hosted Git

Features
HWID (Digital License) Method to Permanently Activate Windows
Ohook Method to Permanently Activate Office
TSforge Method to Permanently Activate Windows/ESU/Office
KMS38 Method to Activate Windows Till the Year 2038
Online KMS Method to Activate Windows/Office For 180 Days (Lifetime With Renewal Task)
Advanced Activation Troubleshooting
$OEM$ Folders For Preactivation
Change Windows Edition
Change Office Edition
Check Windows/Office Activation Status
Available in All In One and Separate Files Versions
Fully Open Source and Based on Batch Scripts
Fewer Antivirus Detections
Activations Summary
Activation Type	Supported Product	Activation Period	Is Internet Needed?
HWID	Windows 10-11	Permanent	Yes
Ohook	Office	Permanent	No
TSforge	Windows / ESU / Office	Permanent	Yes, needed on build 19041 and later
KMS38	Windows 10-11-Server	Till the Year 2038	No
Online KMS	Windows / Office	180 Days. Lifetime With Renewal Task	Yes
For more details, use the respective activation details in Docs and comparison chart.
To activate unsupported products such as Office on Mac, check here.


Made with Love ❤️
