perl-fcgi.init
==============

init.d script for Nginx perl-fcgi server on RedHat/CentOS

Based on the perl-fcgi process from: [http://nginxlibrary.com/perl-fastcgi/](http://nginxlibrary.com/perl-fastcgi)

Install as root:

    # cp perl-fcgi /etc/rc.d/init.d/
    # chkconfig --add perl-fcgi
    # chkconfig --level 345 perl-fcgi on

Manage with:

    # service <start|stop|restart> perl-fcgi
