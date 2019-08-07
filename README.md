# python_data_matcher
A script to match items in the first columns of two comma-separated-spread-sheets
This project was started to help geneticists to join informations from two long lists of markers. It can be used for other lists.

Basic instructions:

Unzip the directory on your computer and navigate into the unpacked directory. 
You will find the script the script "python_data_matcher.py" in there. 
The script works only on "csv" files. Save spread sheets from Excel as "csv".

Install Python 3.5 or higher.

On Windows click on "python_data_matcher.py" icon.

A window will pop up and ask you for the name of your first file.
You best put the file in the same directory as the python script - less typing. 

You have to type or copy the name and hit "return".
Tip: Python is case sensitive and you need to add ".csv" when you type in the file name.

The script will then ask you for the name of the second file.
You have to type or copy the name of the second file and hit "return".

The script then reports back if it finds items in the second file not present in the first.
If you want items added to your list, you answer that question with:
 "y" + "return".
If you don't want items added just hit "return".

"python_data_matcher.py" will then produce the joint file, using the first file name and adds 'extended' to it.

All done, you can hit "return" to leave the script.
