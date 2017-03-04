# kippo-log2db

This script was inspired by kippo2mysql by Ioannis “Ion” Koniaris
(bruteforce.gr/kippo2mysql) which I really liked, but that script 
while populating a MySQL database, was not populating the actual 
kippo schema, so I wrote this script.  This can be useful for anyone 
who started logging to files and now wishes to switch to logging 
to MySQL, but doesn't want to lose old data.  It could also be 
useful if the sensor is a lightweight VM or remote from the DB and 
you don't need real-time updaes to the DB, the logs compress very 
nicely and can be rsync-ed to the system where the DB resides.

Send any feedback to me at jclausing@isc.sans.edu or handlers@sans.edu.
 
This script is distributed under the terms of BSD-3-Clause license
