# ansible ntp sample

tested with version 2.11 and greater

task done by ntp.yml:

- install or update ntp to latest version
- set ntp server array 
- update timezone 
- Reconfigure Timezone Data (needed on ubuntu or debian from 10+)
- save ntp.conf file using template ntp.conf.j2
- restarting ntp

Tested on Ubuntu 20.04 and Debian 11.

