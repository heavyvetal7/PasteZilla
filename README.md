PowerShell based GUI for VMKeyStrokes script by William Lam

Original script: https://github.com/lamw/vmware-scripts/blob/master/powershell/VMKeystrokes.ps1

Pre-requisites:
Requires VMware PowerCLI module

Install-Module -Name VMware.PowerCLI

No installation is required. Save the file to any location and run.
On the first run it will create a "hostlist.txt" file in the same directory to store vCenter names/IPs.
NOTE: vCenter name will be added after successfull connection.

How to use

Once connected the list of all VMs is loaded to the dropdown list
1. Select the required VM
2. Put the text into text area
3. Use the buttons below to perform required action (Type all; Type selected)
4. Use "Type clipboard" button to type the clipboard contents directly to the selected VM
5. Use "Hit Enter after typing" checkbox when working with commands (paste & execute) 
6. Use notification area icon to access the typing options

Use "Rescan VMs" button to update the dropdown list of VMs (to add VM(s) created after application was started.
