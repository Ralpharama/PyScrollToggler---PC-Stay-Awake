# PyScrollToggler - PC Stay Awake

By Ralph Capper https://github.com/Ralpharama
License: Free

## Purpose

Toggles the scroll lock on and off every 200 seconds on a Microsoft Windows machine. 
This will stop many programs that time out due to inactivity from doing so for example, Windows screensaver, Microsoft Teams, etc. Thanks to Faisal Khan for the base code on StackOverflow.
Just start the program and leave it running minimized. 
Tested working with Teams in Dec 2022.

This uses virtually zero CPU as it just sleeps between toggles, and takes up about 6MB of memory when running.

## Running the program

You can run the .py file directly if you have python installed:

```
C:\> cd c:\path-to-the-file
C:\path-to-the-file> py PyScrollToggler.py
```

If you can't open a command prompt, try Right-Click Start/Run, then enter:

```
py c:\path-to-the-file\PyScrollToggler.py
```

Or download and run the exe in the dist folder (which was made with pyinstaller).
