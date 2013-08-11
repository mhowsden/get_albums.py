**get_albums.py**

*A utility to quickly pull down a user's facebook albums.*

This utility creates two directories:
 * data - folder where Graph API JSON data is cached/stored
 * albums - folder where album content is stored

**PREREQUISITES**

This requires the python requests library.

    pip install requests

The other Python modules in use are built-ins.  This has only been 
tested under Ubuntu 12.10 with Python 2.7.3.  

It also requires an access token which can be gotten from the 
[Graph API Explorer](https://developers.facebook.com/tools/explorer) 
and placed in the same directory as this script in a file named 
"access_token".

**USAGE**

    git clone https://github.com/mhowsden/get_albums.py.git fb_albums
    cd fb_albums
    ./get_albums.py
    
    
