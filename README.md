# fetch-my-scripts
Simple plugin in Godot to fetch scripts and classes from Github repos.
Adds a single button to the top right. Click it to display possible scripts to fetch.

Change the setup.cfg to point to a public repo. Currently set up to fetch my personal custom classes, feel free to use them!

## How to set up your personal Github Repository.
The file structure is fairly easy, you can see the example at https://github.com/ItsBen321/godot-custom-classes
- Main directory:
	- Can hold a README.md that will print to the terminal when initially fetched.
	- Holds folders, the names are what shop up when fetched.
- Folders:
	- In each folder you can also put a README.md that will print to the terminal when fetched.
	- All the files that should get fetched when the folder is selected! (takes the raw strings and file names)
The folder and the text files will be placed as a sub-folder of this plugin. Enjoy!
