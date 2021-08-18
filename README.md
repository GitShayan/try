# try
A useful bash script for executing Linux commands with a specified number and time interval

# Default Values:
Wait interval seconds between executing command = 5  
Maximum number of retries to successfully execute the command = 12  

# Switches:  
-i: interval  
Wait interval seconds between executing command.  
-n: number  
Maximum number of retries to successfully execute the command.  
  
# Exit Status:  
0: command was successful without any errors.  
1: command was failure  
  
# Example Usage:  
./try -i 3 -n 5 ssh 192.168.100.100  
  
  
[@dwsclass](https://github.com/dwsclass) dws-dev-006-bash

