.. Remote Access Portal documentation master file, created by
   sphinx-quickstart on Mon Dec 12 21:57:03 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Install a computer as the gateway
=================================

.. toctree::
   :maxdepth: 2

A gateway computer is a server that can be accessed directly. Please make sure the gateway computers are powered on all the time.

Obtain a domain name
--------------------

The domain name is obtained from a free service from `FreeDNS`_.

The following domain name has been registered:

``murchlab-E3.mooo.com``

.. _FreeDNS: https://freedns.afraid.org/


Install noVNC
----------------------------------

Download the noVNC source code from the GitHub repository `noVNC`_.

.. _noVNC: https://github.com/novnc/noVNC

Place the folder at ``C:\remote\noVNC``

Install websockify
----------------------------------

In order to run noVNC, we need to install websockify.
I've created a packed websockify with
embeded python and some useful scripts for installing as a service.

Obtain a SSL certificate
-------------------------

The SSL certificate is obtained from a free service from `Let's Encrypt`_

.. _Let's Encrypt: https://letsencrypt.org/

Install rathole
----------------------------------

Install piping-server
----------------------------------

Install node.js server
-------------------------

Download and install: `Download | Node.js`

.. _Download | Node.js: https://nodejs.org/en/download/
