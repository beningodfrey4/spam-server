# spam-server
A simple text-based spam-server based on exclusion lists.

## client.c 

takes 2 arguements

* hostname/IP of the server
* Path to text file with extension

## spam.txt

Can contain any number of words/phrases that must be filtered/excluded.

## server.c

Processes requests sent by the client.
