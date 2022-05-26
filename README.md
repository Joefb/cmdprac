# cmdprac

## Learn by repetition
cmdprac is a bash script to help you learn a command by repetition.

The questions and answers are stored in arrays in the learning-arrs
directory. I call them learning arrays. You can eaisly create more
learning arrays by using the template file in learning-arrs dir. Just
copy the template and add the questions and answers.

The learning arrays also have a global var `Cm_nm` which is the name
of the command you are learning. Change this to the name of the command
you are learning. Changing this is not required for the script to work
but the intro screen and exit screen will have the wrong command name.

---
### Requirements
`toilet` command</br>
Not really required but the intro and exit screen will not
display properly (I just discovered this command and had to use it!
Best command name ever!)

### Installation
* `chmod +x cmdprac` - Make the script executable

### Usage
`cmdprac learningArrName` Run the learning array of your choice
`cmdprac --ls` List avaliable learning arrays
`cmdprac --help` Display help

### Create a new learning array
1. Go into the `learning-arr` directory
2. `cp template newName` to make a new learning array
3. Use your favorite editor to edit the new learning array
4. Change the `Cm-nm` var to the command name.
5. Add in questions and answers.

**When creating or changing questions and answers make sure the index
of the arrays line up!** For example if you add a question at index 0 in
the `ques` array then the answer must be at index 0 in the `answ` array.

Enjoy!
