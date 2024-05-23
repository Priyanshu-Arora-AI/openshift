# openshift

setup minishift in virtualbox otherwise we can use crc  CodeReady Containers (CRC) but it not support by virtualbox 

go to link download software
https://github.com/minishift/minishift/releases

cmd
 .\minishift.exe config set vm-driver virtualbox
 .\minishift.exe start --vm-driver virtualbox
