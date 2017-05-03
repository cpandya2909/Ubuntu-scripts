#llp

Usage: /usr/bin/scanwifi

Description: A small script which lists avaliable wifi networks near you. 

Sample use:
<pre>
$ llp
-rw------- 600 'config-err-r1w8Fa'
drwx------ 700 'systemd-private-9ceb737afc454745afe86782537ff4da-colord.service-9qU8bJ'
drwx------ 700 'systemd-private-9ceb737afc454745afe86782537ff4da-rtkit-daemon.service-rlJXbO'
drwx------ 700 'systemd-private-9ceb737afc454745afe86782537ff4da-systemd-timesyncd.service-VYSViw'
drwx------ 700 'systemd-private-9ceb737afc454745afe86782537ff4da-tor@default.service-PVQzYN'
-rwsrwsrwt 7777 'tmpfile'
-rw-rw-r-- 664 'unity_support_test.0'
drwxrwxrwt 1777 'VMwareDnD'
drwx------ 700 'vmware-root'

$ llp /tmp
-rw------- 600 '/tmp/config-err-r1w8Fa'
drwx------ 700 '/tmp/systemd-private-9ceb737afc454745afe86782537ff4da-colord.service-9qU8bJ'
drwx------ 700 '/tmp/systemd-private-9ceb737afc454745afe86782537ff4da-rtkit-daemon.service-rlJXbO'
drwx------ 700 '/tmp/systemd-private-9ceb737afc454745afe86782537ff4da-systemd-timesyncd.service-VYSViw'
drwx------ 700 '/tmp/systemd-private-9ceb737afc454745afe86782537ff4da-tor@default.service-PVQzYN'
-rwsrwsrwt 7777 '/tmp/tmpfile'
-rw-rw-r-- 664 '/tmp/unity_support_test.0'
drwxrwxrwt 1777 '/tmp/VMwareDnD'
drwx------ 700 '/tmp/vmware-root'


$ llp /tmp/tmpfile 
-rwsrwsrwt 7777 '/tmp/tmpfile'

$ llp /nofile
Something went wrong

</pre>
