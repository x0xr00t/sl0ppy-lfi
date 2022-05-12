# sl0ppy-lfi
A small lfi framework writen in bash.   

# includes 
* lfi validator
* lfi linux files scanner
* lfi windows files scanner
* lfi windows-linux all files scanner
* lfi filther encode 

# Changes 
* v1.3-beta rolled-out
* Added lfi validator to the framework


# install
* make all files executable with this command
* chmod +x install && ./install

# config 
## {!} change the static set user and hash out the read -p "Please Enter Systems Username: " on all 5 blocks in sl0ppy-lfi-fw{!}
* Or use the pre-default implemented(read -p), and submit system user when asked for it.


# Usage sl0ppy-lfi-fw (sl0ppy-lfi-framework)

# Usage 
* `./sl0ppy-lfi-fw` 
* Choice 1 for lfi validator
* Choice 2 for windows based lfi file checks
* Choise 3 for linux based lfi file checks
* Cboise 4 for linux & windows lfi file checks
* choise 5 for PHP://filther encoding.. (fixed)
* Enter the lfi url when it ask for it like this.. http://server.vulnerable.com/index.php?page=` 
* Else as http://server.vulnerable.com/index.php?page=../../../../../../../../../../
* Or any other lfi param or pages... 

# Examples sl0ppy-lfi-fw

# usage lfi-validator 
* `./sl0ppy-lfi-fw`
* * option 1
* Enter Username when asked for it
* enter url when it ask for it like this `http://server.vulnerable.com`
* Enter the file param when asked for it. Like this  `index.php?page=`
* or any other page, or lfi param

# usage Windows-lfi 
* `./sl0ppy-lfi-fw`
* * option 2
* Enter Username when asked for it
* enter url when it ask for it like this `http://server.vulnerable.com/index.php?page=`
* or any other page, or lfi param

# usage linux-lfi 
* `./sl0ppy-lfi-fw`
* * option 3
* Enter Username when asked for it
* enter url when it ask for it like this `http://server.vulnerable.com/index.php?page=`
* or any other page, or lfi param

# usage Windows-linux-lfi 
* `./sl0ppy-lfi-fw`
* * option 4
* Enter Username when asked for it
* enter url when it ask for it like this `http://server.vulnerable.com/index.php?page=`
* or any other page, or lfi param

# Usage php://Filther-encoding` 
* `./sl0ppy-lfi-fw`
* Enter Username when asked for it
* * option 5 
* enter url when it ask for it like this `http://server.vulnerable.com/index.php > sl0ppy-enc.txt || cat /home/$user/sl0ppy-lfi/sl0ppy-enc.txt` 



# Legal Disclaimer:

    I am not responsible for U using it on non authorized systems, make sure u use it on systems u own or are authorized on.

    x0xr00t

