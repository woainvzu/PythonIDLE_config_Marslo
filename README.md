PythonIDLE_config_Marslo
========================

The configuration of Python IDLE
# IDLE:
## Usage:

### Linux:
- Copy the .idlerc folder to `$HOME` folder
- Re-start IDLE

### Windows:
- Copy the .idlerc folder to `%HOMEPATH%`
- Re-start IDLE

## Specific Shortcuts:
- Ctrl+p: Previous history
- Ctrl+n: Next history
- Alt+p:  Print page
- Alt+n:  New page

## IDLE Screenshots:
![IDLE1](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/IDLE1.png?raw=true)
![IDLE2](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/Screenshot2.png?raw=true)

# IPython
## Installation

### Linux(Ubuntu)
- Mandatory
    - $ sudo apt-get install ipython
        - Installed packages:
           - python-configobj
           - python-decorator
           - python-simplegeneric
- Optional
    - $ sudo apt-get install ipython-qfconsole  [Recommend]
        - Installed packages:
            - libpgm-5.1.0
            - libzmq1
            - python-pygments
            - python-zmq
    - $ sudo apt-get install ipython-doc
    - $ sudo apt-get install notebook
    - $ sudo apt-get install python-matplotlib
    - $ sudo apt-get install python-numpy

### Windows
- Mandatory
    - IPython:      pip install ipython
    - PyReadline:   pip install pyreadline 
- Optional
    - Pygments:     pip instal Pygments
    - PyQt:         http://sourceforge.net/projects/pyqt/ 
    - PySide        easy_install pyside
## Configuration:
    - Copy the style file to /usr/lib/python2.7/dist-packages/pygments/styles
    - Copy .config folder to $HOME/.config
## IPython screenshots
- `$ ipython`
![IPython](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/ipython.png?raw=true)
- `$ ipython qtconsole --IPythonWidget.font_size=12 --IPythonWidget.font_family=Monaco --color=linux --style=marslo`
![IPython QTConsole](https://github.com/woainvzu/PythonIDLE_config_Marslo/blob/master/Screenshots/qfconsole.png?raw=true)
