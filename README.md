# epgpgattr

SCRIPT OBJECTIVES
- Allows an administrator to find VM's based on Operating System Type, change the portgroup to something new,
  then report from ACI VM's attached to EPG.

WORKFLOW
- User kicks off aci-sel-os-pg.py
- Prompted to enter operating system type and name of portgroup that will be used to reconfigure the VMs.

DEPENDENCIES
- Requires ACIToolKit. You can find it here: https://github.com/datacenter/acitoolkit

CREDENTIALS
- Scripts use basic user/password that is embedded into the scripts for ease of testing. Recommend a more robust auth method.


There is limited error checking in these scripts. 







