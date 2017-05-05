# port_scanner

AIM
To scan host in order to find open ports, and then try to send data to open port(s) in order to obtain a reply (return information about the system on the other end).

METHODOLOGY

1.Open command line (Windows)
2.Using Python 3 (version 3.6 in this case), install PyQt
3.Run portScanner.py
4.In the port scanner GUI, enter the URL for the target site for which you want to scan for open ports
5.Specify the range of ports you wish to scan
6.Click “Start”
7.Observe information about which ports are accessible in the output window
8.When scan is complete, switch to the “Attack open ports” tab
9.Select the open port through which you want to send data
10.Enter the hexadecimal byte string for the packet you want to send
11.Click “Send data”
12.Observe information returned in the output window
