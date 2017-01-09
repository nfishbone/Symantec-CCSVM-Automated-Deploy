# ><(((('>
# Symantec-CCSVM-Automated-Deploy
Scripts used for automating the setup/deployment of Symantec CCSVM (Rapid7 Nexpose) Scan Engines

hostnamescript - Script used to set the hostname for the OS image. Reboots OS after setting the hostname in the /etc/hostname & /etc/hosts files.
staticip - Script used for setting on the OS: Static IP Address, Network Mask, Gateway, Nameserver, & Search. Restarts networking service to save changes made.
pairscript - Script used to enable and pair the scan engine to the master CCSVM (nexpose) server.

After scripts are ran, the scan engine will show up in the CCSVM (rapid7) console and be ready to be initialized.
