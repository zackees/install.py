# install.py

Super easy script that can make a virtual environment then drop in an active.sh at your project root.

[![Windows_Tests](https://github.com/zackees/install.py/actions/workflows/push_win.yml/badge.svg)](https://github.com/zackees/install.py/actions/workflows/push_win.yml)

[![MacOS_Tests](https://github.com/zackees/install.py/actions/workflows/push_macos.yml/badge.svg)](https://github.com/zackees/install.py/actions/workflows/push_macos.yml)

[![Ubuntu_Tests](https://github.com/zackees/install.py/actions/workflows/push_ubuntu.yml/badge.svg)](https://github.com/zackees/install.py/actions/workflows/push_ubuntu.yml)


# Quick install


  * `cd <YOUR DIRECTORY>`
  * Download and install in one line:
    * `curl -X GET https://raw.githubusercontent.com/zackees/make_venv/main/install.py | python`
  * To enter the environment run:
    * `source activate.sh`


# Notes
    This script is tested to work using python2 and python3 from a fresh install. The only side effect
    of running this script is that virtualenv will be globally installed if it isn't already.
