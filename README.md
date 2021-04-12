# Bash Keylogger

Bash script to log all keystrokes in a current terminal session. 

Save `bkl.sh` to desired directory.

Modify `bkl.sh` argument's mode with `chmod a+x`

Usage of this would be:

`./bkl` Once initiated the script will create a `.txt` file in the local directory of the script, to exit and save the current session while running `./bkl` type `exit` file will be saved with date and time of script.

The resulting output file will be called `%m_%d_%Y.%H_%M_%S.txt` and be saved in the current directory.
