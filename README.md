# **NotePal**

An intuitive Text Editor with a simple Graphical User Interface for Linux, built with GTK+ Libraries. With **NotePal**, you can open multiple files at once (as tabs) and can interact with your files intuitively. **NotePal** was built using GTK 2.0. It's great for those who prefer a Grapic based text editor.

It has only the basic functions such as:
* Open
* Close
* Save
* Copy
* Paste
* Change Font

## Installation

To install **NotePal**, simply use compile the command:

```gcc -g -Wall CompileNotePal.c -o NotePal `pkg-config --cflags --libs gtk+-2.0````

Which produces an executable **NotePal** instance.


**_NOTE:_** The only dependencies for **NotePal** are the GTK Libraries.
If you encounter dependency errors, simply run:

```sudo apt-get install gtk2.0```

followed by the compile command again.

# Credits:
I would like to thank ```Glenn Schemenauer``` for the helpful documentation provided by him.
