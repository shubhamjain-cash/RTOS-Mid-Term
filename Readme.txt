This has been upgraded from chat program, so it supports voice as well as chat features.

How to make call to another online user:

1. Compile client.c using "gcc client.c -o client -lpthread -lpulse-simple -lpulse" and run using "./client [ip of server] [port of server]".

2. When connected to server, client can set its user name.

3. Enter "-call" command to initiate call will other online user. This command will display list of online users and client can select
   another user to call.

4. If callee accepts the call by pressing "-yes", real time voice chat will be initialised for these users.

5. Press "ctrl + c" to end call.
