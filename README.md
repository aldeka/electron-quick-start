# electron-quick-start

Sample app demonstrating undocumented behavior in Electron's `shell.showItem()` method, at least on OSX. (Haven't tested on Windows or Linux.)

To see what I mean:
* Clone repo, follow setup instructions
* In `index.html`, edit paths called by the buttons for wherever you put this repo on your system.
* Run application and try clicking each of the buttons.

You should see that the fully designated path (`/users/<username>/`) works (it opens the file), but the absolute path using `~` does not do anything (nor does it return an error message). The totally relative path (with `.`) also works.

**Clone and run for a quick way to see an Electron in action.**

This is based on a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](http://electron.atom.io/#get-started) app for API code examples to help you get started.**

#### License [CC0 (Public Domain)](LICENSE.md)
