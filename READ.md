astmanproxy  [![Build Status](https://travis-ci.org/augcampos/astmanproxy.svg?branch=master)](https://travis-ci.org/augcampos/astmanproxy)
============

The need for a proxy to Asterisk's manager interface has been 
clear; almost all GUIs and other interfaces to asterisk implement a 
proxy of some kind.  Why?  A proxy offers:

 - A single persistent connection to asterisk
 - A more secure (non-root) TCP interface
 - Ability to offer filtered input/output
 - Less connections and networking load for asterisk

It can serve as the basis for an extensible application framework
for communication with multiple Asterisk servers.
