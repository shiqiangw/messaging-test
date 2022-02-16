# messaging-test

Sends a vector of a given size from client to server, then the server replies the same vector back to the client. The round trip time is measured at the client.

Example:

On server, run
```
python3 server.py -ip SERVER_IP_ADDRESS -port 56567
```

On client, run
```
python3 client.py -ip SERVER_IP_ADDRESS -port 56567 -size 100 -sim 5
```

Replace SERVER_IP_ADDRESS with the server's IP address. The port can be arbitrary. The size corresponds to the number of floating point numbers transmitted as payload, which is configurable.
