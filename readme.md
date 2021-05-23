# VS Code Apl Debug

This is a starter sample for developing VS Code debug adapters.

**Apl Debug** simulates a debug adapter for Visual Studio Code.
It supports *step*, *continue*, *breakpoints*, *exceptions*, and
*variable access* but it is not connected to any real debugger.

The sample is meant as an educational piece showing how to implement a debug
adapter for VS Code. It can be used as a starting point for developing a real adapter.

More information about how to develop a new debug adapter can be found
[here](https://code.visualstudio.com/docs/extensions/example-debuggers).

## Using Apl Debug

* Install the **Apl Debug** extension in VS Code.
* Create a new 'program' file `readme.md` and enter several lines of arbitrary text.
* Switch to the debug viewlet and press the gear dropdown.
* Select the debug environment "Apl Debug".
* Press the green 'play' button to start debugging.

You can now 'step through' the `readme.md` file, set and hit breakpoints, and run into exceptions (if the word exception appears in a line).

![Apl Debug](images/apl-debug.gif)

## Build and Run

[![build status](https://travis-ci.org/Microsoft/vscode-apl-debug.svg?branch=master)](https://travis-ci.org/Microsoft/vscode-apl-debug)
[![build status](https://ci.appveyor.com/api/projects/status/empmw5q1tk6h1fly/branch/master?svg=true)](https://ci.appveyor.com/project/weinand/vscode-apl-debug)


* Clone the project [https://github.com/Microsoft/vscode-apl-debug.git](https://github.com/Microsoft/vscode-apl-debug.git)
* Open the project folder in VS Code.
* Press `F5` to build and launch Apl Debug in another VS Code window. In that window:
  * Open a new workspace, create a new 'program' file `readme.md` and enter several lines of arbitrary text.
  * Switch to the debug viewlet and press the gear dropdown.
  * Select the debug environment "Apl Debug".
  * Press `F5` to start debugging.
