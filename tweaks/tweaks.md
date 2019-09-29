Change the screen scaling factor
    gsettings set org.gnome.desktop.interface text-scaling-factor 1.35

No Password:
 sudo visudo
 {userName} ALL=(ALL) NOPASSWD: ALL

 If you want have everyone in a group without a password use:
 %sys ALL=(ALL) NOPASSWD: /bin/kill, /bin/rm
(all members of sys run sudo without password)