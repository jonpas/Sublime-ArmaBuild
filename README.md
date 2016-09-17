# Arma Build

<a href="https://packagecontrol.io/packages/ArmaBuild">
    <img src="https://packagecontrol.herokuapp.com/downloads/ArmaBuild.svg">
</a>

Arma build system for Sublime Text 2/3 adds a custom build system for building development packages of ACE3-like mods using `build.py`.

### Installation

- **Automated:** [ArmaBuild](https://sublime.wbond.net/packages/ArmaBuild) using [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
- **Manual:** Clone this repository into your `Sublime Text x/Packages`

### Prerequisites

- [Python 3](https://www.python.org/)
- Current open folder a project with `tools\build.py`

### Usage

- Under `Tools -> Build System` select `Arma` (works with any focused file) or `Automatic` (only works when a `*.sqf` file is currently in focus).
- Initiate the build (`Tools -> Build` or applicable keybind).

### Note

This build system will be updated with whatever the current ACE3 uses as a build system. Change to another system will mean a major increase in the version.
