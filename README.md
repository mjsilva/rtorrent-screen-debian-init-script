# Init script for rtorrent + screen for Debian

A simple init.d script for Debian based systems to start rtorrent in the background using screen. The script is based on [Greg Methvin's great init.d script](http://methvin.net/scripts/rtorrent). The difference here is that this init script is specifically designed for the usage of rtorrent together with rutorrent. It will ensure that the socket that is used by rtorrent for the XMLRPC connection gets deleted before attempting to start rtorrent or when stopping rtorrent.

Feel free to contact me and help extending the script to make it more awesome!
