# cmdprac

## Learn by repetition
cmdprac is a bash script to help you learn a command by repetition.

The questions and answers are stored in the arrays `ques` and `answ`. 
You can easily change the questions and answers to a command you would 
like to drill. First copy the file and give it a new name like 
apt-cmdprac `cp cmdprac apt-cmdprac`. Now change the questions and 
answers and save.

**When changing questions and answers make sure the index of the arrays
line up.** 

The script also has the global var `Cm_nm` which is the name of the
command you are learning. Change this to the name of the command you
are learning. Changing this is not required for the script to work but
the intro screen and exit screen will have the wrong command name.

---
### Installation
* `chmod +x cmdprac` - Make the script executable
* `./cmdprac` - Run the script


Enjoy!
