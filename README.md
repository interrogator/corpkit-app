### *corpkit* app

This is a submodule of [*corpkit*](https://www.github.com/interrogator/corpkit), designed to store the GUI version(s) of the tool for download and auto-update, but **not for forking and cloning**. Documentation for the GUI is [here](http://interrogator.github.io/corpkit/).

This repository holds:

1. The up-to-date version of the *corpkit* GUI app, inside a `.tar.gz` file
2. A human-readable change log.
3. A Unix executable for the app
4. A copy of the [`gui.py`](https://github.com/interrogator/corpkit/blob/master/corpkit/gui.py), with a versioned name.

The executable and .py files exist for the sake of *corpkit*'s auto-update feature. They, like everything else in this module, are automatically generated via some build scripts. Thus, there is no real reason to fork or clone this submodule. Instead, just `Download Zip`, or better yet, just the most recent `tar.gz` file.

If you want to fork *corpkit*, fork the [main repo](https://www.github.com/interrogator/corpkit). If you want to edit the GUI code, edit [this version](https://github.com/interrogator/corpkit/blob/master/corpkit/gui.py).

