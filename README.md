# VPN-ALL

When you run this script, it will list all the available network interfaces. You can choose the input and output interfaces by entering their names when prompted. The script then enables IP forwarding, clears existing forwarding rules for both IPv4 and IPv6, and sets up the necessary forwarding rules using the `ip` command.

Please note this assumes that the chosen interfaces are capable of handling both IPv4 and IPv6 traffic. 
