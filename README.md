# simple_port_scanner
# it only scans the port from 1 to 1024
This is a simple port scanner written in Python. It can be used to scan a target machine for open ports. The script takes one argument, which is the hostname or IP address of the target machine. If the argument is not provided, the script will print an error message and exit.

The script works by creating a socket for each port and trying to connect to the target machine on that port. If the connection is successful, the script prints a message indicating that the port is open. Otherwise, the script prints a message indicating that the port is closed.

Syntax: python3 simpleportscanner.py <ip>

The script also handles the following exceptions:
KeyboardInterrupt: This exception is raised when the user presses Ctrl+C to interrupt the script.
socket.gaierror: This exception is raised when the target machine's hostname cannot be resolved.
socket.error: This exception is raised when the script cannot connect to the target machine.
