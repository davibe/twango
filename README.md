Twango
======

A script I use to launch Django web apps from twisted using Django's wsgi
handler. The server is bound to port 8010 (no reason, feel free to change it).

Example
-------

    cd [django application directory]
    twisted -ny [path to twango.py]
