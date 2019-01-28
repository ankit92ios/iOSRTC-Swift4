# iOSRTC-Swift4
iOSRTC-master(https://github.com/digixtechnology/iOSRTC) copy for Swift 4.1 (Xcode: 9.3+) compiled.

Code is compiling and running but not working.

To make it work.. 

Change the code in
SocketIOManagerCall.m

Line 33.

according to 

https://nuclearace.github.io/Socket.IO-Client-Swift/12to13.html


Old Line 
// self.socket = [[SocketIOClient alloc] initWithSocketURL:url config:options];

socket.io-client-swift version 13 has big changes.

Reference : 
https://github.com/digixtechnology/iOSRTC

https://github.com/socketio/socket.io-client-swift
