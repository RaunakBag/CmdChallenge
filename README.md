# CmdChallenge
Q1 - Your first challenge is to print "hello world" on the terminal in a single command.
A - echo hello world

Q2 - Print the current directory.
A - pwd

Q3 - List names of all the files in the current directory, one file per line.
A - ls

Q4 - There is a file named access.log in the current directory. Print the contents. 
A - cat access.log

Q5 - Print the last 5 lines of "access.log"
A - tail -5 access.log

Q6 - Create an empty file named take-the-command-challenge in the current working directory. 
A - touch take-the-command-challenge

Q7 - Create a directory named tmp/files in the current working directory 
A - mkdir tmp && cd tmp && mkdir files && cd files

Q8 - Copy the file named take-the-command-challenge to the directory tmp/files. A - cp -r take-the-command-challenge tmp/files/

Q9 - Move the file named take-the-command-challenge to the directory tmp/files
A - mv take-the-command-challenge cd tmp/files

Q10 - A symbolic link is a type of file that is a reference to another file. Create a symbolic link named take-the-command-challenge that points to the file tmp/files/take-the-command-challenge.
A - ln -s -v tmp/files/take-the-command-challenge take-the-command-challenge 