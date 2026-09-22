# Traceroute Practice

## Command

traceroute -n 8.8.8.8

we use 3 probe packets for each TTL(Time To Live)

## ECMP : One type of load balancer
### Equal Cost Multi Path
#### It uses hashing. (Source IP, Destination IP, Source Port, Destination Port, Protocol) 
#### For example, we use UDP(User Datagram Protocol) as defaul in linux.
![Traceroute result](1.png)
#### This happens because we use different ports for each probe packets.

