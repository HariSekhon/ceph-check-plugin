ceph-check-plugin
=================

ceph check plugin (for nagios, shiken etc)

1. ensure that Ceph is installed in /usr/lib or in /usr/local/lib, and the rados library is in /usr/local/include/rados/ 
   or somewhere else.

2. compile the program with -L {Ceph library path}, -lrados, -I {rados library path} 
