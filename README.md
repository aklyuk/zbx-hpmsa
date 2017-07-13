# zbx-hpmsa
Zabbix module to monitor HP MSA storages

zbx-hpmsa provides possibility to make LLD of physical and virtual disks on HP MSA storages via it's XML API. Also it can gets status of discovered component.

Version 0.2.3
LLD:
  - physical disks 
  - virtual disks
Receiving status:
  - physical disks 
  - virtual disks

Dependencies:
  - None

Usage:
  LLD:
  $ ./zbx-hpmsa.py --discovery --msa MSA-NAME-OR-IP --component vdisks
  $ {"data":[{"{#VDISKNAME}":"vDisk01"},{"{#VDISKNAME}":"vDisk02"}]}
