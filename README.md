SHS Geronimo
============

[![GPLv3](https://img.shields.io/badge/license-GPLv3-blue.png)](https://github.com/shs-geronimo/shs-geronimo/blob/master/LICENSE)
![GitHub build](https://img.shields.io/github/workflow/status/shs-geronimo/shs-geronimo.github.io/Build%20site%20and%20check%20output)


This is the website for the
[SHS Geronimo](https://www.shs-geronimo.org).


Building the site
-----------------

Whenever changes are made to the source branch GitHub will automatically
build the website and put it in the master branch.


Installing cactus
-----------------

This site uses [Cactus](https://github.com/eudicots/Cactus) to build.

Cactus is a Python program, so Python 2.7 is required.
Also pip is used to install cactus.
Other packages that are required by cactus are automatically installed.
So open a Terminal and run:

    pip install cactus

If all goes well cactus can now be used.

To start a local webserver navigate to the repository in the Terminal
and run:

    cactus serve

You can then point your browser to http://127.0.0.1:8000 to view the
local version. If you make any changes to the code this should be
reflected almost immediently in the local website.
