# Keylogger
Simple keystroke logger for Linux

## Installation
You'll need to install python-xlib if you don't have it.

`sudo apt-get install python-xlib`

Check that you have git installed, and then run this.

`git clone https://github.com/coderganesh/keylogger`

This will clone this entire repo. Find the folder, extract it, and open it. Rename the extracted folder to `linux-logger` Then run this:

`$ cd linux-logger/`

Set where you want the log to go **before** running this step.

```
~/linux-logger$ python keylogger.py

<class 'Xlib.protocol.request.QueryExtension'>

<class 'Xlib.protocol.request.QueryExtension'>

RECORD extension version 1.13
```

The keylogger is now running! It will log your strokes to the file you specified. Stop it by hitting the grave key. Thats the one under escape on a standard keyboard.

---

You can make it run on startup:

`python /home/py-keylogger/keylogger.py`

