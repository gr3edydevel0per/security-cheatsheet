When we first run the bash it will run a startup script 
.bash_rc or .bash_profile  [used for changing the behaviour and appearence of the shell]

every bash script has a .sh extension or there is no extension for script file

#! is known as Shebang or HashBang
it is followed by path to the bash in which the script is written

Commands of script file are interpreted line by line

& - adding this in a command will execute the command in background with interrupting the other commands


--------------------------------------------------
       Permission System in Linux                 
--------------------------------------------------
- --- --- ---
   U   G  O 

U - User                  if first bit is '-' then it is a file 
G - Group                 else it will have 'd' which specifies directory
O - Other

   ---
   rwx    read - write - executable
   ---
0  000
1  001
2  010
3  011
4  100
5  101
6  110
7  111

Giving permission to a file  -   chown permissionBits fileName
chown 465 textFile
Here  4 6 0 :
4 - 100   User will have the permission to read
6 - 110   group will have r and w permission
0 - 000   others will have no permission


