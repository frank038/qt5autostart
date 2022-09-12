# qt5autostart
Program to manage autostart applications.

V. 0.9

Free to use and modify.

Require: python3, pyqt5, pyxdg.

With this program, autostart applications/desktop files found in the autostart folders will be executed, unless they are marked with Hidden=true. Applications can be added, removed, modified in the user autostart folder, while the application in the system folder (usually /etc/xdg/autostart) can be only setted as hidden to not to be executed. Useful for custom DE.

How to execue:
- python3 qt5autostart.py --help (or ./qt5autostart.py --help) to get a simple help on usage;
- python3 qt5autostart.py -gui (or ./qt5autostart.py -gui) to launch the program in gui mode to manage the applications to be started automatically;
- python3 qt5autostart.py (or ./qt5autostart.py) to launch this program in console mode: in this case the programs in the autostart folders will be executed, if not disabled.

Put the mouse over an item to get its description/comment and executable. In gui mode, this program cannot start or stop any programs.

The option in the config file:
- LOG_TO_FILE : the program can log all the tasks it made, programs executed from system and use folders, programs skipped, etc.;
- DEST_LOG : where to write the log.

![My image](https://github.com/frank038/qt5autostart/blob/main/screenshot1.png)
