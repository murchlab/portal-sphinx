.. Remote Access Portal documentation master file, created by
   sphinx-quickstart on Mon Dec 12 21:57:03 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Install a new lab computer for remote accessing
===============================================

.. toctree::
   :maxdepth: 2

Install VNC server
----------------------------------

Two open source projects are available: TightVNC and UltraVNC. We can choose either one of them, in principle.

I feel TightVNC works slightly better on Win10, which can be downloaded at `Download | TightVNC`_.

UltraVNC works slightly better on Win7, which can be downloaded at `Download | UltraVNC`_.

.. _Download | TightVNC: https://www.tightvnc.com/download.php
.. _Download | UltraVNC: https://uvnc.com/downloads/ultravnc.html

TightVNC
~~~~~~~~

I recommend setting these parameters:

.. code-block::

   Screen polling cycle: 5000 ms
   Video recognition interval: 30 ms

And please enable the option ``Allow loopback connections``.

UltraVNC
~~~~~~~~

I recommend to make sure these options are enabled on UltraVNC:

.. code-block::

   Poll Full Screen (Ultra Fast)
   Poll Foreground Window
   Poll Window Under Cursor

   Multi viewer connections
     - Keep existing connections

These options to be disabled:

.. code-block::

   Low Accuracy (Turbo Speed)

Please make sure the password is set correctly.

Ports
~~~~~~~~

Please set the correct ports and update the OneNote page `VNC rathole token`_

.. _VNC rathole token: https://onedrive.live.com/view.aspx?resid=6D807F6801FF0C41%21716&id=documents&wd=target%28Passwords.one%7CA9CF002A-74B5-194A-8BEE-6DE6861FD3A9%2FVNC%20rathole%20token%7CC3B026F9-0A3D-BB48-86B2-D3778B84A754%2F%29

Install rathole service
----------------------------------
