#llp

Usage: /usr/bin/scanwifi

Description: A small script which lists avaliable wifi networks near you. Use the output in other tools for automation. Use "refresh" as argument to automatically run this script every 2 secconds with help of watch command.

For batter result, run the script with sudo.

Sample use:
<pre>
$ sudo scanwifi 
Breaker1
Maker1
Client1
Guest1
JioFi2_AAE6F1
JioFi2_7B7B38

$sudo scanwifi refresh

Every 2.0s: iwlist scan 2>&1 | grep -i essid | cut -d'"' -f2                                            Wed May  3 14:56:15 2017

Breaker1
Guest1
Maker1
Client1
JioFi2_AAE6F1
JioFi2_7B7B38
extreme
Storm
SPiDiGO




</pre>
