# PQMinion
Rewrite of Minion software with PyQT4

## Installation
1. set up a virtual environment
1. install python dev tools
   ```shell
   sudo apt-get install python-dev
   ```
2. install pyqt4
   ```shell
   sudo apt-get install PyQt-dev-tools
   ```
3. make symlink to virtual environment:
  1. link PyQt4
     ```shell
     ln -s /usr/lib/python2.7/dist-packages/PyQt4/ PathToVirtualEnv/lib/python2.7/site-packages/
     ```
  2. link sip.so
     ```shell
     ln -s /usr/lib/python2.7/dist-packages/sip.so PathToVirtualEnv/lib.python2.7/site-packages/
     ```

