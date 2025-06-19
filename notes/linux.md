Welcome to Linux Notes:


. "cd", "<directoryname> will place you inside of said directory
. "Cd .." Will take you to the previous directory
. "Pwd" will tell you where you are in the file system at that current moment
. "Ls" will list the contents of the directory you are in
. "Ls -a" will list all of the contents of your directory including all of the hidden stuff
. "Touch" is to create a new file
. "Open" is to open a file
. "cat" will display the text of the file inside of the terminal
. "Mv", "<filename>", "<directoryname>", will move a file to said directory
. "nmap" will scan your network for ip addresses
. "Rm", <filename> will instantly remove that file
. "Rmdir", "<directoryname>", will remove and empty directory
. "rmdir -rf" "<directoryname>", will forcefully remove a directory and all of its contents
. "/" is the root of the system 
. "cd /" will take you to the root of the system if you type "cd" by itself it will take you back to the home of the system.
. "man", "<nameofcommand>", will give you every tool associated with that command
. "rm -rf /", THIS IS THE KILL SWITCH AND WILL ERASE EVERYTHING OFF OF THE COMPUTER
. "W", will tell you who is on your terminal, and "who" will do the same thing but with less information 
. "Top" will give you a list of everything running on your device and tell you what is taking up the most space in your system.
. "netstat" will give you insight to every connection your computer is making. Whether that be to the internet or different networks, or if your computer has an open port which would be like you hosting a server that other people can connect to.
. "Sudo netstat" will run a more detailed report of what your computer is connecting to
. "htop" is the better version of "top" and you can also use the sudo command prefix
. "Cp" will copy a file. You can write the file then the destination of where you would like to copy it to 
. "nano" will allow you to edit a file in the terminal just like this one!
. "echo "some text" > somefile": this will create a file called somefile in this case and store the information you wrote after echo. If you put ">>" this will add information to whatever
file you list at the end.
. "<some sort of command or error> > somefile": you can also print the output of a command or error into a made up file or >> to add this to whatever was already in the file. If you want to
print and error message into your file, you must do "2>" instead of the traditional "1>" aka ">".
      - ">" is for output redirection and "<" is for input redirection.
      - so if you wanted to send an email you could do: mail "this is my subject line" < filethatholdswhatyouwanttosendinemail.
