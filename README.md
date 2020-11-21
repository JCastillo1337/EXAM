# EXAM

# 

# deb cdrom:[Debian GNU/Linux 10.5.0 _Buster_ - Official i386 DVD Binary-1 20200801-13:12]/ buster contrib main

#deb cdrom:[Debian GNU/Linux 10.5.0 _Buster_ - Official i386 DVD Binary-1 20200801-13:12]/ buster contrib main

deb http://deb.debian.org/debian/ buster main
deb-src http://deb.debian.org/debian/ buster main

deb http://security.debian.org/debian-security buster/updates main contrib
deb-src http://security.debian.org/debian-security buster/updates main contrib

# buster-updates, previously known as 'volatile'
deb http://deb.debian.org/debian/ buster-updates main contrib
deb-src http://deb.debian.org/debian/ buster-updates main contrib

#DEBIAN 10 BUSTER ACTUALIZACIÓN DE REPOSTIORIOS DE MEXICO
deb [arch=amd64] http://ftp.mx.debian.org/debian/ buster main contrib non-free
deb-src [arch=amd64] http://ftp.mx.debian.org/debian/ buster main contrib non-free

deb [arch=amd64] http://ftp.mx.debian.org/debian/ buster-updates main contrib non-free
deb-src [arch=amd64] http://ftp.mx.debian.org/debian/ buster-updates main contrib non-free

deb [arch=amd64] http://security.debian.org/ buster/updates main contrib non-free
deb-src [arch=amd64] http://security.debian.org/ buster/updates main contrib non-free
