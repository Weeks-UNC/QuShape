QuShape Installation
================================================================================
Executable files will be made available in the near future. At present, users
need to download and install the Python software to be able to run QuShape.

Instructions for Windows
--------------------------------------------------------------------------------
1. Download PythonXY from www.pythonxy.com and install as instructed.
2. Download the QuShape software package from this website to a chosen folder on
your computer.

To run QuShape, open the IDLE program by going to Start  Programs à Pythonxy à
IDLE. This will open the Python Shell.

In the Python Shell from the File menu use the Open option to go to the (unzipped) folder
containing the QuShape software and open the mainWindow.py script.

Start the graphic user interface (GUI) by either clicking F5 key on the keyboard or clicking
the Run Module option in the Run menu in the mainWindow.py screen.

Follow instructions in the QuShape Tutorial to operate the GUI.

Instructions for Mac OS X
--------------------------------------------------------------------------------
First, make sure you have X11 installed. If not, it can be downloaded from
apple.com/support/.

1. Download Enthought Python Distribution for Mac Os X from enthought.com and
install as instructed.
2. Download Qt4 from qt.nokia.com/downloads/mac-os-cpp and install as instructed.
Note: for 10.6 or higher, make sure to download the “cocoa” package.
3. Install SIP: from riverbankcomputing.co.uk/software/sip/download get the current
version of SIP and install in the terminal. Read the readme text for details.
  * For OS X 10.6 or higher, enter this code:

```
python configure.py --arch=i386
make
sudo make install
```

  * Otherwise, enter the following code:

```
cd sip-4.10
python configure.py
make
sudo make install
cd ..
```

4. Install PyQT from riverbankcomputing.co.uk/software/pyqt/download get the current
version of PyQt (Mac OS Source). Read the readme text for details.
  * For OS X 10.6 or higher, enter this code:

```
python configure.py --use-arch=i386
make
sudo make install
```

  * Otherwise, enter the following code:

```
cd PyQt-mac-gpl-4.7
python configure.py (you will have to accept licenses by typing 'yes')
make
make install
cd ..
```

To run QuShape, open the IDLE program in (Application/Enthought/EPDv7.0.0/IDLE).

From the File menu use Open to run MainWindow script.

Under the /src/ folder, open mainwindow.py.

Note: if “make:command not found” error message appears, you need to install X11. It can
be downloaded from apple.com/support/.
