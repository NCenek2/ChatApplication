This chat application has two folder: one for the server and one for the client.
The client folder houses the .exe for the WPF client application.
The server folder houses the .exe for the Console App through which the server will run.

The ServerInfo.txt file must have two pieces of information, including the the IP Address of the server,
which I placed by default to target the users local host (127.0.0.1). 
Additionally, the file must have the port that the server will listen on. I chose an arbitary port.

Missing either of these items will cause the application to fail at run time.

Example:
127.0.0.1
7891