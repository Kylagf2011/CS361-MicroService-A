# CS361-MicroService-A

## Requesting Data
Once the socket is created and connected to the correct port, send the string of the user inputed <br>
term using the method send_string(), where term is the term the user would like to define.<br>
      socket.send_string(term)<br>

## Receiving Data
The response will be sent back in a string format. Use the recv_string() to correctly store the data.<br>
      definition = socket.recv_string()<br>
From there, the definition can be printed out by simply referencing the variable the data is stored in.<br>
      print("hfdjdfh %s", definition)<br>

## End the Process
To end the process, send the message exit. This does not send any message back to the client. This can be<br>
done at the end of the main program to ensure use until the microservice is no longer needed.<br>
      socket.send_string("quit")<br>

## UML Sequence Diagram
Will be added later.
