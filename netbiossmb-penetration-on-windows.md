# NetBIOS/SMB Penetration on Windows

---

### Scanning open port for NetBIOS Enumeration

> You will scan the target network for open TCP and UDP ports and protocol.

```bash
nmap -sT -sU 192.168.1.128
```

#### Ports That Open

### 

## You Can Enumerate The Network Using Nbtstat

```bash
nbtstat -a 192.168.1.128
```

### Hardening The Targeted System

#### Open Windows Firewall Settings

#### Filtering Ports 135-139

> 1. Click on Inbound Rules
> 2. Click NEW RULE
> 3. Click Button for port to create new rule \(TCP or UDP\)
> 4. Click Next
> 5. Click UDP port to apply rule
> 6. Click next
> 7. Chose Block Connection



#### Scan Target System Again

```
nbtstat -a 192.168.1.128
```













#### 



