﻿Negar
======

Negar trying to be a spell corrector for Persian language. I'm working on new algorithm that I found from here:

https://github.com/aziz/virastar/blob/master/lib/virastar.rb

Thank you Aziz.

It doesn't work completely now.

Screenshot & Features
=====================
You can run gui version like this:

    negar --gui

![NegarsScreenshot](https://github.com/shahinism/python-negar/raw/master/docs/screenshot/window1.png)

How to install
==============

First of all depend on you Distribution/Operation System install Pythons ‘setuptools’. 
In some Linux distribution its name is something like ‘pysetuptools’. 

After that execute commands:

    $ git clone https://github.com/shahinism/Negar.git
    $ cd Negar
    $ sudo python setup.py install

For now there is no requirements except Pythons standard library.

How to use
==========

Full list of args with description:
::

    --fix-dashes                 Disable fix dashes feature
    --fix-three-dots             Disable fix three dots feature
    --fix-english-quotes         Disable fix english quotes feature
    --fix-hamzeh                 Disable fix hamzeh feature
    --hamzeh-with-yeh            Use 'Hamzeh' instead of 'yeh' for fix hamzeh feature
    --fix-spacing-bq             Disable fix spacing braces and qoutes feature
    --fix-arabic-num             Disable fix arabic num feature
    --fix-english-num            Disable fix english num feature
    --fix-non-persian-chars      Disable fix misc non persian chars feature
    --fix-p-spacing              Disable fix perfix spacing feature
    --fix-p-separate             Disable fix perfix separating feature
    --fix-s-spacing              Disable fix suffix spacing feature
    --fix-s-separate             Disable fix suffix separating feature
    --aggresive                  Disable aggresive feature
    --cleanup-kashidas           Disable cleanup kashidas feature
    --cleanup-ex-marks           Disable cleanup extra marks feature
    --cleanup-spacing            Disable cleanup spacing feature

