#opens

Usage: /usr/bin/opens "file with extention"

Description: Finds mimetype of the given file and from default application lists, tries to find which command is used to open the application

Sample use:
<pre>
$ opens 1.txt
Command : gedit 1.txt
Command : gedit --new-window
Command : gedit --new-document

$ opens 1.txtt
I can not find mimetype of 1.txtt

$ opens session.sqlite
Can not find default file handler for session.sqlite of mime type application/x-sqlite3
</pre>
