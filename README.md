# Keylogger-Code

This code is a keylogger meant for educasional purposes only, it is only for windows based machines as it uses batch scripts for the majority of the files.

## Usage

HOW TO USE:

### Step 1: Clone the repository

```bash
git clone https://github.com/Lewis418/Keylogger-Code.git
```

In order to get this code to work, you must have the 5 main files:

1. `Python-installer.bat`
2. `keyboard-package-check.bat`
3. `K-logger_Code.pyw`
4. `K-logger-internal-code.bat`
5. `K-logger-start.bat`

once you have these files downloaded in the same directory, you only have to start the `K-logger-start.bat` file in order to start the keylogger, once the keylogger has started it will run all cmd prompts in a minimized window.

1. The first window will check to see if python is installed and if not it will install python through the command line.

2. The second window will be the package check file which checks to see if you have the keyboard module installed, if not then it will be installed.

3. The third and final prompt is the keylogger itself and it will document what keys where pressed for as long as the cmd prompt stays open, it will document the keys pressed within a .txt file named keystrokes.txt which will be in the same directory as the other files.

## Testing

For testing I used a windows 10 virtual machine to test the python install script and the keyboard module check script of which both scripts where succesful in downloading content where content was missing and not downloading anything when the program and module where already installed.

## Notes

22/04/2024 03:00 AM
This code was created by me and was created in the vision that eventually I will have made a functioning Keylogger to prove that I can actually code stuff and things.

23/04/2024 01:00 AM
I have managed to get the code to work along with adding two batch files in order for the script to run correctly.

23/04/2024 06:00 AM
I have just remembered that in order for this to work, the device would need to have python installed along with the keyboard python module, the keyboard module is easy enough to install within the batch script however the actual installation of python would most likely be too lengthy which is not good.

24/04/2024 17:30 PM
I have created a batch script that checks to see whether the keyboard module is installed or not and if not then it installs it, this file will make sure that the key logger itself will work if the individual has python installed and has python added to the command line PATH.

24/04/2024 23:15 PM
I have created a batch script to check if python is installed in the first place and if not then it will be installed quietly through the command line, the only problem is that windows defender warns you that the batch files have an unknown publisher, I guess if the attacker quickly ran the start script and allowed windows to run it then left the computer it would be fine but still id say I need to find a way to counteract that.
