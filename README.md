Nodelic
=============
Usage (Not finished, may change)
-------------
yes, no <code>listen</code> yet

    api = require('nodelic').api
    # Login
    key = api.login('Test', 'mypassword', 123)._ # You've got the key
    # Say something
    api.msg key, 123, 'ah ah'
    # Kick someone
    api.kick key, 123, 'William Fox', 'jk'
    # Change color
    api.color key, 123, 'ff6600'
    # Reset it
    api.color key, 123, null
    # Logout
    api.logout key, 123
    
    
