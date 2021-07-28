Pada linux, saya menemukan error "Pyperclip could not find a copy/paste mechanism for your system."
Untuk mengatasinya:

    * sudo apt-get install xsel to install the xsel utility.
    * sudo apt-get install xclip to install the xclip utility.
    * pip install gtk to install the gtk Python module.
    * pip install PyQt4 to install the PyQt4 Python module.
