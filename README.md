# Hidden-garden

## Goal
This tool aims at becoming a very simple and secure way to send a secret message with attachements if desired through email, without the help of the third-party certification authority (hence it is free !). "Secure" means that a man-in-the-middle intercepting emails between you and the person you are exchanging secret messages with should not be able to decypher the content of the message or any of the attachments. Of course, as every "secure" method of communication, this is not bullet proof but it requires a lot of efforts to crack the method used. This is like securing your house: one cannot forbid burglars to come in but you can slow them down enough to discourage most of them.
Another advantage of the tool is that no software needs to be installed to run it, apart from any standard Internet browser if allowed to execute code on a web page hosted on your computer.

## Notes on licenses on some parts of which this tool is composed
* crypto-js is released under a [New BSD license](http://opensource.org/licenses/BSD-3-Clause).
* functions library [JSBN](www-cs-students.stanford.edu/~tjw/jsbn/) is released under a [BSD license](http://www-cs-students.stanford.edu/~tjw/jsbn/LICENSE)
