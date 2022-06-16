# Meterpreter Cheat Sheet

## Commands

- sysinfo: show system information

- show_mount: show partitions

- idletime - localtime: displays the idle time of the system and the local time.

- shutdown - reboot: shuts down or restarts the system. (authorization is required)

- ipconfig: displays the ip configuration of the system

- portfwd: does packet forwarding

- route : allows viewing and changing routes

- ps: show processes

- kill -pid- : kill the process

- getpid : show which pid is running our session

- migrate : moves transactions one on top of the other. runs the related process behind another process

- clearev : clear event daily

- shell : get system shell

- help or ? : get help

- pwd : show current working directory

- ls : show contents of directory

- cd : change directory

- cat : read a file

- edit : edit a file

- del or rm : delete a file

- mkdir - rmdir : create directory - remove a directory

- execute -f -filename- : execute a file (-i file, -H hide, -i execute and call)

- search -f -filename- : search a file

- download -what- -where-: download a file

- upload -what- -where-: upload a file

- background or bg : puts the session in the background

- sessions -i -session -id- : go to session

- sessions -l : show session's list

- bgrun or bglist or bgkill : in the background, the meterpreter executes, lists, finishes

