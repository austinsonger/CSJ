# NMAP COMMANDS

> By Austin Vern Songer

### NMAP BASIC SCANS

```
Single Target     > nmap <IP Target>
Multiple Target   > nmap IP, IP
List of Targets   > nmap -iL <IP Target>
Range of Hosts    > nmap <IP - IP>
Entire Subnet     > nmap <IP Target>/cdir
Random Host       > nmap -iR <IP Target>
Aggressive Scan   > nmap -A <IP Target>
IPv6 Target Scan  > nmap -G <IP Target>
```

## NMAP DISCOVERY SCANS

```
PING Scan                > nmap -sP <IP Target>
Don't PING Specific IP   > nmap -PN <IP Target>
TCP SYN PING             > nmap -PS <IP Target>
TCP ACK PING             > nmap -PA <IP Target>
UDP PING                 > nmap -PU <IP Target>
SCTP Init PING           > nmap -PT <IP Target>
ICMP echo PING           > nmap -PE <IP Target>
ICMP timestamp PING      > nmap -PP <IP Target>
ICMP add mask PING       > nmap -PM <IP Target>
IP Protocol PING         > nmap -PO <IP Target>
ARP PING                 > nmap -PR <IP Target>
Traceroute               > nmap -traceroute <IP Target>
```

## NMAP ADVANCED SCANNER OPTIONS

```
TCP SYN SCAN                > nmap -sS <IP Target>
TCP Connect SCAN            > nmap -sT <IP Target>
UDP SCAN                    > nmap -sU <IP Target>
TCP Null SCAN               > nmap -sN <IP Target>
TCP FIN SCAN                > nmap -sF <IP Target>
XMAS SCAN                   > nmap -sX <IP Target>
TCP ACK SCAN                > nmap -sA <IP Target>
Custom TCP SCAN             > nmap -scanflags <IP Target>
IP Protocol SCAN            > nmap -sO <IP Target>
Send Raw Ethernet Packets   > nmap -send-eth <IP Target>
Send IP Packets             > nmap -send-ip <IP Target>
```

## NMAP PORT SCANNER OPTIONS

```
Fast SCAN                   > nmap -F <IP Target>
Specific ports SCAN         > nmap -p [Port #] <IP Target>
Port by Name SCAN           > nmap -p [Port Name] <IP Target>
Port by Protocol SCAN       > nmap -sU -sT -pU
All Ports SCAN              > nmap -p "*" <IP Target>
Sequential Port SCAN        > nmap -r <IP Target>
```

## NMAP VERSION DETECTION

```
OS Detection              > nmap -O <IP Target>
Attempt to Guess          > nmap -O -osscan-guess <IP Target>
Service Version Detection > nmap -sV <IP Target>
```



