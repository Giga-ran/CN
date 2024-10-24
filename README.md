# CN
Multiple IP Addresses on a Single Network Interface (Linux/Windows)
On Linux (using ip or ifconfig command)
Using the ip command:
        sudo ip addr add 192.168.1.10/24 dev eth0
        sudo ip addr add 192.168.1.11/24 dev eth0
