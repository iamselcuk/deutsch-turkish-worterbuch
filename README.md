# deutsch-turkish-worterbuch
i edited this dictionary for program called `ding worterbuch`.

you must install  ding 
https://www-user.tu-chemnitz.de/~fri/ding/

To install it on Linux (RPM based, such as Fedora, Red Hat, SuSE) - as root:
   # rpm -Uhv ding-1.8.1-1.noarch.rpm
Packages for other Linux systems	
Debian:
   # apt-get install ding trans-de-en
Gentoo Linux: 
   # emerge -v app-text/ding
Arch Linux: 
   # pacman -S ding
To install it on other Unix systems: 	
   #  gzip -dc ding-1.8.1.tar.gz | tar -xvf -
   #  cd ding-1.8.1
To install simply run - as root:	
   # ./install.sh
Or manually - as root:	

     edit ding and change some options explained there, esp. the location
     of the dictionary file.
   # cp ding /your/bin/dir
   # cp de-en.txt /your/lib/dir
   
   after ding worterbuch installation go to where save de-tur.txt   and type 
   
   # cp '/home/...../Desktop/de-tur.txt' '/usr/local/bin

whola ding  program preferences you can choose turkish dictionary
