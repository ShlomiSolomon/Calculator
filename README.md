# Calculator
Linux\C real-time TCP calculator in socket programming using client-srever 

**How to run**



The Server side :

Open terminal for the server and type line :

gcc server.c -o server 



The client side :

Open another terminal for the client and type :

gcc client.c -o client


Now back to previos terminal (the server one) and type :

./server 9974                                          // you can type another port.


Now go again to the client terminal and type :

./client 127.0.0.1 9974                                // type the port you enter before



Good work , now enter the numbers and choose from the options by the number as described , you can see your numbers and the answer in the sever terminal.
