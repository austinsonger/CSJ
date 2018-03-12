# Using hping3

> hping3 is the "packet crafting tool," which means that it can create just about any type of packet.

```
hping3 -h
```

```
hping3 -h |more
```

> * **-a switch **enables us to spoof our IP address
> * **--rand-dest **produces packets with random destination ports
> * **--rand-source **produces packets with random addresses
> * **-t **sets the Time to live for the packets
> * **-f **fragments the packets



> * **-Q **shows only the sequence number
> * **-S **scan using SYN packets
> * **--tcp-timestamp **grabs the timestamp from the tcp packet



