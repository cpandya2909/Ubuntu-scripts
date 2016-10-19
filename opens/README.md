#opens

Usage: /usr/bin/opens "file with extention"

Description: Finds mimetype of the given file and from default application lists, tries to find which command is used to open the application

Sample use:

$ opens 1.txt <br>
Command : gedit 1.txt<br>
Command : gedit --new-window<br>
Command : gedit --new-document<br>

$ opens 1.txtt<br>
I can not find mimetype of 1.txtt

$ opens session.sqlite<br>
Can not find default file handler for session.sqlite of mime type application/x-sqlite3
