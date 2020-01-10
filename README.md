WELCOME WELUNYMOUS script 2020
====
* copy the following script into the profile file
* $ cd ../usr/etc
* $ nano profile 

Profile File
====
```
clear
cowsay -f welu "ANONYMOUS INDONESIA" | lolcat
figlet "WELCOME ANONYMOUS" | lolcat
echo SYSTEM READY :
python ../usr/etc/welunymous/ip.py -m | lolcat
echo TODAY IS :
date | lolcat
echo KERNEL TYPE :
uname -smr | lolcat
```
* CTRL+X AND Y [ENTER]


Download/Installation
====
* pkg update && upgrade
* pkg install ruby
* gem install lolcat
* pkg install cowsay
* pkg install toilet
* pkg install neofetch
* pkg install git
* git clone https://github.com/romanticano/welunymous.git
* cd welunymous
* mv -r -f welu.cow ../usr/share/cows
* cd 
* mv -r -f welunymous ../usr/etc
* pkg install nano
* pkg install python
* pip install termcolor


Requirements
=====
* git
* Python
* termcolor
* colorama
* ruby

Geolocation Information
====
* ASN
* City
* Country
* Country Code
* ISP
* Latitude
* Longtitude
* Organization
* Region Code
* Region Name
* Timezone
* Zip Code


Usage
====
```
$ ./ip.py
usage: ip.py [-h] [-m] [-t TARGET] [-T file] [-u User-Agent]
                        [-U file] [-g] [--noprint] [-v] [--nolog] [-x PROXY]
                        [-X file] [-e file] [-ec file] [-ex file]

IPGeolocation 2.0.4

--[ Retrieve IP Geolocation information from ip-api.com
--[ Copyright (c) 2015-2016 maldevel (@maldevel)
--[ ip-api.com service will automatically ban any IP addresses doing over 150 requests per minute.

optional arguments:
  -h, --help            show this help message and exit
  -m, --my-ip           Get Geolocation info for my IP address.
  -t TARGET, --target TARGET
                        IP Address or Domain to be analyzed.
  -T file, --tlist file
                        A list of IPs/Domains targets, each target in new line.
  -u User-Agent, --user-agent User-Agent
                        Set the User-Agent request header (default: IP2GeoLocation 2.0.3).
  -U file, --ulist file
                        A list of User-Agent strings, each string in new line.
  -g                    Open IP location in Google maps with default browser.
  --noprint             IPGeolocation will print IP Geolocation info to terminal. It is possible to tell IPGeolocation n
ot to print results to terminal with this option.
  -v, --verbose         Enable verbose output.
  --nolog               IPGeolocation will save a .log file. It is possible to tell IPGeolocation not to save those log
files with this option.
  -x PROXY, --proxy PROXY
                        Setup proxy server (example: http://127.0.0.1:8080)
  -X file, --xlist file
                        A list of proxies, each proxy url in new line.
  -e file, --txt file   Export results.
  -ec file, --csv file  Export results in CSV format.
  -ex file, --xml file  Export results in XML format.
```
  
