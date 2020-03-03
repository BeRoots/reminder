# Lunix commands & tricks reminder
**Ctrl+R** => search in history

**Ctrl+R search** + **Ctrl+R** => go to the searched word

**Ctrl+E** et **Ctrl+A** => Begin & End in command

**Echap+.** => last argument

**Echap+#** => comment the command

**Ctrl+w** => delete next element

**Echap+D** => delete back element

**screen** => to make splited terinal

**for i in $(seq 10); do command; done**
**for file in *.php; do echo -n "$file "; git rev-list @ -- $file | wc -l; done**

**df -h** => espace disk
**du -h** => espace d'un dossier 

**cat** =>
**head** & **tail** =>

**ps -aux** => list all process

**top** => list all process but more graphic friendly in full screen

**kill <pid>** => kill process by id…


**fc -2 -1**  => open buffer editor with history commands enumerated as new line to edit (see fd to a buffer history at /dev/fd/bufferIdLike123

**diff -u** => make a diff

**<(command)** => process substitution
	Example:
	diff -u <(cmd1) <(cmd2) return a diff of the result of this to command
	
**cat /proc/cpuinfo** => info cpu
**cat /proc/meminfo** => info memory

**uname -a** => display distrib info

**find /etc/ -name *.conf** => searching about .conf file into /etc

**apropos search** => recherche manuel? @toCheck
**man something** return nothing? Test **help** after to search if command provide --help

**ip address** => display ip address
**ip maddr** => display mac address

**lsof -i** => see what is open @toCheck

**tty** => info about the tty
**stty** => info about speed of the tty

**su -** => **sudo su** => permanent root

**strace -c -p <processid>** =>
**vmstat -S M** =>

**iostat -xmdz 1** => not in a container (@tocheck)

**mpstat -P ALL 1** => same as iostat but for performance




