# discord-websockets-connection

This is a simple Discord gateway connection and handling events such as MESSAGE_CREATE, MESSAGE_UPDATE and MESSAGE_DELETE.

For updated and deleted messages, i would suggest making a simple caching system to compare the deleted message's id with the id in your cache that way you can accomplish it.


Note: This is using websockets library to connect to gateway, here is the full documentation https://websockets.readthedocs.io/en/stable/
