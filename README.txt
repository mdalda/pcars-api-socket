## pCARS API Socket
Is a tiny program to connect through sockets to the Project CARS API Memory.
Actually is in a Draft stage but supports multiple TCP connections and the responses are formatted in JSON (XML soon).


## How to use
Run it and will be a socket listening in the port 23614.
Connect through this port to obtain information about your car.

## Testing with putty
Launch this program, launch Project CARS and get ready on track.
Launch Putty and set:
RAW mode
Server: localhost
Port: 23614

You will receive a welcome message.
Write "json" (without quotes) and push Enter.

