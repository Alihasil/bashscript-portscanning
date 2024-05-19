How it works:

The script checks if an IP address is provided as an argument. If not, it prints the usage and exits.
It sets the start_port and end_port variables to define the range of ports to scan (in this case, 1 to 1024).
The script then enters a loop that iterates over the port range.
For each port, it uses the timeout command to attempt to establish a TCP connection to the target IP address and port.
If the connection is successful (indicated by the exit status of 0), it means the port is open, and a message is printed.
After scanning all ports, a final message is displayed to indicate the completion of the scan.
