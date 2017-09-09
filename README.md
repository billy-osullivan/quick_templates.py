Quick Templates

Purpose
This application copies text from one of the text files to the
clipboard, which is useful for writing repetitive emails, etc.

Usage
In order to use, save the data which you want to copy regularly 
in one of the text files in the same directory as the script. 
Then when the script is running click on one of the buttons which
are numbered corresponding to each text file. This will put what
ever is saved in the text file to the clipboard, allowing you to
quickly paste your templates to where ever you wish.

Setting Up
In the same directory as the script, create 5 textfiles to store
your templates. Name these textfiles doc1.txt, doc2.txt, doc3.txt
doc4.txt and finally doc5.txt. Put the data you wish to copy into
these files and save them.

Requirements
This script is cross platform compatible, but does require the
pyperclip library to be installed. Get it with pip - 
	sudo pip install pyperclip

Tips
1. Set this script to run automatically on startup. On Mac OS 
follow the steps on stack overflow at the following link to 
accomplish this - 
https://stackoverflow.com/questions/29338066/mac-osx-execute-a-python-script-at-startup
