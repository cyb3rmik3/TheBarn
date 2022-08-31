# TheBarn
A description of DFIR lab setup through experience/notes/courses

VirtualBox

### Flare-VM
IP address:

### REMnux
IP address: 10.0.0.3

##### Basic setup
- Make sure OracleBox VM Tools is installed by adjusting screen resolution.
- inetsim setup
 - sudo nano /etc/inetsim/inetsim.conf
 - #start_service dns (remove #)
 - #service_bind_address 10.10.10.1 (service_bing_address 0.0.0.0)
 - #dns_default_ip 10.10.10.1 (dns_default_ip 10.0.0.3)
 - Exit nano: CTRL+O & CTRL+X

# Basic static analysis

##### Hashing malware samples
- sha256sum.exe file
- md5sum.exe file

##### Strangs & FLOSS
- floss file | floss -n 6 file for strings of 6 characters and more

##### PEview
##### PEStudio

