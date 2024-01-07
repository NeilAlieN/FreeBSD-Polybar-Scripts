# FreeBSD-Polybar-Scripts
Some of my FreeBSD Polybar scripts
First of you will need the following pkgs:
1. ifstat
2. freebsd-memory.sh from: #https://www.cyberciti.biz/faq/freebsd-command-to-get-ram-information/

   


Next we will setup doas for pkg updates.
   Add the following to your /usr/local/etc/doas.conf:
       permit nopass neil as root cmd pkg args update
       permit nopass neil as root cmd pkg args upgrade

# ----------------------------------------------------



       
