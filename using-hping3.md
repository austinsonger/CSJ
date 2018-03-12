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
>
> * **-Q **shows only the sequence number
>
> * **-S **scan using SYN packets
>
> * **--tcp-timestamp **grabs the timestamp from the tcp packet

## Host Discovery / Recon

```
hping3 -S <Target IP Address> -p 80
```

### Port Status

```
SA Set = Port Open
RA Set = Port Closed
```

> If we want to scan all the ports beginning with 1, we can simply add the increment switch \(++\) after the port \(p\) switch and the port number where we want to start scanning \(in this case 1\), like so:

```
hping -S <Target IP Address> -p ++1
```

### Fragment Packets

#### hping3 fragmentation

```
hping3 -f <Target IP Address> -p 80
```













