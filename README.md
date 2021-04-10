# Keylogger-For-Debian-Linux
This is a simple Keylogger written in Python for LINUX and is easy to use.

*****I take NO RESPONSIBILITY for the misuse of this piece of code. This code is created and shared for Educational Purposes ONLY!*****

*****Voilation of any law using this piece of code is not my concent and is not at all apreciated and I should not be held RESPONSIBLE for your ACTIONS*****

## DEPENDENCIES

Python 3

pynput Library of Python 

sys Library of Python

### Installations

#### Python3
sudo apt install software-properties-common

sudo add-apt-repository ppa:deadsnakes/ppa

sudo apt update

sudo apt install python3.8                                                   (Or any of the latest version)

#### pynput Library of Python
**There should be PIP available on your system, if not try command--> sudo apt install python3.8**

pip3 install pynput

## How to USE?

**Clone or download the code from my repository.**

Using Terminal go to the directory where you have this code.

*When in directory run the command below:-*

sh keylogger_script.sh 

The script will start working.

Close the terminal and it will log all the key strokes of your keyboard.

*To stop the program running in backgroud Press ESC key on your Keyboard, and it will stop working*

*You can check your captured keystrokes in the file logs.out, ONLY AFTER THE PROCESS OF THE PROGRAM IS KILLED*

****To check or manually kill the program****
Open your Terminal and write the following command

*ps -aux* 
and find the process id of your program, Usually running by the command **python3 keylogger.py**

after finding the process id write the following command on your terminal to kill it.

*sudo kill 'pid'*

****Check logs.out For Output****
