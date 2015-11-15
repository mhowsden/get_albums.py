**get_albums.py**

*A utility to quickly pull down a user's facebook albums.*

This utility creates two directories:
 * data - folder where Graph API JSON data is cached/stored
 * albums - folder where album content is stored

**PREREQUISITES**

This requires the python requests library.

    pip install requests

The other Python modules in use are built-ins.  This has only been
tested under Ubuntu 14.10 with Python 2.7.6 and requests 2.5.1.

It also requires an access token which can be gotten from the
[Graph API Explorer](https://developers.facebook.com/tools/explorer)
and placed in the same directory as this script in a file named
"access_token".

**USAGE**

    git clone https://github.com/mhowsden/get_albums.py.git fb_albums
    cd fb_albums
    echo "LONGACCESSTOKENFROMAPIEXPLORERGOESHERE" > access_token
    ./get_albums.py
