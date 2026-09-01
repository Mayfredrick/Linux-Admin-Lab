# Week 1 Day 3

## Objectives
To learn about networking and utilization of secure shell(SSH)
## Network Information
-hostname = may
-hostname -I = 192.168.114.10 and 10.1.154.0
-interface name = ens33
-default gateway =  192.168.114.2

## Commands Used
-hostname,hostname -I,ip addr, ip route, ip -br addr, nmcli device status

## SSH Configuration
Running command systemctl status SSH to check if SSH is installed and active or not.In my case it was disabled.
To enable SSH I had to run sudo systemctl enable SSH and sudo systemctl start SSH.
To verify connectivity I had to run SSH localhost and login with my password.

## Problems Encountered
In this lab i did not encounter any problems when executing necessary commands.

## Lessons Learned
In this lab I learnt a useful command hostname -I which displays the ip addresses currently assigned to the system. This is useful because has a system administrator you can quickly identify a server's network address for troubleshooting or remote access.


