# Google-Firefox-Script
This is a script written in Bash that allows the user to make a google search through a terminal and view the search results in firefox.

#Usage
$google "first word of query" "second word of query" "third word of query" ... "nth word of query"

#Installaton
1. First and foremost, make sure that firefox is installed on your OS. 
2. Make sure you have a folder to keep all of your scripts and then use "cd" to change to that directory. If you don't, open your terminal, and type in "mkdir bin" to create a directory in your home directory to store all of your scripts. Then type "cd bin" to make ~/bin your current working directory. Use export PATH=$PATH:~/bin to add ~/bin to your path. You may need to start a new terminal session before ~/bin will be recognized in your path.
3. Download the script by opening the terminal and typing in "wget https://raw.githubusercontent.com/mashbeck/Google-Firefox-Script/master/google"
4. 4. Make the script an executable with read, write, and execute permissions by typing "chmod 755 google"

