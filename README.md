# CS361-MicroService-A

## Requesting Data
Once the socket is created and connected to the correct port, send the string of the user inputed "\n"
term using the method send_string(), where term is the term the user would like to define."\n"
"\t"socket.send_string(term)

## Receiving Data
The response will be sent back in a string format. Use the recv_string() to correctly store the data."\n"
      "\t"definition = socket.recv_string()
From there, the definition can be printed out by simply referencing the variable the data is stored in."\n"
      "\t"print("hfdjdfh %s", definition)

## End the Process
To end the process, send the message exit. This does not send any message back to the client. This can be"\n"
done at the end of the main program to ensure use until the microservice is no longer needed."\n"
      "\t"socket.send_string("quit")

## UML Sequence Diagram
Will be added later.
