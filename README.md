# osx-reset-clipboard
Reset Clipboard - OSX App for quickly resetting your system clipboard to fix wonky copy/paste.

Runs:
```shell
launchctl stop com.apple.pboard
launchctl start com.apple.pboard
killall Finder
```

**Instructions:**

* Download, unzip, and move to location of choice (I prefer "Applications")
* Option 1: Drag into the dock for easy access, double-click to execute
* Option 2: Execute via shortcut using `Automator`

![osx-reset-clipboard](https://cloud.githubusercontent.com/assets/12876929/26416291/fcc8ab72-407a-11e7-80d3-1876c39315b8.png)
