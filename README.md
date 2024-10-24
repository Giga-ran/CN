# CN
1) Multiple IP Addresses on a Single Network Interface (Linux/Windows)
   On Linux (using ip or ifconfig command)
Using the ip command:

       sudo ip addr add 192.168.1.10/24 dev eth0
       sudo ip addr add 192.168.1.11/24 dev eth0

Using the ifconfig command

       sudo ifconfig eth0:0 192.168.1.10 netmask 255.255.255.0 up
       sudo ifconfig eth0:1 192.168.1.11 netmask 255.255.255.0 up
      
2) Using netstat and route commands of Linux, do the following: View current routing table,
Add and delete routes, Change default gateway.
              
1. View the Current Routing Table
   using netstat
   
          netstat -rn

   using route    

         route -n
